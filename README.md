circlator
=========

A tool to circularise bacterial genome assemblies




Installation
------------

circlator has the following dependencies, which need to be installed:
  * [BWA] [BWA] version >= 0.7.12
  * [prodigal] [prodigal] >= 2.6
  * [samtools] [samtools] (version 0.1.9 or 1.2)
  * [MUMmer] [mummer] version >= 3.23
  * [SPAdes] [spades] version >= 3.5.0


Once the dependencies are installed, install circlator using pip3:

    pip3 install circlator

Alternatively, you can download the latest release from this github repository,
or clone the repository. Then run the tests:

    python3 setup.py test

If the tests all pass, install:

    python3 setup.py install


Usage
-----

The input is an assembly in FASTA format and corrected long reads in FASTA or FASTQ format. To run:

    circlator all assembly.fasta corrected_reads.fasta output_directory

The final output file is called

    output_directory/06.fixstart.fasta


  [BWA]: http://bio-bwa.sourceforge.net/
  [mummer]: http://mummer.sourceforge.net/
  [prodigal]: http://prodigal.ornl.gov/
  [samtools]: http://www.htslib.org/
  [spades]: http://bioinf.spbau.ru/spades


