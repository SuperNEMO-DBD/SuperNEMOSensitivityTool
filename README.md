# SuperNEMO-Sensitivity
SuperNEMO background and 0nbb sensitivity analysis

Paolo Franchini (Imperial College London) - p.franchini@imperial.ac.uk

Official SuperNEMO repository for this code: https://github.com/SuperNEMO-DBD/SuperNEMOSensitivityTool

Analysis talk: http://nile.hep.utexas.edu/cgi-bin/DocDB/ut-nemo/private/ShowDocument?docid=5170

## Requirements:

* ROOT installed and sourced (${ROOTSYS})

## Files: 

* sensitivity.cpp
* constants.h
* Makefile

## Usage:

Edit sensitivity.cpp:
* MC files
* define selections
* define number of pseudo experiment
* define range of the exposure studies

```
make
./sensitivity
```

