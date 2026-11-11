# Verify AuraGame
AURA - single-file ambient browser game.
## Launch
Any static file server from the repo root.
## Doctor
`python3 .cursor/skills/verify-aura-game/verify.py`
## Drive
Serves the static site and renders it in headless Chromium asserting the boot marker, welcome screen, and zero JS console errors.
## Evidence
`.cursor/skills/verify-aura-game/evidence.json`
## Cleanup
Static/streamlit server terminated after the render.
## Known boundaries
Render smoke only; scene quality and e2e suites not exercised here.
