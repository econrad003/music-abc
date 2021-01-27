The ABC files in this folder are intended to serve as "how-to" examples.  These involve tasks that I've had to figure out how to do at one time or another.  Generally these tasks involve either rendering sheet music (mainly using abcm2ps, either as a standalone program or inside EasyABC) or producing sound files (usually MIDI, generally using abc2midi, either standalone or in EasyABC).  I'm a tinkerer, so some of the examples are quite convoluted.

Loaded so far:

* clef-examples.abc - The Festin Joyeux used a mix of ordinary treble clefs (G clef with G on line 2) and modified G-clefs with G on line 1.  This shows how to produce those clefs and number of others.

  - The last two examples involving D and A clefs (which I've read mentions of but have never actually seen) won't work at all in abcm2ps (and there is no reason to expect them to), but they will still play in abc2midi.  They're an example of the sort of mad-scientist tinkering that I will try.  The remaining examples all work in abcm2ps, but they might not work in other sheet music generators.
  
  - Either I'm doing something wrong or the 15va (double ottava) clefs don't work in abcm2ps.  (I assume the former.)  If I get them working, I'll incorporate them into the examples.  The 8va (ottava) clefs are demonstrated in the examples entitled *Some G clefs*, *Some F clefs*, and *Some C clefs*.

Enjoy!
