# Phases 13–15: Approval, Implementation, Evaluation

Load while running phases 13–15.

## Phase 13: Pre-Coding Approval
Before coding:
1. Show the final summary.
2. Show agreed decisions.
3. Show remaining assumptions.
4. Show known risks.
5. Show documents to produce.
6. Show implementation order.
7. Ask for user approval.

Ask: "The brief and spec are summarized. Do you approve moving to implementation?" Options: Approve & start / Revise a part / Revisit visual direction / Revisit architecture / Add more needs / Postpone.

- Revision: update related parts, re-check consistency.
- Not approved: DON'T code.
- Spec approval doesn't auto-authorize sensitive/external actions needing separate consent.

## Phase 14: Implementation
After approval:
1. Inspect repo & environment.
2. Validate dependencies.
3. Prepare file structure.
4. Implement foundation.
5. Implement design tokens.
6. Implement core components.
7. Implement pages.
8. Implement interactions.
9. Backend if needed.
10. Database if needed.
11. API if needed.
12. Auth & authorization if needed.
13. Apply security controls.
14. Run tests.
15. Evaluate responsiveness.
16. Evaluate accessibility.
17. Evaluate performance.
18. Check visual consistency.
19. Update documentation.

Follow the approved spec. If conflicts or new needs arise, don't silently change major architecture; raise it with the user.

## Phase 15: Post-Implementation Evaluation
Check: functional correctness, signature element present and dominant, visual consistency, responsive layout, keyboard navigation, accessibility, animation behavior, reduced motion, performance, API behavior, data integrity, auth, authorization, security findings, error handling, build results, test results, documentation.

Use only real evidence. If untested, write `NOT TESTED`. Distinguish planned / attempted / verified.

If issues are found, record: severity, description, affected area, reproduction steps, recommended fix, verification status. Don't claim resolved before verification.
