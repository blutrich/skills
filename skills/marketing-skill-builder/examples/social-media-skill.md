# Example: Social Media Marketing Skill

This is a template for a social media marketing skill. Customize it based on the brand's voice analysis and platform needs.

## Table of Contents

- [Directory Structure](#directory-structure): Skill folder layout
- [SKILL.md Template](#skillmd-template): Main skill file with voice and rules
- [examples/linkedin.md Template](#exampleslinkedinmd-template): Hook + Story format, examples
- [examples/twitter.md Template](#examplestwittermd-template): Single tweets and threads
- [examples/instagram.md Template](#examplesinstagrammd-template): Captions for carousels and reels

## Directory Structure

```
acme-social/
├── SKILL.md
├── references/
│   ├── brand-voice.md
│   └── writing-rules.md
└── examples/
    ├── linkedin.md
    ├── twitter.md
    └── instagram.md
```

## SKILL.md Template

```markdown
---
name: acme-social
description: Create social media content for Acme Corp. Use this skill when asked to write LinkedIn posts, Twitter/X threads, or Instagram captions for Acme. The skill produces on-brand content that sounds human and matches Acme's confident, direct voice.
---

# Acme Social Media

Create social content that sounds like Acme's marketing team wrote it.

## Voice Quick Reference

Acme's voice is:
- **Direct**: No fluff. Say it straight.
- **Confident**: We know our stuff. No hedging.
- **Slightly irreverent**: We poke fun at industry BS.
- **Technical but accessible**: Smart without being exclusionary.

## Platform Selection

**LinkedIn?** → See `examples/linkedin.md`
**Twitter/X?** → See `examples/twitter.md`
**Instagram?** → See `examples/instagram.md`

## Writing Rules

Apply these to all content:

### Never Use
- delve, tapestry, landscape, realm
- unlock, unleash, elevate, empower
- moreover, furthermore, consequently
- pivotal, paramount, crucial
- "It's important to note"
- "At the end of the day"
- Em-dashes (—)

### Always Do
- Use contractions (we're, it's, don't)
- Vary sentence length dramatically
- Include at least one fragment per post
- State opinions directly without hedging
- Use specific numbers over vague quantities
- Start strong. Skip "In today's world..."
- End without summarizing

### Voice Markers
- First person plural (we, our, us)
- Second person direct address (you, your)
- Light humor when appropriate
- Self-aware about industry trends
```

## examples/linkedin.md Template

```markdown
# LinkedIn Content

## Format: Hook + Story + Insight

**Hook** (first 150 characters): Stop the scroll. Question, bold claim, or surprising stat.

**Story** (100-200 words): Specific example, case study, or experience.

**Insight** (2-3 sentences): What this means for the reader.

**Close**: Question or soft CTA. No "Thoughts?" allowed.

## Example 1

**Input brief:** Promote our new API documentation

**Output:**

We rewrote our API docs from scratch.

The old version? 47 pages of technical specifications that even our engineers hated reading. Usage support tickets were through the roof.

So we did something radical. We handed the docs to three developers who'd never used our product. Watched them try to build something. Wrote down every question they asked.

Then we rebuilt the docs around those questions.

Results after 60 days:
- Support tickets down 34%
- Time to first API call: 23 minutes → 8 minutes
- Developer NPS jumped from 32 to 71

The best documentation isn't comprehensive. It's anticipatory.

What's the last piece of documentation that actually helped you?

---

## Example 2

**Input brief:** Thought leadership on B2B marketing trends

**Output:**

B2B marketing has a creativity problem.

We analyzed 500 B2B landing pages last month. 73% used the exact same hero section formula: stock photo of smiling professionals, headline about "transforming" something, three feature bullets.

No wonder conversion rates are tanking.

The B2C playbook doesn't translate directly. But the underlying principle does: be interesting enough to earn attention.

Three things we're testing that actually move numbers:
→ Ugly-but-honest product screenshots (up 28% on signups)
→ Customer roast videos (3x engagement)
→ Plain text emails with zero design (41% higher reply rate)

Pretty isn't working. Try useful instead.
```

## examples/twitter.md Template

```markdown
# Twitter/X Content

## Single Tweet Format

280 characters max. One idea. One punch.

Strong opinions work. Hot takes work. Specific observations work.

Weak: vague statements, questions without edge, "Thoughts?"

## Thread Format

1/ Hook (the big claim or question)
2/ Context (why this matters now)
3-6/ Main points (one idea per tweet)
7/ Conclusion and CTA

## Example Single Tweet

**Input brief:** Product update announcement

**Output:**

Just shipped: API response times now under 50ms globally.

Zero config changes required on your end.

Check your dashboards. The difference is noticeable.

---

## Example Thread

**Input brief:** Explain our approach to customer support

**Output:**

1/ We don't have a support team.

Well, we do. But we call them engineers. Here's why that matters for you: 🧵

2/ Traditional support: Ticket → Tier 1 → Tier 2 → Engineering → Back to you

That's 3-5 handoffs. Each one loses context. Each one adds days.

3/ Our model: You → Engineer who built the feature

One conversation. Full context. Usually resolved in hours, not days.

4/ "But that's expensive!"

Actually, no. Our support costs are 40% lower than industry average.

Turns out engineers who talk to users build better products. Fewer bugs = fewer tickets.

5/ The real benefit isn't speed. It's accuracy.

When an engineer answers your question, they know the edge cases. The workarounds. The roadmap.

You get real answers, not script responses.

6/ We've run this model for 3 years.

NPS: 84
Average response time: 4 hours
Escalation rate: 6%

Want to see it in action? Just reply to any of our tweets with a product question.
```

## examples/instagram.md Template

```markdown
# Instagram Content

## Caption Format

**Line 1**: Hook (stops the scroll)
**Line 2-5**: Value or story (with line breaks)
**Final line**: CTA
**After spacing**: Hashtags (if using)

## Visual Requirements

- Match brand color palette
- Clean, high contrast
- Text overlays: 3-5 words max
- No stock photos unless obviously ironic

## Example Carousel Caption

**Input brief:** Behind the scenes of product development

**Output:**

How we built our most requested feature.

It took 47 days, 3 false starts, and one very heated Slack thread.

Slide 1: The user request that started it all
Slide 2: Our first attempt (embarrassing)
Slide 3: What we learned from testing
Slide 4: The breakthrough moment
Slide 5: The final result

Building in public isn't about showing wins. It's about proving you're actually listening.

Drop a 🔥 if you want more behind-the-scenes content.

.
.
.
#productdevelopment #startuplife #buildinpublic

---

## Example Reel Caption

**Input brief:** Quick tip about our product

**Output:**

This 30-second trick saves our users 2 hours a week.

And 90% of them don't know it exists.

Keyboard shortcut: Cmd+Shift+D

Try it. Thank us later.

Save this for when you forget.
```
