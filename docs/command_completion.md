# Command completion 

**Note**: this is only needed for `homebrew` and `MacPorts` installations, as when installing the shell function mannually via [source the shell function](#source-the-shell-function), the completion script is already included.

Install the completion script by running:

### Bash

```sh
echo 'source <(switch completion bash)' >> ~/.bashrc
```
### Zsh
```sh
echo 'source <(switch completion zsh)' >> ~/.bashrc
```
### Fish
```sh
echo 'kubeswitch completion fish | source' >> ~/.config/fish/config.fish
```