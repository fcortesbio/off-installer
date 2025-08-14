## Reqs: Win11x64
##

```powershell
winget install --id Git.Git -e --source winget
```

Extract off-dep set up; discard default configuration

Navitage to source folder
Run:

```powershell
setup /download config.xml
setup /configure config.xml
```

Activate product key
```powershell
irm https://get.activated.win | iex
```
