# Theme QnA for Hexo 

![](https://raw.githubusercontent.com/cheng-kang/hexo-theme-qna/master/QnA.png)

A Knowledge Base Theme for Hexo.

## Documentation

- [中文文档](https://github.com/cheng-kang/hexo-theme-qna/blob/master/Doc/%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3.md)
- [Documentation](https://github.com/cheng-kang/hexo-theme-qna/blob/master/Doc/Documentation.md)

## Showcase:

- [Preview](http://chengkang.me/hexo-theme-qna/)
- [Swift Newbie: a knowledge base for Swift newbie](http://chengkang.me/Swift-Newbie/)


## Installation

### Install

``` bash
$ git clone https://github.com/cheng-kang/hexo-theme-qna.git themes/QnA
```

### Enable

Modify `theme` setting in `_config.yml` to `QnA`.

### Update

``` bash
cd themes/QnA
git pull
```

## Adavanced Features

### Deploy to Github

Install [hexo-deployer-git](https://github.com/hexojs/hexo-deployer-git) plugin for Hexo.

``` bash
$ npm install hexo-deployer-git --save
```

Edit `_config.yml` in root directory of your Hexo blog.

``` yml
deploy:
  type: git
  repo: <repository url> # https://github.com/cheng-kang/hexo-theme-qna.git
  branch: [branch] # master
```

### Enable In-site Search Support for Chinese

> By default, QnA support English in-site search.

Install [hexo-generator-search](https://github.com/PaicHyperionDev/hexo-generator-search) plugin for Hexo.

``` bash
$ npm install hexo-generator-search --save
```

### Add New Page

1. Add a new page with page name, e.g. about page. You can change page content by editing `source/<page_name>/index.md`.

  ``` bash
  $ hexo new page about
  ```

2. Edit `_config.yml` in theme/QnA.

  ```yml

  menu:
    Home: /
    Archive: /archives
    # Add new page config here
    # Page Dispay Name: /pagename
    # e.g.
    About: /about
  ```
