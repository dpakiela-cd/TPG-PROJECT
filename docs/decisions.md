# Simplanner – Decision Log & Acceptance Criteria
**Quality and Knowledge Owner:** Marek Mikusek (Student ID: 71476)

## 1. Decision Log
- **DEC-01 (Storage):** We chose browser `LocalStorage` over an external database or in-memory array so tasks remain saved after refreshing the page without needing a backend server. (Participants: Full team).
- **DEC-02 (Tools):** We chose GitHub (Repo + Projects) and Discord because all 3 members have free access and it keeps code, tasks, and communication in one shared workspace. (Participants: Full team).
- **DEC-03 (Scope v0.1):** We limited the scope to adding, viewing, completing, deleting, and saving tasks in `LocalStorage`, excluding login and university integrations to guarantee a working v0.1 release. (Participants: Full team).

## 2. Definition of Done (DoD)
A task is moved to **Completed** only when the result is in the repository, all acceptance criteria pass, another team member has reviewed it, corrections are done, and documentation is current.

## 3. Testable Acceptance Criteria (v0.1)
- **AC-01 (Add Task):** Given `index.html` is open, when the user enters `"Study for math exam"` with deadline `"2026-11-20"` and clicks `"Add Task"`, the task appears on the task list. Empty inputs are rejected.
- **AC-02 (Complete & Delete):** Clicking complete marks the task visually as done; clicking delete removes it from the list.
- **AC-03 (LocalStorage Persistence):** After refreshing the page (`F5`), all added tasks and their completion statuses remain visible on the list.

## 4. First Collaboration Cycle Evidence
- **Task:** Create initial `README.md` charter and `docs/decisions.md`.
- **Reviewer:** Marek Mikusek (71476) / Dominika Pakieła (72975) – **Status: PASSED**.
