# Linux configuration files

## Git prompt in bash

Files:

- `bashrc-git-prompt`: the bash script code for enabling the git prompt in bash, should be appended to `.bashrc` on the target machine
- `git-prompt.sh`: the bash script code adding the git prompt in bash (by Shawn O. Pearce), should go int `/home/<user>/.git-prompt.sh` to be called correctly with the code from `bashrc-git-prompt`.

## Tmux configuration

Files:

- `tmux.conf`: Preferred configurations for `tmux`, should go into `/home/<user>/.tmux.conf`
