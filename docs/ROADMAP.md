# Build roadmap

This is the proposed semester plan, not a record of completed features. Course weeks are used because exact deadline dates and current progress need confirmation.

## Milestones

| Course weeks | Deliverable |
|---|---|
| 1–3 | Confirm user/problem, collect an interview or sourced statistic, define models and interfaces. |
| 4–6 | Build forms and navigation; create mockups; test one HTTP/JSON source; choose storage and state management. |
| 7 | Submit milestone PDF + Figma/mockup: problem evidence, five or six features, architecture, and weekly responsibilities/risks. |
| 8 | Midterm; keep implementation scope stable. |
| 9 | Local CRUD, restart persistence, basic analysis, and saved feedback. |
| 10 | Authentication, bounded cloud sync, ownership rules, offline/reconnect behavior. |
| 11 | Trends, evidence details, and complete question/correction flow. |
| 12 | Real-device testing, security review, release build, README/screenshots, demo rehearsal. |
| 13 | Working-app presentation, repository, APK/build, videos, and contribution form. |
| 14 | Final exam. |

## First decisions

- Confirm team, current course week, devices, and actual submission deadlines.
- Select a narrow demonstration use case and validate the problem with a real user.
- Choose Provider or Riverpod, and the local database.
- Select the first context source and the records permitted to sync.
- Define one evidence-backed observation, question trigger, and correction rule.
- Evaluate whether live AI fits the semester; preserve a transparent template-based fallback.

## Definition of a working baseline

- A user can set a goal, record a reflection/check-in, and retrieve it after an offline restart.
- An observation links to its evidence and handles missing data honestly.
- A user correction affects the next review rather than prompting the same misunderstanding again.
- Source failures and denied permissions preserve core app functionality.
- Sync handles reconnection without duplicate records; accounts cannot access each other's data.
- Deleting supporting data invalidates dependent insights.

## Final submission

Approximately five-minute working demo with real-phone and offline/online behavior; clean repository with setup/specifications/screenshots; APK/build; two-minute backup video; contribution form.

Final-project rubric: working app **8/20**, Flutter quality **6/20**, cloud/local data **3/20**, presentation and Q&A **3/20**. The milestone is 10% of the course grade and the final project is 20%.
