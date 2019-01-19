1.1.1学生填写申请表
刺激响应序列
	刺激：学生进入申请表填写板块
	响应：系统返回学生需要填写的空白申请表
	刺激：学生选择对姓名进行繁简转化
	响应：系统调用API进行完成转化
	刺激：学生确认转化后姓名无误，否则选择申请审核
	响应：系统将标记该份申请数据	
	刺激：学生点击“暂存”按钮
	响应：系统将表单数据保存在本地cookie中
	刺激：学生点击“提交”按钮
	响应：系统将表单数据提交至服务器

系统功能需求
	Client.fillApplication.showBlankApp	显示空白申请表
	Client.fillApplication.nameTrans	姓名繁简转化
	Client.fillApplication.setTag	标记姓名审核
	Client.fillApplication.tempStore	暂存表单
	Client.fillApplication.submit	提交表单



1.1.2管理员查看学生列表
刺激响应序列
	刺激：管理员发起查看学生列表的申请
	响应：系统显示学生列表
	刺激：管理员选定特定标记
	响应：系统显示符合该标记的学生列表
	刺激：管理员点击某条学生信息
	响应：系统显示该学生的详细信息
	刺激：管理员发起下载该学生申请表的申请
	响应：系统执行下载

系统功能需求：
	Administrator.checkStuList.showList	显示全部学生列表
	Administrator.checkStuList.selectTag	选定特定标签
	Administrator.checkStuList.showInfo	显示详细信息
	Administrator.checkStuList.downloadApp	下载申请表