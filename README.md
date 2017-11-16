使用xadmin管理django后台
=

使用环境Python3.X + Django1.11

下载后解压，进入xadmin-master把xadmin放到项目的根目录

1、安装依赖包
django-crispy-forms<br>
django-import-export<br>
django-reversion<br>
django-formtools<br>
future<br>
httplib2<br>
six<br>

2、然后在settings.py的INSTALLED_APPS 里面添加下面二个

    'crispy_forms',
    'xadmin',

3、在项目的目录下创建adminx.py文件，里面配置和django自带的admin方法一样


