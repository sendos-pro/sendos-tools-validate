# sendos-tools-validate

```
npm i sendos-tools-validate
```

## Usage

``` js
const validate = require('sendos-tools-validate');

validate
	.isValid('testers722+2@gmail.com')
	.then(function(result) {
		console.log(result);
	})
	.catch(function(err) {
		console.log(err);
	});
```