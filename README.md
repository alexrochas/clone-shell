# Clone Shell
> Shell utility, kind of a plugin

Tiny utility for create new shells in the same path than the last opened shell.

## Installation

Install with [basher](https://github.com/basherpm/basher) (shell package-manager).

```
~$ basher install alexrochas/clone-shell
```

You could also add manually to your PATH or even use fullpath to clone-shell script.

## Usage

As an [i3](https://i3wm.org/) user, you should override your [i3](https://i3wm.org/) new terminal keybinding to call clone-shell.

```
bindsym $mod+Return exec clone-shell
```

[Yakuake](https://yakuake.kde.org/) also has a configurable command to new shell's.

Well, you get it!

For now, will try create a new urxvt terminal-emulator. Soon will make it configurable.

## Roadmap

* Make terminal-emulator configurable

## Release History

* 0.0.1
    * Work in progress

## Meta

Alex Rocha - [about.me](http://about.me/alex.rochas)
