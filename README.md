# AzScalesetConfig
Stuff for managing an Azure Scales Set based build agents


To install/update the software on a Windows based build agent run the following from an
administrative Powershell.

```powershell
$ScriptFromGitHub = Invoke-WebRequest https://raw.githubusercontent.com/arvesv/AzScalesetConfig/arve/WindowsAgent/software.ps1
Invoke-Expression $($ScriptFromGitHub.Content)
```