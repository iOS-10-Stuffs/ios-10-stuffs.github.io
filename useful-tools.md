--- 
layout: default 
title: Useful Tools 
---

## A List Of Useful Tools

### jtool

  The jtool command is meant to meet and exceed the functionality to XCode's otool(1), picking up along the way additional 
  Mach-O commands such as atos(1), dyldinfo(1), nm(1), segedit(1), pagestuff(1), strings(1) , and even codesign(1) and the 
  informal ldid. jtool also provides novel features, such in-binary search functionality, symbol injection and a disassembler 
  functionality with (limited but constantly improving) emulation capabilities. It also provides color output. Most importantly,
  it can be run on a variety of platforms - OS X, iOS, and even Linux. It is ENTIRELY FREE for use of any type.
    
  More info can be found [here](http://newosxbook.com/tools/jtool.html).


### joker

  Joker is a quick and dirty iOS kernelcache handling utility Jonathan Levin has written ^(as well as jtool) to assist in reverse 
  engineering. Apple tries their damn hardest to make reversing the kernel as hard as possible: With every release, more symbols
  are stripped. The kernelcache, being prelinked, requires less symbols to begin with (and tables in memory, as all LINKEDIT 
  segments, are jettisoned). And - let's not forget - the kernelcache is encrypted. 32-bit kernelcaches can be decrypted thanks 
  to the holy work by @xerub and others, but no 64-bit kernelcache keys exist (publicly), and the only way to "see" the kernel 
  is by dumping it.
    
  More info can be found [here](http://newosxbook.com/tools/joker.html).
