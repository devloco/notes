```bash
# Did you forget to use "sudo" with a command? Use this alias to auto add sudo and re-run it.
# usage example:
# > apt update
# Could not open lock file /var/lib/apt/lists/lock - open (13: Permission denied)
# > oops
# (now your previous command runs with sudo)

alias oops='sudo $(fc -ln -1)'
```
