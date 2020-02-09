# Advanced SSH Topics

## Automatic Host Finder

In this repo, I've included a Python script which will go to the
available hosts webpage, choose the best host based on number of
users and load, and issue the SSH command for you.

The script is named `UnixHostFinder.py` and it can be run from the command line in the following way:

```bash
python3 UnixHostFinder.py <CS Username>
```

Make sure you are in the same directory as the script before
issuing this command.

To make this even easier, you can assign running this script to an
alias in your shell's rc file.

## A Better Terminal App

The pre-installed Mac terminal would be perfectly sufficient for SSH-ing into the lab machines, but maybe you want something a little fancier.

iTerm2 allows for a lot more customization and features than the default terminal app. I highly recommend it, here's a link:

[iTerm2](https://iterm2.com)

## VSCode SSH Plugin

WIP