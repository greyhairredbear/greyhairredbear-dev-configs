# Setup a new MacOS device

## steps until repo setup

### Homebrew

```shell
./setup-homebrew.sh
```

### iTerm

```shell
brew install iterm2
```

### Jetbrains Mono nerdfont

```shell
brew install font-jetbrains-mono-nerd-font
```

### Browser

```shell
brew install vivaldi
```

### Install password manager

```shell
brew install ...
```

### Setup GitHub

- Login, new passkey, ssh setup

### Clone this repo

`git clone`

## Steps with data from this repo

### Shell

```shell
./setup-ohmyz.sh
```

```shell
chmod +x symlink.sh
```

```shell
./symlink.sh
```

### Keyboard

#### Macos keyboard settings

```shell
./keyboard-settings-setup.sh
```

#### Karabiner

```shell
brew install karabiner-elements
```

- move files from `karabiner` to karabiner config folder

#### Vial

```shell
brew install vial
```

### IDE

```shell
brew install visual-studio-code
brew install jetbrains-toolbox
```

### lazygit

```shell
brew install lazygit
```

- Copy `../git/lazygit/config.yml` to lazygit Application Support folder

### MacOS settings

- wallpaper from `../ui`
- profile picture from `../ui`

### Moom

```shell
brew install moom
```

- import actions (`moom/Actions.moom`)
- set snap corners

### Apple ID

Don't forget to remove old devices from "Find My"

### Alfred

```shell
brew install alfred
```

- remove spotlight shortcut from macos settings
- change shortcut to ctrl+space
- preferences export/import

### Thunderbird

```shell
brew install thunderbird
```

- setup mail + calendars

### jenv

```shell
brew install jenv
```

```shell
jenv add /Library/Java/JavaVirtualMachines/temurin-25.jdk/Contents/Home/
```

# Further homebrew installs

```
tap "dart-lang/dart"
tap "osx-cross/arm"
tap "osx-cross/avr"
tap "qmk/qmk"

brew "avrdude"
brew "dart-lang/dart/dart"
brew "duti"
brew "fzf"
brew "git-delta"
brew "git-flow"
brew "git-lfs"
brew "gradle"
brew "gradle-completion"
brew "ktfmt"
brew "lazydocker"
brew "maven"
brew "ncdu"
brew "node"
brew "qmk/qmk/qmk"
brew "qrencode"
brew "renameutils"
brew "tokei"
brew "tree"
brew "watch"

cask "alfred"
cask "cyberduck"
cask "docker-desktop"
cask "firefox"
cask "hex-fiend"
cask "keyboardcleantool"
cask "libreoffice"
cask "mac-mouse-fix"
cask "notunes"
cask "numi"
cask "openmtp"
cask "sensiblesidebuttons"
cask "slack"
cask "stats"
cask "temurin@21"
```
