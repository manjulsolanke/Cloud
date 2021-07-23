
az --version
az login # Sign into an azure account
az account show # See the currently signed-in account.
az account show --output table  # See the currently signed-in account in table format
az account list --query "[?isDefault]" ## get the current default subscription using list
az account list --query "[?isDefault == \`false\`]" # get a list of subscriptions except for the default subscription

azure-spring-cloud-workshop-manjul

#kgp --sort-by='.metadata.creationTimestamp'