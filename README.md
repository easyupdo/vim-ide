# vim-ide
vim-ide 没有什么花里胡哨的东西,常用的自动补全,自动格式化,语法高亮,目录树,符号表,接口/源码跳转等

## after:

c/cpp语法配置 包括高亮(目前的cpp代码颜色配置都是在此目录下)

## bundle:

  vim管理插件，其他vimscript都放在这个下

## doc:

  目前配置的vim8的中文

## tools:

  放置各种第三方工具，目前有cpplint{谷歌代码风格检测工具,在vim-advanced-lint中使用cpplint来检测}、astyle（在bundle下的vim-autoformat中是使用该自动化格式工具格式化cpp代码）


## 注:.vim配合是独立于系统可用的，其内容是包含所有的使用文件的。
## 其中:
    bundle/YouCompleteMe(自动补全插件要编译) 
    tools/astyle需要编译 
    tools/cpplint是被bundle/vim-advanced-lint直接调用使用的cpplint.py文件(已经包含cpplint.py 脚本程序 无需编译)
