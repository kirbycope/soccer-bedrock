![Soccer](/soccer-bedrock.png)

# soccer-bedrock
A soccer ball add-on for Minecraft Bedrock Edition.

## Installation
1. Download the [mcaddon](https://github.com/kirbycope/soccer-bedrock/releases/latest/download/soccer-bedrock.mcaddon)
1. Double-click the `.mcaddon` file
1. Edit world
   - Activate the Behavior pack
   - Activate the Resource pack

# Usage
`/give @s soccer:ball_spawn_egg` or `summon soccer:ball`

## Requirements
Minecraft Bedrock 1.26.0 or newer, with no experiments.

## Releasing
Pushing a tag that starts with `v` (for example `git tag v1.0.0 && git push origin v1.0.0`) runs the Release workflow in `.github/workflows/release.yml`, which builds the add-on and attaches `soccer-bedrock.mcaddon` to a GitHub Release.

To build it locally, run `python tools/build_addon.py`. It writes `build/soccer-bedrock.mcaddon`, which git ignores, and leaves the committed `soccer-bedrock.mcaddon` as it is.
