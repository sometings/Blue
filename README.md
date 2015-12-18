## BLUE
#### An alternative Powershell module for interacting with Azure through Azure Resource Manager. Very much work in progress.

[![Build status](https://ci.appveyor.com/api/projects/status/7346c8vmr9s6k8ql?svg=true)](https://ci.appveyor.com/project/trondhindenes/blue)

* [License](LICENSE.md)

### Design goals for the module:
* Better abstraction from Azure's APIs (i.e. more PowerShell-y)
* Make it easy to extend by providing internal functions to abstract away stuff like Rest calls etc
* Robust pipeline support (for example `Get-ArmResourceGroup | Get-ArmVm` or whatever else makes sense)

### Features working
* Simple authentication support (MS account and OrgId)¨
* Helper functions to make function development as easy as possible (the *armresourcegroup functions will serve as "templates")

### Features in progress
* Interacting with Resource Groupx
* support for credentials with multiple subscriptions

### Features planned
* Azure Automation functions
* IaaS functions
* Support for refresh tokens
