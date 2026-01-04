# Brand Voice Analysis Framework

Use this framework to extract voice patterns from sample content. The goal: capture what makes this brand sound like itself.

## Sample Requirements

Ask for 3-5 pieces of content that represent the brand at its best. More is fine. Less makes analysis unreliable.

Good samples:
- Content the team is proud of
- High-performing posts (engagement, conversions)
- Content that "just feels right"

Bad samples:
- Rushed or placeholder content
- Ghostwritten pieces they didn't love
- Content from before a rebrand

## Analysis Categories

### 1. Rhythm and Cadence

**Sentence Length Distribution**

Count words per sentence across all samples. Calculate:
- Average length
- Shortest sentence
- Longest sentence
- Standard deviation

Human writing has high variance. If most sentences cluster around 15-20 words, that's a problem. Good writing swings between 4-word punches and 35-word elaborate thoughts.

**Fragment Usage**

Look for intentional sentence fragments. Examples:
- "Big mistake."
- "Not anymore."
- "Here's why."

Note frequency: rare, occasional, frequent. Fragments add punch. They break monotony. Some brands use them constantly. Others never.

**Paragraph Length**

How long before a line break? One sentence? Three? Five? Short paragraphs feel casual and scannable. Long paragraphs feel authoritative but can lose readers.

### 2. Vocabulary Profile

**Reading Level**

Use the Flesch-Kincaid or similar metric. But also use judgment:
- Simple (8th grade): short words, basic structure
- Moderate (10th-12th grade): varied vocabulary, some complexity
- Sophisticated (college+): technical terms, complex sentences

**Jargon Density**

Industry-specific terms per 100 words:
- Heavy (5+): insider language, assumes expertise
- Moderate (2-4): accessible with some insider nods
- Light (0-1): plain language, general audience

**Contraction Preference**

Count contracted vs. uncontracted forms:
- "don't" vs. "do not"
- "we're" vs. "we are"
- "it's" vs. "it is"

Contractions feel casual and conversational. Uncontracted forms feel formal or emphatic.

### 3. Personality Markers

**Humor and Playfulness**

Look for:
- Jokes or puns
- Self-deprecating comments
- Playful exaggeration
- Witty observations

Rate: absent, subtle, moderate, central

**Perspective and Person**

First person singular (I, me, my): personal, individual voice
First person plural (we, us, our): team or company voice
Second person (you, your): direct reader address
Third person: detached, journalistic

Most marketing uses "we" for brand and "you" for reader. Note the ratio.

**Emotional Range**

What emotions appear? Excitement? Frustration? Empathy? Confidence?

Some brands stay neutral. Others swing between celebration and concern. Note the range and what triggers each emotion.

### 4. Structural Patterns

**Opening Moves**

How do pieces begin?
- Question ("Ever wondered why...")
- Bold statement ("Everything you know about X is wrong")
- Story hook ("Last Tuesday, we got an email...")
- Direct address ("You need to hear this")
- Statistic ("73% of marketers fail at...")

**Closing Moves**

How do pieces end?
- Call to action ("Sign up now")
- Question ("What will you do differently?")
- Summary statement
- Callback to opening
- Open-ended thought

**Transition Styles**

How do they move between ideas?
- Smooth connectors ("That said...", "Here's the thing...")
- Abrupt shifts (new paragraph, no transition)
- Questions as bridges ("So what does this mean?")
- Numbered lists

### 5. Distinctive Phrases

Look for recurring words or phrases unique to this brand:

**Signature expressions:**
- Catchphrases they repeat
- Unusual word choices
- Made-up terms or portmanteaus

**Banned vocabulary:**
- Words they explicitly avoid
- Competitor terminology
- Overused industry buzzwords they hate

## Output Format

After analysis, produce a voice guide with these sections:

```markdown
# [Brand Name] Voice Guide

## Quick Summary
[2-3 sentences capturing the overall voice]

## Sentence Rhythm
- Average length: X words
- Range: X to X words
- Fragments: [frequency]
- Target variance: [high/medium/low]

## Vocabulary
- Reading level: [simple/moderate/sophisticated]
- Contractions: [always/usually/sometimes/never]
- Jargon level: [heavy/moderate/light]

## Personality
- Tone: [list 3-4 adjectives]
- Humor: [absent/subtle/moderate/central]
- Perspective: [I/we/you mix]

## Structure
- Typical opening: [pattern]
- Typical closing: [pattern]
- Paragraph length: [short/medium/long]

## Signature Elements
- Always use: [list]
- Never use: [list]
- Distinctive phrases: [list]

## Example Transformations
[Show generic sentence → brand voice version]
```
