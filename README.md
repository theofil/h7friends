# h7friends
Python script to create ROOT friend tree starting from a NANOGEN file. For creating NANOGEN starting from GEN see the ```makeNanoGEN.py``` script for example, or refer to [https://github.com/kdlong/WMassNanoGen/blob/master/runCmsDriverGenToNanoGEN.sh](https://github.com/kdlong/WMassNanoGen/blob/master/runCmsDriverGenToNanoGEN.sh)

Examples:

```
python -i makefriends.py DYJetsToLL_M-50_TuneCP5_13TeV-amcatnloFXFX-pythia8/13D0AD97-6B32-CB4C-BA87-5E37BA4CF20E.root --xs 6404.4 --output amc.root  &
python -i makefriends.py DYToLL_NLO_5FS_TuneCH3_13TeV_matchbox_herwig7_cff_py_GEN_NANOGEN_inNANOAODGEN.root --xs 6009.0 --output h7mbox.root &

python -i makefriends.py DYJetsToLL_M-50_TuneCP5_13TeV-amcatnloFXFX-pythia8/*root --xs 6404.4 --output amc@nlo-py8.root  &
python -i makefriends.py PPD-RunIISummer20UL18GEN-00014/497AD23B-7A83-FB4C-A70E-52BB92F1EB54.root --xs 3953 --output herwig_r15.root
```
