1.1.1学生附件上传
刺激响应序列
	刺激：学生进入附件上传板块
	响应：系统返回学生需要上传的所有附件需求
	刺激：学生在每个需求下使用文本选择器选择上传文件
	响应：系统显示该文件路径
	刺激：用户希望提交
	响应：系统返回缺交附件（此时未提交）
	刺激：用户确认提交
	响应：系统发送所有附件至服务器，显示提交完成

系统功能需求
	Client.Upload.FileChooser	系统允许用户选择文本
	Client.Upload.IsCompleteFiles	系统提示用户附件是否完整
	Client.Upload.GetUpload	系统允许用户上传附件



1.1.2管理员发布志愿
刺激响应序列
	刺激：管理员点击招生开始
	响应：系统转跳到专业选择版面
	刺激：管理员添加本次招生专业
	响应：系统显示本次招生专业
	刺激：管理员编辑材料提交ddl
	响应：系统显示编辑内容
	刺激：管理员选择发布
	响应：系统提示管理员进行核查
	刺激：管理员确认发布
	响应：系统发布志愿

系统功能需求：
	Administrator.Release.SelectProfession	系统允许管理员选择专业
	Administrator.Release.SetDDL		系统允许管理员编写材料提交DDL
	Administrator.Release.CheckDetail	系统提示管理员核查发布专业及DDL
	Administrator.Release.SendOut	系统允许管理员发布招生专业及DDL