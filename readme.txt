/*	本项目是King开发时留有的备用
**	Author:King
**	Author-Email: king2934@126.com
****************************************************/

git init
git add README.md
git commit -m "first commit"
git remote add php https://github.com/king2934/php.git
git push -u php master
说明文件的更新
git init //初始化 在当前项目目录中生成本地git管理,并建立一个隐藏.git目录
git add . //添加当前目录中的所有文件到索引
git commit -m "first commit" //提交到本地源码库，并附加提交注释
git remote add php https://github.com/king2934/php.git //添加到远程项目，别名为php 
git push -u php master //把本地源码库push到github 别名为php的远程项目中，确认提交