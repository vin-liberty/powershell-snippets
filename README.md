# PowerShell Snippets for VSCode
This is a collection of PowerShell Snippets for VSCode.  

English | [简体中文](README-CN.md)

## Description
The Snippets are based on the built-in Alias of PowerShell5.1.  
You can use `Get-Alias` to view all built-in Alias in PowerShell if you don't know what Alias are built-in.

Some Alias are not adopted as Snippets. Some are not so useful in `ps1` script files such as `man` and `help`. And the other part is that the commands that Alias is based on have been removed in PowerShell 7 such as `Suspend-Job`，`Set-WmiInstance`, `Invoke-WmiMethod`.

Except for the built-in Alias in PowerShell, I also added some code snippets that are **not built-in Alias in PowerShell**. As follows:

|Prefix|Body|
| ------------ | ------------ |
|touch|New-Item|
|mk, mkdir|New-Item -ItemType Directory|
|wh|Write-Host|
|debug|Write-Debug|
|warning|Write-Warning|
|error|Write-Error|
|import|Import-Moodule|

**All Snippets** are as follows:
|Prefix|Body|
| ------------ | ------------ |
|ac|Add-Content|
|cat, gc, type|Get-Content|
|cd, chdir, sl|Set-Location|
|CFS|ConvertFrom-String|
|clc|Clear-Content|
|clear, cls|Clear-Host|
|clhy|Clear-History|
|cli|Clear-Item|
|clp|Clear-ItemProperty|
|clv|Clear-Variable|
|cnsn|Connect-PSSession|
|compare, diff|Compare-Object|
|copy, cp|Copy-Item|
|cpp|Copy-ItemProperty|
|curl, iwr, wget|Invoke-WebRequest|
|cvpa|Convert-Path|
|dbp|Disable-PSBreakpoint|
|del, erase, rd, ri, rm, rmdir|Remove-Item|
|ls, dir, gci|Get-ChildItem|
|dnsn|Disconnect-PSSession|
|ebp|Enable-PSBreakpoint|
|echo, write|Write-Output|
|wh|Write-Host|
|debug|Write-Debug|
|warning|Write-Warning|
|error|Write-Error|
|epal|Export-Alias|
|epcsv|Export-Csv|
|epsn|Export-PSSession|
|etsn|Enter-PSSession|
|exsn|Exit-PSSession|
|fc|Format-Custom|
|fhx|Format-Hex|
|fl|Format-List|
|foreach|ForEach-Object|
|ft|Format-Table|
|fw|Format-Wide|
|gal|Get-Alias|
|gbp|Get-PSBreakpoint|
|gcb|Get-Clipboard|
|gcm|Get-Command|
|gcs|Get-PSCallStack|
|gdr|Get-PSDrive|
|ghy, h, history|Get-History|
|gi|Get-Item|
|gin|Get-ComputerInfo|
|gjb|Get-Job|
|gl, pwd|Get-Location|
|gm|Get-Member|
|gmo|Get-Module|
|gp|Get-ItemProperty|
|ps, gps|Get-Process|
|gpv|Get-ItemPropertyValue|
|group|Group-Object|
|gsn|Get-PSSession|
|gsv|Get-Service|
|gtz|Get-TimeZone|
|gu|Get-Unique|
|gv|Get-Variable|
|icm|Invoke-Command|
|iex|Invoke-Expression|
|ihy|Invoke-History|
|ii|Invoke-Item|
|ipal|Import-Alias|
|ipcsv|Import-Csv|
|ipmo, import|Import-Module|
|ipsn|Import-PSSession|
|irm|Invoke-RestMethod|
|ise|powershell_ise.exe|
|kill, spps|Stop-Process|
|lp|Out-Printer|
|md, mkdir|New-Item -ItemType Directory|
|measure|Measure-Object|
|mv, mi, move|Move-Item|
|mount|New-PSDrive|
|mp|Move-ItemProperty|
|nal|New-Alias|
|ndr|New-PSDrive|
|ni, touch|New-Item|
|nmo|New-Module|
|npssc|New-PSSessionConfigurationFile|
|nsn|New-PSSession|
|nv|New-Variable|
|ogv|Out-GridView|
|oh|Out-Host|
|popd|Pop-Location|
|pushd|Push-Location|
|r|Invoke-History|
|rbp|Remove-PSBreakpoint|
|rcjb|Receive-Job|
|rcsn|Receive-PSSession|
|rdr|Remove-PSDrive|
|rjb|Remove-Job|
|rmo|Remove-Module|
|rnp|Rename-ItemProperty|
|rp|Remove-ItemProperty|
|rsn|Remove-PSSession|
|rv|Remove-Variable|
|rvpa|Resolve-Path|
|sajb|Start-Job|
|sal|Set-Alias|
|saps, start|Start-Process|
|sasv|Start-Service|
|sbp|Set-PSBreakpoint|
|sc|Set-Content|
|scb|Set-Clipboard|
|select|Select-Object|
|set, sv|Set-Variable|
|shcm|Show-Command|
|si|Set-Item|
|sleep|Start-Sleep|
|sls|Select-String|
|sort|Sort-Object|
|sp|Set-ItemProperty|
|spjb|Stop-Job|
|spsv|Stop-Service|
|stz|Set-TimeZone|
|tee|Tee-Object|
|trcm|Trace-Command|
|where|Where-Object|
|wjb|Wait-Job|

Hopefully it will be helpful to you.  

## Usage
---
Create or open a file with the `ps1` or `psm1` suffix in VSCode, and the plugin will take effect automatically.

## Feedback
---
If you have any questions or suggestions, please feel free to contact me.  
Email address: `zbvin@outlook.com`.   
<a href="https://github.com/vin-liberty/powershell-snippets">GitHub</a>  
<a href="https://marketplace.visualstudio.com/items?itemName=vin-liberty.powershell-snippets&ssr=false#review-details">Vscode Marketplace</a>.
