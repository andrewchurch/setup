# New Mac Setup

## Apps

* [Chrome](https://www.google.com/chrome/)
* [Remember the Milk](https://www.rememberthemilk.com/)
* [VS Code](https://code.visualstudio.com/)
    * Add 'code' to PATH (do via command palette)
* [Miscrosoft 365 Apps](https://www.office.com/)
* [Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app)
* [Quick View Calendar](https://apps.apple.com/us/app/quick-view-calendar/id1087080039?mt=12)
    * [Start app on Mac startup](https://support.apple.com/guide/mac-help/open-items-automatically-when-you-log-in-mh15189/)
* [Sequel Ace](https://apps.apple.com/us/app/sequel-ace/id1518036000)
* [Postman](https://www.postman.com/downloads/)
* [Zoom](https://zoom.us/download)
* [Spotify](https://www.spotify.com/us/download/other/)
* [Discord](https://discord.com/)

## Terminal Setup

* Install [Homebrew](https://brew.sh/)
* Install [Fish Shell](https://fishshell.com/)
    * Make Fish the [default shell](https://fishshell.com/docs/current/index.html#default-shell)
    * Add fish to PATH

            fish_add_path /opt/homebrew/bin

* Add [Solarized Dark](https://github.com/altercation/solarized) Terminal profile
    * Open this profile on startup and for new windows
    * Set profile Window size (90x60ish)
* Install [Oh My Fish](https://github.com/oh-my-fish/oh-my-fish)
* Install [Fisher](https://github.com/jorgebucaran/fisher)
* Install [Lavender Theme](https://github.com/tungpun/fish-theme-lavender)

## Dev Workflow

* [LAMP setup](https://getgrav.org/blog/macos-ventura-apache-multiple-php-versions)
* Generate/add [GitHub SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
* Add .gitconfig
* Install [nvm.fish plugin](https://github.com/jorgebucaran/nvm.fish)
    * Install node (latest, lts)
    * Set default node version

            set --universal nvm_default_version v18.4.0