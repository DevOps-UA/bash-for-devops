# Using Bash for Devops

## How to improve Bash error handling with the set builtin

This repo contains example files for [Using Bash for DevOps](https://medium.com/expedia-group-tech/using-bash-for-devops-7046eed1aa63), a blog post on Expedia Group Technology. The blog post contains full instructions for using the scripts.

To clone the repo

```
git clone https://github.com/jakecollins/bash-for-devops

cd bash-for-devops
```

To reset the files and start again source the reset script as shown below, then type `y` at the confirmation dialogue. 

```
source 0-reset-tutorial.sh
```

Note, you must use `source` to run the reset script above to ensure the `file_name` variable is unset. The other scripts in the repo **should not** be run using `source`.
