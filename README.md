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

// output
// "a","b","c"
// 1,2,
// 1,,3
```

```js
import { SimpleNodeCsv } from './simple-node-csv';

SimpleNodeCsv.obj2csv({a: 1, b:2}, ",");

// output
// "a","b"
// 1,2
```

```js
import { SimpleNodeCsv } from './simple-node-csv';

// input
// "a","b"
// 1,2

SimpleNodeCsv.csv2obj(input, ",");

// output
// {a: 1, b:2}
```
