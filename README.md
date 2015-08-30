## Description: ##
Hook into the 'Speak with Fairy Iris' skill to create a full simple trainer menu, incase you want to have fun!

## Media: ##
![complete_one.png](https://github.com/mibshidobu/owh-trainer-menu/raw/master/media/complete_one.png "Menu Media One" =696x523)

![complete_two.png](https://github.com/mibshidobu/owh-trainer-menu/raw/master/media/complete_two.png "Menu Media Two" =696x523)

![complete_three.png](https://github.com/mibshidobu/owh-trainer-menu/raw/master/media/complete_three.png "Menu Media Three" =696x523)

![complete_four.png](https://github.com/mibshidobu/owh-trainer-menu/raw/master/media/complete_four.png "Menu Media Four" =696x523)

![complete_five.png](https://github.com/mibshidobu/owh-trainer-menu/raw/master/media/complete_five.png "Menu Media Five" =696x523)

## Installation: ##
It may look complicated, but it's all really simple... trust me.
* Click the 'Download ZIP' button.
* Download the English translation of Wolf RPG Editor [here](https://www.dropbox.com/s/c7gwr2x2j2y9rqx/WolfEditorENG.zip).
* Extract *owh-trainer-menu-master.zip* and *WolfEditorENG.zip* somewhere.
* Goto ````Steam/steamapps/common/One Way Heroics/Data```` on your computer.
* Inside your *Data* folder, drag the *Event.wolf* file onto the *arc_conv.exe* program from the *WolfEditorENG.zip*. This will create a *Event.wolf.rar* file in the *Data* folder.
* Rename *Event.wolf* file to *Event.wolf.old* and extract *Event.wolf.rar*.
* Rename the extracted *Event.wolf* folder to *Event*.
* Go into the new *Event* folder and find *fairy_skilltalk_new.txt* if you have the expansion or *fairy_skilltalk.txt* if you're running vanilla.
* Rename the file to *fairy_skilltalk_original.txt* and make a new *.txt* file using the old name.
* In the new *.txt* file with the old name, simply put ````@loadfile trainermenu/home```` into it.
* Take the *trainermenu* folder from your extracted *owh-trainermenu-master.zip* folder and put it into the *Event* folder.

And bamo, you're done! Just get back ingame and talk to your fairy!

## Usage: ##
Once installed, just go ingame and speak with your fairy.

## Credits: ##
Myself - Made an awesome trainer<br />
[UTF64](https://www.reddit.com/user/UTF64)/[Reddit Link](https://www.reddit.com/r/OneWayHeroics/comments/29usz1/i_made_some_cheats) - For the original menu I based this off of and giving a method into expanding the menu even more.<br />
[Stiltzkinator](http://www.ulmf.org/bbs/member.php?u=1020)/[Forum Link](http://www.ulmf.org/bbs/showthread.php?t=22900) - Partially translated Wolf RPG Editor and provided .wolf decompression tool.