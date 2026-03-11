# zsh

Copy `.zshrc` to `~/.zshrc`.

For API keys and secrets, create a separate `~/.zshrc_secrets` file (not committed to git) and source it from `.zshrc`.

# Brew

````
brew install go
````

# iTerm2

Download: https://iterm2.com/
Shell: https://ohmyz.sh/

## Fonts

Install **Menlo for Powerline** (used as the main terminal font):

```bash
git clone https://github.com/powerline/fonts.git --depth=1
cd fonts && ./install.sh
cd .. && rm -rf fonts
```

## Importing the profile

1. Open iTerm2 → Preferences → Profiles
2. Click the gear icon (Other Actions) → Import JSON Profiles
3. Select `iTerm-profile.json` from this repo
