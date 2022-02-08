# MyITProcess-Automation

Example automation scripts for the MyITProcess API using the PowerShell wrapper.

- Feel free to have a look around and if you have a fun script\report to share go ahead and send in a Pull Request
> Be sure check out the [MyITProcessAPI](https://github.com/Celerium/MyITProcess-PowerShellWrapper) project first before running these sample reports.

---

## Wiki & Help :blue_book:

  - Help info and a list of parameters can be found by running `Get-Help <command name>`, such as:

```posh
Get-Help .\Get-MyITProcessUsersReport
Get-Help .\Get-MyITProcessUsersReport -Full
```

## Install MyITProcessAPI Module

Be sure to have the MyITProcessAPI module installed **before** running any of the sample reports.
- The MyITProcessAPI module can be installed directly from the [PowerShell Gallery](https://www.powershellgallery.com/packages/MyITProcessAPI) with the following command:
- :information_source: This module supports PowerShell 5.0+ and should work in PowerShell Core.
```posh
Install-Module -Name MyITProcessAPI
```

If you are running an older version of PowerShell, or if PowerShellGet is unavailable, you can manually download the *Master* branch and place the *MyITProcessAPI* folder into the (default) `C:\Program Files\WindowsPowerShell\Modules` folder.

After installation (by either methods), load the module into your workspace:

```posh
Import-Module MyITProcessAPI
```