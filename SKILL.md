---
name: snarky-comeback
description: Generate sharp, sarcastic, cutting but bounded comeback drafts for online arguments, replies, chat rebuttals, and tone rewrites. Use when Codex is asked to 回怼、阴阳怪气、刻薄反击、冷嘲热讽、反讽回应、写一句让人破防但不过线的回复, especially in Chinese or bilingual social/chat contexts. Keep the result sharp, concise, and satisfying without slurs, threats, doxxing, sexual humiliation, protected-class attacks, or harassment escalation.
---

# Snarky Comeback

## Overview

Craft short, pointed comebacks that feel satisfying because they expose weakness instead of spraying abuse. Default to concise Chinese unless the user clearly wants another language.

## Read the Target

- Identify the actual claim, posture, and weakest point in the target message.
- Decide whether the main weakness is one of these: `逻辑漏洞`、`双标`、`虚张声势`、`偷换概念`、`情绪输出`、`无知硬装懂`、`转移话题`.
- Infer the narrowest plausible reading when context is missing. Do not invent extra facts just to make the line hit harder.
- Preserve concrete details from the user's input when they make the reply feel more specific and less generic.

## Pick an Attack Vector

Choose one primary vector before writing. Do not stack every trick into one sentence.

- `拆逻辑`: Expose contradiction, inconsistency, or empty confidence.
- `降身位`: Reduce the target from “authority” to “noise”.
- `假客气`: Use polite wording with clear contempt underneath.
- `镜像反弹`: Reuse the target's structure and turn it back on them.
- `冷处理`: Treat the target as unserious or beneath a full response.
- `封口句`: Land one short line that ends the exchange.

If the user does not specify intensity, default to `冷嘲` using `拆逻辑` or `假客气`.

## Hold the Boundary

- Do not use slurs, threats, or encouragement of harassment.
- Do not attack family members, appearance, body, disability, illness, sexuality, race, ethnicity, nationality, religion, or gender.
- Do not produce sexual humiliation, violent fantasies, doxxing language, or dogpile bait.
- Avoid generic profanity as the main engine of the line. Make the reply cut because it is precise.
- If the user requests content beyond these bounds, redirect toward mocking the argument, posture, or behavior instead of the person's identity.

## Write the Line

- Default to three options unless the user explicitly asks for one.
- Keep each option compact. Aim for under 28 Chinese characters for fast-thread use; stretch only when the setup needs one more clause.
- Prefer implication over explanation. Let the insult emerge from the framing.
- Cut filler such as `笑死`、`无语`、`你真有意思` unless it is doing real tonal work.
- Avoid sounding like a template. Reuse the target's topic words when useful.
- End as soon as the damage lands.

## Match Intensity

Use these intensity levels unless the user specifies another scale:

- `轻刺`: teasing, eyebrow-up, lightly dismissive
- `冷嘲`: elegant contempt, dry and pointed
- `封口`: short, terminal, dismissive
- `公开处刑`: quote-friendly exposure of the flaw, not abuse of the person

Escalate by increasing precision, compression, and asymmetry. Do not escalate by adding uglier language.

## Format the Output

Use the simplest format that fits the request.

- If the user asks for direct usable lines, return only the lines.
- Otherwise default to three labeled candidates:
  - `短`: fastest hit
  - `准`: clearest attack on the weak point
  - `冷`: driest and most contemptuous version
- If the user asks for refinement, explain the lever briefly: `抓手: 双标`, `策略: 假客气`.

## Tune to Context

- Write for comment sections, group chats, quote-replies, and one-on-one rebuttals.
- Keep public-thread replies more legible and quote-friendly.
- Keep private-chat replies sharper and more intimate, but still inside the boundary rules.
- Mirror the user's register when it helps: internet slang, polished sarcasm, office-polite shade, or deadpan intellectual dismissal.

## Avoid Weak Output

Reject or rewrite lines with these problems:

- `太脏`: relies on profanity instead of a real angle
- `太空`: could fit any argument because it has no specific hook
- `太长`: sounds like a rant instead of a finish
- `太直白`: says “你很蠢” instead of making the reader feel it
- `太像AI`: symmetrical, explained, over-labeled, and emotionally flat

## Use References

- Read [references/style-patterns.md](references/style-patterns.md) when a specific sarcastic flavor, attack vector, or anti-pattern matters.
- Read [references/corpus-template.md](references/corpus-template.md) when the user wants to extend the skill with their own examples or build a reusable style bank.
