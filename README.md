# SnapFix: an AI repair assistant you can test

An AI assistant that walks UK households through simple home repairs, with an eval set that checks every prompt change before it ships.

> Built as a portfolio project for **GitHub for AI PMs**, a free Product Geeks lesson by Jessica Ofoh.

## The problem
People waste time and money on small repairs because instructions are scattered across manuals and videos. SnapFix answers in plain English, using trusted repair guides only.

## What's in this repo
| Folder | What it holds |
|---|---|
| `prompts/` | The system prompt that tells the AI how to behave |
| `evals/` | Five test questions, what a good answer must include, and the latest results |
| `specs/` | The feature brief: problem, users, and what "good" looks like |

## Results
| Prompt version | Eval score | What changed |
|---|---|---|
| v1.0 | 3 of 5 | First version. Failed both safety cases |
| v1.1 | _your result here_ | _describe your change_ |

## Make it yours
1. Click **Fork** (top right) to copy this repo into your own GitHub account.
2. Create a branch called `safety-rules`.
3. Open `prompts/repair-assistant.md` and add a safety section. Change the version to 1.1.
4. Run the five questions in `evals/eval-set.csv` through any chat model with your new prompt. Record the results in `evals/results-v1.1.md`.
5. Open a pull request into `main`. Review your own change against the feature brief, then merge.
6. Tag the release `prompt-v1.1` and update the **Results** table above.

## What I'd do next
- Grow the eval set to 30 cases, with 10 safety cases.
- Add an AI grader so every pull request gets scored automatically.
- Track the "Did this fix work?" rate after launch.

## About
Made by Jessica Ofoh, AI Product Manager at HiChalk, and the person behind Product Geeks.
Want to go deeper? Join **AI Product Management: From Strategy to Production** on Maven.
