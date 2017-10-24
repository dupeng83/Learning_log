# learning log 网站

这是跟随No Starch Press出版的书 [Python Crash Course](https://www.nostarch.com/pythoncrashcourse/) 所做的网站

运行 `git clone https://github.com/dupeng83/Learning_log` 克隆以后运行下列命令:

`cd Learning_log`

`virtualenv my_env`

`source my_env/bin/activate`

`pip install Django==1.11.1`

`pip install django-bootstrap3`

`pip install dj_static`

`python manage.py migrate`

`python manage.py runserver`

用户注册登录之后可以创建“topic”（例如“下棋”，“攀岩”），每个“topic”下面可以添加若干“entry”（例如下棋具体学到了哪些内容）。

只能查看自己创建的“topic”和“entry”，不能看别人的。

部署[在heroku上](https://guarded-ridge-21841.herokuapp.com/)
