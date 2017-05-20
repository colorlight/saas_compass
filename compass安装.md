#compass 安装与hello world

1. 安装 gem install compass
2. 创建工程  compass create compass-init
### 创建工程后蹦出来的说明
* 1. 你可以在sass子目录中添加和编辑sass文件
* 2. 以一个下划线命名开头的文件是一个局部sass文件，不会单独编译，但是可以被其他文件引用
* 3. 可以通过config.rb文件来配置工程
* 4. 在sass改变的时候，必须生成真是css，才能生效   
* 5. 编译方式 ```compass compile file``` ```compass watch file ```
* stylesheets 是css输出文件目录
* sass存放的是scss文件 


3.compass是提供了一个框架，让你写sass
有print，screen和ie