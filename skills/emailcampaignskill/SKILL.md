---
name: emailcampaignskill
description: "Use when Codex, Hermes, OpenClaw, Claude Code, Cowork, or another AI agent needs to plan, review, implement, audit, or improve email work focused on campaign briefs, audience logic, creative QA, launch readiness, and post-send analysis. Triggers include requests about campaign briefs, creative review, performance retrospectives, audience QA, launch checklists, and campaign optimization."
---

# Email Campaign Skill

Run the campaign as a controlled operation: brief, audience, creative, QA, launch, monitor, learn.

## When To Use

Use this skill for campaign briefs, audience logic, creative QA, launch readiness, and post-send analysis. It is designed for agent workflows where email work must be specific, reviewable, and safe across planning, drafting, implementation, QA, or operational handoff.

## Operating Workflow

1. Start with the campaign brief: objective, audience, offer, send window, success metric, constraints, and approval owner.
2. Validate audience logic before copy, including inclusions, exclusions, consent, suppression, and expected recipient count.
3. Review creative for promise match across subject, preview, body, proof, CTA, landing page, and follow-up path.
4. Prepare launch QA: links, tracking, personalization, rendering, plain-text fallback, footer, and reply handling.
5. For analysis, compare performance against baseline, segment, source, and hypothesis rather than judging one metric alone.
6. Return a launch decision or retrospective with next actions and risks.

## Review Criteria

- The campaign has one primary goal and one primary CTA.
- Audience eligibility and exclusions are written in operational terms.
- The creative does not promise more than the landing page delivers.
- Post-send analysis includes deliverability and list-quality context.
- Recommendations separate immediate fixes from future tests.

## Output Pattern

Return campaign briefs, audience QA tables, creative reviews, launch checklists, test plans, and post-send retrospectives. Keep recommendations concrete. Separate analysis from live-system actions, and require explicit approval before sending email, importing contacts, changing DNS, altering suppression rules, or editing production automations.
