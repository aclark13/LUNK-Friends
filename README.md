# rekt-Friends

## How to use the list
Close out all UO / Steam related processes

Navigate to your UO Steam file for Outlands.  
The path should be:
> C:\Program Files (x86)\Outlands Ultima Online\Steam\Profiles

Open the XML Steam profile you'd like to add the friends list to. (I used Notepad++ for code colors and ease of use)

Scroll down to roughly line 80, you should see the following line:
> ```<data name="StaticFieldsMode">0x0</data>```
  
After that line will be your current friends list (if applicable), which will be wrapped by the tags 
> ```<friends> </friends>```

Between those 2 tags, paste in the list provided here.  The top half of the list has been verified to be a rekt character, and the discord name has been added to the name.  The lower list...below the ```***********``` are characters (or pets) that people have had on their friends list.  These are not verified and should be used __**at your own risk**__. *If using the whole list, take out the ```***********```.*

Save and restart Steam / UO.  Your friends list should be updated.

## How to pull your character information
In UO Steam go to the "Macros" tab and click on "Object Inspector".  
![Object Inspector](https://i.postimg.cc/852JyRrg/Object-Inspector.png)

This will bring up a targeting cursor in UO.

Target your charater, or any alt that you'd like to add to the list
![Targer](https://i.postimg.cc/m2G1CSsQ/target.png)

When the "Object Inspector" box pops up, note the Serial for your character.  You can copy this by using "ctrl+v"
![Inspector Window](https://i.postimg.cc/T2bWK4Zd/serial.png)

## Submitting your character to the list
You can either send me a screen shot of your character paperdoll (name) and the object inspector (serial), or you can format it for the list, and send me that.  The format is:
> ```<friend name="CHAR-NAME (DISCORD NAME)">SERIAL</friend>```

