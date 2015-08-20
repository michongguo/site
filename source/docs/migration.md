草榴,草榴社区,caoliu,草榴社区最新地址,草榴社区邀请码,caoliushequ,草榴社区最新网址,t66y,1024
---
警告 / WARNING

__ 滿 １８ 歲, 請按此__
2015/7/30彻底更新!草榴社区最新有效地址，强烈建议CTRL+D收藏这个地址发布页，不要保存单个网址！如需要邀请码，请加Q：2460400533

草榴社区地址1

草榴社区地址2

草榴社区地址3

草榴社区地址4

草榴社区地址5

草榴社区地址6

手机地址

投广告、买邀请码

= = = 请留意下方消息公告 = = =

凡是说开放注册的都是假网站，凡是打开网站就要求登录的都是假网站，凡是说官方要求买会员才能进入网站的都是假网站，凡是说邀请多少人点击就能注册为会员的都是假网站，千万不要去注册，有账号的更不要去登录，小心被盗号！如需要邀请码，请加Q：2460400533
我要啦免费统计


First, install the `hexo-migrator-rss` plugin.

``` bash
$ npm install hexo-migrator-rss --save
```

Once the plugin is installed, run the following command to migrate all posts from RSS. `source` can be a file path or URL.

``` bash
$ hexo migrate rss <source>
```

## Jekyll

Move all files in the Jekyll `_posts` folder to the `source/_posts` folder.

Modify the `new_post_name` setting in `_config.yml`:

``` yaml
new_post_name: :year-:month-:day-:title.md
```

## Octopress

Move all files in the Octopress `source/_posts` folder to `source/_posts` 

Modify the `new_post_name` setting in `_config.yml`:

``` yaml
new_post_name: :year-:month-:day-:title.md
```

## WordPress

First, install the `hexo-migrator-wordpress` plugin.

``` bash
$ npm install hexo-migrator-wordpress --save
```

Export your WordPress site by going to "Tools" → "Export" → "WordPress" in the WordPress dashboard (see the [WordPress support page](http://en.support.wordpress.com/export/) for more details).

Now run:

``` bash
$ hexo migrate wordpress <source>
```

Where `source` is the file path or URL to the WordPress export file.

## Joomla

First, install the `hexo-migrator-joomla` plugin.

```bash
$ npm install hexo-migrator-joomla --save
```

Export your Joomla articles using the [J2XML](http://extensions.joomla.org/extensions/migration-a-conversion/data-import-a-export/12816?qh=YToxOntpOjA7czo1OiJqMnhtbCI7fQ%3D%3D) component.

Now run:

```bash
$ hexo migrate joomla <source>
```

Where `source` is the file path or URL to the Joomla export file.
