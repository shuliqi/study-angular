<!DOCTYPE html>
<html ng-app="app">
<head>
    <meta charset="utf-8">
	<title></title>
	<script type="text/javascript" src="angular-1.3.0.14/angular.js"></script>
  <script type="text/javascript" src="angular-1.3.0.14/angular-route.min.js"></script>
</head>
<body>
<div ng-controller="title">{{title}}</div>
<script type="text/javascript">
var app = angular.module('app',[]);
app.controller('title',['$scope',function ($scope){
  $scope.title = "舒丽琦";
}])
</script>
</body>
</html>