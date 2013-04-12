Sublime Text 2 Snippets
===========

Just another set of snippeds for javascript and node.js

## Install

**Without Git:** Download the latest source from `GitHub <https://github.com/unlucio/sublimeSnippets>`_ and copy the whole directory into the Packages directory.

**With Git:** Clone the repository in your Sublime Text 2 Packages directory, located somewhere in user's "Home" directory::

    git clone git://github.com/unlucio/sublimeSnippets.git


The "Packages" packages directory is located at:

* OS X:: ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/

* Linux:: ~/.Sublime\ Text\ 2/Packages/User/

* Windows:: %APPDATA%/Sublime Text 2/Packages/User/

## Usage: Avvailable snippets shortcuts:

__General JS__
* forin
```javascript
for(var indexName in map){
	var object = map[indexName]
	 // body...
}
```

* jparse
```javascript
JSON.parse(string, optinalReviver)
```

* jstring
```javascript
JSON.stringify(object)
```

* stt
```javascript
var self = this;
```

__Node.js__
* node.object.class
```javascript
module.exports = (function (ObjectName) {
	ObjectName = function(options) {
		//constructor body
	};
	ObjectName.prototype.methodName = function(arguments) {
	  //method body
	};
	return ObjectName;
}());
```

__Express.js__
* express.callback
```javascript
function (req, res, next) {
	res.send("responseText");
});
```

* express.errorCallback
```javascript
function (err, req, res, next) {
	res.status(err.status || 404).end(err.message);
}
```
* express.res.status
```javascript
status(statusCode)
```
* express.res.set
```javascript
set(field, [value])
```

* express.res.head
```javascript
header(field, [value])
```

* express.res.get
```javascript
get(field)
```

* express.res.cookie
```javascript
cookie(name, value, [options])
```

* express.res.clearCookie
```javascript
clearCookie(name, [options])
```

* express.res.redirect
```javascript
redirect([status], url)
```

* express.res.location
```javascript
location(location)
```

* express.res.charset
```javascript
charset = 'value';
```

* express.res.send
```javascript
send([body|status], [body])
```

* express.res.json
```javascript
res.json([status|body], [body])
```

* express.res.jsonp
```javascript
jsonp([status|body], [body])
```

* express.res.type
```javascript
type(type)
```

* express.res.format
```javascript
format(object)
```

* express.res.attachment
```javascript
attachment([filename])
```

* express.res.sendfile
```javascript
sendfile(path, [options], [callback])
```

* express.res.download
```javascript
download(path, [filename], [callback])
```

* express.res.links
```javascript
links(linksMap)
```


## LICENSE - "MIT License"

Copyright (c) 2013-2012 Luciano Colosio (@unlucio)

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
