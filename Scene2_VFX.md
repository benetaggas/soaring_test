# Scene 2 — Tile-Clear VFX Technical Breakdown

Tech Art notes:

The usual animation workflow im comfortable with is the animator controller, graphs and blend trees. Playable Director was a new Unity component that I had'nt used before, so I asked Claude to guide me through the fastest and most efficient way to finish the task. The scene layout, anchoring and heirarchy I setup manually (I'm good at this) and Claude gave me an editor script I could run to create placeholder wiring of the timelines in the Playable Director along with with placeholder anim files. (Hooray Claude for this idea as writing actual animation code was not allowed) The rest was a matter of keying in animations with an approximate length of 30 frames per clip and once I started playing with the sequencer I understood just how much fun this system is and how quickly animation sequences can be duplicated and reused. The result is a bouncy and juicy match 3 tile clear sequence as requested. The burst and circular particles during the tile drop vfx sequence could have been done better although in my defence the time constraints given had me compromise on that. Cheers!

