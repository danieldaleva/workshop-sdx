# workshop-sdx

1) init 1.0.0
2) Create branch ```develop```
3) Release Candidate version **1.0.1-rc.0**
```bash
npm version prerelease --preid=rc
```
4) Create branch ```feature/feat-001```
5) update readme.md feat-001
6) **1.0.2-rc.0**
```bash
npm version prepatch --preid=rc
```