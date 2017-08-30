# wordfilter
Angular JS module to filter out bad words from input and returns a boolean true if input string contains a bad word.


# Installation

bower install wordfilter

and Add 'wordFilter' module as a dependency.

Injecting: 

var app = angular.module('myApp', ['wordfilter']);`

Using in Controller

app.controller('myCtrl', function(wfilter) {
    console.log(wordfilter.isBlacklisted($scope.value));
    
}); 

## Contributions

For problems/suggestions please create an issue on Github.

## Contributors

* [@Rahul](https://github.com/rahulvarma1906/wordfilter)
