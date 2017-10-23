# 购物 网站

这是跟随PACKT出版的书 [Django by Example](http://djangobyexample.com/) 所做的购物网站

运行 `git clone https://github.com/dupeng83/myshop` 克隆以后运行下列命令:

`cd myshop`

`virtualenv my_env`

`source my_env/bin/activate`

`pip install Django==1.8.6`

`pip install Pillow==2.9.0`

`pip install celery==3.1.18`

`pip install flower`

`python manage.py migrate`

`python manage.py runserver`

可以在后台添加商品，在前台购买，在后台还可以查看订单
