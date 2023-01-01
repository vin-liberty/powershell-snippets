# PowerShell Snippets for VSCode
适用于VsCode的PowerShell代码片段插件。 

[English](README.md) | 简体中文

## 介绍
---
代码片段基于PowerShell5.1的内置别名设置。  
如果你不知道PowerShell中有那些内置别名，你可以在PowerShell中使用 Get-Alias 命令查看所有内置别名。

一些别名没有被采用为代码片段。因为我觉得这些别名不会在`ps1`脚本文件中用到，比如`man`和`help`。另一部分是别名基于的命令在PowerShell 7中已被删除，包括命令`Suspend-Job`，`Set-WmiInstance`, `Invoke-WmiMethod`。

除了PowerShell中内置Alias，我还添加了一些**不属于PowerShell内置Alias中的代码片段**。如下：
|Prefix|Body|
| ------------ | ------------ |
|touch|New-Item|
|mk, mkdir|New-Item -ItemType Directory|
|wh|Write-Host|
|debug|Write-Debug|
|warning|Write-Warning|
|error|Write-Error|
|import|Import-Moodule|

**所有代码片段如下：**
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

## 使用
---
在VsCode中创建或打开`ps1`或者`psm1`后缀文件，插件会自动生效。

## 反馈
---
邮箱：`zbvin@outlook.com`。  
<a href="https://github.com/vin-liberty/powershell-snippets">GitHub</a>  
<a href="https://marketplace.visualstudio.com/items?itemName=vin-liberty.powershell-snippets&ssr=false#review-details">Vscode Marketplace</a>。  

