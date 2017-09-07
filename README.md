# .dotfiles

My personal environment.

## Contents

1. [Introduction](#introduction)
1. [Variables](#variables)

## Introduction

WIP

## Variables

Environment variables to be `export`'ed.

### User

```bash
USERNAME="Realetive"
FULLNAME="Roman Ganin"
EMAIL="realetive@yandex.ru"
```

### OS

```bash
DEFAULT_LANG="ru_RU"
SECOND_LANG="en_EN"
```

Current OS — [macOS Sierra](https://itunes.apple.com/ru/app/macos-sierra/id1127487414?mt=12).

#### Installation

1. Load installation image from iTunes;
1. Prepare USB drive (>= 8Gb), erase it with memory name (ex. `Untitled`);
1. in Terminal.app:

```bash
sudo "/Applications/Install\ macOS\ Sierra.app/Contents/Resources/createinstallmedia" \
  --applicationpath "/Applications/Install\ macOS\ Sierra.app" --nointeraction \
  --volume "/Volumes/Untitled"
```

### Apps

```
EDITOR="vim"
```
