scss使用easy sass  
在.vscode文件夹中创建settings.json  
添加配置  
```
{
  "easysass.compileAfterSave": true, //保存sass文件后是否自动编译
  "easysass.excludeRegex": "", //文件名正则表达式,匹配的文件不会被编译,默认为空
  "easysass.formats": [
    {
      "format": "compressed", //使用压缩
      "extension": ".wxss" //输出格式为.wxss
    }
  ],
  "easysass.targetDir": "" //编译后文件的路径
}
```
