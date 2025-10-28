---
layout: page
title: "Software: NeEstimator"
permalink: /neestimator
---

The NeEstimator software estimates genetic effective population sizes (Ne) from genotype data.

**Price:**	This software is freely available for non-commercial scientific use  
**Download:**	[DOWNLOAD – Please register your details before downloading this software](https://forms.gle/nAG8pxqjkFKiUfgY7)  
**Product author:**	NeEstimator development team  
**Release date:**	December 2017  
**Version:**	2.1 — This version is a major update of version 2.01  
**Download format:**	2.9 MB ZIP file  

## Product information
NeEstimator V2 is a tool for estimating contemporary effective population size (Ne) using multi-locus diploid genotypes from population samples. By “contemporary” we mean that the estimates apply to the time period(s) encompassed by the samples.

Version 2.1 is a major update on V2.01. The changes largely enhance the linkage disequilibrium (LD) capacity of the software for the estimation of genetic effective population size. Enhancements include faster estimation of Burrows r, an option to estimate r between loci on different chromosomes or linkage groups (user needs to upload linkage information), an improved method of estimating jackknifed confidence intervals, and improvements to the handling of low-frequency alleles.

Four methods are available to calculate Ne: three single-sample (point estimation) methods and one two-sample (temporal) method. The user needs to provide genotypic data in a common format (e.g. FSTAT, GENEPOP).

The download package (.zip folder) contains the graphical user interface (.jar), executables for PC, Mac or Linux, test input files, an example output file, a help file (.pdf), accessory files (mathematical details of methods implemented), and files to facilitate batch processing of input files.

## Preferred citation
When publishing results based on NeEstimator analyses, you should cite the original methods as well as the NeEstimator program note. For example:

> “We estimated Ne using the molecular co-ancestry method of Nomura (2008), as implemented in NeEstimator V2.1 (Do et al. 2014).”

Do, C., Waples, R. S., Peel, D., Macbeth, G. M., Tillett, B. J. & Ovenden, J. R. (2014). *NeEstimator V2: re-implementation of software for the estimation of contemporary effective population size (Ne) from genetic data.* Molecular Ecology Resources 14, 209-214.  

## Computing requirements
NeEstimator V2.1 works on Windows, Linux and Mac operating systems.

MacOS users may need to install XQuartz.  
The Java interface is compiled under JDK 8 but will run under Java Runtime Environment (JRE) version 8 or higher.

## Frequently asked questions

**Q:** Is there a version of NeEstimator V2 available for Mac or Linux?  
**A:** Yes. The Java GUI is the same for all platforms; it automatically detects the operating system and calls the appropriate program (‘Ne2L’ for Linux, ‘Ne2M’ for Mac, or Ne2.exe for PC). When the software is downloaded (and the folder unzipped) it contains executables for all systems.

---

**Q:** How do I get a copy of NeEstimator V2?  
**A:** [DOWNLOAD – Please register your details before downloading this software](https://forms.gle/nAG8pxqjkFKiUfgY7)

---

**Q:** How do I start NeEstimator V2 after downloading?  
**A:** Download and unzip the package. Among other files, it contains the Java executable “NeEstimator2x1.jar”, the help file, and the appropriate Ne program for your system:  
- `Ne2-1.exe` for Windows  
- `Ne2-1M` for Mac  
- `Ne2-1L` for Linux  

Ensure “NeEstimator2x1.jar” and your system-specific Ne program are in the same directory. Double-click the .jar to start.

---

**Q:** Can I use my data from Microsoft Access or Excel?  
**A:** Yes — as long as it’s exported as a text file in one of the accepted formats (GENEPOP, FSTAT).

---

**Q:** How do I uninstall NeEstimator?  
**A:** Delete the program files (`NeEstimator.jar`, `Ne2.exe`, `Ne2M`, or `Ne2L`) and empty the trash.

---

**Q:** How will estimates from the LD method differ from previous implementations?  
**A:** Version 2 includes the Waples (2006) bias correction, not present in V1.3. LD estimates from V2 will generally be lower. Results should match those from LDNe (Waples & Do 2008) if there are no missing data. V2 implements improved handling of missing data (Peel et al. 2013).

---

**Q:** How large a dataset can V2 accommodate?  
**A:** The software can handle large datasets, but performance depends on hardware. We’ve successfully run LD analysis on 20–30 individuals × >46,000 SNPs on a 32-bit system (≈1 billion pairwise comparisons). Very large datasets (100k+ loci) may exceed memory limits — users can split input files or restrict loci.

---

**Q:** Is there a 64-bit version?  
**A:** Yes — 64-bit versions are available for Mac, Linux and Windows.

---

## Feedback
Please send any questions or feedback to  
molecularfisherieslaboratory[at]gmail[dot]com