# oneisall api
koa重写了one一个api


## 运行方式

* 导入sql（保存了以往的数据）
* 修改server/config db.js 数据库连接方式
* npm install
* node app.js

## 获取数据接口 GET

* 通过日期获取one: http://qust.me:8889/api/one/date/2017-11-22

* 通过vol获取one: http://qust.me:8889/api/one/vol/100

* 通过日期获取文章: http://qust.me:8889/api/essay/date/2017-11-24

* 通过id获取文章: http://qust.me:8889/api/essay/id/102

* 通过id获取问题:
http://qust.me:8889/api/question/id/102

* 通过日期获取问题:
http://qust.me:8889/api/question/date/2017-11-24

* get获取最新one essay question 并保存到数据库（数据库没有）:

    1. http://qust.me:8889/api/new/one

    2. http://qust.me:8889/api/new/question

    3. http://qust.me:8889/api/new/essay

 ## 遍历更新所有数据到数据库(使用时请自行替换网址)
1. http://qust.me:8889/api/add/one
2. http://qust.me:8889/api/add/questions
3. http://qust.me:8889/api/add/