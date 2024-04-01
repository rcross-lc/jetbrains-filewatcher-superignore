
# To use:

Download and compile [modified fsNotifier](https://github.com/rcross-lc/intellij-community/tree/fsnotifier-ignore/native/fsNotifier/linux).

Compile and install this plugin

Add this to your custom properties:

```
com.rcross.filewatcher.executable.path=/path/to/intellij-community/native/fsNotifier/linux/fsnotifier
com.rcross.filewatcher.disabled=false
idea.filewatcher.disabled=true
```
