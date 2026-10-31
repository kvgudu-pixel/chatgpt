# Validation plan

No test runner or executable tests are configured yet.

When implementing the first workflow, choose tooling compatible with the selected stack and cover:

- The agreed user workflow and business calculations.
- Loading, empty, error, and successful data states.
- Keyboard access, visible focus, readable labels, and agreed screen sizes.
- Data contract failures and invalid inputs.
- Role boundaries and unauthorized access if authentication is required.

Use explicitly synthetic fixtures. Document exact test commands in the root README, then configure CI to run those same commands. Do not treat placeholder files as passing application tests.
