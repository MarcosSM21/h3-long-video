# Agent Instructions

Follow the project constitution in `.specify/memory/constitution.md`; it is authoritative and its
principles are not repeated here.

- Keep repository files in English. Explain work, decisions, and results to the user in Spanish.
- Work only on the requested SDD phase and increment. Do not add future capabilities, scope, or
  abstractions to the current increment.
- Read the files relevant to the task. Expand context only when a dependency requires it; do not
  load the whole repository or reread files without a task-specific reason.
- Prefer small, clear changes with few dependencies and concrete responsibilities.
- Run checks proportionate to the change. Clearly distinguish automated tests from real ComfyUI or
  GPU validation, and report only checks actually run.
- Do not assume workflows, media, models, tools, or services exist. Verify availability before
  depending on them.
- Before asking the user to run anything, briefly explain its purpose and identify files that will
  be created or modified.
- At completion, summarize the capability added, verification performed, and remaining
  limitations. Never claim unperformed verification.
- Preserve existing user changes. Exclude secrets, personal paths, private media, models, and
  local results from publishable files.
