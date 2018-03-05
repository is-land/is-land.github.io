# is-Land Blog


This is a fresh looking and responsive theme for [Jekyll](http://jekyllrb.com) with more features and some build-in Chinese service based on [Hexo Jacman](https://github.com/wuchong/jacman).  

## Local Setup

Check whether you have `Ruby 2.1.0` or higher installed:

```sh
ruby --version
```

Install `Bundler`:

```sh
gem install bundler
```

You can change the `language` setting to `en` in `_config.yml`.

You can also disable share buttons by setting `share_to` to `false`.

Install Jekyll and other dependencies from the GitHub Pages gem:

```sh
bundle install
```

Run your Jekyll site locally:

```sh
bundle exec jekyll server
```

More Details：[Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

## Features

- **menu**  
 Main navigation menu.
- **widget**  
 Widgets displaying in sidebar.The github card, category,tag,rss,archive,tagcloud,links,weibo are supported.
- **Image**  
 Images about favicon, site logo, author image, banner image. Support different image styles like `img-logo`,`img-topic`,`img-center` etc.
- **index**  
 Two different home page display modes.You can visit [Demo](http://jacman.wuchong.me) to check the difference.
- **author**  
 Author imformation, used to show your social network links on the bottom right. Including github, stackoverflow, twitter, facebook, linkedin, google+, weibo, douban, zhihu, email.
- **toc**  
 Show Table Of Contents in article & aside.
- **comments**  
 [duoshuo](http://duoshuo.com/) & [disqus](https://disqus.com/) are supported.
- **jiathis**  
 Build-in share tool or [JiaThis](http://www.jiathis.com/) share buttons at the bottom of articles.
- **Analytiscs**  
 [Google analytics](http://www.google.com/analytics/) & [Baidu tongji](http://tongji.baidu.com/) & [CNZZ tongji](http://www.cnzz.com/) are all supported.
- **Search**  
 [Googlle Custom Search](https://www.google.com/cse/ ) & [Baidu Site Search](http://zn.baidu.com/) & [Tiny Search](http://tinysou.com/) are supported.
- **totop**  
 Scroll to top
- **rss**  
 RSS subscription link (change if using Feedburner).
- **fancybox**  
 Enable [Fancybox](http://fancyapps.com/fancybox/)
- **others**
 You can configure sidebar not show in post pages.

## License

[MIT](/LICENSE)
