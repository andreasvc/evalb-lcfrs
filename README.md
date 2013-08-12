evalb-lcfrs
===========

An evalb implementation for LCFRS

Extension of the evalb program, to evaluate the output of a PLCFRS parser.
In the context-free case, this program should yield the same results as
evalb, but you should check that for yourself. This program returns 
only recall, precision and f-measure. It expects its input data to be in 
export format (Brants 1997) V3 (no lemma field).

Comparsion is done on the basis of "signatures", sets of bracketings
for non-terminals. Tagging is not evaluated. To match the sentences which 
are to be compared, the program uses the export sentence numbering

Author: Wolfgang Maier <maierw@hhu.de>

Release date: October 9, 2011

Current version: October 17, 2011