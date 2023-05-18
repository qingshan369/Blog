---
title: Git的基础操作
date: 2023-05-18 12:06:37
tags:
    - 编程
---

1. 在文件夹目录下鼠标右键单击==Git Bush Here==弹出git命令行

2. 创建本地仓库
```Git
	git init
```

3. 查看本地仓库状态
```Git
	git status
```

4. 将本地项目工作区的所有文件添加到暂存区
```Git
	git add --all
	git commit -m "[提交说明]"
```

5. 将本地仓库关联到Github上
```Git
	git remote add origin [仓库地址]
```

6. 将代码由本地仓库上传到Github远程仓库
```Git
	git push -u origin master
```

