#项目文档
<br/>
##1.项目说明
>非常感谢大家可以欣赏MxOnline这个项目，中文名称在线教育系统，这个项目的本身非常的简单，没有什么技术难度！

##2.所需要的环境与组件
>主要用到环境：Python3.6<br/>
>Django1.11.7<br/>
>Pymysql<br/>
>Mysql<br/>
>pure_pagination<br/>
>DjangoUeditor<br/>
>captcha<br/>
>xadmin<br/>
>crispy_forms<br/>

##3.安装
>1.下载项目后进入项目目录```cd Online-education/MxOnline/```<br/>
>
>2.如果阁下没有安装上面我所说到的环境，请阁下自行安装。<br/>
>
>3.安装环境后请修改```Online-education/MxOnline/MxOnline/```目录下的```settings.py```文件里面的```DATABASES ```数据库连接信息和邮箱配置信息
>
<br/>
>4.然后进入项目```Online-education/MxOnline/```目录执行:```python manage.py makemigrations```<br/>
>
>5.在执行：```python manage.py migrate```<br />
>
>6.在建创后台管理员```python manage.py createsuperuser```
><br/>

##4.运行
>5.然后请阁下执行```python manage.py runserver```<br/>
>
>6.然后访问```http://127.0.0.0:8000```<br/>
>
>7.后台地址```http://127.0.0.0:8000/admin/```<br/>
>

##5.项目效果图
![Alt text](./images/1.png)<br/>
![Alt text](./images/2.png)<br/>
![Alt text](./images/3.png)<br/>
![Alt text](./images/4.png)<br/>
![Alt text](./images/5.png)<br/>
![Alt text](./images/6.png)<br/>
<br/>
###项目不提供后期更新，有兴趣的小伙伴可以拿去玩玩