# New-Autoinstall
A PowerShell 7+ script which creates a cloud-init config files from a user JSON file for an Ubuntu automated installation.

# Getting Started
## Installation
To install, drop the entire New-Autoinstall folder into one of your PowerShell 7 (or later) module directories. The default PowerShell module paths are listed in the **$Env:PSModulePath** environment variable.

## Requires

* [PowerShell 7+ Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-7)

## Usage

Refer to the comment-based help in the module script for detailed usage information or see [New-Autoinstall.md](./docs/New-Autoinstall.md)

# Notes
This has only been tested on PowerShell 7 Core on Windows 10 2004. Your mileage may vary if using this with PowerShell 5.1 or PowerShell 6 (Core) and/or other OSes.

# PowerShell Local DevOps
[New-Autoinstall](https://github.com/simplenotsimpler/New-Autoinstall)

[New-PackerVbFile](https://github.com/simplenotsimpler/New-PackerVbFile)

[Invoke-PackerBuildVbVm](https://github.com/simplenotsimpler/Invoke-PackerBuildVbVm)

[DeployVbVm](https://github.com/simplenotsimpler/Deploy-VbVm)

# License
New-Autoinstall is [MIT licensed](./LICENSE).