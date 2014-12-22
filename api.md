TODO

* 分类详情模块 

1.1 全部分类 
/catalog

1.2 分类内资源
/catalog/catid

1.3 资源详情
/item/info/id

1.4 资源下载
/item/down/id

1.5 评论资源
/item/comment

1.6 评分资源 
/item/score


* 榜单列表模块

2.1 资源排行榜
/top/id  （下载排行，上升排行，最新上架排行）

2.2 专题列表 
/feature

2.3 专题内资源 
/feature/id


* 搜索推荐模块

3.1 搜索资源
/search

3.2 热门搜索
/search/hot

3.2 详情页-相关推荐
/rec/info/id

3.3 首页 - 推荐
/rec/index



* 附录：

1. Item 数据模型
<pre>
    {
    id:112,
    name:'hello app',
    intro:'',
    author:'qq',
    keyword:'hello',
    tags:'new,offcial,update',
    
    versionName:'1.0',
    versionCode:'120',
    size:'12M',
    iconUrl:''
    downUrl:'',
    downCount:222,
    commentCount:20,
    score:4.9,
    
    itemType:'',
    saleType:'free',
    channel:1,
    }
</pre>
