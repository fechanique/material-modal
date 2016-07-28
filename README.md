# material-modal
Vanilla JavaScript Google's MaterialDesign-like modal window

##How to use

```html
<html>
	<head>
		<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet' type='text/css'>
		<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/fechanique/material-modal/master/material-modal.css">
		<script src="https://cdn.rawgit.com/fechanique/material-modal/master/material-modal.js"></script>
	</head>
	<body>
		<button onclick="materialConfirm('Title','Content',function(result){console.log(result)})">Show confirm</button>
		<button onclick="materialAlert('Title','Content',function(result){console.log(result)})">Show alert</button>
	</body>
</html>
```
