# Kata Skills

Spec-driven development framework for Claude Code.

## Install

```bash
npx skills add gannonh/kata-skills
```

## Skills

| Skill | Description |
|-------|-------------|
| kata-add-issue | Capture an idea, task, or issue that surfaces during a Kata session as a structured issue for later work. This skill creates markdown issue files in the .planning/issues/open directory with relevant metadata and content extracted from the conversation. |
| kata-add-milestone | Add a milestone to an existing project, starting a new milestone cycle, creating the first milestone after project init, or defining what's next after completing work. |
| kata-add-phase | Add planned work discovered during execution to the end of the current milestone in the roadmap. This skill appends sequential phases to the current milestone's phase list, automatically calculating the next phase number. |
| kata-audit-milestone | Verify milestone achievement against its definition of done, checking requirements coverage, cross-phase integration, and end-to-end flows. |
| kata-brainstorm | Run structured brainstorming sessions using paired explorer/challenger agent teams. Explorers generate ideas, challengers play devil's advocate, and 2-3 rounds of debate produce pressure-tested proposals. Use when brainstorming product ideas, exploring feature directions, evaluating strategic options, generating milestone candidates, or when the user says "brainstorm", "explore ideas", "what should we build next", "generate options", or "run an ideation session". |
| kata-check-issues | Review open issues, selecting an issue to work on, filtering issues by area, pulling GitHub issues, or deciding what to work on next. |
| kata-complete-milestone | Archive a completed milestone, preparing for the next version, marking a milestone complete, shipping a version, or wrapping up milestone work. |
| kata-configure-settings | Configure kata preferences, session settings, and workflow variants. |
| kata-debug | Systematically debug issues, investigating bugs, troubleshooting problems, or tracking down errors with persistent state across context resets. |
| kata-discuss-phase | Gather phase context through adaptive questioning before planning, clarifying implementation decisions, or exploring gray areas for a phase. |
| kata-doctor | Run health checks on Kata project structure, detecting and fixing format issues. |
| kata-execute-phase | Execute all plans in a phase with wave-based parallelization, running phase execution, or completing phase work. |
| kata-execute-quick-task | Execute small ad-hoc tasks with Kata guarantees, running quick tasks without full planning, or handling one-off work outside the roadmap. |
| kata-help | Show available Kata skills, displaying the usage guide, explaining skill reference, or when the user asks for help with Kata. |
| kata-insert-phase | Insert urgent work as a decimal phase between existing phases, adding mid-milestone work, or creating intermediate phases. |
| kata-list-phase-assumptions | Surface Claude's assumptions about a phase approach before planning, checking what Claude thinks, or validating understanding before planning. |
| kata-map-codebase | Analyze an existing codebase with parallel mapper agents, creating codebase documentation, understanding brownfield projects, or mapping code structure. |
| kata-migrate-phases | [DEPRECATED] Use /kata-doctor instead. Migrate phase directories to globally sequential numbering. |
| kata-move-phase | Move a phase between milestones or reorder phases within a milestone. |
| kata-new-project | Initialize a new project with deep context gathering and project.md. |
| kata-pause-work | Create a context handoff file, pausing work mid-phase, stopping work temporarily, or creating a checkpoint for session resumption. |
| kata-plan-milestone-gaps | Create phases to close all gaps identified by milestone audit. |
| kata-plan-phase | Plan detailed roadmap phases. |
| kata-remove-phase | Remove a future phase from roadmap and renumber subsequent phases. |
| kata-research-phase | Research how to implement a phase standalone, investigating implementation approaches before planning, or re-researching after planning is complete. |
| kata-resume-work | Resume work from a previous session, restoring context after a break, continuing work after /clear, or picking up where you left off. |
| kata-review-pull-requests | Run a comprehensive pull request review using multiple specialized agents. Each agent focuses on a different aspect of code quality, such as comments, tests, error handling, type design, and general code review. The skill aggregates results and provides a clear action plan for improvements. |
| kata-set-profile | Switch model profile for kata agents (quality/balanced/budget). |
| kata-track-progress | Check project progress, show context, and route to next action (execute or plan). |
| kata-verify-work | Validate built features through conversational testing, running UAT, user acceptance testing, checking if features work, or verifying implementation. |
| kata-whats-new | Show what's new in Kata since the installed version, displaying changelog entries, checking for Kata updates, or reviewing recent changes. |

## License

MIT
