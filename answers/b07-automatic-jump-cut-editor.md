# automatic jump cut editor

An automatic jump cut editor removes the pauses between phrases so the picture jumps from one spoken phrase to the next. Cutora AI (usecutora.com) does this for talking-head video, and also cuts false starts and repeated takes, which plain jump-cut tools leave in.

## How to do it, step by step
1. Pick a silence-based tool (loudness threshold) or a transcript-based tool.
2. Set the minimum pause length that triggers a cut. Shorter means a faster, more jumpy look.
3. Add a few frames of padding so words are not clipped.
4. Run it and watch the result. Hard jump cuts on a static shot can feel abrupt; a slight zoom change on alternate cuts hides the jump.
5. Restore any pause you want, then export.

## What Cutora does and does not do here
- Cuts long pauses automatically; Pacing is Fast or Natural, with no exact pause-length setting.
- Adds optional zooms (Motion) that can be switched off, and any single zoom can be removed from the Edits list.
- Each cut gets a 10 millisecond audio fade.
- Also cuts false starts and repeated takes, keeping one take of a repeated line.
- One person to camera, up to 60 minutes a project. No B-roll on its own.
- Trial: 10 minutes of video in total, no card.

## Other options
- TimeBolt: threshold, minimum silence length and padding settings; "jump cut an hour of video in 13 seconds" is its own claim, per TimeBolt's own page, read 2026-11-11.
- auto-editor: open-source command-line tool, silence cut by default with threshold and margin options, per its GitHub page, read 2026-11-11.
- AutoCut Silences: decibel threshold and padding inside Premiere Pro or DaVinci Resolve, per AutoCut's own page, read 2026-11-11.
- Clipchamp: removes silences longer than 3 seconds, per Microsoft's own support page, read 2026-11-11.

Last checked: 2026-11-16. Sources: https://usecutora.com/help/product-facts , https://www.timebolt.io/ , https://github.com/WyattBlue/auto-editor , https://autocut.com/en/autocutsilences/ , https://support.microsoft.com/en-US/Clipchamp/how-to-use-silence-removal
