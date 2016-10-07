[kaoscript/highlight-jedit](https://github.com/kaoscript/highlight-jedit)
===============================================================

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](./LICENSE)

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

Copyright &copy; 2016 Baptiste Augrain

Licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php).