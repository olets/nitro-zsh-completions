# nitro-zsh-completions ![GitHub release (latest by date)](https://img.shields.io/github/v/release/olets/nitro-zsh-completions)

> zsh completions for https://github.com/craftcms/nitro

1. [Installation](#installation)
1. [Usage](#usage)
1. [Uninstalling](#uninstalling)
1. [Changelog](#changelog)
1. [Contributing](#contributing)
1. [License](#license)

## Installation

### Plugin (recommended)

You can install nitro-zsh-completions with a zsh plugin manager. Each has their own way of doing things. See your package manager's documentation or the [zsh plugin manager plugin installation procedures gist](https://gist.github.com/olets/06009589d7887617e061481e22cf5a4a).

After adding the plugin to the manager, restart zsh:

```shell
exec zsh
```

### Manual

Clone this repo and add `source path/to/nitro-zsh-completions.zsh` to your `.zshrc`. Then restart zsh:

```shell
exec zsh
```

### Package

nitro-zsh-completions is available on Homebrew. Run

```
brew install olets/tap/nitro-zsh-completions
```

and follow the post-install instructions logged to the terminal.

## Usage

In an interactive zsh terminal (ie on the command line) type `nitro`<kbd>TAB</kbd> to see subcommands and top level options, and `nitro <subcommand>`<kbd>TAB</kbd> to see sub-subcommands and subcommand options.

## Uninstalling

### Plugin

Follow the standard uninstallation procedure for your manager.

### Manual

Remove the reference from your `.zshrc` and delete the nitro-zsh-completions directory.

### Package

```shell
brew uninstall --force nitro-zsh-completions
```

## Changelog

See the [CHANGELOG](CHANGELOG.md) file.

## Contributing

Thanks for your interest. Contributions are welcome!

> Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

Check the [Issues](https://github.com/olets/git-replay/issues) to see if your topic has been discussed before or if it is being worked on.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text"><a rel="cc:attributionURL" property="dct:title" href="https://www.github.com/olets/git-replay">git-replay</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.github.com/olets">Henry Bley-Vroman</a> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0">CC BY-NC-SA 4.0</a> with a human rights condition from <a href="https://firstdonoharm.dev/version/2/1/license.html">Hippocratic License 2.1</a>. Persons interested in using or adapting this work for commercial purposes should contact the author.</p>

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" />

For the full text of the license, see the [LICENSE](LICENSE) file.
