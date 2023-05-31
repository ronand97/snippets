# System path
`$env:Path += ";SomeRandomPath"`            (appends to existing path)

`$env:Path` (print path)

# add environment variable
`$env:KEY = 'VALUE'`

# Auth to azure using Azure Powershell module
`Connect-AzAccount`

change default subscription:
`Update-AzConfig -DefaultSubscriptionForLogin <subscription id>`

list available subscriptions:
`az account list`