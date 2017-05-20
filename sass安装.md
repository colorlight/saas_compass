## sass的安装

1. 首先安装ruby http://rubyinstaller.org/downloads/  
addrubytopath
2. 安装好ruby，自带安装好包管理工具gem， 修改gem source
```gem sources --remove https://rubygems.org/ ```
```gem sources -a http://gems.ruby-china.org/ ````

3. 安装 sass  ```gem insatall sass``` 
4. 常用 的gem命令   
```gem update```升级gem  
```gem install sass --version=3.3 ``` 安装特定版本的sass  
```gem list``` 列出安装的所有程序包
```gem uninstall sass```

5. 新建scss的文件
6. ```sass main.scss main.css```这种方法生成文件