cause this is simple and the name may have some ambiguity,I won't publish this to npm.
# How to use
### For Node.js
```
import NodeWatchFileSystem from 'path-to-the-NodeWatchFileSystem.js'；
const fs = require(fs);

const instance = webpack(config,callback);

instance.watchFileSystem = new NodeWatchFileSystem(fs);
```
### For command line

It seems we can't custom file systems for webpack in command line mode.
