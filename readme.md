# Setup for Modern Development
This is my first real foray into modern web development. This gist is a documentation of the apps and packages I used to setup my modern development workflow.

## OS setup
### Apps
1. [Sublime Text 2](http://www.sublimetext.com/2) - Text editor for code, markup and prose.
	- [Spacegray theme](http://kkga.github.io/spacegray/)
	- [Package Control](https://sublime.wbond.net/)
	- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter-for-ST2)
	- [Color Picker](https://github.com/weslly/ColorPicker)
	- [Emmet](http://emmet.io/)
	- [All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete)
	- [Better Completion](https://github.com/Pleasurazy/Sublime-Better-Completion)
	- [GitGutter](https://github.com/jisaacks/GitGutter)
	
2. [iTerm 2](http://www.iterm2.com/) - Terminal emulator for OS X.
3. [GitX](http://gitx.frim.nl/) - Git GUI for OS X.

### Plugins/packages
1. [Homebrew](http://brew.sh/) - The missing package manager for OS X.
2. [pip](http://www.pip-installer.org/en/latest/) - Tool for installing and managing Python packages.
3. [YADR dotfiles](https://github.com/skwp/dotfiles) - The top dotfile repos, vim and zsh plugins curated in one place.
4. [NPM](https://www.npmjs.org/) - Node packaged modules.
5. [Heroku Toolbelt](https://toolbelt.heroku.com/) - Everything to get started using Heroku.
6. Command Line Interface (CLI)
	- [AWS CLI](http://aws.amazon.com/cli/) - A unified command line interface to many Amazon Web Services.
	- [Dandelion](https://github.com/scttnlsn/dandelion) - Incremental Git repository deployment for OS X.

## Front-end setup
1. [Packagist](https://packagist.org/) - Composer package repository.
2. [Composer](https://getcomposer.org/) - Dependency manager for PHP.
3. [Grunt](http://gruntjs.com/getting-started) - JavaScript task runner.
4. [Bower](https://github.com/bower/bower) - A generic, unopinionated solution to the problem of front-end package management.

## Back-end setup
1. [Pagodabox](https://pagodabox.com/) — Object oriented hosting framework.

## Sublime Text User Settings
Default settings for Sublime Text.
	{
  "theme": "Spacegray Eighties.sublime-theme",
  "color_scheme": "Packages/Theme - Spacegray/base16-eighties.dark.tmTheme",
  "font_face": "Source Code Pro",
  "font_size": 14,
  "line_padding_bottom": 2,
  "line_padding_top": 2,

  "highlight_line": true,
  "bold_folder_labels": true,

  "translate_tabs_to_spaces": true,
  "tab_size": 2,
  "ignored_packages":
  [
    "Vintage"
  ]
}