# Performance Profiling Example Traces

These traces accompany the NAG [Webinar](https://www.youtube.com/watch?v=t7yBoq6183A) and [Blog
Series](https://www.nag.co.uk/content/application-performance-profiling-part-1-what-profile) on
performance profiling.

These traces were created using the [Extrae](https://tools.bsc.es/extrae) and
[Darshan](https://www.mcs.anl.gov/research/projects/darshan/) profiling tools.  The example
application profiled for these cases was the [EPOCH]() open source PIC code.  EPOCH was run in all
cases using 8 MPI ranks.

## Using these Files

This repository contains three objects:

* `extrae` - This directory contains the Extrae trace and instructions for use

* `darshan` - This directory contains the Darshan trace and instructions for use

* `input.deck` - This is the original EPOCH input file used when generating the traces
