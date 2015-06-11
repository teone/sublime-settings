# Sublime Settings for a Js Developer

This are my Sublime Text 3 Settings, not perfect but I'm working on this, here are some of the features:

## Configuration


Enter your settings folder:
`cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`

Remove all the content in that folder:
`rm -rf ./*` **Note** _All your settings will be lost, this is the best options if you have nothing to loose, otherwise skip this_

Start a new repsitory:
`git init`

Add this repo as remote:
`git remote add origin git@github.com:teone/sublime-settings.git`

**If you have not cleared your folder**
`git add .`
`git commit -m "My Config"`

Pull!
`git pull origin master`

Resolve eventual conflicts

## Installed Packages

[All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete),
[AutoFileName](https://github.com/BoundInCode/AutoFileName),
[Babel](https://github.com/babel/babel-sublime),
subli[DocBlockr](https://github.com/spadgos/sublime-jsdocs),
[Emmet](https://github.com/sergeche/emmet-sublime),
[Git](https://github.com/kemayo/sublime-text-git),
[GitGutter](https://github.com/jisaacks/GitGutter),
[MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing),
[Package Control](https://packagecontrol.io/),
[SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3),
[SublimeLinter-contrib-eslint](https://github.com/roadhump/SublimeLinter-eslint),
[SublimeLinter-contrib-tslint](https://github.com/lavrton/SublimeLinter-contrib-tslint),
[SublimeLinter-jshint](https://github.com/devdoc/SublimeLinter-jslint),
[Surround](https://github.com/jcartledge/sublime-surround),
[Tag](https://github.com/titoBouzout/Tag)"

## Shortcuts

`super+shift+c`     ==>     toggle_comment <br>
`super+alt+s`       ==>     surround_selection <br>
`super+alt+r`       ==>     surround_change <br>
`super+shift+r`     ==>     expand_selection_to_paragraph <br>
`super+l`           ==>     lint tags
`super+ctrl+i`      ==>     indent tag in document

## Snippets

Any of this come with the ES2015/ES6 version.

### Promise Chains

`pr` | `pr6`

`then` | `then6`

### Callbacks

`cb` | `cb6`

### Console

`clog`

### ngDocs

Just start tiping `ngdocs` for all the possibilities

### BDD

`desc`

`it`

`be`

`expect`

### Nice to Have

- Bluebird Promisify Snippet
- ES6 promise Snippet
- Angular Controller | Services | Directive Snippets
- Promise Catch Snippet

## Helpers 

Start logging:
`sublime.log_commands(True)`
`sublime.log_input(True)`

Stop logging: 
`sublime.log_commands(False)`
`sublime.log_input(False)`

