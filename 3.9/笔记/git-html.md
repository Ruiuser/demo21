# 工作流程
工作区 =》暂存区 =》 本地仓库 =》 远程仓库

## git三连
- git add . -- 保存到暂存区
- git commit -m "xxx" --文件提交到本地仓库
- git push origin（仓库名） master（分支名）  --文件从本地仓库提交到远程仓库

## git其他常用命令
### 配置相关
- git config --global user.name xxx --设置提交名字（只用执行一次，无需下次再次配置）
- git config --global user.mail xx  --设置提交邮箱 (同上)
- git config --list --查看git全局配置信息
- git --version --查看git软件版本
  ### 操作相关
- git init  --初始化git仓库（一个空项目只用执行一次）![](C:\Users\Rui\Desktop\bluej44\img\git流程图png.png)
- git remote -v --查看已经连接的远程仓库
- git remote add origin(自定义仓库名)

# HTML
> 超文本标记语言，包括：文字+图片+视频+链接

## HTML语法规范
## HTML基本结构
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

### `<!doctype html>`
  文档声明，用于告诉浏览器当前文件的类型
- 声明html，会默认识别为html5进行解析

## 常用标签
### 标题标签
```
<h1></h1>

```

### 段落标签 块级元素：独占一行
```
<p>段落标签</p>
```

### 文本标签 行级元素：与其他行级或者行块级元素同在一行
```
<span></span>
```

### 图像标签 行块级元素：可以和其他行级或者行块级元素同在一行
```
<img src="" alt="加载失败" width="100" height="100"/>
```

src|地址|
alt|文字|
title|文字|
width|数字|默认px
height|数字|默认px
importance|下载资源时相对重要性，或者说优先级

### 超链接标签
> 用于与网络上另一个文档进行连接，点击跳转至设定的网络地址或者本地地址，点击的内容可以是图片或者文字
href|
target|

锚点两种写法
```
<a href="#top">点击跳转顶部</a>
<p id="top">已到达顶部</p>
```

```
<a href="#top">点击跳转顶部</a>//点击跳转
<a name="top">已到达顶部</p>//跳转目标
```

### 其他常用标签
<br/> 换行标签
<hr/> 分割线标签

### HTML标签关系
1. 父子关系/包含关系/嵌套关系
2. 兄弟关系/并列关系