# betterbrew-zsh-plugin - better command aliases for the macOS Homebrew Package Manager in zsh

`betterbrew-zsh-plugin` contains short aliases for all homebrew commands.

This is for my personal use and is always a work in progress. Feel free to hang with it.

## Example

Without typing full homebrew commands in console, like:
```console
$ brew install zsh --build-from-source
```

there is more convenient alias:
```console
$ bifs zsh
```

## Installation on oh-my-zsh

1. Go to `oh-my-zsh` plugins directory:

    ```console
    $ cd ~/.oh-my-zsh/plugins
    ```

2. Clone the repository into a new directory `betterbrew` :

    ```console
    git clone https://github.com/timothyrowan/betterbrew-zsh-plugin.git betterbrew
    ```

3. Enable `betterbrew` plugin by adding to your .zshrc configuration file:

    ```console
    plugins=(betterbrew)
    ```

4. Restart your shell.

## Aliases

| Alias  | Command         |
|:-------|:----------------|
| br     | brew            |
| brana  | br analytics    |
| brcat  | br cat          |
| brcle  | br cleanup      |
| brcom  | br command      |
| brcoms | br commands     |
| brcon  | br config       |
| brdep  | br deps         |
| brdes  | br desc         |
| brdiy  | br diy          |
| brdoc  | br doctor       |
| brfet  | br fetch        |
| brgis  | br gist-logs    |
| brhom  | br home         |
| brinf  | br info         |
| brins  | br install      |
| brlea  | br leaves       |
| brlis  | br list         |
| brln   | br ln           |
| brlog  | br log          |
| brmig  | br migrate      |
| brmig  | br missing      |
| broca  | br --cache      |
| broce  | br --cellar     |
| broen  | br --env        |
| bropr  | br --prefix     |
| bropt  | br options      |
| brore  | br --repository |
| brout  | br outdated     |
| brove  | br --version    |
| brpin  | br pin          |
| brpos  | br postinstall  |
| brpru  | br prune        |
| brrea  | br readall      |
| brrei  | br reinstall    |
| brsea  | br search       |
| brsh   | br sh           |
| brsty  | br style        |
| brswi  | br switch       |
| brtap  | br tap          |
| brtapi | br tap-info     |
| brtapp | br tap-pin      |
| brtapu | br tap-unpin    |
| bruin  | br uninstall    |
| bruli  | br unlink       |
| brupa  | br unpack       |
| brupd  | br update       |
| brupdr | br update-reset |
| brupg  | br upgrade      |
| brupi  | br unpin        |
| bruse  | br uses         |
| bruta  | br untap        |
| brse   | br services     |
| brseli | brse list       |
| sbrse  | sudo brse       |
