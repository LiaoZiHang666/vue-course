配置：
	name
	email
	git config --global user.name "liaozihang"
	git config --global user.email "769037937@qq.com"
使用git:
	git status 查看项目状态
	git init 初始化仓库
	
	刚添加的文件处于未跟踪状态：
		未跟踪--->暂存
			git add .\filename 将文件切换到暂存状态
			git add  * 将所有已修改(未跟踪)的文件暂存
		暂存--->未修改
			git commit -m "xxxx"将暂存的文件存储到仓库中
			git commit -a "xxxx"提交所有已修改的文件(未跟踪的文件不会提交)
		未修改--->修改
			修改代码后，文件会变为修改状态git add .\filename