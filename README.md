<h1>nlog</h1>

<h2>Simple Node.js Logging Library</h2>

<h3>Installation</h3>

<p>Install <code>nlog</code> using npm:</p>


```bash
npm install nlog
```



```js
const { Logger, LogLevel, nlog } = require("nlog");

const log = new Logger({ production: true, prefix: "MyLibrary" });
log(LogLevel.Info, "Hello, World!");

// or

const newLog = nlog({ production: true, prefix: "MyLibrary" });
newLog(LogLevel.Info, "Hello, World!");
```

