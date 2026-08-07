# DLA Sandbox

Generated demo copy of the Wesley College Digital Learning Assistant, used for
presentations. **Do not edit these files by hand** - they are overwritten on
every build.

Regenerate from the main repo (digital-learning-assistant-v2):

    node tools/build-sandbox.mjs --out ../dla-sandbox

No AI calls, no analytics, frozen leaderboard snapshot. Not live data.

Every idea the tool picker can show is written ahead of time:
`data.json` holds each unit's own ideas, and `sandbox-extra-ideas.json`
holds the extra ones the picker falls back to when a tool has no ready-made
idea for that unit. Regenerate those with:

    node tools/gen-sandbox-extra-ideas.mjs
