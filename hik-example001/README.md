# oq-haz-example
An example workout for hazard calculation using OpenQuake to generate a hazard map. This example is based on Grand Inversion ERF model for Hikurangi-interface. 

## Setup conda environment

```
cd gmcm-haz-sensitivity
conda env create -f environment.yml
```

## Quick Description

```
Hik-interface-ERF contains files for source model
gmm contains files for ground motion models

job file is hazmapjob-grin-hik-MSR_LW.ini
```

## Command  
```
oq engine --run hazmapjob-grin-hik-MSR_LW.ini

optional argument can be: --exports csv

```

More details can be found online: https://docs.openquake.org/manuals/OpenQuake%20Manual%20%28latest%29.pdf


