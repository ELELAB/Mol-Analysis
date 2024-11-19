## Files required:
  - config.cfg and output files from GROMACS simulation

## Run the script:

```
module load python/3.10/modulefile
source /usr/local/gromacs-2024/bin/GMXRC.bash
python -u ../Mol_Analysis.py -f config.cfg -nt 8
```

