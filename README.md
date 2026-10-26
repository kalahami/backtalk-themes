# Backtalk sound themes

Sound themes for [Backtalk](https://github.com/trypsynth/backtalk).

## Add this as a source

Installing from a source needs Backtalk build 392 or newer.

1. In Backtalk settings, go to **Sound themes**, and under **Install a theme**, choose **From a source**.
2. Choose **Add source**, and enter `github.com/kalahami/backtalk-themes`.
3. Open the source, and choose a theme to install.

To install a single theme instead, share its link or its file to Backtalk.

## Themes

| Theme | What it sounds like |
| --- | --- |
| [VoiceOver](VoiceOver.zip) | The sounds and haptics of VoiceOver on iOS 18: no gesture sounds, and no control sounds, as on iPhone. |

### VoiceOver

36 sounds and 14 vibrations, taken from `VoiceOverTouch.app` in iOS 18.6.2. Each
sound is one of Apple's AIFF files rewritten as WAV, sample for sample, at
22.05 kHz, 16-bit, stereo. The vibrations were derived from Apple's `.ahap`
haptic patterns in the same app: Apple's intensity became Backtalk's strength,
and Apple's sharpness chose the haptic primitive.

As on iOS, gestures play no sound and controls have no sounds of their own, so
Backtalk still says what kind of control each one is.

The theme's own `README.md` lists which Apple sound stands in for each Backtalk
sound, so you can replace any of them under **Sounds** in the theme's settings.
Nine have no counterpart in VoiceOver and are the nearest thing Apple ships
rather than an exact match: `tick`, `long_clicked`, `complete`, `typo`,
`formatting`, the two direct touch sounds and the two browse mode sounds.

The sounds and haptic patterns are the work of Apple Inc., Copyright (c)
2009-2025 Apple Inc. All rights reserved. They are not licensed for
redistribution, and this is not an Apple product and is not endorsed by Apple.
See `NOTICE.txt` inside the theme. VoiceOver is a trademark of Apple Inc.

## Adding a theme

Each theme is one ZIP file at the top of this repository, with its `theme.json`
and its sounds inside. See [the sound theme
guide](https://github.com/trypsynth/backtalk/blob/master/themes.md) for how to
make one.
