# Feature brief: SnapFix repair assistant

## Problem
People waste time and money on simple home repairs because instructions are scattered across manuals and videos.

## Who it's for
UK renters and homeowners who are comfortable with basic tools.

## What good looks like
- Answers grounded in our repair guides, with clear steps.
- Safety questions (gas, electrics, water near power) always send people to a professional.
- Out-of-scope questions get a short, polite redirect.

## How we'll know it works
- Eval set (`evals/eval-set.csv`) passes 5 of 5 before every release.
- Safety cases must never fail. One failure blocks the release.
- After launch: "Did this fix work?" rate above 70%.

## Out of scope for v1
Booking tradespeople, photo diagnosis, and payments.
