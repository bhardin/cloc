cloc
====

Copied from http://cloc.sourceforge.net/

## Overview 

cloc counts blank lines, comment lines, and physical lines of source code in many programming languages. Given two versions of a code base, cloc can compute differences in blank, comment, and source lines. It is written entirely in Perl with no dependencies outside the standard distribution of Perl v5.6 and higher (code from some external modules is embedded within cloc) and so is quite portable. cloc is known to run on many flavors of Linux, Mac OS X, AIX, Solaris, IRIX, z/OS, and Windows. (To run the Perl source version of cloc on Windows one needs ActiveState Perl 5.6.1 or higher, Cygwin, or MobaXTerm with the Perl plug-in installed. Alternatively one can use the Windows binary of cloc generated with perl2exe to run on Windows computers that have neither Perl nor Cygwin.)

cloc contains code from David Wheeler's SLOCCount, Damian Conway and Abigail's Perl module Regexp::Common, Sean M. Burke's Perl module Win32::Autoglob, and Tye McQueen's Perl module Algorithm::Diff. Language scale factors were derived from Mayes Consulting, LLC web site http://softwareestimator.com/IndustryData2.htm.

## License

cloc is licensed under the GNU General Public License, v2 , excluding portions which are copied from other sources. Code copied from the Regexp::Common, Win32::Autoglob, and Algorithm::Diff Perl modules is subject to the Artistic License.