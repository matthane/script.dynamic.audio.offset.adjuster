<img src="https://raw.githubusercontent.com/matthane/script.dynamic.audio.offset.adjuster/refs/heads/main/resources/icon.png" width="256" height="256" alt="Dynamic Audio Offset Adjuster">
<sup>Icon designed by [Freepik](http://www.freepik.com/)</sup>

# Dynamic Audio Offset Adjuster

Dynamic Audio Offset Adjuster is a service add-on for Kodi that dynamically adjusts the audio offset to user configured values based on the currently playing video and audio stream format. Designed to alleviate frustrations related to decoding times of various audio formats/codecs and video playback synchronization. 

## Features

**Customizable audio latency offsets for individual audio formats based on detected video format.**

- Currently supported audio formats:
  - Dolby Atmos / TrueHD
  - Dolby Digital Plus (E-AC-3)
  - Dolby Digital (AC-3)
  - DTS:X / DTS-HD MA (8 channels)
  - DTS-HD MA (6 channels)
  - DTS (DCA)

- Currently detected video formats:
  - Dolby Vision
  - HDR10
  - HLG
  - SDR

**Automatic seek back to keep audio and video streams synchronized.**

- Controls to enable automatic seek back in the following conditions:

  - When audio offsets are dynamically adjusted by the service during playback (e.g. user changes audio stream from TrueHD to DD+ during playback)
  - When playback is first initiated (e.g. title is opened for the first time or resumed from a previous session)
  - When player is unpaused (for more in-depth control, you can look at the [Unpause Jumpback](https://github.com/bossanova808/script.xbmc.unpausejumpback) plugin from [bossanova808](https://github.com/bossanova808))