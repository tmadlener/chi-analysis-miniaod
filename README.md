#Ponia-OniaPhoton

This package is mean to be run using MINIAOD (2017 version and up)

* Setup: (it has being tested on 9_2_x should run in any of the recent cmssw releases)

```
export SCRAM_ARCH=slc6_amd64_gcc530
source /cvmfs/cms.cern.ch/cmsset_default.sh
cmsrel CMSSW_9_2_6_patch1
cd CMSSW_9_2_6_patch1/src/
cmsenv
git clone url Ponia/OniaPhoton
scram b

```

* Run: (use your favorite input sample)

```
cmsRun Ponia/OniaPhoton/test/run-chib-miniaod.py (for chib reconstruction)
```

In test directory you can find other examples to run over data and mc.
