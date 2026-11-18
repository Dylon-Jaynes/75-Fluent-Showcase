# 75 Fluent

75 Fluent is a web app I’m building for a small business to help language learners follow a 75-day study challenge. I’m developing the React frontend, NestJS API with Typescript, and PostgreSQL data model.

**Status:** Onboarding is in development. Daily activity logging and progress tracking are planned.

https://github.com/user-attachments/assets/1faf8cb3-cbf6-44ae-a866-11f01605c3d7

## Onboarding demo

<!-- Paste the GitHub video upload URL here. -->

The demo shows how a learner chooses a language, sets their proficiency level, and adds a second language.

## One product decision

Soft mode is available for a single language. Adding a second language requires Standard mode and a proficiency level for each language. If a learner tries to add a language while in Soft mode, the app explains the change and asks them to confirm. If they continue, the form keeps their first language and proficiency level so they can pick up where they left off.

The language picker also supports alternate search terms. For example, searching for `nihongo` finds Japanese.

## Tech stack

- **Frontend:** React, TypeScript, Vite
- **Backend:** NestJS, TypeScript
- **Database:** PostgreSQL

The application source code is in a private repository.
