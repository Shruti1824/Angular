<!Doctype html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.2/angular.min.js">
</script>
<title>Angular js directives</title>
</head>
<body>
<h1>Sample Application</h1>
<div ng-app="" ng-init="countries=[{locale:'en-USA'name:'United States of Ammerica'}
{locale:'en-UK' name:'United kingdom'}]">
<p>Enter name:<input type="text" ng-model="name"></p>
<h1>HELLO<span ng-bind="name"></span>!</h1>
<p>List of countries with locale:</p>
<ol>
<li ng-repeat="country in countries">
{{'country:' + country.name + 'locale:' + country.locale}}
</li>
</ol>
</div>
</body>
</html>
