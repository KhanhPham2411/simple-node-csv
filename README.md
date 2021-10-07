# simple-node-csv

# Install

```bash
	git submodule add -b master https://github.com/KhanhPham2411/simple-node-csv.git
```



## Examples:

```js
import { SimpleNodeCsv } from './simple-node-csv';

SimpleNodeCsv.appendFile(path, {a: 1, b:2});
SimpleNodeCsv.appendFile(path, {a: 2, c:3});

// Output
// "a","b","c"
// 1,2,
// 1,,3
```
