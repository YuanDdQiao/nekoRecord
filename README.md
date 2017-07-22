记录宠物日常喂养的微信小程序 
===================

### 效果图
![效果图](https://github.com/feiaaa/nekoRecord/blob/master/readMe/nekoRecord.jpg)

### 诞生背景
>“我有努力养好我家的鱼，为什么它还是死了？”  
>
>"养的兔子拉稀了，医生问我什么时候给它换了粮食的品牌，我不知道！"  
>
>"啊！我忘记我家的狗狗什么时候该去打疫苗了！"  
>
>平日匆忙懒散，是不是不记得最近一次给家里的主子换水是什么时候？  
>
> 主子内心的os：“和别人家的铲屎官比起来，我家的铲屎官抠门的要死，罐头都不我吃，真想炒了他。”  
>

### 应用描述
- 管理宠物的健康，记录日常饲养过程
- 记录宠物疫苗/洗澡/就医复诊等预约活动


### 使用工具
- 微信小程序默认的开发工具
- egret wing
- bmob 后端云 （mongodb）
- 马克飞象

### 需要
- weUI
- flex
- template

### 参考记录
- [小程序日历](https://github.com/treadpit/wx_calendar)
- [bmob接口文件](http://docs.bmob.cn/data/wechatApp/a_faststart/doc/index.html)
- 



### 当前进度
- 日历，我的（进行中，ui方面需美化，数据已经可以填写，但提交未做）
- 预约列表 过期内容需要归档，不可改动
- 添加预约 的时间需要设置为：日期+时间，数据部分要求能读到

### 日志
>2017-6-9
注册appid
下载小程序自带开发工具， wing
完成helloworld
了解每个页面的用途
>
>2017-6-10
git上引入calendar
 导航条以及添加页面
云数据bmob 注册，配置api
>
>2017-6-11
calendar控件，去掉一周，当日标红：
铺预约事件ui
单选复选picker监听器
>
>2017-6-12
铺添加预约事件，我的，日历
pages/index/index
>
>2017-6-13
使用weui
绑定数据，添加字段。
预约事件列表
复选框内容进不去（修复 ）
>
>2017-6-14
完成：修改日历为当日标红
添加tag 数据库（判定过期进行中）
>
>2017-6-15
重写 我的，美化页面
添加 宠物管理
>2017-6-17
添加导航图标
>
>2017-6-18
修复宠物列表
>
>2017-6-19
修复显示宠物属性
>
>2017- 6-24
修复switch按钮
修复picker
>
>2017-6-25
回滚到全部input输入，排查无法增加的宠物的问题
>
>2017-6-26
完成：添加宠物
calendar页面美化
>
>2017-6-26
完成：添加宠物
calendar页面美化，添加纵向滚条
>
>2017- 6-28
使用滚条的列表，背景颜色非白色
宠物列表添加头像展示；添加宠物，上传头像。
>

>2017-7-20
修复宠物详情页/预约详情页 展示问题，样式问题
>

>2017-7-21
修复：输入预约时间日期
>
>2017-7-22
修改提醒按钮样式 
修复：地点修改 
添加：预约列表：判断预约事件过期； 
日历页：铺预约事件样式
>