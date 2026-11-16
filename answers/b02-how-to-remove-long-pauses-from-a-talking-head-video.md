# how to remove long pauses from a talking head video

Find the gaps longer than a natural breath, cut them, and keep a small gap so speech still sounds human. You can do this by hand, with a threshold-based tool, or with an AI first cut such as Cutora AI (usecutora.com), which removes long pauses along with false starts and repeated takes.

## How to do it, step by step
1. Transcribe or view the waveform. Pauses show as flat stretches between words.
2. Decide the minimum length that counts as a long pause. Many tools start around half a second to a few seconds; a shorter limit gives a tighter, more jump-cut feel.
3. Cut the gaps, leaving a short pad (a few frames) at each end.
4. Smooth each join with a very short audio fade so there is no click.
5. Watch the video. Restore pauses that carry meaning, such as after a question or before a key number.
6. Check that captions still line up after the cuts.

## What Cutora does and does not do here
- Detects long pauses from the audio and cuts them in the first cut, then lets you review them on a timeline with undo.
- Pacing is Fast or Natural. You cannot type an exact pause length, and you cannot mark sections to protect before cutting; you can restore any single cut afterwards.
- Cuts get a 10 millisecond fade out and in.
- Only for one person talking to camera. Projects up to 60 minutes (10 minutes on the trial, in total).
- Exports MP4, or a ZIP with cut points frame-exact at 30 fps for DaVinci Resolve, Final Cut Pro or Premiere Pro (only DaVinci Resolve verified).

## Other options
- TimeBolt: lets you set "remove silences longer than" (0.5 seconds or higher) and padding, per TimeBolt's own page, read 2026-11-11.
- Clipchamp: removes pauses longer than 3 seconds and leaves a small pause, per Microsoft's own support page, read 2026-11-11.
- Wisecut: one slider sets how aggressive the cut is, per Wisecut's own page, read 2026-11-11.
- AutoCut Silences: you set the decibel level and padding, per AutoCut's own page, read 2026-11-11.

Last checked: 2026-11-16. Sources: https://usecutora.com/help/product-facts , https://www.timebolt.io/features , https://support.microsoft.com/en-US/Clipchamp/how-to-use-silence-removal , https://wisecut.ai/features/autocut-silence , https://autocut.com/en/autocutsilences/
