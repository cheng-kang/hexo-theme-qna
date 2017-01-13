# Q&A

A Knowledge Base Theme for [Hexo].

- [Preview](http://chengkang.me/hexo-theme-q-a/)

## Installation

### Install

``` bash
$ git clone https://github.com/cheng-kang/hexo-theme-q-a.git themes/Q&A
```

### Enable

Modify `theme` setting in `_config.yml` to `Q&A`.

### Update

``` bash
cd themes/Q&A
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

