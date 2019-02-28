# rekt-Friends
Close out all UO / Steam related processes

Navigate to your UO Steam file for Outlands.  
The path should be:
> C:\Program Files (x86)\Outlands Ultima Online\Steam\Profiles

Open the XML Steam profile you'd like to add the friends list to. (I used Notepad++ for code colors and ease of use)
Scroll down to roughly line 80, you should see the following line:
>  <data name="StaticFieldsMode">0x0</data>
  
After that line will be your current friends list (if applicable), which will be wrapped by the tags <friends> </friends>
Between those 2 tags, paste in the list provided here.
Save and restart Steam / UO.  Your friends list should be updated.
