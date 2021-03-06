When you find a bug which has steps that are difficult to explain, you 
can save the development team lots of time trying to repeat your bug by 
recording your gameplay.

##How it works
When you record your gameplay, you record the keypresses you made during 
gameplay into a text file. This can then be run by someone who needs 
more information about your bug.

##How to do record
You need to be able to use the command line.
Open the command line, and run SuperTux with these arguments 

``supertux2 <level file> --record-demo <demo filename>.txt``.

``<demo filename>`` should be a path on your computer where you wish to save the demo recording.

**Note: You have no obligation to use the extension .txt, but this
means you can easily just drag it into the GitHub comment box**

##How to play recordings
Then, after recording your bug in action, test it out using

``supertux2 <level file> --play-demo <demo filename>.txt``

##Uploading to GitHub
Finally, drag the demo file into your issue report 
Also drag in the level used to record the gameplay (rename to 
``issueXYZ.stl.txt`` as GitHub is okay with .txt),
or name it if it exists in an addon or is included already in the game.
