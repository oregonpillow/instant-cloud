## oh-my-zsh + powerlevel10k + neofetch with cloud-init

![screenshot](./screenshot.png)


To use, add following to user-data file:

```yaml
#include
https://raw.githubusercontent.com/oregonpillow/powerlevel10k/master/cloud-init.yml
```

## Requirements
- [iTerm2](https://iterm2.com/) (needed for image rendering)
- .zshrc on client should include (for mosh to work):
  ```bash
  export LC_ALL=en_US.UTF-8
  export LANG=en_US.UTF-8
  export LANGUAGE=en_US.UTF-8
  ```

### Tested

|OS            |Tested|
|--------------|------|
| Debian 11    |   ✓  |
| Ubuntu 22.04 |   ✓  |


