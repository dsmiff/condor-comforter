# condor-comforter
Helper routines for using condor at Bristol, particularly aimed at CMS users.

These will probably be a little hacky, but should offer some inspiration for other users.

Please report any issues, and add any helpful scripts for other users!

I take no responsibility for your results using these - with great power comes great potential for DDOS'ing DAS.

##cmsRunCondor

This holds example code for running CMSSW jobs on condor. Like CRAB3, but on condor.
Very much a work in progress!

TODO:
- figure out how to use user's code, not clone from git
- use the fact that /users is readable

##exampleDAG

This holds a simple example of a DAG (directed acyclic graph), i.e. a cool way to schedule various jobs, each of which can depend on other jobs.
Also includes a neat little monitoring script for DAG jobs
