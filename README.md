```
$f = "$env:TEMP\AllowScripts.cmd"; iwr "https://github.com/hytthynn/WinSux/raw/refs/heads/main/AllowScripts.cmd" -OutFile $f; Start-Process $f -Verb RunAs
```

```
iwr https://github.com/hytthynn/WinSux/raw/refs/heads/main/WinSux.ps1 -useb | iex
```
