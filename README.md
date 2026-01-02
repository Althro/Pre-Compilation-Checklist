# Pre-Compilation-Checklist

Personal checklist for compiling via Wabbajack.


## Meta Files

- Ensure .meta files are properly configured, refer to [Creating your own modlist](https://github.com/wabbajack-tools/wabbajack#creating-your-own-modlist)
- Ensure LOD files are uploaded to nexus or whitelisted (if uploaded to Mega or GDrive)

## Maintanance

- Delete old downloads of updated mods while updating your list
- Re-run behavior engines if applicable
- If mods updated, make sure there are no resolution errors in xEdit in your custom patches
- If mods updated, check that formids weren't renumerated, if so, fix in custom patches
- Maintain a changelog while working on the list, so things aren't forgotten, set date to `TBD`
- Rename Version separator in MO2
- Re-run dynamic patchers if applicable
- Update Grass Cache if applicable
- Update LOD if applicable
- Occlusion if applicable
- Update Readme and Changelog

## Compilation

- If using [this](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)) method to keep game folder files clean, ensure the ModOrganizer.ini is correct, keep a backup of the dev .ini to run the game on your local install
- If ENB is edited or tweaked, replace files in Stock Game/ENB manager
- Make sure modlist.json is set correctly in the precompile settings so that it can write to the repository.
- Ensure GitHub token is up to date/active.
- Update modlist on Load Order Library if applicable

## Pre-Release announcement
- Do a test download and install to ensure that it is working correctly.
- Verify that GitHub data is all to date
- Use the template for the Wabbabot announcement message.
- Publish :)
