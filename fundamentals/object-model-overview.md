# Workfront Object Model Overview

Workfront is built on a relational object model that connects projects, tasks, issues, users, groups, and portfolios.

## Key Objects
- **Project** – container for tasks, issues, documents, and approvals.
- **Task** – actionable work item with duration, predecessors, and assignments.
- **Issue** – request or problem that may convert to a task or project.
- **Portfolio / Program** – strategic grouping of projects.
- **User / Group / Team** – defines ownership, permissions, and collaboration.

## Relationships
- Projects contain tasks and issues.
- Tasks can have predecessors and successors.
- Issues can convert into tasks or projects.
- Users belong to groups; groups control access and governance.

Understanding these relationships is essential for reporting, permissions, and workflow design.

<img width="791" height="573" alt="Workfrot_objects_hierarchy" src="https://github.com/user-attachments/assets/f66dc24b-e70b-4ccb-bac8-07d941c27e3f" />
