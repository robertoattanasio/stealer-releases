# Stealer

Stealer mirrors your system audio to a second output device in real time. Windows keeps playing on its default output, and Stealer plays the same sound on the device you pick: two Bluetooth headsets on the same film, wireless speakers next to the TV, a headset that has to hear what the speakers are playing.

No virtual audio cables, no drivers, no sound settings to change. Close it, and your system is exactly how you left it.

## Download

[Download the latest installer](https://github.com/robertoattanasio/stealer-releases/releases/latest/download/Stealer-setup.exe)

All versions are listed in [Releases](https://github.com/robertoattanasio/stealer-releases/releases).

## Requirements

- Windows 10 or 11, 64-bit
- A second audio output device: wired or Bluetooth headphones, a USB headset, a monitor or a TV over HDMI

## Installing

Run the installer and choose where to put the app. Stealer updates itself when a new version is out.

The installer is not code-signed, so Windows SmartScreen shows a warning on the first launch. Click **More info**, then **Run anyway**.

## Using it

Pick the second device and press **start**. Stealer shows the output Windows is already playing on, so you always know which device is the original and which one gets the copy. It doesn't change your default device or the system volume.

- **Its own volume.** The copy has a separate slider, up to 120% for a device that doesn't keep up. A double click puts it back to 100%.
- **A live meter.** You can see the sound going out, so a silent device is never a mystery.
- **Switch on the fly.** Change the second device while it's running, and the audio follows without stopping.
- **Remembers you.** The device and the volume are saved for the next time.
- **Plug and play.** Connect a headset or pair a speaker, and it shows up in the list on its own.

## Good to know

- **No echo.** Sending the copy to the device Windows is already using would play the same sound twice, slightly out of sync. Stealer tells you, and keeps **start** off until you choose another output.
- **Stereo, not Hands-Free.** Bluetooth headsets often appear twice. The Hands-Free one is mono, with phone-call quality: pick the Stereo one. If you pick the wrong one, Stealer points it out.
- **When Windows stops the capture.** Stealer goes back to idle and tells you why, instead of looking active while nothing comes out.

## License

Stealer is free to download and use. All rights reserved.
