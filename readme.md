## 使用方法
先将自己的sep账号登录，
进入选课系统→院系课程选课
打开浏览器开发者工具，控制台输入以下代码
```js
a=document.querySelectorAll('#main-content > div > div:nth-child(3) > div.mc-body > table > tbody  > tr > td:nth-child(2)>a'
for (i=0;i<a.length;i++){console.log(a[i]['href'])}
```
将控制台的url复制到，urls.txt文件中，执行main.py即可

⚠️如果非必要，不要导入到本地，建议使用icloud，exchange等同步。部分安卓机无法批量删除本地日程


> 感谢[junyilou](https://github.com/junyilou/python-ical-timetable)的ics生成代码