
# GitHubActions _(0.7.0)_
Supports interacting with Github Actions environment
| Cmdlet | Synopsis |
|-|-|
| [Add-ActionPath](Add-ActionPath.md) | Prepends path to the PATH (for this action and future actions). |
| [Add-ActionSecretMask](Add-ActionSecretMask.md) | Registers a secret which will get masked from logs. |
| [Enter-ActionOutputGroup](Enter-ActionOutputGroup.md) | Begin an output group. |
| [Exit-ActionOutputGroup](Exit-ActionOutputGroup.md) | End an output group. |
| [Get-ActionContext](Get-ActionContext.md) | Returns details of the executing GitHub Workflow assembled from the environment. |
| [Get-ActionInput](Get-ActionInput.md) | Gets the value of an input.  The value is also trimmed. |
| [Get-ActionInputs](Get-ActionInputs.md) | Returns a map of all the available inputs and their values. |
| [Get-ActionIssue](Get-ActionIssue.md) | Returns details of the issue associated with the workflow trigger,<br/>including owner and repo name, and the issue (or PR) number. |
| [Get-ActionRepo](Get-ActionRepo.md) | Returns details of the repository, including owner and repo name. |
| [Invoke-ActionWithinOutputGroup](Invoke-ActionWithinOutputGroup.md) | Executes the argument script block within an output group. |
| [Set-ActionFailed](Set-ActionFailed.md) | Used as a shortcut for `Write-ActionError` and `exit 1` |
| [Set-ActionOutput](Set-ActionOutput.md) | Sets the value of an output. |
| [Set-ActionVariable](Set-ActionVariable.md) | Sets env variable for this action and future actions in the job. |
| [Write-ActionDebug](Write-ActionDebug.md) | Writes debug message to user log. |
| [Write-ActionError](Write-ActionError.md) | Adds an error issue. |
| [Write-ActionInfo](Write-ActionInfo.md) | Writes info to log with console.log. |
| [Write-ActionWarning](Write-ActionWarning.md) | Adds a warning issue. |
###### Copyright (C) Eugene Bekker.  All rights reserved.
