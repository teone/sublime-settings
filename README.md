# Sublime Settings for a Js Developer

This are my Sublime Text 3 Settings, not perfect but I'm working on this, here are some of the features:

## Shortcuts

`super+shift+c`     ==>     toggle_comment
`super+alt+s`       ==>     surround_selection
`super+alt+r`       ==>     surround_change
`super+shift+r`     ==>     expand_selection_to_paragraph

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

