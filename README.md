# Heyo!

So, there's going to be some AngularJS code here apparently..

## Class notes
- directives: telling AngularJS how to treat this particular object
- expressions: write code that Angular interprets for you, e.g. ```<p>The answer is {{ 41 + 1}}.</p>```
- controllers: to get crazy and supply data to your expressions, use controllers

### creating a module
- ```var app = angular.module('foo', []);
- name the module and pass in any dependencies you may need

- save it all to your app.js file, reference it with a directive on the ```html``` element