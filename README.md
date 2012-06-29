Simrun
======

This is a simple tool to let you run n instances of a programm with the
possibility to specify how many instances should run in parallel (a little bit
like make -j for every programm...).

This comes in handy, if you want to start e.g. a huge amount of testruns.

Usage
-----

simrun -n \<num_of_processes\> [-j \<simultan>] \<cmd\>
