Maschine AutoSave
By TvHeaded Robots, 2012
http://blog.tvheadedrobots.com/

Maschine AutoSave is an AppleScript that implements an autosave function
in Native Instruments Maschine drum machine software. The script will 
detect if Maschine is running and if it is the application that has focus
if it is it will perform a [Command]+S keystroke every 5 minutes (by default.)
This is by no mess a perfect solution and is not a replacement for a properly 
implemented autosave feature, but it will effectively save you from loosing
hours of work because you forgot to save.


How to use this script

Setup:
1. If you have installed NI's Maschine in the default location of 
   Macintosh HD:Applications:Native Instruments:Maschine:Maschine then
   you can use the compile binary found in "Maschine AutoSave.zip"
	A. Unzip "Maschine AutoSave.zip" 
	B. Copy the resulting "Maschine AutoSave" into a safe location,
	   such as you Maschine folder.
	C. Launch the "Maschine AutoSave" application. 
	D. Once Maschine starts your set will be automatically saved every 5 minutes.

2. If you have not installed NI's Maschine in the default location you will need to edit
   a line in the script.
   A. Locate the path to your Maschine executable. 
   B. open the Maschine AutoSave.scpt file in the AppleScript editor.
   C. Find the 5th line, you notice a comment above it that talks about changing the 
      line incase Maschine isn't installed in the default path. 
   D. Change the "Macintosh HD:Applications:Native Instruments:Maschine:Maschine" 
      part of the line to point to the location of your Maschine executable.
   E. Now click File->Save As
   F. In the save dialog select "Application" from the File Format: dorp down, then 
      pick a good place to save the file and click save.
   G. See step "1-C" above
	
NOTE: 
      A. Maschine AutoSave will automatically launch Maschine when it is run. If 
         you want the AutoSave functionality to work you must use the Maschine 
         AutoSave application to launch Maschine.
      B. If you do not save your set before the first autosave interval you will be 
         prompted to name ans save you set. After doing this you will no longer be
         prompted when autosave occurs. (I am planning to try to implement 
         autosaveing to a separate autosave file rather than the current file. This 
         may be difficult to do in AppleScript though.)