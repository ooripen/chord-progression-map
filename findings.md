# Findings

## Requirements
- Fix provided HTML/CSS/JS so it runs correctly.
- Suggest practical improvements.
- Create/push a GitHub repo under the user's personal account.
- Deploy the project to Vercel under the user's personal account.

## Research
- Source code has typographic corruption (en dashes in CSS vars, smart quotes, invalid universal selector).
- App logic is mostly solid and can be preserved with small UX/perf fixes.

## Technical Decisions
| Decision | Rationale |
|----------|-----------|
| Normalize all typography to ASCII-safe syntax | Prevent parsing/runtime issues from copied rich text |
| Keep data model and map layout from original | Preserve expected behavior while fixing correctness |
| Add small enhancements (reset action, accessibility, lighter hover work) | Improve usability without changing core concept |

## Resources
- Vercel CLI workflows from installed local skill docs
- User-provided source HTML in chat
