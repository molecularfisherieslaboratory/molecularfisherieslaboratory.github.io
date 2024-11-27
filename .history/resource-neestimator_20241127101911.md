---
---

# NeEstimator
The NeEstimator software estimates genetic effective population sizes (Ne) from genotype data.

**Price:**	This software is freely available for non-commercial scientific use
**Download:**	DOWNLOAD – Please register your details before downloading this software. Note that the email addresses will only be used for notifying downloaders of new versions of the software.
**Product author:**	NeEstimator development team
**Release date:**	December 2017.
**Version:**	2.1. This version is a major update of version 2.01
**Download format:**	2.9MB ZIP file

## Product information
NeEstimator V2 is a tool for estimating contemporary effective population size (Ne) using multi-locus diploid genotypes from population samples. By ‘contemporary’ we mean that the estimates apply to the time period(s) encompassed by the samples.

Version 2.1 is a major update on V2.01. The changes largely enhance the linkage disequilibrium (LD) capacity of the software for the estimation of genetic effective population size. Enhancements include faster estimation of Burrows r, an option to estimate r between loci on different chromosomes or linkage groups (user needs to upload linkage information), improved method of estimating jackknifed confidence intervals and improvements to the handling low frequency alleles.

Four methods are available to calculate ; three single-sample (point estimation) methods and one two-sample (temporal) method. The user needs to provide genotypic data in a common format (e.g. FSTAT, GENEPOP).

The download package (a .zip folder) contains the graphical user interface (.jar), executables for PC, Mac or Linux, test input files, an example output file, a help file (as .pdf), accessory files (mathematical details of methods implemented) and files to facilitate batch processing of input files.

## Preferred citation
When publishing results based on NeEstimator analyses, you should cite the original methods as well as NeEstimator program note. For example:

“We estimated Ne using the molecular co-ancestry method of Nomura (2008), as implemented in NeEstimator V2.1 (Do et al. 2014.).”

Do, C., Waples, R. S., Peel, D., Macbeth, G. M., Tillett, B. J. & Ovenden, J. R. (2014). NeEstimator V2: re-implementation of software for the estimation of contemporary effective population size (Ne) from genetic data. Molecular Ecology Resources. 14, 209-214.

## Computing requirements
NeEstimator V2.1 works on Windows, Linux and Mac operating systems.

MacOS users may need to install XQuartz.

The Java interface is compiled under JDK 8, but will run under Java Runtime Environment (JRE) version.

## Frequently asked questions
Q: Is there a version of NeEstimator V2 available for Mac or Linux?

A: Yes. The Java GUI is the same for all platforms; it automatically detects the operating system and calls a program called ‘Ne2L’ for Linux, ‘Ne2M’ for Mac computers or Ne2.exe for PC’s. When the software is downloaded (and the folder is ‘unzipped’) the folder will contain Ne2.exe (Windows), Ne2L (Linux), and Ne2M(Mac).

Q: How do I get a copy of NeEstimator V2?

A: Download the software from the web address above.

Q: How do I get NeEstimator V2 started once I have downloaded the installation file?

A: Download the .zip package and expand it. Among other files, it contains the java executable files “NeEstimator2x1.jar”, the help file, the Ne-program for your system:

Ne2-1.exe or windows
Ne2-1M for Mac
Ne2-1L for Linux
The two files “NeEstimator2x1.jar” and the Ne-program should be in the same directory in your machine. Once you have a copy of the installation file on your computer, double-click the icon for NeEstimator2x1.jar. You will now be able to use the software.

Q: Can I use my data that are saved in Microsoft Access or Excel?

A: Yes, you can use data from any program as long as it is saved as a text file in one of the accepted formats (GENEPOP, FSTAT).

Q: How do I uninstall NeEstimator?

A: Delete NeEstimator.jar, Ne2.exe, Ne2M or Ne2L for Windows, Mac or Linux respectively, the help file and empty the trash.

Q: How will estimates from the LD method differ from previous implementations?

A: The V2 implementation of the LD method includes the (Waples 2006) bias correction, which was not included in the version included in NeEstimator V1.3. As a consequence, LD estimates from V2 will generally be lower than those from the previous implementation. If there are no missing data, LD results from NeEstimator V2 should be identical to those obtained from LDNe (Waples & Do 2008). Some differences can be expected if not all individuals have been scored for all loci, as V2 implements an improved method for dealing with missing data (Peel et al. 2013).

More recent changes to V2.01 and V2.1 do not change the LD calculations but provide more options.

Q: How large a dataset can V2 accommodate?

A: The capacity for numbers of individuals, loci, and populations is very large, but we cannot at present identify a specific upper limit. We have successfully run the LD method on a dataset with 20-30 individuals and >46,000 diallelic (SNP) loci using a 32-bit version of the software. These analyses required consideration of over 1 billion pairwise comparisons of loci.

When there are too many loci (perhaps 100,000+), it may exceed the memory capacity of your hardware. Moreover, some parameters used as integers can be overflown, resulting in error calculations (arithmetic operations with integers are faster than with decimals).

The user can split the input file into several files with subsets of loci, or use the option of restricting loci. This issue is discussed below under section entitled “Types of genetic marker data”.

Q: Is there a 64-bit version of the software?

A: 64-bit versions are available for download for Mac, Linux and PC.

## Feedback
Please send any questions or feedback to Contact Us