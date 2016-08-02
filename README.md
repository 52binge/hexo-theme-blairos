# Blairos

Blairos is a fresh looking and responsive theme for [Hexo](http://hexo.io) with more features and some build-in service and some libin's style based on [Minos](https://github.com/ppoffice/).  

**Blairos support Hexo 3.0 now !**

[Demo](http://52binge.github.io)

[如何使用 Blairos 主题](https://github.com/52binge/blairos/)

## Installation
### Install
```
$ git clone https://github.com/52binge/blairos.git themes/blairos
```
**Blairos requires Hexo 2.7 and above.** 

### Enable

Modify `theme` setting in blog folder` _config.yml` to `blairos`.

### Update

```
cd themes/blairos
git pull origin master
```

**please backup your `_config.yml` file before update.** 

## Configuration

Modify settings in  `/themes/blairos/_config.yml`. 


## Configuration

### Theme configuration example
```
# Header
menu:
  Home: /
  Archives: archives
  Categories: categories
  Tags: tags
  Tweet: tweet
  About: about

# Content
excerpt_link: Read More
toc: false
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **excerpt_link** - Cooperate with, you can use article description instand of this <!--more-->
- **toc** - Whether to show the table of contents in articles.
- **fancybox** - Enable [Fancybox].
- **google_analytics** - Google Analytics ID.
- **favicon** - Favicon path.

Don't forget to rename `_config.yml.example` to `_config.yml` to enable theme config!


## Features

### Custom Categories & Tags Pages

Get your categories and tags listed in single pages to make your blog more methodic. of course, tweet
is my favorite feature.

### Fancybox

Minos uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)
```

### Monokai Sublime Syntax Highlight

Thanks to [Highlight.js](https://highlightjs.org/).

## Development

### Requirements

- [Grunt] 0.4+
- Hexo 3.0+

### Grunt tasks

- **default** - Download [Fancybox] and [Font Awesome].
- **fontawesome** - Only download [Font Awesome].
- **fancybox** - Only download [Fancybox].
- **clean** - Clean temporarily files and downloaded files.

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
[Grunt]: http://gruntjs.com/

## Sites

- [Blairos Theme](http://52binge.github.io) - The demo site of Blairos Theme
- [Blair Chan's Blog](http://blairos.org) - The author's blog of Blairos

If you are using Jacman,you can add your site [here](https://github.com/52binge/blairos/wiki/Sites) ! I'll push the available sites here.

##License
[MIT](/LICENSE)
