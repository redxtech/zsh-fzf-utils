# fzf-utils
> fzf-utils is a zsh plugin that provides functions which use fzf to do cool things.

## Installing

### zinit
Add this to your zinit config (.zshrc):
```zsh
zinit light redxtech/zsh-fzf-utils

# it also works with turbo mode:
zinit ice wait lucid
zinit load redxtech/zsh-fzf-utils
```

### oh-my-zsh
Install it with your favourite zsh package manager, or clone it directly to your
`$ZSH_CUSTOM/plugins` directory with git, and add `zsh-fzf-utils` to the plugins
array in your `.zshrc` file:

```zsh
plugins=(... zsh-fzf-utils)
```

## Usage
`kp` is very easy to use, simply run the command with the name of the
process you wish to kill as the only arg:

```zsh
kp <process name>
```
`fp` is also very easy to use. Simply run the command and select the directory
in your path that you want to search, and then you can see all the binaries
inside that directory.
```zsh
fp
```

## Credit
I adapted these functions from this medium article:
[How FZF and ripgrep improved my workflow][1].

[1]: https://sidneyliebrand.medium.com/how-fzf-and-ripgrep-improved-my-workflow-61c7ca212861

## Author
**fzf-utils** © [Gabe Dunn](https://github.com/redxtech), Released under the [MIT](./license.md) License.

