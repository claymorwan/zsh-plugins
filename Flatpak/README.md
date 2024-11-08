# Flatpak plugin

This plugin adds a few aliases for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).

1. Install the plugin by cloning it in the right directory using this command <br>
`git clone --depth 1 -- https://github.com/claymorwan/Flatpak-zsh-plugin.git $ZSH_CUSTOM/plugins/flatpak` 

2. If you're using oh my zsh, enable it by adding `flatpak` to the plugins array in your `.zshrc` file:
```zsh
plugins=(
    ... 
    flatpak
    )
```
## Aliases

| Alias        | Command                                | Description                                                      |
|--------------|----------------------------------------|------------------------------------------------------------------|
| flatin       | `flatpak install`                      | Install an application or runtime                                |
| flatre       | `flatpak uninstall`                    | Uninstall an application or runtime                              |
| flatupg      | `flatpak update`                       | Update an application or runtime                                 |
| flatlist     | `flatpak list`                         | List installed applications and/or runtimes                      |
| flatrun      | `flatpak run`                          | Run an application or open a shell in a runtime                  |
| flatrep      | `flatpak repair`                       | Repair a flatpak installation                                    |
| flatkill     | `flatpak kill`                         | Stop a running application                                       |

# Credit
- Made by [claymorwan](https://github.com/claymorwan) :3c
- Inspired by the [Arch Linux plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/archlinux)