# npm

## Command

### Install

* `npm install xxx` （安装模块）  
* `npm install xxx@1.1.1` （安装1.1.1版本的xxx）  
* `npm install -g xxx` （将模块安装到全局环境中）  

### Uninstall

* `npm uninstall xxx` （卸载模块）
* `npm uninstall -g xxx` （全局卸载模块）  

### Update

* `npm update xxx` （更新模块）  

### Ls

* `npm ls` （查看安装的模块及依赖）  
* `npm ls -g` （查看全局安装的模块及依赖）  
* `npm help xxx` （查看帮助）    
* `npm view moudleName dependencies` （查看包的依赖关系）  
* `npm view moduleNames` （查看node模块的package.json文件夹）  
* `npm view moduleName labelName` （查看package.json文件夹下某个标签的内容）  
* `npm view moduleName repository.url` （查看包的源文件地址）  
* `npm view moduleName engines` （查看包所依赖的Node的版本） 
* `npm help folders` （查看npm使用的所有文件夹）

### Other

* `npm cache clean` （清理缓存）  
* `npm rebuild moduleName` （用于更改包内容后进行重建）  
* `npm outdated` （检查包是否已经过时，此命令会列出所有已经过时的包，可以及时进行包的更新）  
