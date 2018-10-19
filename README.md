# DynamiQ: Intelligent Frequency-Aware Volume Boost

DynamiQ is an open-source and modular package of scripts that allow you to boost the volume of the audio from your Windows device.

How It Works:
DynamiQ reduces bass on demand to free up enough headroom for you to boost volume without clipping. The amount of bass attenuation varies with the loudness of the audio in real-time. This way, you get quality (good tonality) when you want it and quantity (loud volume) when you need it.

How to Install:
1. Make sure [Equalizer APO](https://sourceforge.net/projects/equalizerapo/ "Equalizer APO") is installed and working.
2. Make a folder called *DynamiQ* in *%ProgramFiles%\EqualizerAPO\config*.
2. Download [DynamiQ](https://github.com/Brad331/DynamiQ/archive/master.zip "DynamiQ") and extract its contents into that folder.
3. Include *DynamiQ\DynamiQ.txt* in your Equalizer APO config file, after any EQ you have for your speakers.
4. Download [APOpreamp](https://github.com/Brad331/APOpreamp.ahk/releases "APOpreamp") and put it in *%Username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup* so that it automatically starts at login.
6. Run APOpreamp.exe.


How to Use:
Once your Windows volume is maxed out, keep pressing the volume up button on your keyboard to boost the gain.

![alt text](https://bradshacks.com/wp-content/uploads/2018/10/Include-DynamiQ.png)

DynamiQ makes use of and includes a copy of [ReaComp](https://www.reaper.fm/reaplugs/ "ReaComp"), a VST plugin by Cockos.
