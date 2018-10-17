### Install MAME4ALL_PI edition

Download
[Link 1](https://sourceforge.net/projects/mame4allpi/)
[Link 2](https://github.com/RetroPie/mame4all-pi)

##### What is MAME4ALL_PI edition?
An old version of MAME that was created specifically for the Raspberry Pi to play much faster than the newer versions with the aim to run games with 0% dropped frames.

##### Installation
For the Pi Store version place the ROMS in the directory:
```sh
/usr/local/bin/indiecity/InstalledApps/mame4all/Full/roms/
```

| File Name | Info |
| ------ | ------ |
| mame | MAME and frontend |
| mame.cfg | MAME configuration file, limited support to only the options in the supplied file (not the full MAME settings). |
| cheat.dat | Cheats definition file |
| hiscore.dat | High Scores definition file |
| artwork | Artwork directory |
| cfg | MAME configuration files directory |
| frontend | Frontend configuration files |
| hi | High Scores directory |
| inp | Game recording directory |
| memcard | Memory card files directory |
| nvram | NVRAM files directory |
| roms | ROMs directory |
| samples | Samples directory |
| skins | Frontend skins directory |
| snap | Screen snapshots directory |
| sta | Save states directory |

##### To run MAME run "mame" executable for GUI frontend.
```sh
./mame
```
##### To run "mame" without GUI
```sh
./mame {gamerom} (gamerom is the game to run)
```
It will work in X-Windows or in the Console (which is preferred).

For the prebuilt image you have been supplied, the Roms folder has been moved to within the Mame folder, see “ROMs directory” above.

[Troubleshoot](https://github.com/RetroPie/mame4all-pi)

##### Supported Games
Folder names or ZIP file names are listed on "gamelist.txt" file.
Romsets have to me MAME 0.37b5 ones (July 2000)
Additionaly there are additional romsets from newer MAME versions.

Use "clrmame.dat" file to convert romsets from other MAME versions to the ones used by this version, using ClrMAME Pro utility, available [Here](http://mamedev.emulab.it/clrmamepro/)

Note: File and directory names in Linux are case-sensitive. Put all file and directory names using lower case.

##### Sound Samples
The sound samples are used to get complete sound in some of the oldest games.
They are placed into the 'samples' directory compressed into ZIP files.
The directory and the ZIP files are named using low case!

The sound samples collection can be downloaded [Here](http://dl.openhandhelds.org/cgi-bin/gp2x.cgi?0,0,0,0,5,2511)

You can also use "clrmame.dat" file with ClrMAME Pro utility to get the samples pack.

##### Artwork
Artwork is used to improve the visualization for some of the oldest games.
Download [Here](http://dl.openhandhelds.org/cgi-bin/gp2x.cgi?0,0,0,0,5,2512)