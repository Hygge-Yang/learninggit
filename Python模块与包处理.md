# Python模块与包处理

+ Python模块：

  一个模块就是指python代码的一个文件，

  一个.py文件就称之为一个模块

+ import语句

  使用import语句导入已经写好的模块

  import几种写法:

  直接导入

  使用别名

```
import+模块名
import+模块名+as+模块的重命名
from+模块名+import+模块内引用部分（函数）##若这样写则无需在本文件中写模块名.
from+模块名+import+模块内引用部分（函数）+as+函数重用名
```

+ 包

  多个模块组织成文件层次，这就是一个包

  要在目录下面添加一个文件init.py

  这个目录就作为一个包了
  
  from 包 import 模块

+ Python标准库

  包 管理工具

  使用pip安装和管理第三方库