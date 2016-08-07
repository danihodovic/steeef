# steeef-modified

![Screenshot](https://github.com/danihodovic/steeef/blob/master/steeef-modified.png)

Zsh steeef theme as a standalone repository. The purpose behind this repo is avoid having a
dependency on oh-my-zsh when using the steeef theme. Zsh plugin managers such as Antibody can use
the theme without having to use oh-my-zsh. Credits to the original theme authors.

Modified to my liking.

# Usage
Example usage with Antibody:

    source <(antibody init)
    antibody bundle danihodovic/steeef

# Changes from the original steeef
- Removed the checks in the preexec and chpwd hooks to see if the current command is a git or vcs
  command. Instead always update the prompt.

# Credits
- Stephen Price
- Steve Losh
- Henrique Vicente
