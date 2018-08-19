# BioHub页面需求详情

## 登录页
![](BioHub登陆注册忘记密码/preview/pages-登陆页.png)
**需求**
- 左手挥动
- 超链接鼠标移上去颜色变化（可为插件默认效果）

**待改进**
- 输入密码错误提示incorrect password 
- 用户名不存在incorrect username

## 注册页
![](../Art/BioHub登陆注册忘记密码/preview/pages-注册页.png)
**需求**
- 移到button上会有颜色变化（可为插件默认效果）
**待改进**
- Uername错误输入框后面出现警告图标，Ｕsername变红，出现提示语句（Username exists）
- Email错误输入框后面出现警告图标，Email变红，出现提示语句（incorrect email）
- password输入过程中下方有强度提醒.(有插件可以用就先直接用.没有美工再画素材)
- password输入错误输入框出现警告图标.　password变红,出现提示语句(at least 8 characters)
- 巨幕相应的伸缩变长
- 可找到类似插件改进左侧多边形图，让图运动

## 忘记密码
![](../Art/BioHub登陆注册忘记密码/preview/pages-忘记密码01.png)
**需求**
- Email错误输入框后面出现警告图标，Email变红，出现提示语句（incorrect email）
- 熊猫挥手


## 个人中心
**需求**
#### 别人看到的个人中心：
**需求**

>此页面中头像下方的Reports,Following,Followers,Praises和右上角的Reports,Following,Followers,Praises点击效果等价.

默认：
Reports被选中，如下

点击后：
- 点击右上角的Following,Followers,Praises标签，显示相应的信息（转换效果见下方说明）
- 在Following,Followers显示中能点击相应的profile进入其他用户的个人主页.显示follow或者unfollow选项.点击可以进行修改是否关注
- 点击Archive或者Archive中的标签，显示如下
- 点击Labels或者Lables中的标签，显示如下
- 点击Popular Reports中的内容跳转到报告显示页面

**转换效果**　
1. 如果此时显示了右上角的Following,Followers,Praises标签：
    1. 点击Archive和Labels时，Following,Followers,Praises渐影消失,相应的标签或者归档右侧快速插入出现
    2. 点击Following｜Followers｜Praises直接显示即可
2. 如果此时没有显示右上角的Following,Followers,Praises标签：
    1. 点击Archive和Labels及其相关内容时，直接显示即可
    2. 点击点击Following｜Followers｜Praises时，相应的标签或归档渐影消失,Following,Followers,Praises右侧快速插入出现

#### 自己看到的个人中心：
- 鼠标移到　**collections** 和　**favorites** 下方有选中的阴影线条
- 点击右上角 **collections** 和 **favorites** 显示自己的收藏和点赞文章
- 点击**collections**中的收藏夹分类可以收缩或展开收藏夹的内容
- 点击相应的　报告跳转到报告显示页面
- 点击edit跳转到修改信息页面
- 点击向下的小箭头显示下一组信息 collections | favorites 信息
- 点击Reports|Following|Followers|Praises|跳转到点击后的相应展示页（展示页中没有About Me,location,email,organization）


#### 修改个人信息页面
**需求:**
- 左侧目录Basic Information|Account|Reports鼠标指示有颜色变化
- 点击目录的内容显示相应的内容（点击Reports时，左侧目录向左收缩成一个hamberger button）
- 点击hamberger button目录展开回来
- 修改信息不符合要求的（长度受限制，特殊字符等）save之后给出相应的错误提示样式

