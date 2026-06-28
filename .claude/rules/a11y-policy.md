---
description: Invoke the a11y-context-web-react skill before generating React component code.
alwaysApply: true
---

# Accessibility Policy

Run the `a11y-context-web-react` skill when generating user-facing React UI.

**Invoke when the task involves:**
- Pages, routes, or views
- UI components a user sees or interacts with (buttons, forms, dialogs, navigation, carousels, toasts, etc.)
- Modifications to existing UI-rendering components

**Do not invoke when the task involves only:**
- Custom hooks (`use*` functions)
- Context providers or consumers
- Higher-order components or wrapper utilities
- Server-side logic, API handlers, or data-fetching layers
- Type definitions, constants, or utility functions
- Test helpers or mock components

When ambiguous, or when non-UI work touches a UI-rendering component, invoke the skill — the cost of unnecessary invocation is lower than missing accessibility guidance on user-facing UI.
