[kaoscript/highlight-jedit](https://github.com/kaoscript/highlight-jedit)
===============================================================

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](./LICENSE)
[![Syntax Version](https://img.shields.io/badge/syntax-v0.8%20/%20outdated-critical.svg?style=flat)](https://github.com/kaoscript/kaoscript)

Provides syntax highlighting support for [kaoscript](https://github.com/kaoscript/kaoscript) in [jEdit](http://www.jedit.org/).

Getting Started
---------------

Copy *kaoscript.xml* to your jEdit modes directory.

This is located at:
- on MacOS: `~/Library/jEdit/modes/`
- on Linux: `~/.jedit/modes/`
- on Windows: `~\AppData\Roaming\jEdit\modes\`


Also, add the following line to your `/modes/catalog` file:
```xml
<MODE NAME="kaoscript" FILE="kaoscript.xml" FILE_NAME_GLOB="*.ks" />
```

License
-------

[MIT](http://www.opensource.org/licenses/mit-license.php) &copy; Baptiste Augrain