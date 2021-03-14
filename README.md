# online-resume

[English](README.md) | [简体中文](README_CN.md)

---

Yet another resume template based on Jekyll. You can write your resume using Markdown, it will be rendered into HTML and can be printed as PDF file.

Features:

+ Easy to use/edit/hide
+ Jekyll + Markdown + Github Pages
+ Multiple languages
+ Multiple skins
+ Content modular
+ Responsive display
+ Print-friendly

## Getting Started

### Usage

#### Quickly

Fork this repository:

![](./assets/images/fork.png "fork this repository")

Edit the YAML file located in `_data/data.yml`:

![](./assets/images/edit.png "edit the yaml file")

Setting the Github pages source branch in `settings -> Github Pages -> source`, select `master branch`:

![](./assets/images/source.png "select github pages source branch")

Wait a little while, open `https://YOUR_GITHUB_USERNAME.github.io/online-resume` in your browser. You can see your resume.

with profile photo:

![](./assets/images/resume1.png "resume with profile photo")

without profile photo:

![](./assets/images/resume2.png "resume without profile photo")

If you want to print your resume, just press the shortcut of print. Also, it can be saved as a PDF file.

#### Locally

If you want to use it locally, you should clone this repository then just like deploying a regular Jekyll website.

### Customization

+ `_data/data.yml`: All the resume content.
+ `assets/images/profile.png`: Your profile photo.
+ `_config.yml`: Site's general settings.
+ `index.html`: Change the resume content's display order.
+ `_sass/_base.scss`: Change the resume display style.
+ `robots.txt`: If you don't want your resume to be recorded in the search engine, modify this file.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

Inspired by [online-cv](https://github.com/sharu725/online-cv), this is a very amazing resume template.
