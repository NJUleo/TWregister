1.1.1 个人信息设置
-----------------

刺激响应序列|foo-bar
---------:|----------
刺激:| 用户进入注册界面
响应:| 系统返回并向用户展示需要填写的信息
刺激:|用户填写信息，并验证邮箱
响应:|系统发送验证邮件
刺激:|用户点击确认注册
响应:|系统保存用户信息，提示注册成功
刺激:|用户选择退出
响应:|系统提示退出成功

foo | bar 
---------|----------
Client.RegisterInfo.getInformation | 返回需要用户填写的信息 
Client.RegisterInfo.sendVerifyMail | 发送验证邮件 
Client.RegisterInfo.saveUserInfo | 保存用户信息 

1.1.7 修改姓名
-----------------

刺激响应序列|foo-bar
---------:|----------
刺激:| 用户进入注册界面
响应:| 系统返回并向用户展示需要填写的信息
刺激:|用户填写信息，并验证邮箱
响应:|系统发送验证邮件
刺激:|用户点击确认注册
响应:|系统保存用户信息，提示注册成功
刺激:|用户选择退出
响应:|系统提示退出成功

foo | bar 
---------|----------
Client.RegisterInfo.getInformation | 返回需要用户填写的信息 
Client.RegisterInfo.sendVerifyMail | 发送验证邮件 
Client.RegisterInfo.saveUserInfo | 保存用户信息 