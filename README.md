# Doug Lenat's EURISKO from SAIL archives circa 1981

These files are extracted from the SAILDART archive maintained by Bruce Baumgart, in Douglas Lenat's AM section here: https://www.saildart.org/[AM,DBL]/ 

"There was literally an ancient wizard who created a hidden artifact with legendary power, that he never shared with the world, until when he died, the seals (password on the directory) broke and the artifact was revealed" - Daj

## Notes

The whole program is contained in `EUR`, including general heuristics. Searching all of SAILDART for any RLL, TCS, or related heuristics & input data for specific domains has all come up empty.

[seveno4](https://github.com/seveno4/EURISKO) is getting this running in [Medley Interlisp](https://interlisp.org/). If you're seeking to actually run it, look there. This repo is for the unmodified original and commentary on it.

The [wiki](https://github.com/white-flame/eurisko/wiki) is active and open for anyone to post their knowledge and discoveries.

SAILDART's usage of "←" and "↑" were how those character's glyphs looked, but their original character codes mean "\_" and "^" respectively in today's ASCII. `EUR` only uses "←", in its "Snazzy" GUI code. You probably need to change those characters to "\_" in order to have the source file interpreted properly in Interlisp as plain 8-bit characters in the original pre-ASCII encoding.

I'm slowly working on a direct Common Lisp port [here](https://github.com/white-flame/eurisclo/).

Discord: https://discord.gg/vhsmVCwgvK
