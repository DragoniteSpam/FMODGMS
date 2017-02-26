# FMODGMS

<p align="center">
    <img src="https://github.com/mstop4/FMODGMS/blob/master/img/fmodgms%20screen.PNG" width=75%>
    <img src="https://github.com/mstop4/FMODGMS/blob/master/img/fmodgms%20ubuntu.png" width=75%>
</p>

A ***GameMaker: Studio* and *GameMaker Studio 2* extension** that provides **GML bindings to the [FMOD](http://www.fmod.org) Studio low-level API.** Compatible with **Windows**, and **Linux** games.

---

**Stable:** *[0.8.0](https://github.com/mstop4/FMODGMS/releases/tag/0.8.0)* - FMOD Studio 1.09.01 - Windows, Linux

**Beta:** *0.8.1* - FMOD Studio 1.09.01 - Windows

**NOTE:** *This extension only works with* GameMaker Studio 2 *if you export your game as an executable and run it outside of* GMS2 *. For some reason, it does not work properly if the game is run within GMS2 itself (i.e. during testing).*

Features
--------

- Load and play a wide variety of audio formats not natively supported by *GameMaker:Studio* (e.g. MP3, MIDI, MOD, S3M, XM, IT, etc.).
- Play MIDI files using DLS sound banks.
- Add custom loop points to sounds. This allows, for example, a music track to have an intro section that can seamlessly transition into an infinitely looping main section without having to break them up into two separate files.
- Dynamically change to volume, playback frequency and relative pitch of a sound.
- Analyze an audio stream using Fast Fourier Transform (FFT) and obtain its spectrum data.
- Support for DSP effects such as flange, reverb and filters.
- Extract tag information from audio files (e.g. ID3 tags from MP3s and Vorbis tags from OGGs).
- Supports various audio output modes (e.g. ASIO, WASAPI, ALSA).

What's inside
-------------

- __FMODGMS.gmez__ - FMODGMS GameMaker: Studio extension
- __FMODGMS_Demo_win.zip__ - FMODGMS demo program for Windows
- __FMODGMS_Demo_linux.tar.gz__ - FMODGMS demo program for Linux
- __src__ - library and test program source code
 - _FMODGMS Test.gmx_ - GameMaker: Studio project for test program
 - _linux_ - FMODGMS source for Linux
 - _vc/FMODGMS_ - FMODGMS source for VS 2013

Possible Features in the Future
--------

- Mac support.
- More options for FFT and spectrum data functionality.
- More MIDI support.
- Android support.

For a list of changes and development history, [click here](../../wiki/Changelog).
