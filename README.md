#### ELF file corpi used in experiments

Sourcing the repo variables depends on env variable **REPO\_ROOT**
```
/path/to/repo$ REPO_ROOT=$PWD source repo-vars.source
/path/to/repo$ printenv | grep CORPUS
CORPUS_STD=/path/to/repo/standard
CORPUS_BF=/path/to/repo/brute-force
CORPUS_ENG=/path/to/repo/engineered
```
