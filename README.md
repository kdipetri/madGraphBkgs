# madGraphBkgs
produce SM backgrounds for dark QCD pheno study


## Install Madgraph
```
wget https://launchpad.net/mg5amcnlo/3.0/3.5.x/+download/MG5_aMC_v3.5.3.tar.gz
tar -xvzf MG5_aMC_v3.5.3.tar.gz
```

## Install additional dependencies
```
cd MG5_aMC_v3_5_3 
./bin/mg5_aMC
```

Then once madgraph has started do
```
>> install pythia8
```
answer yes to install other dependencies, then exit madgraph

## Produce a SM background sample

```
./bin/mg5_aMC ../wjets.txt
``` 

You'll need to untar or unzip the output hepmc from the "decayed" step.  
