# cd-gitroot

## Synopsis
zsh plugin to change directory to git repository root directory

Inspired by [id:hitode909 blog post](http://hitode909.hatenablog.com/entry/20100211/1265879271).

## How to set up

### Manually install

Put cd-gitroot and _cd-gitroot files somewhere in your $fpath and add the following line to your .zshrc:

```
autoload -Uz cd-gitroot
```

### Installing using Antigen
If you use [Antigen](https://github.com/zsh-users/antigen), add the following line to your .zshrc:

```
antigen bundle mollifier/cd-gitroot
```

You can set alias to this function.
e.g.

```
alias cdu='cd-gitroot'
```

## Usage

```
cd-gitroot [PATH]
```

If PATH isn't specified, change directory to current git repository root directory.
else change directory to PATH instead of it.
PATH is treated relative path in git root directory.

## Options
\-h display help and exit

