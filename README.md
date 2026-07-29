# exam-tools

Multiple-choice and essay exam question generators for law school faculty.

## Owner

TBD (hire from Summer 2026 applicant pool — see `Box: AI Teaching Lab/team/role-specs/03-exam-creation-tools.md`)

## Status

🚧 **Stub.** v1 prototypes exist for both MCQ and essay generators. This repo will consolidate and extend them.

## What this is

Two related tools:

1. **MCQ generator.** Produces high-quality multiple-choice questions for law school exams. Enforces psychometric quality controls (Haladyna-Downing-Rodriguez taxonomy compliance, distractor validation, cognitive level tagging, coverage balancing). Currently scoped for Intro to IP; expanding to other doctrinal areas.
2. **Essay / fact-pattern generator.** Produces issue-spotter essay questions with SOLO taxonomy layering, construct alignment to course materials, grading rubrics, and model answers calibrated for AI-assisted grading.

Both ship as Python CLIs on the Claude API.

## What's planned (Summer 2026)

- Migrate working code from Polk's existing skills (`law-mcq-generator`, `law-essay-generator`) into this repo as the canonical home.
- Extend doctrinal coverage (contracts, torts, civ pro, con law).
- Faculty pilot at Penn Carey Law and 1–2 partner schools.
- Open-source release with documentation.

## Related

- `pennai-law/essay-grader` — grading pipeline that pairs with this generator.
- `pennai-law/course-materials` — the structured course-material data this tool can query for construct alignment.
- `Box: AI Teaching Lab/team/role-specs/03-exam-creation-tools.md` — role spec for the workstream lead.
- `Box: AI Teaching Lab/workstreams/03-exam-tools/` — workstream home.
