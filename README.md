# Background session notification screenshots

Captured from the real Obsidian 1.15.1 macOS app in an isolated demo vault.
The screenshots use a local deterministic ACP agent, without model credentials.
The production plugin bundle handles the protocol events and renders the UI.

- Before: upstream master `ba8b2e0cc069f0f3187f94ab9aa73d7ab0d08968`.
- After: the proposed background-session notification UI.

The final patch also corrects cross-window input focus, which does not change
the appearance shown here.

In both screenshots, “Review release notes” has completed in a background tab
while “Draft README summary” retains focus. Only the fixed version shows the
clickable in-app notice.

These images are kept on a separate review branch to keep binary assets out of
the code contribution.
