# music-abc
a place for my abc music transcriptions from old manuscripts.

ABC is a portable notation for transcribing music.  It can be use equally for sharing tunes on index cards or, using a text editor, on a computer.  A number of computer tools are available for working with ABC notation:

  abcm2ps - a command line program for converting music from ABC notation into sheet music
     github project: https://github.com/leesavide/abcm2ps
  abc2midi - a command line program for converting music from ABC notation into MIDI files
     official site: https://ifdo.ca/~seymour/runabc/top.html
     (scroll down the page for more information on where to get source and binaries.)

There are a number of graphical user interfaces which can facilitate creating ABC collections. (I use EasyABC.)  Information on these and other tools can be founs at the ABC+ Project site:
      http://abcplus.sourceforge.net/#ABCGuide
More information can be found at: http://abcnotation.com/

As a simple example, here is my transcription of the children's song *Skip to my Lou*:

```abc
X:1
T:Skip to my Lou
C:Traditional
M:4/4
R:reel
L:1/4
Q:1/2=90
K:G
"G"B2G2 | BB/B/d2 | "D"A2F2 | AA/A/ "C"c2 |
"G"B2G2 | BB/B/d2 | "C"Ac/c/ "D"AD | "G"G2 G2 |]
```

The first header (X:) is the index number 1.  The remaining headers are data about the song, including title, time signature (4/4) and key (G).  The last two are the music.  The quoted string are the guitar chords "G", "C" and "D" - fancier chords like "D7" and "Dm", and "Dsus2" are also available. The rest of the music are notes. (CDEFGAB cover middle C to B above middle C, and cdefgab cover the next octave. Since the key is G, F and f represent F-sharp.  For other octaves and accidentals, consult the ABC standard.)

ABC 2.1 standard: http://abcnotation.com/wiki/abc:standard:v2.1
