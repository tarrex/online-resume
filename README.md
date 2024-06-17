<h1 align="center">online-resume</h1>

<p align="center">
  <a href="https://github.com/tarrex/online-resume/blob/master/LICENSE"><img src="https://img.shields.io/github/license/tarrex/online-resume?style=flat-square" alt="GitHub License"></a>
  <a href="https://github.com/tarrex/online-resume/forks"><img src="https://img.shields.io/github/forks/tarrex/online-resume?style=flat-square" alt="GitHub forks"></a>
  <a href="https://github.com/tarrex/online-resume/stargazers"><img src="https://img.shields.io/github/stars/tarrex/online-resume?style=flat-square" alt="GitHub Repo stars"></a>
  <a href="https://tarrex.github.io/online-resume"><img src="https://img.shields.io/website?down_color=red&down_message=down&style=flat-square&up_color=green&up_message=up&url=https%3A%2F%2Ftarrex.github.io%2Fonline-resume" alt="Demo Website"></a>
  <a href="https://jekyll-themes.com/tarrex/online-resume">
    <img
      src="https://img.shields.io/badge/featured%20on-JT-red.svg"
      height="20"
      alt="Jekyll Themes Shield"
    />
  </a>
</p>

<h4 align="center">A minimalist Jekyll theme for your resume.</h4>

---

## Live Demo

:point_right: [online-resume][Demo] :point_left:

## Getting Started

Online-Resume is a Jekyll theme designed for creating resumes. It enables you to write your resume in YAML file using Markdown and manage it through Git. It can be displayed on a web page and printed as a PDF file directly from the browser.

You can deploy it on various platforms that support Jekyll or static files, such as GitHub Pages, Cloudflare Pages, Vercel, Netlify, your own hosting service, and others.

Features:

- User-friendly and easy to deploy.
- Built with Jekyll and Markdown.
- Supports multiple languages.
- Customizable theme color and basic styles.
- Modular content design.
- Responsive display.

### Usage

#### Quickly

- Fork the repository.
- Click the `settings` option above.
- Click `pages` in the Code and automation category on the left.
- Set up github pages in the build and deployment category.
  - find `source`, drop down and select `Deploy from a branch`.
  - find `branch`, drop down and select `master` branch.
  - Click the `save` button on the right.
- Wait a little while for the successful building.
- Open `https://YOUR_GITHUB_USERNAME.github.io/online-resume` in your browser.
- Now you can see the resume page.
- Edit the `_data/data.yml` file directly to update your resume.

#### Customization

- `_data/data.yml`: Edit the resume content.
- `assets/images/profile.png`: Your profile photo.
- `_config.yml`: Website and theme style settings.

## FAQ

#### How to change the order of the sections in the resume?

There is an `order` option in each section, you can adjust the order by modifying this, the smaller the value the more forward the position.

#### How to hide the specified section in the resume?

If there is no content you want to keep in the section, you can remove it directly. If you want to keep the content, you can set the value of the `show` option of the section to `false`.

#### How to create a resume in other languages?

For example, if you already have an English version resume and you want to create a Chinese version. Copy a `data.yml` file in the `_data` folder named `cn.yml` and edit the content, then copy an `index.html` file in the root directory named `cn.html` and change the `{%- assign data = site.data.data %}` in the `cn.html` file to `{%- assign data = site.data.cn %}`. After successful building, you can preview the Chinese version of your resume by visiting `https://YOUR_GITHUB_USERNAME.github.io/online-resume/cn`.

#### How to deploy on other platforms, like cloudflare, vercel?

You can read and follow [Cloudflare Pages][Cloudflare Pages], [Vercel][Vercel] documents.

## Others

- Hugo Version: [hugo-theme-online-resume][Other Version]


[Demo]: https://tarrex.github.io/online-resume
[Cloudflare Pages]: https://developers.cloudflare.com/pages/framework-guides/deploy-a-jekyll-site/
[Vercel]: https://vercel.com/guides/deploying-jekyll-with-vercel
[Other Version]: https://github.com/tarrex/hugo-theme-online-resume
