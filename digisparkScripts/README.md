# These are scripts for the Arduino Digispark board.

They're all used in the keyboard setting, for it to be used similarly to a Hak5 Rubber Ducky at a fraction of the cost.

Here's some more elaborate info on what they are and how to get started with them: 

# The Digispark

![Image of the board.](https://cdn.discordapp.com/attachments/590366497797570561/590488707774152714/unknown.png)

The Digispark board is an Arduino USB development board that’s low cost and small. We use it to imitate a HID to be used in the same fashion as the rubber ducky.
It costs about $2.60 USD on Amazon if bought in packs of 5. 

# Setting it up

First, download the Arduino IDE [here.](https://www.arduino.cc/en/main/software)

Then open it and navigate to **File > Preferences**. Where it says “Additional Boards Manager URLs”, paste **http://digistump.com/package_digistump_index.json**.

Next, close **Preferences**. Now open **Tools > Board > Boards Manager** and from the drop down hit **Contributed** and select **Digistump AVR Boards** and install it.

![Image of the preferences page.](https://cdn.discordapp.com/attachments/590366497797570561/590490004279525386/unknown.png)

Now, download and install [these drivers.](https://github.com/digistump/DigistumpArduino/releases/download/1.6.7/Digistump.Drivers.zip)

Next, go back to the Arduino IDE, and navigate to **Tools > Board** and select **Digispark (Default – 16.5mhz)**.

Finally, go to **File > Examples > DigisparkKeyboard > Keyboard**.

# Using the Digispark as a Ducky clone

Now, where the “Hello Digispark!” Code is, you can replace it with your own code. Note: Ducky code does NOT natively work here. However, there is a program called [Duck2Spark](https://github.com/mame82/duck2spark) that can help you with that, in addition to a GUI alternative, [MrSpark](https://mega.nz/#!oFVCRI4A!vtftblVV9g8PFrgZy3A27wUXX2DCokV_xMl3baHw-1k).

After you’ve put your code in the box, click the upload button (see visual) to begin the upload process. (IMPORTANT: WAIT TO PLUG IN THE DIGISPARK UNTIL IT TELLS YOU TO IN THE BLACK BOX BELOW) After it tells you to plug it in, plug it in. Once it says it’s done, you can either unplug it, or keep it in and it will run.

![Image of IDE](https://cdn.discordapp.com/attachments/590366497797570561/590491505710333962/unknown.png)

I hope this helps someone reading it! 
