# Python Developer 中文版

## 引言

职业目标：Python 后端开发工程师、Python 数据科学工程师

本人从 2018 年 10 月毕业后开始工作，因为技术水平不足，而无法写出清晰凝练的个人博客。于是，希望在这里首先记录自己在工作学习中遇到的知识点，并温故而知新。

- [Python Developer 中文版](#python-developer-%E4%B8%AD%E6%96%87%E7%89%88)
  - [引言](#%E5%BC%95%E8%A8%80)
  - [Python](#python)
    - [Python 基础](#python-%E5%9F%BA%E7%A1%80)
    - [Python 进阶](#python-%E8%BF%9B%E9%98%B6)
    - [Python 实战中问题](#python-%E5%AE%9E%E6%88%98%E4%B8%AD%E9%97%AE%E9%A2%98)
    - [Python 数据科学 基础](#python-%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6-%E5%9F%BA%E7%A1%80)
    - [Python 数据科学 实战中问题](#python-%E6%95%B0%E6%8D%AE%E7%A7%91%E5%AD%A6-%E5%AE%9E%E6%88%98%E4%B8%AD%E9%97%AE%E9%A2%98)
  - [Python 面试](#python-%E9%9D%A2%E8%AF%95)
  - [Git 代码版本管理](#git-%E4%BB%A3%E7%A0%81%E7%89%88%E6%9C%AC%E7%AE%A1%E7%90%86)
  - [Django web 框架](#django-web-%E6%A1%86%E6%9E%B6)
    - [Django 基础](#django-%E5%9F%BA%E7%A1%80)
    - [Django 进阶](#django-%E8%BF%9B%E9%98%B6)
    - [Django 实战](#django-%E5%AE%9E%E6%88%98)
    - [Django 面试](#django-%E9%9D%A2%E8%AF%95)
  - [操作系统 基础](#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F-%E5%9F%BA%E7%A1%80)
  - [Linux 命令行 基础](#linux-%E5%91%BD%E4%BB%A4%E8%A1%8C-%E5%9F%BA%E7%A1%80)
  - [数据库/SQL/MySQL](#%E6%95%B0%E6%8D%AE%E5%BA%93sqlmysql)
  - [Docker 基础](#docker-%E5%9F%BA%E7%A1%80)
  - [其他](#%E5%85%B6%E4%BB%96)
  - [为分类](#%E4%B8%BA%E5%88%86%E7%B1%BB)

## Python

### Python 基础

- [Learn python3 in Y minutes](https://learnxinyminutes.com/docs/python3/) :star:
- [Built-in Types](https://docs.python.org/3/library/stdtypes.html)
- [变量/可变-不可变类型/局部-全局变量](https://www.cnblogs.com/guigujun/p/9926446.html) :star:
- [python-sets-are-mutable](https://stackoverflow.com/questions/14193438/are-python-sets-mutable)
- [Python 基础：is 和==的区别](https://www.cnblogs.com/lilz/p/9410319.html)
- [python 的星号（\*）和双星号（\*\*）用法](https://www.cnblogs.com/empty16/p/6229538.html)
- [@classmethod and @staticmethod for beginner](https://stackoverflow.com/questions/12179271/meaning-of-classmethod-and-staticmethod-for-beginner) :star:
- [Python's Instance, Class, and Static Methods](https://realpython.com/instance-class-and-static-methods-demystified/)

### Python 进阶

- [Absolute vs Relative Imports in Python](https://realpython.com/absolute-vs-relative-python-imports/)
- [itertools — Functions creating iterators for efficient looping](https://docs.python.org/3/library/itertools.html#module-itertools) :star:
- [python 语法之 装饰器 decorator](https://www.cnblogs.com/yutongzhu/p/5615764.html) :star: :star2:
- [Python decorator](https://chase-seibert.github.io/blog/2013/12/17/python-decorator-optional-parameter.html#) :star:
- [Python Decorators - \_\_call\_\_ in class](https://stackoverflow.com/questions/19497771/python-decorators-call-in-class)
- [元类/metaclasses](https://stackoverflow.com/questions/100003/what-are-metaclasses-in-python) :star: :star2:
- [为什么 Python 不支持函数重载](https://www.zhihu.com/question/20053359)
- [Intro to Threads and Processes in Python](https://medium.com/@bfortuner/python-multithreading-vs-multiprocessing-73072ce5600b)
- [improve-your-python-performance](https://www.monitis.com/blog/7-ways-to-improve-your-python-performance/)
- [Awesome Python Repo in Github](https://github.com/vinta/awesome-python)
- [ansii、unicode、utf8 区别和关系](https://www.cnblogs.com/a-xu/p/4448032.html)
- [PyCodeObject 初探](https://blog.csdn.net/jasonblog/article/details/7338840)
- [.pyc 和 PyCodeObject 是什么](https://blog.csdn.net/huanhuanq1209/article/details/79724632)
- [pip commands](https://pip.pypa.io/en/stable/user_guide/)
- [PyPI 使用国内源](https://www.cnblogs.com/sunnydou/p/5801760.html)
- [python-closures 闭包](https://www.geeksforgeeks.org/python-closures/)
- [python 的异步 gevent、async、await](https://www.jianshu.com/p/0a91a446dda8) :star:
- [关于 gevent 的几点思考](https://www.jianshu.com/p/861f29ac68e8)
- [python 数据结构之哈希表](https://www.cnblogs.com/kumata/p/9157738.html)
- [python 数据结构与算法 29-1 哈希查找](https://www.cnblogs.com/cxchanpin/p/7389133.html)
- [Python 中的垃圾回收机制](http://python.jobbole.com/87843/)

### Python 实战中问题

- [solve dictionary changed size during iteration](https://stackoverflow.com/questions/13519644/how-to-solve-dictionary-changed-size-during-iteration-in-python)
- [What does metavar and action mean in argparse in Python?](https://stackoverflow.com/questions/19124304/what-does-metavar-and-action-mean-in-argparse-in-python)
- [Python requests.post 方法中 data 与 json 参数区别](https://www.cnblogs.com/yanlin-10/p/9820694.html)
- [Python requests.post 方法中 data 与 json 参数区别 2](https://www.jianshu.com/p/fae6bd1b2d76)
- [Difference between using requests.get() and requests.session().get()?
  ](https://stackoverflow.com/questions/32986228/difference-between-using-requests-get-and-requests-session-get)
- [发布 Python 为可执行文件](https://www.cnblogs.com/mywolrd/p/4756005.html)
- [Python 3.6 Typing Syntax / Type hint](https://medium.com/@ageitgey/learn-how-to-use-static-type-checking-in-python-3-6-in-10-minutes-12c86d72677b)
- [Python 3.6 Typing Syntax / Type hint2](https://stackoverflow.com/questions/38727520/adding-default-parameter-value-with-type-hint-in-python)
- [create-union-of-all-values-contained-in-multiple-lists](https://stackoverflow.com/questions/2151517/pythonic-way-to-create-union-of-all-values-contained-in-multiple-lists)
- [一些改善 Python 程序的建议](https://mp.weixin.qq.com/s/ndfQUAjgLZYX1IUuF3K2QA)
- [Intermediate Python(Book)](http://book.pythontips.com/en/latest/index.html)
- [set a number to NaN or infinity](https://stackoverflow.com/questions/5438745/is-it-possible-to-set-a-number-to-nan-or-infinity)
- [get an environment variable in Python using os.environ](https://www.systutorials.com/241675/how-to-get-an-environment-variable-in-python/)

### Python 数据科学 基础

入门的话，[Top 20 Python libraries for data science in 2018](https://medium.com/activewizards-machine-learning-company/top-20-python-libraries-for-data-science-in-2018-2ae7d1db8049)

- [Creating Pandas DataFrames from Lists and Dictionaries](https://pbpython.com/pandas-list-dict.html) :star:
- [Applying Operations Over pandas Dataframes](https://chrisalbon.com/python/data_wrangling/pandas_apply_operations_to_dataframes/)
- [用 matplotlib 绘制柱状图和饼图](http://ningning.today/2015/04/17/python/%E7%94%A8matplotlib%E7%BB%98%E5%88%B6%E6%9F%B1%E7%8A%B6%E5%9B%BE%E5%92%8C%E9%A5%BC%E5%9B%BE/)
- [Seaborn 热图绘制](https://blog.csdn.net/sunchengquan/article/details/78573244)
- [10 个提高工作效率的 Pandas 小技巧](https://mp.weixin.qq.com/s/cH7glwk_YrBJ-48tY-hnFQ)

### Python 数据科学 实战中问题

- [pandas.pivot_table](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html)
- [Pandas date_range to generate monthly data](https://stackoverflow.com/questions/34915828/pandas-date-range-to-generate-monthly-data-at-beginning-of-the-month)
- [numpy.insert](https://www.tutorialspoint.com/numpy/numpy_insert.htm)

## Python 面试

- [Python 面试 from Github](https://github.com/taizilongxu/interview_python) :star: :star2:
- [coding-interview-tips](https://realpython.com/python-coding-interview-tips/) :star:
- [python_interview_question](https://github.com/kenwoodjw/python_interview_question)
- [2018 最常见的 Python 面试题](https://blog.51cto.com/13719825/2172133)

## Git 代码版本管理

## Django web 框架

### Django 基础

- [Django models.py, what's the difference between default, null, and blank?](https://stackoverflow.com/questions/4384098/in-django-models-py-whats-the-difference-between-default-null-and-blank)
- [Django Making queries](https://docs.djangoproject.com/en/dev/topics/db/queries/#complex-lookups-with-q-objects) :star:
- [Django queries - Aggregation](https://docs.djangoproject.com/en/2.2/topics/db/aggregation/) :star:
- [Django Admin 管理工具](http://www.runoob.com/django/django-admin-manage-tool.html)
- [Django 框架全面讲解](https://www.cnblogs.com/LiCheng-/p/6920900.html) :star: :star2:
- [Django 的中间件原理&执行](https://blog.csdn.net/weixin_42181824/article/details/81125406)
- [uWSGI+django+nginx 的工作原理流程与部署历程](https://blog.csdn.net/c465869935/article/details/53242126) :star:
- [Setting up Django and your web server with uWSGI and nginx 官方](https://uwsgi-docs.readthedocs.io/en/latest/tutorials/Django_and_nginx.html)
- [每个 Model 自动添加上必备 3 字段, create_time/update_time](https://segmentfault.com/q/1010000010700842) :star:
- [Django 的时间字段 DateTimeField](https://www.cnblogs.com/wuxunyan/p/9266888.html)
- [Django--自定义 Command 命令](https://www.cnblogs.com/polly-ling/p/9830060.html) :star:
- [Django Model 规范](https://steelkiwi.com/blog/best-practices-working-django-models-python/) :yellow_heart:

### Django 进阶

- [XSS 与 CSRF](https://segmentfault.com/a/1190000007059639)
- [Django 之 CSRF](https://segmentfault.com/a/1190000007059639)
- [CSRF 攻击原理&Django 的应用方法](https://blog.csdn.net/u012556900/article/details/57412707)
- [OAuth Authentication in Django with social-auth](https://medium.com/trabe/oauth-authentication-in-django-with-social-auth-c67a002479c1)
- [A Django content management system](https://wagtail.io)

### Django 实战

- [combine 2 or more querysets in a Django view](https://stackoverflow.com/questions/431628/how-to-combine-2-or-more-querysets-in-a-django-view)
- [django 项目之 api 验证部分](https://www.cnblogs.com/ArmoredTitan/p/7639387.html) :star:
- [django 之基于 requests API 验证](https://blog.csdn.net/bbwangj/article/details/86526228)
- [drf-yasg - Yet another Swagger generator](https://github.com/axnsan12/drf-yasg) :star:
- [Django queryset values_list return a list](https://stackoverflow.com/questions/37140426/does-django-queryset-values-list-return-a-list-object) :star:
- [objects.all().aggregate(Max('rating'))](https://stackoverflow.com/questions/844591/how-to-do-select-max-in-django)
- [Django advanced LIKE filtering](https://stackoverflow.com/questions/53087065/django-advanced-like-filtering)
- [Django JSON response error status](https://stackoverflow.com/questions/35059916/django-json-response-error-status)
- [RESTful Error Messages with Django by JsonResponse](https://medium.com/@mwhitt.w/restful-error-messages-with-django-537047892dff)
- [Excluding Basic Authentication In A Single View - Django Rest Framework](https://stackoverflow.com/questions/33539606/excluding-basic-authentication-in-a-single-view-django-rest-framework)
- [Linux + Nginx + Uwsgi + Django 搭建单服务实现多域名访问](https://mp.weixin.qq.com/s/baYuDLhlFsFrBXqGq9pBDA)

### Django 面试

- [Django 的笔试题 2015](http://python.jobbole.com/81871/)
- [Django 的认识，面试题](https://www.cnblogs.com/chongdongxiaoyu/p/9403399.html)

## 操作系统 基础

- [进程、线程、协程及 IO 模型](https://www.cnblogs.com/xuyaping/p/6825115.html) :star:
- [python 并发编程之多进程、多线程、异步和协程](https://www.cnblogs.com/tyomcat/p/5486827.html)
-

## Linux 命令行 基础

## 数据库/SQL/MySQL

## Docker 基础

- [Stop and remove all docker containers and images](http://blog.baudson.de/blog/stop-and-remove-all-docker-containers-and-images)

## 其他

- [PyCharm 常用快捷键和设置方法](https://www.jb51.net/article/131005.htm?utm_medium=referral)
- [后端工程师成长路线图](./_static/backend_developer.jpg) :star:

## 为分类

- [HTTP Session、Cookie 机制详解](https://www.cnblogs.com/lyy-5518/p/5460994.html)
- [跨域的问题](https://segmentfault.com/a/1190000015597029)
