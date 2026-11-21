<p align="center"><img src="https://vidray.app/icon-512.png" width="96" height="96" alt="Vidray icon"></p>

# Vidray: cut, join, compress and convert video on Windows and macOS

Vidray is a video tool for Windows and Mac. It cuts and joins video to the exact frame, compresses a video to fit a size such as 10 MB, converts between MP4, MOV, MKV, WebM, GIF and ProRes, and extracts the audio. It works on your own computer with your graphics card, and nothing is uploaded.

**[Download Vidray](https://vidray.app/download)** · [Microsoft Store](https://apps.microsoft.com/detail/xp87xc1fqspmsb) · [User guide](https://vidray.app/docs) · [Release notes](https://vidray.app/whats-new) · [Website](https://vidray.app)

<img src="https://vidray.app/docs/editor.webp" alt="Vidray's Editor: two clips on the timeline, the first one being cut, with the Cut, Crop, Rotate, Speed, Sound and Watermark tools and Re-encodes only the cuts next to Save">

## What Vidray does

- **Cut and join video without losing quality.** The Editor trims, splits and joins clips to the exact frame. Only the frames at each cut are re-encoded, so the rest of the picture stays as it was. It also crops to 16:9, 9:16, 1:1 or 4:5, rotates and mirrors, changes the speed from a quarter to 4×, adjusts the sound and adds a text or picture watermark.
- **Compress a video to a specific size.** Fit a size makes the file fit under 10, 20, 50 or 100 MB, or any size from 1 to 2000 MB, for Discord, email or WhatsApp. Under means under: 10 MB is at most 10,000,000 bytes. Same look keeps the picture as it is and makes the smallest file it can.
- **Convert video formats.** MP4, MOV, MKV, M4V, WebM, AVI, GIF and ProRes. When a video already suits the new format, Vidray repackages it without re-encoding, so the picture doesn't change.
- **Extract audio from video.** MP3, M4A, OGG, WAV, FLAC, AIFF or ALAC.
- **Use the graphics card.** NVIDIA, AMD, Intel and Apple video hardware do the encoding, and the processor takes over when there is none. iPhone HDR video stays bright.
- **Work through many files.** Queue videos or a whole folder, or start from the right-click menu in File Explorer or Finder. Originals are never overwritten: each new file gets "(Vidray)" in its name.

Vidray opens MP4, MOV, M4V, MKV, AVI, WebM, MPG, VOB, 3GP, MTS, TS, MXF, WMV, FLV and GIF. When you convert, this is what it copies as is and what it encodes:

| Converting to | Copied without re-encoding | Otherwise encoded as |
|---|---|---|
| MP4, M4V | H.264, HEVC, AV1 | H.264 |
| MOV | H.264, HEVC, ProRes | H.264 |
| MKV | Any codec | H.264 |
| WebM | VP8, VP9, AV1 | AV1 |

<img src="https://vidray.app/docs/compress.webp" alt="Vidray's Compress screen: forest-walk.mp4 fitted under 10 MB, 44.8 MB before and 9.8 MB after, with Show in folder">

## Free and Pro

- **Free**, with no watermark: every tool, 10 videos a month. Failed or cancelled jobs give their turn back, and previews don't count.
- **Pro**, $24.99 once: no monthly limit, and every future update is included. One computer at a time, Windows or Mac. See [pricing](https://vidray.app/pricing).

To compress one video without installing anything, [vidray.app/compress-video](https://vidray.app/compress-video) does it in the browser, without uploading the file.

## Download and system requirements

| Platform | File | Requirements |
|---|---|---|
| Windows | `Vidray_<version>_x64-setup.exe` | Windows 10 or 11, 64-bit, Intel or AMD processor, 100 MB of disk space |
| macOS | `Vidray_<version>_universal.dmg` | macOS 11 Big Sur or later, Apple silicon or Intel, 150 MB of disk space |

Download from [vidray.app/download](https://vidray.app/download) or the [Microsoft Store](https://apps.microsoft.com/detail/xp87xc1fqspmsb). The Windows installer is signed, and the Mac app is notarized by Apple. The interface is in English.

## Coming from HandBrake, LosslessCut or UniConverter?

Vidray does in one app the jobs that are often split between HandBrake for compressing, LosslessCut for cutting without re-encoding and a converter such as UniConverter, on both Windows and Mac. Instead of codecs and bitrates, you pick a target size or a format. There are side-by-side pages for [HandBrake](https://vidray.app/blog/handbrake-alternative), [LosslessCut](https://vidray.app/blog/losslesscut-alternative), [UniConverter](https://vidray.app/blog/uniconverter-alternative) and [Freemake Video Converter](https://vidray.app/blog/freemake-video-converter-alternative), and guides to [compressing a video to a specific size](https://vidray.app/blog/compress-video-to-a-specific-size) and [MOV to MP4 without re-encoding](https://vidray.app/blog/mov-to-mp4-without-re-encoding).

## FFmpeg

Vidray uses FFmpeg, which is not Vidray's code. FFmpeg is licensed under the GNU Lesser General Public License version 2.1 (LGPLv2.1). Each release here includes `vidray-ffmpeg-source.zip`, with FFmpeg's source code and the scripts used to build it.

## About this repository

This repository holds Vidray's installers, the update files and the FFmpeg source package. Vidray's own source code is not public. For questions and bug reports, use [vidray.app/support](https://vidray.app/support).
