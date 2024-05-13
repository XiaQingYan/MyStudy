# MyStudy
自己学习用的而已~~~
##### 全流程如下

# 安装Git
"""
下载Git Bash安装，这没啥
"""
# 连接到GitHub
"""
用的SSH，先确定电脑安了SSH服务再说，设置里就有
然后创建密钥（非对称加密一对）公钥上传到Github
要自己编辑一个config文件在.ssh目录下
运行之后会生成host什么文件
之后创建一个远程仓库，本地建立一个同样名字的
在本地打开Git Bash后，先用git init创建.git
之后按GitHub提示连接就行，注意要选SSH方式（git@什么什么）
然后注意GitBash的复制粘贴是Ctrl+Insert和Shift+Insert
之后大功告成
"""
# 将本地文件同步到云
"""
最简单的操作如下：
git add {文件名}
    用来把修改放到暂存区，用.就是全部
git commit {-m “说明”}
    将暂存区的更改创建为一个提交记录，并保存到本地版本库中。简单说明就在这写，复杂的不加
git push origin {远程仓库名}
    推送指定分支到远程仓库
"""