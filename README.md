### 接口介绍

支持超星学习通、智慧树、智慧职教、职教云、词达人等超过20家网课平台的答案查询

收录超过1400W道题目，并在不断更新，日更新量2W+。

#### 题目数据来源于互联网，非爬取网课平台题库，如有侵权请联系删除

### 脚本下载地址

油猴脚本，下载完了自己复制到油猴里使用吧。

视频+测验： [http://imnu.52king.cn/api/wk/xxtsk.user](http://imnu.52king.cn/api/wk/xxtsk.user)

考试： [http://imnu.52king.cn/api/wk/xxtks.user](http://imnu.52king.cn/api/wk/xxtks.user)

[不用用脚本的直接下载专用浏览器吧](https://cloud.189.cn/t/nqUzMj2mEVFz)（访问码：d2co）

### 接口地址

|接口类型                   | URL                                    | 传递参数                   |token|每天调用总数|
| ----------------------- | -------------------------------------- | -------------------------- | --- |-----|
|http                      |http://imnu.52king.cn/api/wk/index.php  |  c=问题                    |无 |本接口每日免费查询10w次|
|http收费接口                      |http://nw.52king.cn/api/wk/vip.php  |  c=问题&token=你购买的token                   |[购买token](http://imnu.52king.cn/wk/?cid=7&tid=16)   |20000|
|微信公众号                | http://imnu.52king.cn/api/wk/v1.php    | 无                         | weixin|无限制|
|微信公众号（语音查题）                | http://imnu.52king.cn/api/wk/v2.php    | 无                         | weixin|无限制|
 


### 接口格式

| 类型     | JSON接口                                                     | 
| -------- | ------------------------------------------------------------ |
| 返回格式 | {‘tm’:"该处返回题目",'da':"该处返回答案","code":0} | 



### :sunny: 有问题联系微信 97081753 :sunny: 添加好友时请注明来意

### 更新内容：
    2021.01.29 增加分词功能，匹配度更高。
    2021.02.09 限制并发数为2,超出的封禁1天。
    2021.02.20 公众号v2接口新增语音查题功能。需要开启语音识别接口。
