# GIT CONFIG

Stunning backup of atom's configuration to work faster in the most unbelievable
environment. A copy of my ~/.atom/ directory, there is all config files to code
in php, javascript, etc.

Each environment has its own branch. Theses branch are called like features are
usually named, branch's purpose, slash and name of the environment in a url's
notation, for example, environment/php.

Packages used are in package.list file, you can replace that list for your own
by calling.

```shell
apm list --installed --bare > ~/.atom/package.list
```

And install or restore all these packages using

```shell
apm install --packages-file ~/.atom/package.list
```

## Editor

scrollPastEnd it's activated to avoid looking at the bottom of the screen when
you’re editing the last few lines of a file.

showInvisibles it's activated to help to differentiate between spaces, tabs and
line feeds.

## General Packages

### Minimap

Provides a preview of the full source code. It helps to move over the file
faster.

### Autosave

It's activated. It with that config removes repeated steps on the development
process.

### Tree View Autoresize

Autoresize the tree view when open/close folders.

### Linter

Base for language linters.

### Linter UI Default

The default UI for linter.

### Busy Signal

Show your package is performing a task.

### Intentions

Base package to show intentions based in Atom.

## PHP Packages

### Language PHP

Add four space to represent a tab, PSR standards says we must use four spaces
instead of tabs.
