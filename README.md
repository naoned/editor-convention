# EditorConfig Naoned

## Table of contents

1. [Installation](#installation)
1. [Explanations](#explanations)
1. [Editors](#editors)
  1. [Sublime Text](#editor_st)<br>
  1. [Atom](#editor_atom)<br>
  1. [PHPStorm](#editor_phpstorm)<br>
  1. [Geany](#editor_geany)<br>

## <a name='installation'>Installation</a>

- Download the **.editorconfig** file from this repo.
- Place it in your project root folder.
- Restart your editor.

## <a name='explanations'>Explanations</a>

The .editorconfig passes configurations directly to your editor without the need for you to configure it by hand.
*See [.editorconfig](.editorconfig) to check available parameters.*


## Editors

## <a href="http://www.sublimetext.com/" target="_blank" name='editor_st'>Sublime Text</a>
### Must-have tweaks
**You must install *Package Control* to be able to use these tweaks.**
*Follow [this link](https://packagecontrol.io/installation) to install Package Control*

- Alignment:
  > This lets you hit `COMMAND-CTRL-A` to align your PHP code with spaces.
  > Usage: use it to align arrays and variables nicely to keep code readable.
- BracketHighlighter:
  > Highlights the brackets of your current scope.
  > ie: Place your cursor in a function and see the function {} highlighted.
- EditorConfig:
  > Enable .editorconfig file support.
- PHPCS:
  > PHP Code Sniffer implementation (can implements *phpcs*, *phpcbf* and *phpmd*).
  > You'll need some requirements, see [this repo](https://github.com/naoned/php-convention) to check how to install it.
- PlainTasks:
  > Adds a TODOList file type management


## <a href="http://www.atom.io/" target="_blank" name='editor_atom'>Atom</a>
### Must-have tweaks
- EditorConfig:
  > Enable .editorconfig file. Follow [this link](https://github.com/sindresorhus/atom-editorconfig#editorconfig) to get the installation instructions
@Tofinish

## <a href="https://www.jetbrains.com/phpstorm/" target="_blank" name='editor_phpstorm'>PHPStorm</a>
### Must-have tweaks
- EditorConfig:
  > Enable .editorconfig file. Follow [this link](https://plugins.jetbrains.com/plugin/7294) to download the tweak
@Tofinish

## <a href="http://www.geany.org/" target="_blank" name='editor_geany'>Geany</a>
### Must-have tweaks
- EditorConfig:
  > Enable .editorconfig file. Follow [this link](https://github.com/editorconfig/editorconfig-geany#installation) to get installation instructions
@Tofinish
