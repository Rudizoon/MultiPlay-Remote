# MultiPlay-Remote
MultiPlay Remote Control

Shortly after discovering MultiPlay*, I decided to use this excellent program for all my sound and
video cue playing in the local amateur theatre I'm involved with.  It meets all my needs plus more. 

However, using the mouse can be a problem as the cursor can move between cues, resulting in a missed
cue.  Using the PC keyboard was inconvenient because I like to have the notebook positioned away
from me, leaving room for following the production in the script. 

So some form of remote would be needed to make this program even more useful. 

I decided that the "GO" button would be essential, but that having the "STOP" and "All Fade" buttons
as well as the ability to move around the cuelist would be handy. 

For the microcontroller, I needed one that could emulate the keyboard, so this means a 32u4 or SAMD
micro based board such as Leonardo, Esplora, Zero, Due and MKR Family.  I settled on the Pro Micro,
as that is one I happened to have. 

After some experimentation, I found that 300 microseconds was about the right delay to build into
the code, less than this can cause repetition, and more than this created excessive delays. 

I created some layouts in Corel Draw/Inkscape, one to assist in placing the right sized holes for
the buttons in the right places, the other for the artwork that goes behind the buttons on adhesive
paper.  A copy of this artwork can be downloaded from here.  Please note that if you wish to use
this, you will need to adjust this for the box and button sizes you decide to use.
I sellotaped (cellulose tape) the drilling guide one onto the box, and drilled the holes with a 4mm
drill bit.  I then reamed them to the correct size.  I don't recommend drilling to the required size
as the larger drill bits tend to tear the plastic. 

At this stage it pays to file a slot into the end of the box to make the USB socket accessible. 

I printed the artwork onto adhesive label paper and placed this onto the box before mounting the
buttons.  Next was wiring the buttons onto the Pro Micro board and hot gluing the board into position. 

In MultiPlay, assign the keyboard shortcuts to the appropriate actions (I think only one or two are
necessary, the rest work okay from scratch).  Best way is to click on the character field in the
setup screen and push the button on the remote control. 

* MultiPlay

To find out more about MultiPlay goto $ https://www.da-share.com/software/multiplay/ $ 

To download the latest (Beta) release, visit $ https://da-share.com/forum/index.php?topic=74.150 $
- but make sure you go to the last entry on the last page to get the latest version. 
