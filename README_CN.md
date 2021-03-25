# online-resume

[English](README.md) | [简体中文](README_CN.md)

---

基于Jekyll的简历模板，可以使用Markdown来写自己的简历内容，然后渲染成HTML并且可以打印成PDF格式的文件。

特性：

+ 上手简单，容易编辑，可以隐藏
+ 使用Jekyll + Markdown + Github Pages技术栈
+ 多语言支持
+ 自定义主题颜色
+ 简历内容模块化
+ 响应式设计
+ 打印格式友好

## 起步

### 使用

#### 快速使用

Fork仓库：

![](https://github.com/tarrex/online-resume/raw/master/assets/images/fork.png "fork this repository")

编辑`_data/data.yml`文件：

![](https://github.com/tarrex/online-resume/raw/master/assets/images/edit.png "edit the yaml file")

设置Github Pages源分支`settings -> Github Pages -> source`，选择`master branch`：

![](https://github.com/tarrex/online-resume/raw/master/assets/images/source.png "select github pages source branch")

等一会儿之后在浏览器中打开`https://YOUR_GITHUB_USERNAME.github.io/online-resume`就可以看到自己的简历了。

带照片简历：

![](https://github.com/tarrex/online-resume/raw/master/assets/images/resume1.png "resume with profile photo")

不带照片简历：

![](https://github.com/tarrex/online-resume/raw/master/assets/images/resume2.png "resume without profile photo")

如果想打印简历，直接在浏览器中打印，或者保存为PDF文件。

#### 本地使用

如果想本地使用直接克隆仓库，然后编辑内容，部署步骤跟普通的Jekyll网站一样。

### 定制化

+ `_data/data.yml`: 简历内容。
+ `assets/images/profile.png`: 默认头像位置。
+ `_config.yml`: Jekyll网站基本设置。
+ `index.html`: 改变简历内容模块的展示顺序。
+ `_sass/_base.scss`: 改变简历的样式。

## 协议

[MIT](https://choosealicense.com/licenses/mit/)

## 其他

+ Hugo版本: [hugo-theme-online-resume](https://github.com/tarrex/hugo-theme-online-resume)