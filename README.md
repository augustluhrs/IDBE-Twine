# IDBE-Twine

Repository of Twine source files for Tandon IDBE Game.

## Current Versions

- *IDBE Game_Twine* is the story-only version of the first three scenarios.
- *v2_Backend* is the above with the added sheet logging and feedback interface.

## TODO

- [X] Instructions for Readers at Start
- [X] Name/NetID Capture
- [X] Glitch Project Site Live
- [ ] QR Code // Bit.ly
- [X] Sheet Logging Player Path
- [ ] Sheet Logging Passage Feedback
- [ ] Feedback Buttons
- [ ] Send POST on final page instead of every page (only 500 requests avail.)
- [ ] Bearer token in glitch .env (is security overkill?)
- [X] ~~Load Game at Start if Cookies Exist~~

## Old Instructions

### How to Download Story

1. Click on the green `<> Code` button to the top right, and download the .zip.
2. Go to [the Twine browser site](https://twinery.org/2/#/).
3. Go to the **Library** tab at the top left, and select **Import**.
4. Select "Choose File" and navigate to the `IDBE-Game.twee` file that was downloaded as a part of the git repository .zip. If you've downloaded an earlier version, this process will overwrite that one, so make sure there aren't any changes that need to be saved.
5. The IDBE-Game story should now show up in your Twine browser as a story you can edit or play.

*To quickly share a non-editable version of the story just for reading, **you can send the `IDBE-Game.html` file** to anyone. Opening that file will allow them to play through the story without needing to mess with Git or the Twine site.*

### How to Update Changes

1. Edit the story/nodes in your Twine browser.
2. When you're done making changes, from within the story on the Twine browser, go to the **Build** tab on the top left, and select **Export as Twee**.
3. Send me (August), the downloaded `.twee` file on Slack along with a bulleted changelog so I know what to look for when I merge your version with the old version.

*If you're comfortable with git, feel free to make a PR with the updated `.twee` file*
