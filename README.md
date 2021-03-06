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

Updates:
* 8 Apr 2020 - added transcriptions from the Malchair musical manuscript.  (Music representing about 30-4 pages of the 134-page MS, plus notes are contained in the transcriptions.)  A complete set of transcriptions (also both more official and more literal) may be found at https://github.com/Gubbledenut/ABC_TuneBooks in the file there named "Malchair.abc".
* 21 Jan 2021 - transcriptions of the first 15 tunes in Festin Joyeux (1732).  See comments in the ABC file for more information.  The entire book (PDF, 150 MB) is available online from the French National Library's Gallica (Bibliothèque Nationale - Gallica) collection, free and without registration.
* 24 Jan 2021 - tunes 16-30 in Festin Joyeux (1732).  (There are 49 tunes in the collection.)
* 26 Jan 2021 - tunes 31-49 in Festin Joyeux (1732).  (There are 49 tunes in the collection.)
* 01 Feb 2021 - Ancient Greek hymns: (1) The Seikilos epitaph (6/8 meter) 1st c CE; (2) First Delphic hymn to Apollo (5/8 meter) 2nd c BCE.
* 13 Feb 2021 - removed one file

