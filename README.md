# github_-
![image](http://a4.qpic.cn/psb?/V14LWyim3xWUYY/MYDeB6oyZTz*XzCk8VmzdkAOVMllL2nFkEou1mI7Rnc!/m/dI8AAAAAAAAAnull&bo=tAOAAgAAAAADBxc!&rf=photolist&t=5)


1.第一步：在as上登陆github



![image2](http://a1.qpic.cn/psb?/V14LWyim3xWUYY/b1aBvaPZ7wzOP1rL8O8DQQV*U3CR5.Z.kO0ff.vRCNQ!/m/dHwBAAAAAAAAnull&bo=0QOAAgAAAAADB3I!&rf=photolist&t=5)


2.第二步:申请key


![image3](http://a2.qpic.cn/psb?/V14LWyim3xWUYY/qnEJAfDqnhJvNTEVcP5jHS0PjjYOnm1JvpeDDbjJ.cY!/m/dHkBAAAAAAAAnull&bo=nASAAgAAAAADBzg!&rf=photolist&t=5)


3.第三步：如果安装好了github命令软件后，右键会显示git Gui Here 与git Bash Here这两列，选择git Bash Here，然后弹出命令窗口


![image4](http://a4.qpic.cn/psb?/V14LWyim3xWUYY/qfeqZY5.Sv9Thk4CvTDaAiL8LucoMqk6T69krCvQj8k!/m/dG8BAAAAAAAAnull&bo=XASAAgAAAAADB*g!&rf=photolist&t=5)


4.第四步:输入命令：ssh-keygen -t rsa -C "your_email@example.com"


![image5](http://a1.qpic.cn/psb?/V14LWyim3xWUYY/0FYHDMuXYzmYaWZZUeGu2ZlR2zIcQ621YGgRIS5eS1I!/m/dNwAAAAAAAAAnull&bo=CQMbAQAAAAADBzI!&rf=photolist&t=5)


5.第五步:命令执行后，找到这个位置，一共是三个文件


![image6](http://a3.qpic.cn/psb?/V14LWyim3xWUYY/5XBCKtcQ112orB1g0A4*pyt7ePxpTfBB0ZIeKdaYi58!/m/dAoBAAAAAAAAnull&bo=QgSAAgAAAAADB.Y!&rf=photolist&t=5)


6.第六步:打开这个文件，然后复制到github 申请key位置那里，然后将key添加到ssh中,这个用命令来执行,命令:$ ssh-add ~/.ssh/id_rsa


![image7](http://a4.qpic.cn/psb?/V14LWyim3xWUYY/wdbo58r0*awxylFX0Zn.vfkw2Lt6CA.X22qfjfq.MRs!/m/dB8BAAAAAAAAnull&bo=tgFDAQAAAAADB9c!&rf=photolist&t=5)


7.第七步:建立远程仓库,命令：$ git remote add origin git@github.com:michaelliao/learngit.git   //origin 库名,michaelliao是github账号，learngit是存储库名


![image8](http://www.liaoxuefeng.com/files/attachments/00138490848464619aebd9a2bb0493c83e132ca1eed6f66000/0)


8.第八步: 将项目的根目录位置下,输入命令 $ git init 结束 $ git add . 结束 $ git commit -m "描述"，最后，$ git push -u origin master 结束。


9.git status 结束，这个命名主要用来查询是否创建成功。
