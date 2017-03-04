# syntax_parser

LabView visual instrument attempt at SQL request parsing and auto correction

* Hardware and software needed

You need the following to get this program working :

\- Labview 2013 at least<br>

* List of programs

\- syntax_parser.vi : parse and store in an array the various delimiters<br>

* How to use it

You have to provide a set of delimiters and a string to parse. Delimiters will be scanned, sorted and compared hierarchically to find and match precedence.

If there is a supposed error, the part that is doing the correction is yet to be written. Well, routed.

* Known limitations

Never really worked as expected, left here to give it a chance to live. Labview's model and prices being what they are, there is little chance I get back to it.

* Some infos

Needed to check correctness of user provided SQL requests before they were fed into the odbc driver, in the risk of crashing the whole VM.
