# gummyj
The GummyJ language

These are the executables of the GummyJ language.  

gmgenerator is the compiler of the language, which is tested and executed in 64 bit Unix.

GummyModule.jar is the library that is needed to execute GummyJ programs

TestProgram.zip contains a tester program

newsemantics.xml contains UPPAAL models



Usage:

NAME
	gmgenerate

SYNOPSIS
	gmgenerate [options]

OPTIONS
	--source=PATH, -s=PATH
		specify the path to the source-gm-script; default: standard-input
	
	--destination=PATH, -d=PATH
		specify the path to the directory to save the output-files in; default: standard-output
	
	--indentation=none|tabs|spaces|NUMBER, -i=none|tabs|spaces|NUMBER
		set indentation-style; if specified as NUMBER the given number of spaces will be used; default is 'tabs'
	
	--trace, -t
		activate parser-log-output
	
	--force, -f
		force code-generation if validation fails
	
	--log, -l
		set log-level
	
	--version, -v
		only output version-string
	

CONTACT
	Authors: 
	  Christian Fraß <fenris@wh17.tu-dresden.de>
	  Somayeh Malakuti <somayeh.malakuti@tu-dresden.de>
