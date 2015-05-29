# Sublime Settings for a Js Developer

This are my Sublime Text 3 Settings, not perfect but I'm working on this, here are some of the features:

## Configuration


Enter your settings folder:
`cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User`

Remove all the content in that folder:
`rm -rf ./*` **Note** _All your settings will be lost, this is the best options if you have nothing to loose_

Start a new repsitory:
`git init`

Add this repo as remote:
`git remote add origin git@github.com:teone/sublime-settings.git`

**If you have not cleare your folder**
`git stash`

Pull!
`git pull origin master`


## Shortcuts

`super+shift+c`     ==>     toggle_comment <br>
`super+alt+s`       ==>     surround_selection <br>
`super+alt+r`       ==>     surround_change <br>
`super+shift+r`     ==>     expand_selection_to_paragraph <br>

## Snippets

Any of this come with the ES2015/ES6 version.

### Promise Chains

`pr` | `pr6`

```javascript
.then(function(res){
    console.log(res);
    $scope.res = res;
})
.catch(function(err){
    console.warn(err);
    $scope.err = err;
})
.finally(function(){
    // do something
    $scope.loader = false;
});
```


`then` | `then6`

```javascript
.then(function(res){
    snippet
})
```

### Callbacks

`cb` | `cb6`

```javascript
function(res){
    console.log(res)
}
```

### Console

`clog`

```javascript
console.log(var);
```

### ngDocs

Just start tiping `ngdocs` for all the possibilities

### Nice to Have

- Bluebird Promisify Snippet
- ES6 promise Snippet
- Angular Controller | Services | Directive Snippets
- Promise Catch Snippet

