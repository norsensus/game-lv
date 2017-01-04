# GameLV - Adventure Game in Post Soviet Environment

Concept of this game were worked out by lot's of people who met in the pub.
Many of them disappeared shortly after. It happened somewhere around year 2000.
During 2001 Jānis Kovaļevskis did the programming. Artūrs Grebstelis and
Atis Grīnbergs did the artwork. We all are programmers not artists therefore
game looks the way it looks. We were young, it was Easten Europe and nobody
cared about any copyright issues - so if you spot something, please tell us
we will remove/replace/fix it. In 2002 at some 60% of completion game was
abandoned. Later in 2007 Jānis signed us up for local gamedev contest Indago.
It served as a motivation and deadline to finish the game. A friend of ours
Toms Miks made music for the game (he is also a programmer not a musician).

We got first place in that contest.

Source code of this game in directory source/ is licensed under
[GPLv2](http://www.gnu.org/licenses/gpl-2.0.html)

Data files of this game in direcory data/ is licensed under
[CC-BY](http://creativecommons.org/licenses/by/3.0/)

**Warning:** Some sound files in data/sound have unknown origin and
unknown licensing and are assumed to be freeware.
If you think otherwise please let us know.

##Ubuntu
```
sudo apt-get install libglu-dev libsdl1.2-dev libsdl-mixer1.2-dev \
	libsdl-image1.2-dev libsmpeg-dev g++ binutils
	
cd data # go to data directory
./run.sh --fullscreen # makes binary and runs game in fullscreen
```