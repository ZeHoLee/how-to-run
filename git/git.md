# git相关用法

## 配置用户名和邮箱
``` 
git config -global user.name "***"
git config -global user.email "***"
```

## 初始化本地环境
```
git init
```

## 提交文件
``` 
git add .

git commit -m 'remark'
```

## 关联远程仓库
```
git remote add origin  仓库地址
```

## 提交到远程仓库
```
git push -u origin master
```