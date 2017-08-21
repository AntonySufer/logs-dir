1.适用于node工程 输出文件日志记录,日志会以 /_logs/xxx/年-月-日.txt形式输出  
==== 
```js
 var logs = require('logs-dir');

 var err_data = "发生错误";

 logs.write('error',err_data);  

```
2.文件 输出夹 _logs/error/2017-8-22.txt; 
====  
3.文件内容
==== 
 ---2017-8-21 11:6:32【发生错误】
