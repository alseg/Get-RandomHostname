# Random hostname generator

```
Import-Module <path>
```

```
Get-RandomHostname
Get-RandomHostname -Length 22
Get-RandomHostname -Length 5 -Number 20
Get-RandomHostname -Length 5 -Number 20 -Format Lowercase
Get-RandomHostname -Length 5 -Number 20 -Format Lowercase -DisableAlwaysStartFromLetter
Get-RandomHostname -Number 5 -Domain dev.example.com
```

```
Get-Help Get-RandomHostname -full
```