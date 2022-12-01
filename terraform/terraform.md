# format
`terraform fmt --recursive` format all tf files

`terraform fmt -check` check if valid format

# unlock remote state file
`terraform force-unlock <state_file_id>`

# locally configure remote back end
re configure local state to match config file, overwrite any already-initialized backend and upgrade all modules

`terraform init --backend-config <config_file> -reconfigure -upgrade`