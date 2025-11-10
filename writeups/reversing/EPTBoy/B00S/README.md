# Writeup: EPTboy
## Team: B00S
Author: xaos333

**Unintended solve - EPTBoy**

The challenge EPTBoy was to beat the game on one of the onsite Analogue Pocket systems.

![](system.png)

Between the Start and Select buttons, the Analogue Pocket system has a 3rd button, called "Analogue".
Pressing it brings the user to the Analogue menu, as seen in the image below.

![](menu.png)

Here, we can find the "Memories" section, which is just another name for "savestates". If while playing the game, the user holds down the DPAD-Up button along with the Analogue button, the system creates a save-state, which is then stored in the Memories tab.

![](keybind1.png)
![](manual.png)

If the player dies, entering the Memories tab in the Analogue menu and selecting the newest savestate brings the player back.
By saving a couple of times before crucial moments, it makes it extremely easy to beat the game. 

![](states.png)
After doing this a couple of times (I used a total of 6 savestates), we get to the end of the game really quickly, and retrieve the flag: 
``EPT{EPT_BOY_MASTER}``

Who needs the konami code when you have savestates?
