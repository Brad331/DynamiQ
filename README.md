
# DynamiQ: Intelligent Frequency-Aware Volume Boost

**May 26, 2020: now updated** with improved algorithm, reduced latency, and optional user-requested vocal clarity option! [Download](https://github.com/Brad331/DynamiQ/archive/master.zip) the new version and overwrite your DynamiQ folder. [See full changelog](https://github.com/Brad331/DynamiQ/commits/master)


**DynamiQ** is an open-source and modular package of scripts that allow you to boost the volume of the audio from your Windows device. It enables you to use aggressive equalizer settings without sacrificing maximum attainable volume.

Binaural demo on MateBook X Pro laptop: https://www.youtube.com/watch?v=o5kS3qjtLgI

### Use Cases:
DynamiQ is the best way to get much better sound from your laptop's speakers or other small speakers. Set an equalizer to correct the frequency response and put DynamiQ after it. You will get your desired frequency response yet be able to reach very high volumes when you turn it up.

### How It Works:

When more power output is demanded than possible, DynamiQ levels the bass on demand to free up just enough headroom to avoid clipping. The amount of bass attenuation varies with the loudness of the audio in real-time. This way, you're gauranteed the volume level you set but also the most ideal frequency response possible at that volume level.
If you've done any EQ'ing on laptop speakers, you've probably run into a shortage of volume after boosting the bass. You might have even set up multiple EQ profiles for bass and for volume. Well, now DynamiQ does that for you automatically.

### How to Install:

1. Make sure [Equalizer APO](https://sourceforge.net/projects/equalizerapo/ "Equalizer APO") is installed and working.
2. [Download DynamiQ](https://github.com/Brad331/DynamiQ/archive/master.zip "DynamiQ").
3. Extract the zip you just downloaded. You should get a folder called "DynamiQ-master" with some files in it.
4. Move that folder into **%ProgramFiles%\EqualizerAPO\config**.
5. Open Equalizer APO's Editor app (search "editor" in Start). Include **DynamiQ-master\DynamiQ.txt** in your Equalizer APO config file, after any EQ you have for your speakers.
![alt text](https://github.com/Brad331/DynamiQ/raw/master/Include%20DynamiQ.png)
6. [Download APOpreamp](https://github.com/Brad331/APOpreamp.ahk/releases "APOpreamp") and put it in **%appdata%\Microsoft\Windows\Start Menu\Programs\Startup** so that it automatically starts at login.
7. Run APOpreamp.exe.


### How to Use:

Once your Windows volume is maxed out, keep pressing the volume up button on your keyboard to boost the gain. You should see a white Gain box pop up near the screen's top left corner and hear an increase in volume.

### FAQ:
Q: Windows volume 100 is now much quieter and I have to use the Gain. Is that normal?

A: Yes, DynamiQ is designed to take advantage of the full amplifier headroom provided when the system volume is maximized. The Gain should give you back as much volume as before, if not more.

Q: Should I turn off DynamiQ when using headphones?

A: Yes, DynamiQ is not for headphones, so you should turn it off. If your headphone is a different sound device (e.g. USB headphones), you can simply not enable E-APO for that device, or use the "Select Device" filter within E-APO to apply DynamiQ to just the speakers.

### Customization:
You can use Equalizer APO's Editor.exe to change the bass crossover frequency in each BassComp*.txt. You can shift them up to make DynamiQ favor more volume or down to favor more bass. Rule of thumb: BassComp1.txt's crossover frequency should be about equal to your speaker's bass rolloff frequency.

Feel free to experiment and modify any part of DynamiQ. Maybe you'll discover something new and even better! Just be careful not to blow your speakers. If you hear distortion, [submit an issue](https://github.com/Brad331/DynamiQ/issues/new) stating your device model and describing the noise so I can help you.

DynamiQ makes use of and includes a copy of [ReaComp](https://www.reaper.fm/reaplugs/ "ReaComp"), a free VST plugin by Cockos.
