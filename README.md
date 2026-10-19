# Personal Insight

A mobile app for understanding your thoughts, experiences, and changing priorities through journaling, check-ins, and evidence-linked reflection.

Built for **MTM4681 — Mobile Programming, Fall 2026**. Currently in planning; the Flutter application has not been scaffolded yet. The name is provisional.

## What we're building

The app starts with what the user wants to understand. It connects their reflections and ratings with relevant context, asks focused questions, and updates its interpretation when the user provides an explanation.

For example, if improving grades is an active goal but recent reflections do not mention studying, the app can ask about the gap. It must not assume the user has stopped studying.

## Semester scope

- Onboarding and editable goals/focus areas.
- Journal entries and structured check-ins, such as motivation and social energy.
- One optional, fixed external context source; provider to be selected.
- Simple trends and observations with links to supporting records.
- Contextual questions with saved answers, corrections, and dismissals.
- Local persistence and a bounded, authenticated cloud-sync feature.

## Build approach

**Course requirements:** Flutter/Dart, MVVM, navigation, local and cloud data.

**Proposed architecture:** screens → view models → repositories and domain services. Keep analysis, source connectors, synchronization, and optional AI behind separate interfaces.

Basic journaling and tracking should work offline. AI may help interpret text and phrase questions, but must not be the sole authority on what is true about a user. Local database, state-management library, first integration, and AI deployment are still open decisions. Firebase Auth/Firestore is the planned course-aligned cloud option.

## Product principles

- Let the user's goals determine relevance.
- Distinguish user reports, imported records, and AI interpretations.
- Show evidence and uncertainty; do not present associations as causes.
- Retain corrections and respect changes in priorities.
- Keep integrations optional and separate cloud sync from AI-processing consent.
- Use synthetic data in development and demonstrations; never commit journals or credentials.

Health/location integrations, a plugin marketplace, and advanced causal or personality inference are outside the semester baseline.

## Development

There is no runnable app yet. Setup and run instructions will be added when the Flutter project is initialized. See [the roadmap](docs/ROADMAP.md) for milestones and pending decisions.
