/*
* author shizhongjie
*/

git下载安装

使用git进行版本控制

使用git下载github项目
1.新建文件夹，文件夹内右键git bash here
2.设置用户名
$ git config --global user.name "runoob"  
3.设置邮箱
$ git config --global user.email test@runoob.com
4.从github地址克隆项目
$ git clone <版本库的网址>
例如： $ git clone https://github.com/Inotbird/zhiliao.git

提交本地项目到github
1.提交文件或文件夹到暂存区
$ git add 文件或文件夹
例如 $git add readme.txt
2.提交文件到本地仓库
$git  commit -m "备注"
3.提交本地仓库文件到github
$git push

更新最新项目到本地
1.本地修改储存
git stash 
2.更新最新到本地
Git pull

删除文件
$ git pull origin master                    # 将远程仓库里面的项目拉下来
$ dir                                                # 查看有哪些文件夹
$ git rm -r --cached target              # 删除target文件夹
$ git commit -m '删除了target'        # 提交,添加操作说明