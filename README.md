# File Cookie Store

As the original `tough-cookie-filestore` seems to be inactive. I have to create another 
implementation of File store with more security consideration for `tough-cookie` module. See 
[tough-cookie documentation](https://github.com/goinstant/tough-cookie#constructionstore--new-memorycookiestore-rejectpublicsuffixes) for more info.


## installation

    $ npm install tough-cookie-filestore2

## Options

  `path` file path of cookiejar.

## Usage
```
  var FileCookieStore = require("tough-cookie-filestore2");
  var CookieJar = require("tough-cookie").CookieJar;

  var jar = new CookieJar(new FileCookieStore("./cookie.json"));
```
## License

 MIT
