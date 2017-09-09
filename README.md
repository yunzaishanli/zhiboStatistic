# zhiboStatistic
定时爬取各直播平台的数据，包括在线观看人数、主播数量、主要游戏观看人数等
#zhiboStatistic
定时爬取各直播平台的数据，包括在线观看人数、主播数量、主要游戏观看人数等，查询后保存成excel文件，每半小时查询一次，并按天保存<br>
<hr /><br>
目前只在<strong>win7 64位机，python2.7</strong> 下测试通过<br>

<hr /><br>
<h3>如何使用</h3>
timeTask：启动定时任务，每隔半小时查询并记录一次<br><br>
<h4>数据来源：</h4>
<pre>
https://www.douyu.com/directory/all?page=1
https://www.quanmin.tv/game/all?p=1
http://live.qq.com/api/live/vlist?page_size=60&page=1&shortName=0
https://api.live.bilibili.com/room/v1/room/get_user_recommend?page=1
https://www.panda.tv/live_lists?status=2&order=person_num&token=&pageno=1&pagenum=120
https://www.huya.com/cache.php?m=LiveList&do=getLiveListByPage&tagAll=0&page=1
http://webh.huajiao.com/live/listcategory?cateid=1000&offset=1&nums=40&fmt=jsonp
http://api.plu.cn/tga/streams?max-results=50&start-index=1&sort-by=views&filter=0&game=0
https://www.zhanqi.tv/api/static/v2.1/live/list/50/1.json

<h4>欢迎交流，xhe6630@163.com</h4>
