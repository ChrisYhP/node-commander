1. 在package.json里面配置好 
  "bin": {
    "outside": "index.js"
  }
2. 执行npm link  
  它将会把当前程序名这个字段复制到npm的全局模块安装文件夹node_modules内，并创建符号链接（symbolic link，软链接），也就是将 当前 的路径加入环境变量 PATH

3. 入口文件加:  #! /usr/bin/env node
  表明这是一个可执行的程序