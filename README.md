# 什么？你在上班？你这个年龄段，你这个年纪，你怎么能全心全意上班呢？


这个文件可以在本地运行， 但是既然可以部署到服务器自动运行为什么要在本地手动呢？

下载moy.py这个文件 上传到青龙的scripts文件目录下()

然后在青龙的定时任务中添加 上文件就行定时的话可以 设置为 0 10 0 * * *(每天10点自动发送)

mail_host="smtp.XX.com"  #设置服务器 替换XX为QQ或者163(根据个人发送的账号平台为准)

mail_user="XXXX"    #用户名  qq发的话就是qq账号  网易的话就是账号就行 不带@163.com

mail_pass="XXXX"   #口令  这个是SMTP 不知道是啥的百度一下教程很多

sender = 'XX@XX.com'   #发送的邮箱号

receivers = ['XXXX']  # 接收邮件账号
 
 在main里面 有str_1可以自己修改想发送的话

#注意：此文件只是一时兴起，代码很烂，仅提供参考。只是个人兴趣，大佬勿喷。欢迎指导！！谢谢使用
