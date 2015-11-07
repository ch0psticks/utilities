# OAT File Template

## Introduction

A 010 editor template for OAT file.

ART(Android Runtime) is the new Android runtime environment for Andorid 5.0 and later Android versions. It replaced Dalvik VM, and became the default/only runtime environment for Android OS.

Under ART, all dex files included in applications are compiled to oat files while installation. Oat file is an elf binary containing all machine code translated from dalvik bytecode. These machine code can be directly executed, and dramtically improved the Android system's performance.

Here, we developed a 010 editor template to parse oat file and help us to locate useful fields qucikly.

Hope you like it.

-----

Note that, ***currently, this template is still under development***. 

### Compatibility

Tested on oat file generated in Android lmy48m(5.1.1)

### References



1. “Hiding Behind ART,” presented at the Blackhat Asia 2015, Singapore. http://www.blackhat.com/docs/asia-15/materials/asia-15-Sabanal-Hiding-Behind-ART.pdf 

2. AOSP--Android 5.1.1_r6: [http://androidxref.com/5.1.1_r6/xref/art/](http://androidxref.com/5.1.1_r6/xref/art/)

	- dex2oat/dex2oat.cc	- runtime/oat.h
	- runtime/oat.cc
	- runtime/oat_file.h
	- runtime/oat_file.cc
	- runtime/image.h
	- runtime/image.cc

