# ionic-sass-coffee-jade-classify-seed

------

The modern starting point for an Ionic project with Sass, Jade, CoffeScript and ngClassify support

ng-classify [documentation](https://github.com/CaryLandholt/ng-classify)

```shell
$ npm install -g ionic
$ ionic start appName https://github.com/ekinertac/ionic-sass-coffee-jade-classify-seed
$ cd appName

$ ./install
```

##Usage:

### Controller
```coffee
class Admin extends Controller
    constructor: ($scope, someService) ->
        $scope.coolMethod = someService.coolMethod()
```

which is equivalent to
```javascript
angular.module('app').controller('adminController', ['$scope', 'someService', function ($scope, someService) {
    $scope.coolMethod = someService.coolMethod();
}]);
```

Nice isn't it ?