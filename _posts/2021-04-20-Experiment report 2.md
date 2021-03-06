---
layout: post
author: david
---


Second Assignment - Developing A Static Website
--------------------------

*  1.The Structure of The Website Directory


![Structure](/assets/images/1.jpg)


*  2.The Web Interface:
    
    (1)Home Page
    ![Home Page](/assets/images/Homepage.jpg)

    (2)Blog Page
    ![Blog Page](/assets/images/Blogpage.jpg)

    (3)Post Page

    ![Post Page](/assets/images/Postpage.jpg)

    (4)Staff Page

    ![Staff Page](/assets/images/Staffpage.jpg)

    (5)Writer Page

    ![Writer Page](/assets/images/Writerpage.jpg)


    (6)About Page

    ![About Page](/assets/images/Aboutpage.jpg)

*   3.The Process of The Assignment
     + 首先根据教程在vscode先完成网站的框架搭建，再对网页内容进行修改，实时观察修改内容是否生效。
     + 完成vscode与github的关连，将所编写的网站代码push到github的仓库上。
     + 安装nginx，先对nginx的配置进行修改，将存储网站代码的github仓库clone到nginx中，再重新启动nginx，观察网页效果。
     + 更新代码到nginx上，首先cd到var/www/html，然后到自己的.io文件夹，先git status查看状态，然后再用sudo
     git pull更新代码(这里用git pull可能会被拒绝访问)，如果失败请多尝试几次


*  4.The Problems and Feedbacks
     + 首先就是在对网站文件修改时遇到的问题，当时我直接是对_site里面的文件进行修改，但是每次重新使用jekyll serve命令之后，都发现之前修改过的文件被删除了；后面通过询问老师发现，_site文件夹里面的文件为系统自动生成的，无法外部修改，必须对该文件夹之外的文件进行操作，才能修改成功。
     + 其次就是在使用nginx时，当我们把网页代码上传到github之后，需要修改里面的默认分支，使其为存储网站代码的分支，不然最后使用nginx时无法成功呈现出网页效果。
     + 心得体会：通过本次实验，我基本了解了有关网站建设，配置等方面的基本知识，同时也对web应用软件开发课程有了一个更深的了解；我也希望能够通过以后的学习，能够对网站建设有更深的理解。




