# Session 0

## Slack (Danilo)

## Connecting to a server, e.g. UPPMAX's rackham cluster

* UPPMAX and clusters
  - Compute and storage projects
* The SSH protocol
* Windows SSH options:
  - UPPMAX suggests MobaXterm
  - Windows 10: Ubuntu installed from Microsoft store
  - Git for Windows provides a Bash interface
* `ssh/config`
* Public key authentication/ssh-agent
* Copying files

## Basics of UNIX commands

* Command anatomy: `command argument`, `command -flags argument0 argument1`
  - `ls -l`
  - `mkdir test` `cd test`
* Fundamental commands: `ls`, `cd`, `mkdir`, `mv`, `rm`, `ln`, `pwd`, `rmdir`.
* Text files and editors
* Types of files: 
  - normal, directories and links
  - permissions and chmod, don't forget executable
* Paths: absolute and relative 
* Important files and directories: `~user` == `/home/user` `/tmp`, `/proj/NN`
* Redirection: `STDIN`, `STDOUT` and `STDERR`
* UNIX pipelines
* Transferring files to, from and between UNIX computers: `scp` (and `rsync`)
* Regular expressions:
  - `grep`
  - `sed`
* Environment: variables, aliases, login scripts (`.profile`/`.bash_profile`, `.bashrc`, (`.bash_aliases`))
* "Sourcing"
* Job control: `&`, `fg`, `bg`, `jobs`, `<ctrl>z`
