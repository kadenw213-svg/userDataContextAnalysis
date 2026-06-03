**userDataContextAnalysis**

User Data Context Analysis is a passive user-profile memory prompt designed to build and maintain a durable profile of a single user across AI chats. It tracks reusable personal context such as career history, resume evidence, education, life timeline, goals, constraints, communication patterns, relationships, health or symptom context, conflict context, and business or creator background.

This prompt is meant to work alongside `llmEnhancementGuidelines`, but it serves a different purpose. `llmEnhancementGuidelines` is the project-context prompt: it handles correctness-first reasoning, coding/project continuity, datasets, rubrics, architecture, files, active work, and task-specific memory. `userDataContextAnalysis` is the user-profile prompt: it focuses on who the user is, what they have done, what context matters about them, and what information should carry forward for resumes, planning, communication, relationships, and long-term personal context.

The prompt saves profile-relevant implications from projects without duplicating full project details. For example, it may store that the user has experience building AI-assisted content systems or automation workflows, but it should not store the full codebase, rubric, project architecture, application criteria, or implementation plan. Those belong in the project-memory prompt.

To use it, paste the full prompt at the start of a new AI chat or install it as the active user-profile context prompt. Once activated, it treats activation as consent to passively learn durable profile context, ask follow-up questions when important context is missing or stale, and prune or supersede outdated information over time. It is best used for resume building, cover letters, career planning, life planning, relationship or communication support, conflict documentation, creator/business positioning, and any task where personal context improves the output.

**Dependencies**

Google Drive Connector

