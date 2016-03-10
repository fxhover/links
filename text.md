**启动unicorn**
undle exec unicorn -c config/unicorn.rb -E production

**rails ngxin配置public/images/xx目录文件访问**
location ~* ^/images/ {
    root /home/ubuntu/rails_app/public
    expires 1y;
    add_header Cache-Control public;
    add_header Last-Modified "";
    add_header ETag "";
    break;
}

**微博分享图片url**
http://service.weibo.com/share/share.php?url=http%3A%2F%2Fwww.ifanr.com%2F249713&appkey=3857924317&title=%E4%BB%85%E4%BB%85%E9%85%B7%E8%BF%98%E4%B8%8D%E5%A4%9F%EF%BC%8C%E9%82%AE%E4%BB%B6%E5%AE%A2%E6%88%B7%E7%AB%AF%20Mailbox%20%E4%BD%93%E9%AA%8C%20%23%E7%88%B1%E8%8C%83%E5%84%BF%E9%95%BF%E5%BE%AE%E5%8D%9A%23&pic=http%3A%2F%2Fcdn.ifanr.cn%2Ffiles%2Fcwb%2Fpost_249713.png%3Fv%3D1361270995490&ralateUid=1642720480&language=zh_cn

**rails like 可以这样写**
users=User.arel_table
User.where(users[:name].matches("%#{user_name}%"))

**rails在controller使用helper方法**
ActionController::Base.helpers.time_ago_in_words
ActionController::Base.helpers.sanitize

**关于使用Carrierwave上传文件的文章**
http://huacnlee.com/blog/carrierwave-upload-store-file-name-config/

http://jiunjiun.logdown.com/posts/2013/12/01/rails-upload-file-with-carrierwave

https://github.com/carrierwaveuploader/carrierwave/wiki/How-to%3A-Store-the-uploaded-file-size-and-content-type

https://github.com/carrierwaveuploader/carrierwave

**shenme?**
第一, 請牢記草榴社區的永久域名 
http://t66y.com 

第二, 草榴社區最新地址發布頁 ( 12.30更新 ) 
複製代碼
http://s821.beta.photobucket.com/user/newt66y/library/

http://www.shlf1314.net/

http://cl.bearhk.info

酷爱费络蒙

http://yamlan.cn/index.asp

http://izzs.net 专注分享福利

搜磁力：

http://www.socili.com/s/HBF

**rvm安装ruby报错的一些参考**
http://stackoverflow.com/questions/23650994/installing-latest-ruby-with-rvm-gives-error-on-ubuntu

https://rvm.io/rvm/offline

http://ruby.taobao.org/

**rails缓存相关的文章**
http://www.ibm.com/developerworks/cn/web/wa-rails1/


http://huacnlee.com/blog/cache-design-in-ruby-china/

**关于序列化**
http://www.sitepoint.com/choosing-right-serialization-format/



http://phrogz.net/programmingruby/ospace.html

**RangeError ._id2ref**
http://stackoverflow.com/questions/15458861/why-does-objectspace-id2ref-give-different-outputs-on-ruby-1-9-and-ruby-2-0#



https://github.com/thoughtbot/capybara-webkit/issues/122


https://github.com/thoughtbot/capybara-webkit/commit/922d197adfe5bb636f381ecae250744c3e8475cc

**php cancan**
https://github.com/machuga/authority

https://github.com/stackus/Allowance

https://packagist.org/search/?search_query[query]=auth

**IP地址**
http://iask.sina.com.cn/b/10867369.html

http://wenda.tianya.cn/question/07f5a598793699db

**同时将代码托管到github和code**
首先我们需要在CODE上创建一个空项目。使用git的–bare参数获取一个裸仓库，然后通过git push --mirror命令将代码推送到CODE。

git clone --bare https://github.com/forcegroup/iBurnMgr.git ibg.git

cd ibg.git

git push --mirror https://code.csdn.net/ipvb/iBurnMgr.git

**好像不错的游戏**
《黑暗之魂2》

《血源诅咒》ps4专属，没有PC版

**ffmpeg**
http://www.glgoo.com/search?newwindow=1&hl=zh-CN&q=ffmpeg+convert+image+to+mp4&spell=1&sa=X&ei=NRFTVb7LIKS8mAXS7oGYCg&ved=0CBcQvwUoAA


https://trac.ffmpeg.org/wiki/Create%20a%20video%20slideshow%20from%20images


http://www.labnol.org/internet/useful-ffmpeg-commands/28490/

http://thierry-xing.iteye.com/blog/2017864

**微信扫码支付**
http://pay.weixin.qq.com/wiki/doc/api/native.php?chapter=4_2

http://www.codes51.com/article/detail_130496.html

http://mch.weixin.qq.com/wiki/doc/api/index.php?chapter=6_3

http://www.mamicode.com/info-detail-517690.html

**优酷会员账号密码**
getu000@163.com       qq432156

13688417103       5201457zws

**支付宝文档**
https://fuwu.alipay.com/platform/doc.htm#c07

http://app.alipay.com/market/document.htm?name=saomazhifu#page-14

https://app.alipay.com/market/document.htm?name=saomazhifu#page-6


** Ruby 1.9+ 的字符编码**

https://ruby-china.org/topics/16856  


http://stackoverflow.com/questions/728308/escape-problem-with-hex


http://stackoverflow.com/questions/27124145/ruby-trying-to-dynamically-create-unicode-string-throws-invalid-unicode-escape

**rails未看完的文档**
http://guides.ruby-china.org/active_record_callbacks.html

http://guides.ruby-china.org/security.html#sql-injection

http://guides.ruby-china.org

**支付宝和微信web手机端支付**
https://b.alipay.com/order/productDetail.htm?productId=2014110308142133


https://pay.weixin.qq.com/wiki/doc/api/index.html

**php composer的资料**
https://getcomposer.org/doc/00-intro.md

http://www.csdn.net/article/2012-07-05/2807142

namespace:

http://blog.csdn.net/xxhsu/article/details/8463624

**IOS不通过app store直接安装应用的一些资料**
http://mobile.51cto.com/hot-439095.htm

http://ios.appchina.com

http://app.kuaiyong.com

nginx配置ssl：

http://www.cnblogs.com/tintin1926/archive/2012/07/12/2587311.html

微信跳转App Store：

http://www.zhihu.com/question/21883363

判断设备是不是IOS：

http://zhidao.baidu.com/link?url=OUlTv1hy0NQCFjn5dTLFko21p1a1nacEVDQbUsJhm3hFUdPDJ2Yde9a8ibwWHYTcYXFDg28YHeu68L6WvC5Pa_7M4NxrQInv4zmlVZqaeKu

**qq登录oauth相关的资料**
http://wiki.open.qq.com/wiki/website/Qzone_OAuth_1.0认证简介

http://wiki.open.qq.com/wiki/website/OpenAPI调用说明_OAuth1.0

http://wiki.connect.qq.com/获取用户openid_oauth2-0

http://wiki.open.qq.com/wiki/website/get_user_info

http://connect.qq.com/sdk/webtools/index.html#get_user_info

http://wiki.open.qq.com/wiki/website/OAuth1.0升级到OAuth2.0指引

https://github.com/046569/qq

**php使用curl cpu100%问题**
http://www.phpddt.com/php/curl_multi.html    cURL multi批处理实现及避免cURL multi造成CPU负载过高问题


http://www.laruence.com/2014/01/21/2939.html    Curl的毫秒超时的一个”Bug” 


http://m.blog.csdn.net/blog/u012810515/18988755   [原]如何实现PHP异步调用或者说并行计算


http://www.workerman.net/workerman-thrift    workerman-thrift-rpc


http://php.net/manual/fr/function.curl-multi-exec.php

**旅游产品**
http://www.travelzoo.com/cn/

**模拟登录百度**
http://www.cnblogs.com/dingli/p/4563766.html

http://bbs.125.la/thread-13706317-1-1.html


**SQL优化方法以及案例**
地址：http://wenku.baidu.com/link?url=DvDKIUVgSd2i4yD3bywN2I1iBP1HLyMVHJyHb8M2oAECsx04T8pOHmm2u77T6EV4J356Cb1mYzhuqrg2J-yHeRUo4dzRsBFiDxnhvzqzo0u
1. 尽量少join:优先内查询》左右连接，子查询。
2. 尽量少排序：
对于MySQL来说，减少排序有多种办法，比如：

　a通过利用索引来排序的方式进行优化　b减少参与排序的记录条数c非必要不对数据进行排序

3. 尽量避免select *
只是大多数时候是不会影响到 IO 量，当我们的查询结果仅仅只需要在索引中就能找到的时候，还是会极大减少 IO 量的。
4. 尽量用join代替子查询
虽然 Join 性能并不佳，但是和 MySQL 的子查询比起来还是有非常大的性能优势。MySQL 的子查询执行计划一直存在较大的问题，虽然这个问题已经存在多年，但是到目前已经发布的所有稳定版本中都普遍存在，一直没有太大改善。
5. 尽量少用or
　当 where 子句中存在多个条件以“或”并存的时候，MySQL 的优化器并没有很好的解决其执行计划优化问题，再加上 MySQL 特有的 SQL 与 Storage 分层架构方式，造成了其性能比较低下，很多时候使用 union all 或者是union(必要的时候)的方式来代替“or”会得到更好的效果。
6. 尽量用union all 代替 union
union 和 union all 的差异主要是前者需要将两个(或者多个)结果集合并后再进行唯一性过滤操作，这就会涉及到排序，增加大量的 CPU 运算，加大资源消耗及延迟。所以当我们可以确认不可能出现重复结果集或者不在乎重复结果集的时候，尽量使用 union all 而不是 union
7. 尽量早过滤
　这一优化策略其实最常见于索引的优化设计中(将过滤性更好的字段放得更靠前)。

　　在 SQL 编写中同样可以使用这一原则来优化一些 Join 的 SQL。比如我们在多个表进行分页数据查询的时候，我们最好是能够在一个表上先过滤好数据分好页，然后再用分好页的结果集与另外的表 Join，这样可以尽可能多的减少不必要的 IO 操作，大大节省 IO 操作所消耗的时间。

8. 避免类型转换
这里所说的“类型转换”是指 where 子句中出现 column 字段的类型和传入的参数类型不一致的时候发生的类型转换：

　　人为在column_name 上通过转换函数进行转换

　　直接导致 MySQL(实际上其他数据库也会有同样的问题)无法使用索引，如果非要转换，应该在传入的参数上进行转换

　　由数据库自己进行转换

　　如果我们传入的数据类型和字段类型不一致，同时我们又没有做任何类型转换处理，MySQL 可能会自己对我们的数据进行类型转换操作，也可能不进行处理而交由存储引擎去处理，这样一来，就会出现索引无法使用的情况而造成执行计划问题。

9. 优先优化高并发的sql，而不是执行效率低某些大sql.
10. 从全局出发优化，而不是片面调整。
 不能只针对某一个进行，而应该充分考虑系统中所有sql。尤其是通过调整索引优化sql执行计划时候，不能顾此失彼。
11. 尽可能对每一条运行在数据库中的sql进行explain.
12. 尽量使用联合（union）来代替手动创建的临时表。
它可以把需要使用临时表的两条或更多的 SELECT 查询合并的一个查询中。在客户端的查询会话结束的时候，临时表会被自动删除，从而保证数据库整齐、高效。使用 UNION 来创建查询的时候，我们只需要用 UNION作为关键字把多个 SELECT 语句连接起来就可以了，要注意的是所有 SELECT 语句中的字段数目要想同。下面的例子就演示了一个使用 UNION的查询。 
SELECT Name, Phone FROM client UNION SELECT Name, BirthDate FROM author 
UNION 
SELECT Name, Supplier FROM product
 
实例：
1.大结果集排序问题。
看看正序取得结果的耗时：

mysql>SELECT a.HandicapID, FROM_UNIXTIME( a.AddTime, '%y-%c-%e %H:%i' ) AS ShowAddTime, a.MatchID, a.MakerID, a.HandicapNumber ...FROM MatchHandicap AS aLEFT JOIN MatchInfo AS b ON ( a.MatchID = e.MatchID )LEFT JOIN Team AS c ON ( e.HomeID = c.TeamID )LEFT JOIN Team AS d ON ( e.AwayID = d.TeamID )LEFT JOIN BookMaker AS e ON ( a.MakerID = e.MakerID ) ORDER BY a.HandicapID LIMIT 11910298, 20;................20 rows in set (1330 sec)

很恐怖吧，暂且不论这个SQL语句其他可以再优化的地方，把它改造成用倒序取得结果的方式试试看：

mysql>SELECT a.HandicapID, FROM_UNIXTIME( a.AddTime, '%y-%c-%e %H:%i' ) AS ShowAddTime, a.MatchID, a.MakerID, a.HandicapNumber ...FROM MatchHandicap AS aLEFT JOIN MatchInfo AS b ON ( a.MatchID = e.MatchID )LEFT JOIN Team AS c ON ( e.HomeID = c.TeamID )LEFT JOIN Team AS d ON ( e.AwayID = d.TeamID )LEFT JOIN BookMaker AS e ON ( a.MakerID = e.MakerID ) ORDER BY a.HandicapID DESC LIMIT 20;........

两次查询的耗时简直是天差地别：1330s VS 0.05s，。有些程序员很懒，或者没有考虑过这个问题，经常会在取结果的时候一直按照同一种排序方式，而没有考虑到当该排序方式碰到超大结果集时会变得非常慢的问题。因此，我们可以在程序中约定，当按原来的排序方式取得结果过程中，如果LIMIT START,OFFSET中的START的值超过总记录数的一定比例(例如一半)，就将排序方式倒过来，虽然这么做可能会导致一些其他小问题，但我认为这是非常值得的。

2.select 的结果集占全表的20%，就会走全表 ，而不走索引！ 我想可能是MYSQL优化器根据CBO成本估算，如果select数据量大，估计走索引的成本会比走全表的还大，所以才会全表扫描而不走索引！
3.order by 后的字段，如果要走索引，须与where 条件里的某字段建立复合索引！！或者说orcer by后的字段如果要走索引排序，它要么与where 条件里的字段建立复合索引【这里建立复合索引的时候，需要注意复合索引的列顺序为（where字段，order by 字段），这样才能满足最左列原则，原因可能是order by字段并能算在where 查询条件中！】，要么它自身要在where 条件里被引用到！
表a       id为普通字段,上面建有索引 
select * from a order by id   (用不上索引)
select id from a order by id (能用上索引)
select * from a where id=XX order by id  (能用上索引)
意思是说order by 要避免使用文件系统排序，要么把order by的字段出现在select 后，要么使用order by字段出现在where 条件里，要么把order by字段与where 条件字段建立复合索引！
4.想从MySQL数据库中随机取一条或者N条记录时，最好把RAND()生成随机数放在JOIN子查询中以提高效率。
SELECT id FROM table ORDER BY RAND() LIMIT n;

改造成下面这个：

SELECT id FROM table t1 JOIN (SELECT RAND() * (SELECT MAX(id) FROM table) AS nid) t2 ON t1.id > t2.nid LIMIT n;

如果想要达到完全随机，还可以改成下面这种写法：

SELECT id FROM table t1 JOIN (SELECT round(RAND() * (SELECT MAX(id) FROM table)) AS nid FROM table LIMIT n) t2 ON t1.id = t2.nid;

**移动套餐**
http://www.bj.10086.cn/service/promotion/4607/index.shtml

http://service.bj.10086.cn/poffice/package/showpackage.action?from=bj&PACKAGECODE=GPRSYW&isCheck=1

http://shop.10086.cn/hd/1111/100.html#czxtc

**padrino设置日志**
csdn_group项目，把config/boot.rb中的Padrino.load! 换成：

Padrino::Logger::Config[:production] = { :log_level => :devel, :format_datetime => " [%Y-%m-%d %H:%M:%S] ", :stream => :to_file }
Padrino::Logger.setup!

Padrino.load!


**西安保利春天里**
http://news.xinhuanet.com/house/xa/2014-07-23/c_1111750295.htm

http://house.southcn.com/lswq/content/2016-01/18/content_140989257.htm

http://news.iygw.cn/2016/xw_shanxxw_0128/234346.html


