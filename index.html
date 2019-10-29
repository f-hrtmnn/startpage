<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

.navbar-nav li:hover .dropdown-menu {
        display: block;
}
#iframediv {
  background-image: url("https://wallpapercave.com/wp/wp1822729.jpg");
  height: 94%;
  width: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: absolute;

}
    
.searchdiv {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

</style>
</head>
<body ng-app="menu" ng-controller="myCtrl">
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="javascript:window.location.href=window.location.href">Home</a>
    <ul class="navbar-nav mr-auto" ng-repeat="navbar in jsonfile">
     <div ng-repeat="menuitem in navbar.navbar">
      <li class="nav-item dropdown"  ng-if="menuitem.dropdown == 'yes'">
        <a class="nav-link dropdown-toggle" href="{{menuitem.url}}" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        {{menuitem.menuname}}
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="{{subitem.url}}" ng-repeat="subitem in menuitem.links">{{subitem.name}}</a>
        </div>
      </li>
      <li class="nav-item" ng-if="menuitem.dropdown == 'no'">
        <a class="nav-link" href="{{menuitem.url}}">{{menuitem.menuname}}</a>
      </li>
     </div>
    </ul>
    <div ng-repeat="menuright in jsonfile"> 
        <div class="navbar-text" ng-repeat="menuitem in menuright.menuright">
        {{menuitem.input}}
        </div>
    </div>
</nav>

<div id="iframediv">
    <div class="searchdiv">
    <iframe src="https://duckduckgo.com/search.html?prefill=Suche&focus=yes" style="overflow:hidden;margin:0;padding:0;width:608px;height:80px;" frameborder="0"></iframe>
    </div>
</div>



<!-- code -->
<script>
var app = angular.module('menu', []);
app.controller('myCtrl', function($scope, $http, $sce) {
  $http.get("menu.json")
  .then(function(response) {
      $scope.jsonfile = response.data;
  });
});
</script>

</body>
</html>
