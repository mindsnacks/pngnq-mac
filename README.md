PNGNQ-Mac
=========

This is a slightly modified version of pngnq, with an Xcode project file.

We've modified the command line interface to better support our workflow.

Original can be found at [http://pngnq.sourceforge.net/](http://pngnq.sourceforge.net/)


	Usage:  pngnq [-fhvV][-g gamma][-n colours][-Q dither][-s speed][input file][output file]
	Options:
	   -n Number of colours the quantized image is to contain. Range: 16 to 256. Defaults to 256.
	   -f Force ovewriting of files.
	   -g Image gamma. 1.0 = linear, 2.2 = monitor gamma. Defaults to 1.8.
	   -h Print this help.
	
	   -Q Quantization: n = no dithering (default), f = floyd-steinberg
	   -s Speed/quality: 1 = slow, best quality, 3 = good quality, 10 = fast, lower quality.
	   -v Verbose mode. Prints status messages.
	   -V Print version number and library versions.
	
	  Quantizes a 32-bit RGBA PNG image to an 8 bit RGBA palette PNG
	  using the neuquant algorithm.
