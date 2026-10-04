---
name: read-in-seconds
description: >-
  Write any report, status update, review result, handoff, or summary email so
  the reader gets the point in seconds: verdict first, only what they must act
  on or trust, short scannable lines. Use for every reply that reports work,
  findings, or results, including scheduled emails. Not for requested raw
  output, full files, or explicitly requested long explanations.
  汇报、反馈、评审结论、交付说明、周报邮件：结论先行、短、好扫读、ADHD 友好。
---

# Read in seconds

Goal: the reader knows the result and what to do next within ten seconds.
Shorten the writing, never the checking.
An explicit request for complete output keeps its required content. A request
for complete checking alone does not ask for a long answer.

## Shape

1. **First line = outcome.** State the result or recommendation and any action
   the reader needs to take.
2. **Only when needed: reader decisions**, numbered, with your recommendation.
   Ask only for missing information or authorization that changes the task;
   do not repeat an approval already given.
3. **Then at most 3–5 facts** that make the verdict trustworthy or change a
   decision. One idea per line, one line per idea. This limit never applies to
   findings that must be reported (review issues, failures, risks): list every
   one, one line each, most severe first.
4. Stop. Offer details in one short line only if they exist and might matter.

## Cut

- Process narration ("first I…, then I…"), tool names, and steps that went fine.
- Restating the request or context the reader already has.
- Hedges, filler, repeated conclusions, closing pleasantries.
- Tables unless comparing several items across the same fields.
- Anything the reader cannot act on and does not need for trust.

## Keep, always, even when short

- Failures, unverified parts, open risks, and actions only the reader can take.
- The exact number, path, command, or link needed to act.
- A tag for uncertainty: `未验证` / `推测` / `unverified`.

## Style

- Lines under ~25 字 / 15 words when possible; bold only the key word.
- Routine update: ≤ 5 lines. Complex result: ≤ 15 lines before "details".
- One name per concept: call the same metric, file, or state by the same word
  throughout; a new word reads as a new thing.
- Steps the reader runs: one action per step, imperative, condition before the
  action ("若 hook 拦截，运行 …").
- Same language as the user; keep code, paths, and identifiers verbatim.
- Emails: subject carries the verdict; body follows the same shape.

## Check before sending

Could the reader stop after line 1 and still act correctly? Is every other line
either a needed decision, a trust-critical fact, or a required action? Delete
the rest.
