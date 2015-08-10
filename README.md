# no-favicon

Express middleware to ignore favicon.* requests

## Install

```shell
npm install --save no-favicon
```

## Example

```js
var express   = require("express")
var nofavicon = require("no-favicon")
var app       = express();

app.use(nofavicon());

app.listen(process.env.PORT)
```

## License

MIT
