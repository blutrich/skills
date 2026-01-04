---
name: marketing-skill-builder
description: Build custom Claude agent skills for marketing teams. Use this skill when a marketing manager, content creator, or brand strategist wants to create their own marketing skill tailored to their specific needs (social media, email campaigns, blog posts, ad copy, newsletters, product launches). The output is a complete, distributable skill package that follows best practices and produces human-sounding content that avoids AI detection patterns.
---

# Marketing Skill Builder

This skill helps marketing professionals create their own Claude agent skills. The result? A custom skill package their team can use to generate on-brand content that sounds like a human wrote it.

## What You're Building

You're creating a skill that will:
- Match the brand's specific voice and tone
- Generate content for specific marketing channels
- Avoid AI-sounding patterns (robotic rhythm, overused words, hedging)
- Follow the team's existing style guidelines

## Creation Workflow

Building a marketing skill has five steps:

1. **Discovery** - Understand the brand voice and content needs
2. **Voice Analysis** - Analyze sample content to extract patterns
3. **Content Mapping** - Define what content types the skill handles
4. **Skill Assembly** - Write the SKILL.md and supporting files
5. **Validation** - Test the skill produces human-sounding output

### Step 1: Discovery

Start by asking these questions. Don't ask all at once. Two or three per message.

**Brand basics:**
- What's the brand name?
- Who's the target audience?
- What's the overall tone? (casual, professional, playful, authoritative)

**Content needs:**
- What content types do you create most often? (social posts, emails, blog articles, ad copy)
- Which platforms? (LinkedIn, Twitter/X, Instagram, email, website)
- How often do you publish?

**Voice samples:**
- Can you share 3-5 examples of content you've written that nails your brand voice?
- Any content that missed the mark? What felt off about it?

**Team specifics:**
- Any words or phrases that are core to your brand?
- Words you never use?
- Any competitors whose voice you like or want to avoid?

### Step 2: Voice Analysis

Read the provided samples carefully. See `references/brand-voice-analysis.md` for the full analysis framework.

Extract these patterns:

**Sentence rhythm:**
- Average sentence length
- Variance (do they mix short punchy sentences with longer ones?)
- Fragment usage (yes/no, how often)

**Vocabulary:**
- Reading level (simple, moderate, sophisticated)
- Industry jargon (heavy, moderate, none)
- Contractions (always, sometimes, never)

**Personality markers:**
- Humor level (none, subtle, frequent)
- First person usage (I, we, our team)
- Direct address (you, your)

**Structural patterns:**
- How do they open? (question, statement, hook)
- How do they close? (CTA, question, statement)
- Paragraph length preferences

### Step 3: Content Mapping

For each content type the skill will handle, define:

1. **Channel specifics** - Platform, character limits, format constraints
2. **Frequency** - How often this content gets created
3. **Templates** - Common structures that work well
4. **Examples** - Input/output pairs showing desired quality

See `references/marketing-content-types.md` for channel-specific guidance.

### Step 4: Skill Assembly

Build the skill package with this structure:

```
[brand-name]-marketing/
├── SKILL.md
├── references/
│   ├── brand-voice.md      # Voice guidelines from analysis
│   └── writing-rules.md    # Anti-AI patterns to follow
└── examples/
    ├── [content-type-1].md # Templates and examples
    └── [content-type-2].md
```

**Writing the SKILL.md:**

The frontmatter needs a clear description. Include:
- The brand name
- What content types it handles
- When Claude should use this skill

The body should include:
- Quick reference to brand voice
- Content type selection logic
- Links to example files
- The writing rules from `references/human-writing-patterns.md`

**Critical: Include the anti-AI writing rules.**

Every marketing skill must include rules that prevent robotic-sounding output. Copy the relevant sections from `references/human-writing-patterns.md` into the generated skill.

These rules cover:
- Banned words (the AI vocabulary to avoid)
- Sentence rhythm requirements
- Hedging elimination
- Specificity requirements

### Step 5: Validation

Before packaging, test the skill by generating sample content. Check:

1. **Voice match** - Does it sound like the brand samples?
2. **Rhythm check** - Are sentence lengths varied? Any monotonous sections?
3. **Word scan** - Search for banned words (delve, tapestry, landscape, etc.)
4. **Hedging scan** - Look for wishy-washy phrases
5. **Human read** - Read it aloud. Does it sound natural?

If issues appear, adjust the writing rules in the skill and test again.

## Packaging the Skill

Once validation passes, package the skill:

```bash
scripts/package_skill.py path/to/[brand-name]-marketing
```

This creates a `.skill` file the marketing team can install and use.

## Quick Reference: What Goes Where

| Content | Location | Purpose |
|---------|----------|---------|
| Trigger conditions | Frontmatter description | When to use the skill |
| Voice guidelines | references/brand-voice.md | Tone, vocabulary, personality |
| Anti-AI rules | references/writing-rules.md | Avoid robotic patterns |
| Content templates | examples/[type].md | Format and structure per channel |
| Channel specifics | examples/[type].md | Platform constraints and norms |
