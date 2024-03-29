========================
输入框标签生成类
========================


+-------------+----------------+
|属性         |值              |
+=============+================+
|命名空间     |fize\\tag       |
+-------------+----------------+
|类名         |Input           |
+-------------+----------------+
|父类         |fize\\tag\\Html |
+-------------+----------------+


:方法:


+-------------------+----------------------------------------------------------------------+
|方法名             |说明                                                                  |
+===================+======================================================================+
|`input()`_         |创建input标签                                                         |
+-------------------+----------------------------------------------------------------------+
|`button()`_        |定义可点击按钮                                                        |
+-------------------+----------------------------------------------------------------------+
|`checkbox()`_      |定义复选框                                                            |
+-------------------+----------------------------------------------------------------------+
|`file()`_          |定义文件上传控件                                                      |
+-------------------+----------------------------------------------------------------------+
|`hidden()`_        |定义隐藏的输入字段                                                    |
+-------------------+----------------------------------------------------------------------+
|`image()`_         |定义图像形式的提交按钮                                                |
+-------------------+----------------------------------------------------------------------+
|`password()`_      |定义密码字段                                                          |
+-------------------+----------------------------------------------------------------------+
|`radio()`_         |定义单选按钮                                                          |
+-------------------+----------------------------------------------------------------------+
|`reset()`_         |定义重置按钮                                                          |
+-------------------+----------------------------------------------------------------------+
|`submit()`_        |定义提交按钮                                                          |
+-------------------+----------------------------------------------------------------------+
|`text()`_          |定义单行的输入字段                                                    |
+-------------------+----------------------------------------------------------------------+
|`email()`_         |email 类型用于应该包含 e-mail 地址的输入域                            |
+-------------------+----------------------------------------------------------------------+
|`url()`_           |url 类型用于应该包含 url 地址的输入域                                 |
+-------------------+----------------------------------------------------------------------+
|`number()`_        |number 类型用于应该包含数值的输入域                                   |
+-------------------+----------------------------------------------------------------------+
|`range()`_         |range 类型用于应该包含一定范围内数字值的输入域。                      |
+-------------------+----------------------------------------------------------------------+
|`date()`_          |选取日、月、年                                                        |
+-------------------+----------------------------------------------------------------------+
|`month()`_         |选取月、年                                                            |
+-------------------+----------------------------------------------------------------------+
|`week()`_          |选取周和年                                                            |
+-------------------+----------------------------------------------------------------------+
|`time()`_          |选取时间（小时和分钟）                                                |
+-------------------+----------------------------------------------------------------------+
|`datetime()`_      |选取时间、日、月、年（UTC 时间）                                      |
+-------------------+----------------------------------------------------------------------+
|`datetimeLocal()`_ |选取时间、日、月、年（本地时间）                                      |
+-------------------+----------------------------------------------------------------------+
|`search()`_        |search 类型用于搜索域                                                 |
+-------------------+----------------------------------------------------------------------+
|`createTag()`_     |创建标签                                                              |
+-------------------+----------------------------------------------------------------------+


方法
======
input()
-------
创建input标签

.. code-block:: php

  public static function input (
      string $type,
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |type   |类型   |
  +-------+-------+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


button()
--------
定义可点击按钮

.. code-block:: php

  public static function button (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


checkbox()
----------
定义复选框

.. code-block:: php

  public static function checkbox (
      string $name = null,
      string $value = "",
      bool $checked = false,
      array $attrs = []
  ) : string


:参数:
  +--------+-------------------+
  |名称    |说明               |
  +========+===================+
  |name    |名称               |
  +--------+-------------------+
  |value   |值                 |
  +--------+-------------------+
  |checked |是否默认选中       |
  +--------+-------------------+
  |attrs   |属性               |
  +--------+-------------------+
  
  


file()
------
定义文件上传控件

.. code-block:: php

  public static function file (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


hidden()
--------
定义隐藏的输入字段

.. code-block:: php

  public static function hidden (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


image()
-------
定义图像形式的提交按钮

.. code-block:: php

  public static function image (
      string $src,
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------------+
  |名称   |说明         |
  +=======+=============+
  |src    |图像的URL    |
  +-------+-------------+
  |name   |名称         |
  +-------+-------------+
  |value  |值           |
  +-------+-------------+
  |attrs  |属性         |
  +-------+-------------+
  
  


password()
----------
定义密码字段

.. code-block:: php

  public static function password (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


radio()
-------
定义单选按钮

.. code-block:: php

  public static function radio (
      string $name = null,
      string $value = "",
      bool $checked = false,
      array $attrs = []
  ) : string


:参数:
  +--------+-------------------+
  |名称    |说明               |
  +========+===================+
  |name    |名称               |
  +--------+-------------------+
  |value   |值                 |
  +--------+-------------------+
  |checked |是否默认选中       |
  +--------+-------------------+
  |attrs   |属性               |
  +--------+-------------------+
  
  


reset()
-------
定义重置按钮

.. code-block:: php

  public static function reset (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


submit()
--------
定义提交按钮

.. code-block:: php

  public static function submit (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


text()
------
定义单行的输入字段

.. code-block:: php

  public static function text (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


email()
-------
email 类型用于应该包含 e-mail 地址的输入域

.. code-block:: php

  public static function email (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


url()
-----
url 类型用于应该包含 url 地址的输入域

.. code-block:: php

  public static function url (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


number()
--------
number 类型用于应该包含数值的输入域

.. code-block:: php

  public static function number (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


range()
-------
range 类型用于应该包含一定范围内数字值的输入域。

.. code-block:: php

  public static function range (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


date()
------
选取日、月、年

.. code-block:: php

  public static function date (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


month()
-------
选取月、年

.. code-block:: php

  public static function month (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


week()
------
选取周和年

.. code-block:: php

  public static function week (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


time()
------
选取时间（小时和分钟）

.. code-block:: php

  public static function time (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


datetime()
----------
选取时间、日、月、年（UTC 时间）

.. code-block:: php

  public static function datetime (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


datetimeLocal()
---------------
选取时间、日、月、年（本地时间）

.. code-block:: php

  public static function datetimeLocal (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


search()
--------
search 类型用于搜索域

.. code-block:: php

  public static function search (
      string $name = null,
      string $value = "",
      array $attrs = []
  ) : string


:参数:
  +-------+-------+
  |名称   |说明   |
  +=======+=======+
  |name   |名称   |
  +-------+-------+
  |value  |值     |
  +-------+-------+
  |attrs  |属性   |
  +-------+-------+
  
  


createTag()
-----------
创建标签

.. code-block:: php

  public static function createTag (
      string $tag,
      array $attrs = [],
      bool $close = false,
      string $text = ""
  ) : string


:参数:
  +-------+----------------+
  |名称   |说明            |
  +=======+================+
  |tag    |标签名          |
  +-------+----------------+
  |attrs  |属性            |
  +-------+----------------+
  |close  |是否闭合        |
  +-------+----------------+
  |text   |显示字符串      |
  +-------+----------------+
  
  

:返回值:
  返回HTML代码段


