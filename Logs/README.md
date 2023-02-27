## 2023-02-27
https://raw.iqiq.io/Coldnine009/cangku/main/README.md
https://ghproxy.com/https://raw.githubusercontent.com/Coldnine009/cangku/main/README.md

蜜蜂 ：https://github.com/FongMi/CatVodSpider

胖鸭接口 : https://agit.ai/cyl518/yl/src/branch/master

dlgtseven : https://github.com/dlgt7/TVbox-interface

duoduo : https://jihulab.com/duomv

dduoduo2 : https://jihulab.com/duomv

xiaosa(潇洒) : https://jihulab.com/yxcqr/TVboxo

第二派-dr模板的python实现 : https://gitcode.net/qq_32394351/dr_py

猫影视TV客户端爬虫自定义接口工程 : https://github.com/q215613905

里边有一堆jar : https://github.com/franksun1211/TVBOX

里边各种API那几个的成品，学学 :https://github.com/gzlinz2/TVBox-jar

里边有一些项目 : https://github.com/vpei

tvbox配置文件。所有资源均来自于各路大神无私分享 : https://github.com/gaotianliuyun/gao  (里边还有直播源)

https://github.com/liu673cn/drpy


🌹欧歌多仓库1号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=1&b=欧歌    已解
🌹派大星多仓库2号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=2&b=派大星    已解
🌹派大星多仓库3号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=3&b=欧歌    已经单独文件
🌹多多多仓4号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=4&b=欧歌
🌹多多多仓5号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=5&b=欧歌
🌹多库仓6号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=6&b=欧歌
🌹可视多库仓7号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=7&b=欧歌
🌹多库仓8号集合🌹 -> http://tv.nxog.top/api.php?mz=xb&id=8&b=欧歌
🌹星河库9号集合🌹 -> http://tv.nxog.top/api.php?mz=xb&id=9&b=欧歌
🌹星河多仓库10号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=10&b=欧歌
🌹多仓库11号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=11&b=欧歌
🌹放学回家看电视多仓库12号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=12&b=欧歌
🌹吾爱多仓库13号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=13&b=欧歌
🌹懒猫多仓库14号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=14&b=欧歌
🌹月光宝盒多仓库15号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=15&b=欧歌
🌹龙爪多仓库16号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=16&b=欧歌
🌹Rio多仓库17号🌹 -> http://tv.nxog.top/api.php?mz=xb&id=17&b=欧歌
🌹欧歌单仓集合🌹 -> https://ghproxy.com/https://raw.githubusercontent.com/Coldnine009/cangku/main/005_urls.txt
🌹欧歌网络收集仓调用本地包🌹 -> http://tv.nxog.top/api.php?mz=xb&id=100&b=欧歌

{
    "storeHouse": [
        {
            "sourceName": "🌹欧歌主仓库🌹",
            "sourceUrl": "http://tv.nxog.top/nxog/ou.php?url=http://tv.nxog.top&b=欧歌"
        },
    ]
}


## TVbox调用alist网盘目录教程

https://www.158xuexi.com/44220.html

## drpy是什么

参考JRK直播.js

道长 drpy仓库 https://gitcode.net/qq_32394351/dr_py

道长 drpy安卓本地搭建说明 https://gitcode.net/qq_32394351/dr_py/-/blob/master/%E5%AE%89%E5%8D%93%E6%9C%AC%E5%9C%B0%E6%90%AD%E5%BB%BA%E8%AF%B4%E6%98%8E.md

道长 drpy写源 模板规则说明 https://gitcode.net/supertlo/dr_py#%E6%A8%A1%E6%9D%BF%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E

道长 drpy写源 套模模版 https://gitcode.net/qq_32394351/dr_py/-/raw/master/js/%E6%A8%A1%E6%9D%BF.js

道长 drpy写源 影片教程 http://101.34.67.237:5244/%E6%95%99%E8%82%B2/drpy

道长 drpy写源 影片教程(m3u8切片) https://freedrpy.run.goorm.io/txt/jc/playlist.m3u8

海阔下载 https://haikuo.lanzoui.com/u/GoldRiver

Pluto Player官方TG https://t.me/PlutoPlayer

Pluto Player官方TG https://t.me/PlutoPlayerChannel

## 一些教程

简单的说就是把爬虫包(jar)上传到码云或类似的数据托管平台，像直播源一样复制源地址然后把txt中的spider一行的爬虫包(jar)改成你上传的爬虫包(jar)源地址，保存txt上传托管获取托管txt的源地址，把地址放到tvbox配置接口，结束

var rule = {
    title:'',//规则标题,没有实际作用,但是可以作为cms类名称依据
    编码:'',//不填就默认utf-8
    host:'',//网页的域名根,包含http头如 https://www,baidu.com
    homeUrl:'/latest/',//网站的首页链接,可以是完整路径或者相对路径,用于分类获取和推荐获取 fyclass是分类标签 fypage是页数
    url:'/fyclass/fypage.html[/fyclass/]',//网站的分类页面链接
    detailUrl:'https://yanetflix.com/voddetail/fyid.html',//非必填,二级详情拼接链接,感觉没啥卵用
    searchUrl:'',//搜索链接 可以是完整路径或者相对路径,用于分类获取和推荐获取 **代表搜索词 fypage代表页数
    searchable:0,//是否启用全局搜索,
    quickSearch:0,//是否启用快速搜索,
    filterable:0,//是否启用筛选,
    filter:{},// 筛选条件字典
    // 筛选网站传参,会自动传到分类链接下(本示例中的url参数)-url里参数为fyfilter,可参考蓝莓影视.js
    filter_url:'style={{fl.style}}&zone={{fl.zone}}&year={{fl.year}}&fee={{fl.fee}}&order={{fl.order}}',
    // 注意,由于猫有配置缓存,搜索配置没法热加载，修改了js不需要重启服务器
    // 但是需要tv_box进设置里换源使配置重新装载
    headers:{//网站的请求头,完整支持所有的,常带ua和cookies
        'User-Agent':'MOBILE_UA',
        "Cookie": "searchneed=ok"
    },
    timeout:5000,//网站的全局请求超时,默认是3000毫秒
    class_name:'电影&电视剧&动漫&综艺',//静态分类名称拼接
    class_url:'1&2&3&4',//静态分类标识拼接
    //动态分类获取 列表;标题;链接;正则提取 不需要正则的时候后面别加分号
    class_parse:'#side-menu:lt(1) li;a&&Text;a&&href;com/(.*?)/',
    // 除开全局过滤之外还需要过滤哪些标题不视为分类
    cate_exclude:'',
    // 除开全局动态线路名过滤之外还需要过滤哪些线路名标题不视为线路
    tab_exclude:'',
    // 服务器解析播放
    play_parse:true,
    // 自定义免嗅
    lazy:'',
    // 首页推荐显示数量
    limit:6,
    double:true,//是否双层列表定位,默认false
    // 类似海阔一级 列表;标题;图片;描述;链接;详情 其中最后一个参数选填
    // 如果是双层定位的话,推荐的第2段分号代码也是第2层定位列表代码
    推荐:'.col-sm-6;h3&&Text;img&&data-src;.date&&Text;a&&href',
    // 类似海阔一级 列表;标题;图片;描述;链接;详情 其中最后一个参数选填
    一级:'.col-sm-6;h3&&Text;img&&data-src;.date&&Text;a&&href',
    // 二级可以是*,表示规则无二级,直接拿一级的链接进行嗅探
    // 或者 {title:'',img:'',desc:'',content:'',tabs:'',lists:''} 同海阔dr二级
    二级:'*',
    // 搜索可以是*,集成一级，或者跟一级一样的写法 列表;标题;图片;描述;链接;详情
    搜索:'*',
}

模板继承写法

var rule = Object.assign(muban.mxpro,{
title:'鸭奈飞',
host:'https://yanetflix.com',
url:'/index.php/vod/show/id/fyclass/page/fypage.html',
class_parse:'.navbar-items li:gt(1):lt(6);a&&Text;a&&href;.*/(.*?).html',
});