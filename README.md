# basic-benchmarks

This repository is used to collect benchmarks used for testing the performance of BBC BASIC and its derivatives.  Most the the becnhmarks in this repository have come from other sources on the Internet.  Links to the original sources of the benchmarks are placed in REM statements in the code.  There are up to three sources files in each directory

1. Files ending in 'S' are Subtilis source files.
2. Files ending in 'BAS' are BBC Basic V source files in text form.  They need to be tokenized before they can be run.
3. In some directories there are source files ending in 'ABC'.  These are versions of the BBC Basic files that will compile with the ABC compiler.  Sometimes, this compiler can't cope with the standard BBC BASIC source and so separate sources are needed.  Sometimes there are three different versions of the ABC files
  1. Files ending in 'BAS' or 'ABC'.  These use the default compile options for ABC.
  2. Files ending in 'ABCOpt'.  These enable some ABC optimisations including disabling escape checking
  3. Files ending in 'ABCOptEsc'.  These enable the ABC optimisations as two but explicitly check for escapes at the entry point to functions, procedures and loops (to mirror the behaviour of Subtilis).