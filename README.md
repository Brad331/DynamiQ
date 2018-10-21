# DynamiQ: Intelligent Frequency-Aware Volume Boost

DynamiQ is an open-source and modular package of scripts that allow you to boost the volume of the audio from your Windows device. It enables you to use aggressive equalizer settings without sacrificing maximum attainable volume.

### Use Cases:
DynamiQ is the best way to get much better sound from your laptop's speakers or other small speakers. Set an equalizer to correct the frequency response and put DynamiQ after it. You will get your desired frequency response yet be able to reach very high volumes when you turn it up.

### How It Works:

When more power output is demanded than possible, DynamiQ levels the bass on demand to free up just enough headroom to avoid clipping. The amount of bass attenuation varies with the loudness of the audio in real-time. This way, you're gauranteed the volume level you set but also the most ideal frequency response possible at that volume level.

### How to Install:

1. Make sure [Equalizer APO](https://sourceforge.net/projects/equalizerapo/ "Equalizer APO") is installed and working.
2. Make a folder called **DynamiQ** in **%ProgramFiles%\EqualizerAPO\config**.
2. [Download DynamiQ](https://github.com/Brad331/DynamiQ/archive/master.zip "DynamiQ") and extract its contents into that folder.
3. Include **DynamiQ\DynamiQ.txt** in your Equalizer APO config file, after any EQ you have for your speakers.
4. [Download APOpreamp](https://github.com/Brad331/APOpreamp.ahk/releases "APOpreamp") and put it in **%Username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup** so that it automatically starts at login.
6. Run APOpreamp.exe.


### How to Use:

Once your Windows volume is maxed out, keep pressing the volume up button on your keyboard to boost the gain.

You can use Equalizer APO's Editor.exe to change the bass crossover frequency in DynamiQ.txt. I have it set at 120Hz, which is the point  in my equalizer setting below which bass starts to go up dramatically.


![alt text](https://bradshacks.com/wp-content/uploads/2018/10/Include-DynamiQ.png)

DynamiQ makes use of and includes a copy of [ReaComp](https://www.reaper.fm/reaplugs/ "ReaComp"), a VST plugin by Cockos.
