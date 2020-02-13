npm常用指令
===
npm為node.js的套件管理器

快速表
```
npm install <package name> -g
npm install <package name>
npm uninstall <package name> -g
npm uninstall <package name>
npm search <package name>
npm ls -g //列表
npm ls -gl //詳細資料
npm ls
npm ls -l 
npm update -g
npm update
```

- -g 全域安裝套件
```code
npm install <package name> -g
```
- 專案裡安裝套件
```code
cd /path/project
npm install <package name>
```
- 移除全域套件
```code
npm uninstall <package name> -g
```

- 移除全域套件
```code
npm uninstall <package name> -g
```

- 移除專案中的套件
```code
cd /path/to/the/project
npm uninstall <package name>
```

- 搜尋套件
```code
npm search <package name>
```

- 列出全域套件
```code
npm ls -g
```

- 列出全域套件詳細資訊
```code
npm ls -gl
```

- 列出專案裡的套件
```code
cd /path/to/the/project
npm ls
```

- 列出專案裡的套件詳細資訊.
```code
cd /path/to/the/project
npm ls -l 
```

- 更新全域套件
```code
npm update -g
```

- 更新案裡的套件.
```code
cd /path/to/the/project
npm update
```