# 配置企业微信机器人推送
`以下方法使用PC端为例`
1. 登录企业微信，创建一个企业 **（必须创建企业而不是创建团队）**

2. 打开企业微信，消息页面点击➕，发起群聊，随便选两个人。(由于微信限制，必须选中额外的两个人，~~然后将他们踢出群聊就行，不然TA就能看到你的签到信息。~~💦)
   。

   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/ed95d53e-8d49-4138-8774-46d59ac4c55e)

   `群聊名称可以随便修改`

2. 进入群聊，点击右上角三个点 `···` --> 添加群机器人 --> 添加机器人

   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/e7496390-8e97-4b40-b942-84d3a8bd5d5f)

   在弹出的页面中点击`新创建一个机器人`
   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/133d5140-199f-43b2-b2ce-354075efa83a)
   
   给机器人随便取个名字后，点击添加机器人
   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/c09c877e-7204-46c5-96ff-05ce1435dcb3)

   出现以下页面代表设置完成
   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/736c6679-2827-4f3f-86f0-38b84f21bd8f)
   
    **❗❗❗复制地址❗❗❗**
   ```
   复制之后你会得到如下：
   https://qyapi.weixin.qq.com/cgi-bin/webhook/send?key=12345678910xxxxxxxxxx
   
   我们不需要等号前面的信息，只需要等号后面的信息，如：`12345678910xxxxxxxxxx`，然后将这段数据设置到对应的环境变量中去。
   ```

   如果不小心将该窗口关闭，可以点击`进入群-->在右侧找到机器人-->左健添加的机器人`就可找到信息了，在这里面还可以设置关键词、对机器人改名、删除机器人等操作。

   成功案例：
   ![image](https://github.com/anduinnn/HiFiNi-Auto-CheckIn/assets/115618748/9833c006-181a-4eb7-a59a-2b43ba58beab)

   
