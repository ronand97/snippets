# add environment variable
`export foo=5`

# create text file
`touch my_file.txt`

# export stdout, stderror to local file in append mode
`<some_command> > temp.log 2>&1 &  # writes to temp.log file`

# Delete local branches that have been merged on remote
``git branch -d `git branch --list "?????-*"` ``

# Continously log CPU and memory usage every 5 seconds to local file
```bash
while true; do (echo "%CPU %MEM ARGS $(date)" && ps -e -o pcpu,pmem,args --sort=pcpu | cut -d" " -f1-5 | tail) >> ps.log; sleep 5; done