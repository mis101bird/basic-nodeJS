basic-nodeJS
============
第一個node.js練習:<br/>
1.實作route的靜態網頁處理<br/>
2.用地三方套件處理post圖片上傳資料<br/>
3.留言板前端用Ajax<br/>
4.index.html的第二個連結有post的Ajax例子<br/>
5.含後端與資料庫mongoDB的處理<br/>
使用到的npm 第三方套件:
============

formidable - 解析post中的file資料<br/>
mongodb - 實作mongo資料庫的CRUD<br/>
server and route 練習
============
server.js處理好GET/POST的資料-有file的POST直接將request傳至loginback.js解析<br/>
route.js處理分配local文件的問題<br/>
資料庫類型:mongoDB
============
database:test<br/>
collections:<br/>
myboard - 存留言板的留言資料<br/>
============
參考網站:http://www.nodebeginner.org/index-zh-tw.html
============
Run the website: node server
