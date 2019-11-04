	This directory contains macros I find useful and macros I've written
but haven't had the brains to delete.  This is the directory I point to with
TEC$MACROS.  The .TES files are the commented, slow versions.  The .TEC files
are the uncommented,  fast versions.  The .DOC files tell you how to use
the macros.
	Many of these macros come from the RSTS/E v9.5 release tape. I pulled
apart the single documentation file (TECORN.DOC) in the release to make
separate .DOC files.
						Pete Siemsen


CHANGE		allows user to change one string to another in a set of files
		specified with a wildcard filespec.  I wrote this before I
		knew about SEARCH.TEC,  and I have yet to try SEARCH.

DATE		computes the day of the week and leaves it in a q-register

DCLLC,
FORLC,
PASLC		Convert keywords in DCL, FORTRAN or PASCAL to lower case.
		These are really old and I never use them.

FMTMAC		Macro-11 formatter.

FORMAT		An aborted attempt to make a TECO macro that will pretty-print
		FORTRAN.  This macro will change edit buffers with 6 spaces at
		the front of each line into the equivalent tab-ified lines.

LOCAL		Macro-11 symbol re-orderer.

LOWCASE		load q-register L with a macro that lowercases "the rest of
		the line".  I use this to lowercase in-line comments in
		FORTRAN and C.

MAKPRNT		Makes unprintable files (like TECO source) printable by
		translating unprintable characters into printable ones.

SEARCH		Searches for a string given the string and a wildcarded
		file specification.  Allows the string to be changed.

SQU		Squishes commented TECO macros to make them fast.

TECKBM		Some weird RSTS/E thing.  See TECKBM.DOC.

TECOIN.TES	Mark Bramhall's initialization macro,  a good example of
		customization.

TECO.INI	My initialization macro,  which sets things up so the function
		keys do what they should. The commented version is TECO.TES.

TYPE		A file displayer.  The VMS TYPE command has many of the
		features of this macro,  but not all of them.  Useful on
		non-VMS systems.

UPCASE		The converse of LOWCASE.

UNSQU		Indents squished TECO macros.  I use this to help figure out
		other people's uncommented TECO macros.  Now if I can just
		get it to put back the comments...

VTEDIT		The newest version I know of of the classic TECO video editor.
