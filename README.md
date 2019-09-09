# 创建django项目
.\django-admin.exe startproject dailyfresh

# 启动服务
python35 .\manage.py runserver

# 创建app
python35 .\manage.py startapp df_user

# 创建app后，在models.py文件中增加user类后，执行以下命令在数据库中创建表
python35 .\manage.py makemigrations
python35 .\manage.py migrate