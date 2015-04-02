# slack-fake-blink-tag

Make it look like you’ve brought back the blink tag in Slack, at least for a little while.

![slack-blink-tag.gif](https://raw.githubusercontent.com/danielgm/slack-fake-blink-tag/master/slack-blink-tag.gif)

Uses OSX Automator and AppleScript to edit your previous message and alternate between two lines of text in your clipboard.

## Usage

1. Open the Applescript workflow in Automator. You’ll want to tweak the code to change the number of repeats.
2. Copy two lines of text to your clipboard. Your previous slack message will alternate between these. Here’s a possibility:

```
Omg swoot! You can do a blink tag in Slack using the pound sign!!1
Omg swoot! You can do a           in Slack using the pound sign!!1
```

3. Type the first line into slack and hit enter.
4. Switch to Automator and run the script.
5. Re-run the script if you want to continue faking blink.

The script will switch back to the Slack window and trigger the necessary keystrokes to make your previous message alternate between the two lines in your clipboard.

