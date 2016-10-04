[kaoscript/jedit-mode](https://github.com/kaoscript/jedit-mode)
===============================================================

Provides syntax highlighting support for kaoscript in jEdit.


Installation
------------

Copy *kaoscript.xml* to your jEdit modes directory.

This is located at:
- on MacOS: `~/Library/jEdit/modes/`
- on Linux: `~/.jedit/modes/`
- on Windows: `~\AppData\Roaming\jEdit\modes\`


Also, add the following line to your `/modes/catalog` file:
```xml
<MODE NAME="kaoscript" FILE="kaoscript.xml" FILE_NAME_GLOB="*.ks" />
```