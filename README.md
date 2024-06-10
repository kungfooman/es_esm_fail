```
(base) homepc@home-pc:/var/www/html/ts_esm_fail$ npm run start

> ts_esm_fail@1.0.0 start
> node src/index.js

file:///var/www/html/ts_esm_fail/src/index.js:3
console.log("ts.ScriptTarget.Latest", ts.ScriptTarget.Latest);
                                                      ^

TypeError: Cannot read properties of undefined (reading 'Latest')
    at file:///var/www/html/ts_esm_fail/src/index.js:3:55
    at ModuleJob.run (node:internal/modules/esm/module_job:193:25)
    at async Promise.all (index 0)
    at async ESMLoader.import (node:internal/modules/esm/loader:530:24)
    at async loadESM (node:internal/process/esm_loader:91:5)
    at async handleMainPromise (node:internal/modules/run_main:65:12)

Node.js v18.12.1
(base) homepc@home-pc:/var/www/html/ts_esm_fail$ 
```
