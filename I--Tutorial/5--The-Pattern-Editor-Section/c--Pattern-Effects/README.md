## Pattern Effects

(From manual)
EE - effect that will be applied to the last note activated on the current track; some effects (marked in bold) can use the last nonzero parameter when XXYY = 0:
01 - slide up (portamento up; sliding speed = XXYY);
02 - slide down (portamento down; sliding speed = XXYY);
03 - slide to note (sliding speed = XXYY);
04 - vibrato; (XX - frequency; YY - amplitude);
07 - set phase (or sample offset) XXYY in percents (from 0000 (0%) to 8000 (100%));
08 - arpeggio (XX - second note increment; YY - third note increment);
09 - set phase (or sample offset) XXYY in samples*256dec;
0A - slide velocity up/down (XX - up speed; YY - down speed);
0F - set playing speed (XXYY: 0001..001F - number of ticks per line; 0020..00FF - BPM) or time grids (XXYY: F001..F020 and F100..F120);
11 - fineslide up;
12 - fineslide down;
13 - set Bypass/Solo/Mute (BSM = XYY) flags; example of mute: 13 0001; example of solo: 13 0010;
14 - reset Bypass/Solo/Mute (BSM = XYY) flags; example of bypass reset: 14 0100;
19 - retrigger note after XXYY ticks during the line;
1C - cut note after XXYY ticks in the current line;
1D - delays the start of note until tick XXYY in the current line;
1F - set BPM;
20 - note probability;
21 - note probability with random velocity;
22 - set controller value to the random number from 0000 to XXYY;
23 - set controller value to the random number with range from XX (00..FF) to YY (00..FF);
30 - stop playing the song;
40…5F - delay an event for selected fraction of the line (from 40 (0%) to 5F (96.875%));
