February 28, 1993

Dear Beta (or in this case, Pre-Alpha) Tester,

Yes, this is the...

	@@@@   @@@   @@@  @   @
	@   @ @   @ @   @ @@ @@
	@   @ @   @ @   @ @ @ @
	@   @ @   @ @   @ @   @
	@@@@   @@@   @@@  @   @

	       PRE-ALPHA!

Your mission: see if DOOM runs on your system.  On some 386s, we have seen 
major slowdown compared to other 386s.  Please include your system stats.  
DOOM at the present time requires 4 Meg of memory.

WHAT IS IN THE PRE-ALPHA
o Four levels-in-progress (1,2,3, and 8)
o Five stub levels (4,5,6,7, and 9)
o Light diminishing
o Light levels
o Monsters "spawning" (but not "thinking" or "moving")
o Different resolution modes of play (all but hi-res available now)
o Animating floors
o Automapping
o Other stuff

WHAT IS NOT IN THE PRE-ALPHA
o Artistic item sprites
o Finished levels
o Real menu
o True network or modem interaction
o All the weapons
o Disgusting displays of gibletty horror and mayhem
o Music, sound effects
o Other stuff

And now, let's look at the controls . . . .

WHAT    KEY     RESULT
Menu    Esc     Go back to Menu (In Menu, go back to game)
	1-9     In menu, go to that level #
	Q       Quits

Game    Ctrl    Fires
	Alt     Strafe/Use (Use doesn't do anything right now)
	Arrows  Move around
	R.Shift Run (with any up or down key)
	1-4     Select weapon

Detail  Q       High detail (for 486s, pretty much)
	W       Medium detail (default)
	E       Low detail (for slower systems)
	R       Use High-color DAC (160 x200, but great color!)
		(Only newer VGA cards have this-if it looks OK, ya got it)
		(This may--okay, will--REALLY screw up the playscreen's
		 graphics.  Just look at the neat colors and don't worry.)

Window  A       Full screen
	S       Regular (helmet view)
	D       Reduced (small helmet view)

Texture Z       Full texture mapping
mappin' X       Ceilings not texture mapped
	C       Floors and ceilings not texture mapped (the Wolf key)

And, ya know, you can use the mouse, just like Wolfenstein.

WHAT YOU NEED TO TEST
o Does it run on your system in:
	o High color DAC mode
	o Regular (helmet) view
	o Small screen view
	o Full screen view
	o Low detail
	o Medium detail
	o High detail

Do any blow-ups occur?  If so, could you press CTRL-ALT-DEL to get out of it?

IMPORTANT!
Go to level 7. Make sure you are at Medium Detail (W), Normal Playscreen (S), 
and Full Texture-mapping (Z). Press T.  The program will time its 
performance.  When it exits to DOS, WRITE DOWN AND REPORT THE NUMBERS IT 
PRINTS OUT.  A 383/33 should be at about 23 frames per second, and a 486/50 
with local bus can go 97 frames per second!

Do not press P.  P starts a profile accumulation.  Hitting P again saves it 
off and quits.  So, in summation, don't hit P.

As you run around, a gauge on the lower left shows tics/frame. If the gauge 
reads seven, you are in too high a detail mode for fun play.  Four is decent.

Try and run DOOM with your normal environment first.  If that doesn't work, 
try a bare boot.
