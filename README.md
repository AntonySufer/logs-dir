﻿

# logs-dir

## Installation

Using npm:
```shell
$ npm insatll logs-dir -s

```

In Node.js:
```js
 var logs = require('logs-dir');

 var err_data = "发生错误";//error log

 logs.write('error',err_data);  //err_data / string  


 var err_list ={"test":"test1"}; //error log

 logs.write('error',JSON.stringify(err_list));  //err_data / object  


```


## result:created file<br>
 /_logs/error/2018-08-21.txt <br>
### error_content:<br>
 ---2017-8-21 11:6:32【发生错误】<br>

 ---2017-8-21 11:6:32【{"test":"test1"}】<br>
 
## exp <br>
![image](https://github.com/AntonySufer/logs/blob/master/img/exp.png)
                                                
## Support

Tested in Chrome 54-55, Firefox 49-50, IE 11, Edge 14, Safari 9-10, Node.js 6-7, & PhantomJS 2.1.1.<br>

