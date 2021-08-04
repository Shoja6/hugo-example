# Hugo Blog Example
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> Hugo 博客模版 使用 [hugo-theme-color-your-world](https://github.com/rmaguiar/hugo-theme-color-your-world) 主题

此项目用于视频教学，适用于新手基于hugo快速搭建github站点


## 配置项目

- [/config.toml](#Config.toml)
- [/.github/workflows/gt-pages.yml](#Gt-pages.yml)
- [/theme](#Theme)
- [/content/posts](#Posts)
- [/content/tools](#Tools)
- [/content/contact](#Contact)

## Config.toml
此文件为hugo官方配置文件，可以参考hugo官方教程
在此只展示必要的修改项目

1. baseURL 该参数为你项目的访问地址，所以必须修改
2. params.social.centralized 该参数为社交账号，请修改
3. languages.zh.menu 为顶部菜单，可按需要调整

## Gt-pages.yml

此文件为github自动部署文件，免去你打包上传的困扰，只需要修改一处配置

1. external_repository 此参数为 github 主页项目，例如你的github账号为 xxx，则此处需要修改成 xxx/xxx.github.io

## Theme

如果感觉这个主题不好看，可以跟换主题，具体参考 [官网主题库](https://themes.gohugo.io/)

## Posts

文章

## Tools

工具教程

## Contact

联系我

## Maintainers

[@OhhInk](https://github.com/ouhaohan8023).

## Contributing

Feel free to dive in! Open an issue or submit PRs.

Standard Readme follows the Contributor Covenant Code of Conduct.

## License

[MIT](LICENSE) © OhhInk
