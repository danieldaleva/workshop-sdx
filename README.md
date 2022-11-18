# workshop-sdx

1) init 1.0.0
2) Create Branch ```develop```
3) Release Candidate version **1.0.1-rc.0**
```bash
npm version prerelease --preid=rc
```
4) Create branch ```feature/feat-001``` 
5) Updated Readme.md **1.0.2-rc.0**
```bashS
npm version prepatch --preid=rc
```
6) Create PR to ```develop```
7) Merge PR to ```develop```
8) Create branch ```bugfix/bug-001```
9) Updated Readme.md for bug fix **1.0.3-rc.0**
10) **1.0.3-rc.0**
```bash
npm version prepatch --preid=rc
```