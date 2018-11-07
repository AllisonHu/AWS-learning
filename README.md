Create new repository
echo "# AWS-learning" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/AllisonHu/AWS-learning.git
git push -u origin master

push file
git commit -m "Update readme.md commit"
git push -u origin master

git config 在本地配置以下远程服务器的信息，使用方式如下：

git config --global user.name "用户名"

git config --global user.email "用户的邮箱名"

change