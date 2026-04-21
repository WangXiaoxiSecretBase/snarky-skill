# Corpus Template

## Purpose

Use this file to collect your own style bank. Prefer self-curated examples over scraped abuse.

## What to Collect

Collect compact, high-signal examples:

- The opponent's exact line or a close paraphrase
- The weak point you want to hit
- The desired tone
- The constraints
- One strong reply you actually like
- Optional notes on why it works

Do not collect:

- Family attacks
- Appearance/body shaming
- Slurs or identity-based abuse
- Threats, doxxing, or harassment bait
- Huge walls of argument that are mostly noise

## Recommended Schema

Use JSON, YAML, or Markdown tables. Keep one example per record.

```json
{
  "opponent": "你这点水平也配评价别人？",
  "context": "公开评论区",
  "weak_point": "虚张声势",
  "tone": "冷嘲",
  "constraints": [
    "不带脏字",
    "不攻击外貌",
    "不提家人"
  ],
  "good_reply": "你这句最大的作用，是提醒别人别把口气当能力。",
  "notes": "不是硬骂，而是把对方的架子拆掉"
}
```

## Tagging Suggestions

Tag records so the style bank stays searchable:

- `pattern`: `拆逻辑` / `假客气` / `镜像反弹` / `冷面终结` / `降身位`
- `intensity`: `轻刺` / `冷嘲` / `封口` / `公开处刑`
- `scene`: `评论区` / `群聊` / `私聊` / `转发评论`

## Quality Filter

Keep examples that are:

- short enough to deploy quickly
- specific to the target's flaw
- sharp without crossing the boundary
- recognizably in your preferred voice

Drop examples that are:

- interchangeable with any fight
- mostly profanity
- funny only because they are cruel
- too long to quote cleanly

## Expansion Workflow

When the bank starts growing:

1. Split examples by `scene` or `pattern`.
2. Keep only your best-performing lines.
3. Add `bad_reply` examples if you want to teach the skill what to avoid.
4. Revise `SKILL.md` only when the workflow changes; keep style examples in reference files.
