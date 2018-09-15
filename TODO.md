


## 相关说明 ##
- 暂时不严格要求：编码请遵循 _`PEP8`_ 规则（ http://pep8.org/ ）
    + 可以通过 _`pycodestyle`_ （ https://github.com/PyCQA/pycodestyle ）来检测是否符合规范
- 代码注释请使用Google Style

## 相关技术 ##
- 语言框架：Python/Flask
- 数据库：Sqlite
- Wiki存储：Markdown
- 模板：jinjia2

## 开发计划 ##

### 近期计划 ###
- 完成一个Wiki主页
    + 位于./transparentWiki/app.py
    + url : 127.0.0.1:5000/wiki/main
- 完成一个Wiki页面模板
    + 代码位于./transparentWiki/model/wiki
    + html页面模板位于./transparentWiki/templates
    + 存储的.md文件及模板位于./transparentWiki/data/data
    + 解释器/转换器位于./transparentWiki/interpreter
    + url : 127.0.0.1:5000/wiki/=?wikiPage=<id>
- 完成Wiki相关数据库建设
    + 完成Wiki页面的数据库设计
- 确定日志格式
- 编写日志通用类
    - 位于./logger
- 编写基本配置文件
    - 包括是否打开日志
    - 启动IP及端口号
    - 位于 ./conf

