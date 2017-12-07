# material-modal
Vanilla JavaScript Google's MaterialDesign-like modal window

## Installation
```html
<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet' type='text/css'>
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/fechanique/material-modal/master/material-modal.css">
<script src="https://cdn.rawgit.com/fechanique/material-modal/master/material-modal.js"></script>
```
## Functions
### Open alert
```javscript
//Opens a modal window with OK button
//materialAlert(title, text, callback)

materialAlert('Title', 'Content', function(result){
	if(result==true) console.log('OK button pressed');
	else console.log('No button was pressed');
});
```

### Open confirm
```javscript
//Opens a modal window with OK and CANCEL button
//materialConfirm(title, text, callback)

materialConfirm('Title', 'Content', function(result){
	if(result==true) console.log('OK button pressed');
	else console.log('CANCEL button was pressed or no button was pressed');
});
```

## Example
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
