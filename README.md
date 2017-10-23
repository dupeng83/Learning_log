# learning log 网站

这是跟随No Starch Press出版的书 [Python Crash Course](https://www.nostarch.com/pythoncrashcourse/) 所做的网站

运行 `git clone https://github.com/dupeng83/Learning_log` 克隆以后运行下列命令:

`cd Learning_log`

`virtualenv my_env`

`source my_env/bin/activate`

`pip install Django==1.11.1`

`pip install django-bootstrap3`

`python manage.py migrate`

`python manage.py runserver`

用户注册登录之后可以创建“topic”，每个topic下面可以添加若干entry

部署[在heroku上](https://guarded-ridge-21841.herokuapp.com/)
