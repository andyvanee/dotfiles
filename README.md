# dotfiles

Andy VanEe's dotfiles.

The `.config/dotfiles` directory should be copied or symlinked into `~/.config/dotfiles`.

Any top level dotfiles should be copied or symlinked into `~`.

    Add .config/dotfiles/gitconfig_local for any local config

    [user]
        name = My Name
        email = my.email@example.com

    [include]
        path = ~/.config/some/other/config

The values set here can be tested by running, for example:

    git config --global --includes --get user.name
