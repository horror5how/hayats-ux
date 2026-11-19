---
name: hayats-ux
description: Use when designing, reviewing, critiquing or rewriting any app screen, landing page, dashboard, onboarding flow, settings page, button set, colour palette or UI copy; when a UI feels off, cluttered, untrustworthy, cheap or AI-generated; when choosing between UI options; and whenever Hayat says "Hayat's UX", "Jack", "zen ux", "UX psychology", "UX laws" or asks why a design works on people.
---

# Hayat's UX (built on Jack, Zen UX)

Jack runs @zen_ux (Jack | Zen UX Design, zen-ux.co), a senior UI/UX designer and hiring
manager. His whole method: design works on people because of psychology, and every rule
below is a psychological reason, not a taste. Built from all 147 of his posts (Apr 2023
to Oct 2026). Every principle with its source post is in `principles.md`.

Core principle: **UX is decision design, not screen design.** Ask what decision the
screen helps with, keep one primary action, remove everything else. Design for the mind
first; Figma comes after.

## A Jack review (or design) is this, in this order

1. **Decision line.** One sentence: the decision this screen helps the user make, and the
   single primary action. Everything not serving it is a candidate for deletion.
2. **3-second test.** Could a stranger name the purpose and the call to action in three
   seconds? If not, say so first: it is a hierarchy or emphasis problem, before colour.
3. **Load.** Count choices and chunks against Hick (fewer choices) and Miller (about seven
   items, grouped). Name what gets hidden (advanced settings), defaulted, or split into
   steps.
4. **Structure.** Proximity (small gaps inside a group, big gaps between), edge
   alignment, one standout element (Von Restorff), big title as anchor, primary action
   in thumb reach, spacing on 8/16/24/32/48, left-aligned paragraphs and forms.
5. **Surface.** Neutral surfaces with colour used as direction, rounded corners unless the
   brand wants strict, soft shadows, soft motion, red reserved for danger, contrast that
   survives dark mode.
6. **Feedback and trust.** Every action answers instantly (skeleton loader, progress
   bar, haptic, micro delight). Same components behave the same everywhere. Familiar
   patterns (nav bottom, search top). Labels on icons.
7. **Copy.** Rewrite the microcopy in human words, with the fix shown as before and after.
   Outcome labels not "Submit". Errors say what happened and what to do next.
8. **AI-generated check.** Purple, emoji icons, several filled buttons, random spacing,
   "seamlessly / effortlessly / powerful / all-in-one". Each one named and replaced.

Each finding carries the rule's name and the one-line reason it works on the brain.
Fixes are concrete (a value, a label, a layout), never "consider improving".

## Quick reference

| Problem you see | Jack's rule | Why it works on people |
|---|---|---|
| Too many options, slow decisions | Hick's law: cut choices, split complex tasks into steps | Decision time grows with number and complexity of choices |
| Screen feels overwhelming | Cognitive load: white space, chunk, hide advanced | Brain only flags friction; less input, more comfort |
| Can't tell what belongs together | Law of proximity: tight inside groups, loose between | Near things read as one group; equal gaps read as nothing |
| Long lists users forget | Miller's law: batches of about seven, related items together | Working memory holds about seven items |
| Nothing stands out | Von Restorff: one standout element per screen | Brain locks onto the thing that breaks the pattern |
| Users hunt for the CTA | One primary action; primary / secondary / tertiary buttons | Four buttons screaming means none carries weight |
| Several filled buttons | One filled button, outline the rest | Classic AI-built tell; emphasis needs a single owner |
| Layout feels off, can't say why | Gestalt: proximity, alignment, hierarchy, grouping, rhythm; perfect edge alignment | Eyes follow edges; lined-up edges feel safe |
| Random 13px / 27px gaps | Spacing system 8, 16, 24, 32, 48; when in doubt add space | Beginner UIs need breathing room, not decoration |
| Everything centred | Centre only headline, support line, button; left-align paragraphs, forms, settings | Centred body copy is harder to read and scan |
| Feels cheap or loud | Neutral palette (beige, off-white, charcoal); colour as direction | Bright colours overstimulate; restraint reads expensive |
| Feels strict or hostile | Rounded corners | Sharp points read as threat; round reads safe and human |
| Flat, can't tell what's clickable | Soft shadows for depth | Depth shows hierarchy; depth reduces uncertainty |
| Feels jittery | Soft, predictable motion | Predictable rhythm calms; motion is emotional design |
| Badges everywhere | Red only for danger or stop | Red hijacks focus; overuse trains users to ignore it |
| Dark mode hard to read | Raise contrast or offer light | Low contrast slows the brain's processing |
| Tap, then nothing | Skeleton loader, progress bar, haptic | Instant feedback says "that worked"; silence feels wrong |
| Waiting feels long | Progress bar; endowed progress (start at 20%) | Brain hates uncertainty; started tasks get finished |
| Feels untrustworthy | Consistency: same spacing, components, tone on every screen | Inconsistency reads as uncertainty; uncertainty feels unsafe |
| New app feels alien | Familiar patterns: nav bottom, search top, real-world metaphors | Brain reuses actions it already knows |
| "What does this icon do?" | Label it | Icons are only universal when the meaning is |
| Primary action at top of phone | Move it to the bottom | Thumb reach; brain picks the lowest-effort action |
| Tiny page header | Large title | Visual anchor tells you where you are, cuts anxiety |
| Robotic copy | Write like a human | Friendly microcopy tells what happened and what to do next |
| Marketing fluff | Delete seamlessly, effortlessly, powerful, all-in-one; say what users do | Those words mean the writer did not know the product |

## Copy rewrites he uses

- "Submission successfully processed." becomes "You're all set."
- "Authentication failed." becomes "That password doesn't match."
- "Submit" becomes the outcome: "Save changes", "Send invoice", "Start trial".

## Common mistakes

- Listing colour and polish before hierarchy. Hierarchy first, then surface.
- Calling a rule "best practice" with no reason. Every finding states why the brain
  reacts, in one line.
- Adding decoration to fix a cluttered screen. Remove, space, group.
- Treating pretty as working. Aesthetic usability makes a UI feel better than it works;
  it does not fix a broken flow.
- Designing only today's screens. Ask what features are coming and leave room.
- Soft findings ("consider a clearer CTA"). Give the value, the label, the layout.

## Heavy reference

`principles.md` holds every rule with its post code and date, plus Jack's views on
research, synthesis, portfolios, hiring and where UX is going.
