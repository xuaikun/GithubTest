# GithubTest
学习将工程上传GitHub
### 1、Windows上安装Git步骤链接：https://www.cnblogs.com/vitah/p/3612473.html
### 2、添加公钥到GitHub上的步骤：https://blog.csdn.net/li_lening/article/details/80865431 （本地和GitHub之间的通信）
### 3、在Windows上使用Git步骤链接：https://www.cnblogs.com/cxk1995/p/5800196.html
### 4、输入git push -u origin master 一定要注意，它会弹出登录GitHub的窗口（一定要注意，可能被挡住了），如果没有注意到，
### 参考链接解决：https://stackoverflow.com/questions/9661059/git-pull-rebase-upstream-git-push-origin-rejects-non-fast-forward
### 5、非常需要注意的是：当你准备上传项目的时候，不应该认为修改，GitHub上面的目标仓库

# 备注：在自己的随便一台电脑，某个目录行，打开Git Bash 利用：git clone + github上某个仓库的路径：比如 https://github.com/xuaikun/GithubTest.git
# 就可以将xuaikun的GitHubTest仓库的文件下载到你的目录下，并且包好仓库里面所有的文件，直接拿出来就可以使用了，就是整个工程，立马可以运行，perfect~

### 几个重要的语句：
### git clone + 仓库链接（接下来这个仓库就成为了本地仓库，每次更新都得来把这个里面的文件进行更改） 
### git add . (记得add 和 . 之间存在一个空格)
### git commit -m "Aikun_Xu_Pc" (" " 双引号中是修改的人)
### git push -u origin master (初次运行时，会弹出窗口让你输入你的GitHub账号和密码，把文件上传到GitHub上面，若出现问题则参考：
### https://stackoverflow.com/questions/9661059/git-pull-rebase-upstream-git-push-origin-rejects-non-fast-forward )
### 文件更新，得把本地仓库的文件修改后，执行以上语句


### 这是利用python在pychram下调用百度人脸比对sdk进行筛图的程序
### TwoClassCompare.py 表示类类比较
### InterClassCompare.py 表示类间比较
### 总体来说程序还是比较简单的，过两天去把公司的最后的那个从大文件中选出指定图片的程序弄回来