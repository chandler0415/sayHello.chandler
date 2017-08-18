# sayHello.chandler
how to publish npm

### 1. 编写模块
exports.sayHello = () => console.log('what you want to print');

### 2. 初始化包描述文件
`$ npm init`

### 3. 注册npm仓库账号
`$ npm adduser`

### 4. 上传包
`$ npm publish`

### 5. 管理包权限  
查看模块拥有者
`$ npm owner ls <package_name>`  
添加一个发布者
`$ npm owner add <user> <package_name>`  
删除一个发布者  
`$ npm owner rm <user> <package_name>`  

### 6. 分析包
查看当前项目引用了哪些包  
`$ npm ls`