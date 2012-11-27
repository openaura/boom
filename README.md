# BOOM

You have a web app.

## How?

```bash
$ git clone https://github.com/deanh/boom.git
$ cd boom
$ npm install
```

## Tests

Tests live under test/ and are run via cake test. This will run all
the tests in test/ with Mocha and the Nyan Cat reporter.

## Server

You have a dev server at your disposal. To run it:

```bash
$ node server.js
```

This will start a server at port 4400 by default. You can change the
port in config.json, or by providing a port as a second argument. The
server will automatically compile any CoffeeScript in src/client and
wrap it up as package.js.

### Public Files

Any file under public/ will be served as a static asset. index.html is
provided. It requires jQuery and package.js by default.

---

Copyright 2012, Dean Hudson (dean@ero.com)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
