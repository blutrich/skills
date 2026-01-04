# Example: Email Campaign Marketing Skill

This is a template for an email marketing skill. Customize it based on the brand's voice analysis and email types needed.

## Directory Structure

```
acme-email/
├── SKILL.md
├── references/
│   ├── brand-voice.md
│   └── writing-rules.md
└── examples/
    ├── newsletter.md
    ├── cold-outreach.md
    ├── nurture-sequence.md
    └── product-announcement.md
```

## SKILL.md Template

```markdown
---
name: acme-email
description: Create email content for Acme Corp. Use this skill when asked to write newsletters, cold outreach, nurture sequences, or product announcements for Acme. The skill produces emails that sound personal, avoid spam filters, and match Acme's direct, helpful voice.
---

# Acme Email Marketing

Write emails that get opened, read, and clicked. No corporate fluff.

## Voice Quick Reference

Acme emails are:
- **Personal**: Written like one person to another
- **Useful first**: Value before ask, always
- **Concise**: Respect the inbox
- **Specific**: Numbers, names, details

## Email Type Selection

**Newsletter?** → See `examples/newsletter.md`
**Cold outreach?** → See `examples/cold-outreach.md`
**Nurture sequence?** → See `examples/nurture-sequence.md`
**Product announcement?** → See `examples/product-announcement.md`

## Writing Rules

### Subject Lines

Keep under 50 characters. Front-load the value.

Good patterns:
- Question: "Is your [thing] actually working?"
- Number: "3 mistakes killing your [outcome]"
- Direct: "[Topic] update: here's what changed"

Bad patterns:
- ALL CAPS anything
- "Quick question" (overused)
- Clickbait that doesn't deliver

### Body Rules

Never start with:
- "I hope this email finds you well"
- "I wanted to reach out"
- "I'm just following up"
- "As a [title], you know..."

Always:
- Use contractions
- Write short paragraphs (2-3 sentences max)
- Include one clear CTA
- Put the main point in the first two sentences
- Sign off like a human, not a brand

### Words to Ban

Same as all Acme content:
- delve, tapestry, landscape, realm
- unlock, unleash, elevate, empower
- leverage, synergy, holistic
- "It's important to note"
- Em-dashes (—)

### Rhythm Requirements

Vary sentence length. Mix short sentences with longer ones that carry more complexity and nuance to show you're actually thinking through the problem rather than just listing points.

Include at least one fragment per email for punch. Like this.
```

## examples/newsletter.md Template

```markdown
# Newsletter Format

## Structure

**Subject line**: Clear value, under 50 chars
**Preview text**: Extend the hook, 40-90 chars
**Opening**: Personal, direct, 1-2 sentences
**Main content**: 150-400 words, scannable
**CTA**: One primary action
**Sign-off**: Personal name, not "The Acme Team"
**P.S.**: Optional secondary CTA or teaser

## Example 1: Weekly Update

**Input brief:** Monthly product update newsletter

**Subject:** March: 3 new features you'll actually use

**Preview text:** Plus the one thing we're killing

**Body:**

Hey [Name],

March was weird. We shipped more features than any month last year. But we also killed one that 2,000 people were using.

Here's the full rundown:

**What's new:**

**1. Batch exports** (finally)
Select up to 500 items. Export as CSV or JSON. Takes about 4 seconds.

**2. Slack notifications that don't suck**
Configure exactly which events trigger alerts. No more notification fatigue.

**3. Dark mode**
Toggle in settings. Works everywhere, including reports.

**What's gone:**

**Legacy dashboard**
We maintained two dashboards for 18 months. Nobody should have to. The new one does everything the old one did, but faster.

If you relied on the old dashboard, see our migration guide here. We'll help you move.

**What's next:**

API v3 beta starts April 15. Reply to this email if you want early access.

Sarah
Head of Product

P.S. We're hiring two engineers. Know someone good? We pay $5k referral bonuses.

---

## Example 2: Content Newsletter

**Input brief:** Weekly industry insights newsletter

**Subject:** The pricing mistake everyone's making

**Preview text:** We analyzed 200 SaaS pricing pages

**Body:**

Hey [Name],

We spent last week looking at pricing pages. 200 of them.

One pattern kept appearing in the lowest-converting pages: too many choices.

The research is clear on this. More than 3-4 options creates decision paralysis. Conversion drops. People leave to "think about it" and never come back.

Yet 67% of the pages we analyzed had 5+ pricing tiers.

**The fix is simple:**

1. Cut to 3 tiers max
2. Make the middle one obviously the best value
3. Name them by outcome, not features

We wrote up the full analysis with 12 before/after examples.

Read it here →

One insight worth highlighting: the companies that simplified their pricing saw average conversion lifts of 23%. Not small.

That's it for this week. Short one today.

Marcus

P.S. Hit reply and tell me your biggest pricing question. I'll answer the best ones next week.
```

## examples/cold-outreach.md Template

```markdown
# Cold Outreach Format

## Rules

- Under 150 words total
- One ask, crystal clear
- Prove you did research in sentence one
- No generic openings
- No "I'd love to pick your brain"
- No attachments on first email

## Sequence Structure

**Email 1**: Research + problem + soft CTA
**Email 2** (3 days later): Value add, no ask
**Email 3** (5 days later): Case study + direct CTA
**Email 4** (7 days later): Breakup

## Example Sequence

**Email 1:**

Subject: [Company]'s checkout flow

Hey [Name],

Saw your talk at SaaStr about reducing cart abandonment. The bit about exit-intent timing was spot on.

We help e-commerce teams cut abandonment by 15-25% without discounting. We did it for [Similar Company] last quarter.

Worth a 15-minute call to see if we can help [Company]?

[Name]

---

**Email 2:**

Subject: Re: [Company]'s checkout flow

Hey [Name],

No response needed on this one. Just wanted to share something useful.

We published research last week on mobile checkout patterns. Page 7 has data on the exact timing issue you mentioned at SaaStr.

Link here: [URL]

[Name]

---

**Email 3:**

Subject: How [Similar Company] cut abandonment 23%

Hey [Name],

Quick case study that might be relevant:

[Similar Company] had 68% cart abandonment last year. We worked with them for 6 weeks.

What changed:
- Abandonment dropped to 52%
- Revenue up $340k/month
- Zero discount codes required

Full case study here: [URL]

Is this something [Company] is trying to solve right now?

[Name]

---

**Email 4:**

Subject: Should I close your file?

Hey [Name],

I've reached out a few times without hearing back. Totally get it if timing's off or this isn't a priority.

I'll assume it's a no for now and won't email again.

But if checkout abandonment becomes a focus later, I'm here.

[Name]
```

## examples/nurture-sequence.md Template

```markdown
# Nurture Sequence Format

## Purpose

Move leads from awareness to consideration. Educate without selling hard.

## Sequence Structure

**Email 1** (Day 0): Welcome + quick win
**Email 2** (Day 3): Core concept education
**Email 3** (Day 7): Common mistake + fix
**Email 4** (Day 10): Social proof + soft CTA
**Email 5** (Day 14): Direct offer

## Example: Post-Webinar Nurture

**Email 1: Welcome**

Subject: Your webinar recording + one thing to try today

Hey [Name],

Thanks for joining yesterday's session on [topic].

Here's your recording: [Link]

One thing to try immediately: [specific tactic from webinar]. Takes 5 minutes. We've seen teams get results from this within 24 hours.

Let me know if questions come up.

[Name]

---

**Email 2: Core Concept**

Subject: The framework behind [topic]

Hey [Name],

In the webinar, I mentioned the [Framework Name] briefly. A few people asked for more detail.

Here's the full breakdown:

**Step 1: [Action]**
[2-3 sentences explaining]

**Step 2: [Action]**
[2-3 sentences explaining]

**Step 3: [Action]**
[2-3 sentences explaining]

The key insight: [one sentence summary of the principle].

This guide goes deeper if you want it: [Link]

[Name]

---

**Email 3: Common Mistake**

Subject: The [topic] mistake I see constantly

Hey [Name],

After 500+ conversations with [audience], one mistake comes up again and again:

[Describe the mistake in 2-3 sentences]

Why it happens: [Brief explanation]

The fix: [Specific solution]

I made this same mistake for two years before figuring it out. Cost us probably $50k in lost [outcome].

Don't repeat it.

[Name]

---

**Email 4: Social Proof**

Subject: How [Customer] did [Result]

Hey [Name],

Quick story about [Customer Name]:

[2-3 sentences on their situation before]

What they did: [1-2 sentences on action]

Results after 90 days:
- [Metric 1]
- [Metric 2]
- [Metric 3]

Full case study here if you want the details: [Link]

If you're trying to get similar results, I'm happy to chat. Just reply and we'll find a time.

[Name]

---

**Email 5: Direct Offer**

Subject: Ready to [outcome]?

Hey [Name],

Over the past two weeks, I've shared:
- The [Framework] approach
- The mistake to avoid
- How [Customer] got [result]

If you're ready to try this yourself, here's how to start:

**Option 1: DIY**
Use the free guide I sent in email 2. Works for most teams.

**Option 2: Done-with-you**
We run a 6-week program. Hands-on help implementing everything.

Details and pricing here: [Link]

Questions? Just reply.

[Name]
```

## examples/product-announcement.md Template

```markdown
# Product Announcement Format

## Structure

**Subject**: What's new, clear benefit
**Opening**: One sentence on what launched
**Why it matters**: 2-3 sentences on the problem it solves
**What it does**: 3-5 bullet points
**How to get it**: Clear CTA
**What's next**: Optional teaser

## Example: Feature Launch

**Subject:** Batch exports are here

**Preview text:** Select 500 items. Export in seconds.

**Body:**

Hey [Name],

Batch exports just shipped.

For two years, you've asked us for this. Exporting one item at a time was painful. We know.

Here's what you can do now:

- Select up to 500 items at once
- Export as CSV or JSON
- Get your file in under 10 seconds
- Works on all plans, no upgrade needed

This is live in your dashboard right now. Just select multiple items and hit the new "Export" button.

Try it here →

Coming next month: scheduled exports on a recurring basis. Stay tuned.

[Name]

---

## Example: Major Release

**Subject:** Introducing [Product Name] 2.0

**Preview text:** Everything you asked for. Finally.

**Body:**

Hey [Name],

Today we're launching the biggest update in our history.

[Product] 2.0 is live.

This isn't a bunch of small tweaks. We rebuilt core pieces from scratch based on 18 months of feedback.

**What's new:**

**Speed**: Everything loads 3x faster. Not an exaggeration. We measured.

**New dashboard**: Rebuilt from zero. More data, less clicking.

**Team features**: Shared workspaces, permissions, and activity logs.

**API v3**: New endpoints, better docs, proper webhooks.

**Mobile app**: Finally. iOS and Android.

**For existing customers:**

Your account automatically upgrades. No action needed. Pricing stays the same.

Log in and explore →

We're hosting a live walkthrough Thursday at 2pm ET if you want a guided tour. Register here.

This took 14 months and every engineer on the team. I'm proud of what we built.

Let me know what you think. Seriously. Reply to this email.

[Name]
CEO

P.S. We're running a 48-hour deal for new customers: 40% off annual plans. Know someone who should try us? Send them here.
```
