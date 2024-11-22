[Gmeek](https://github.com/Meekdai/Gmeek) 一个博客框架，超轻量级个人博客模板，完全基于Github Pages 、 Github Issues 和 Github Actions，可以称作All in Github。不需要本地部署，从搭建到写作，只需要18秒，2步搭建好博客，第3步就是写作。

一、安装

【创建仓库】点击[通过模板创建仓库](https://github.com/new?template_name=Gmeek-template&template_owner=Meekdai)，建议仓库名称为XXX.github.io，其中XXX为你的github用户名。

【启用Pages】在仓库的设置Settings中Pages->Build and deployment->Source下面选择Github Actions。

【开始写作】打开一篇issue，开始写作，并且必须添加一个标签Label（至少添加一个），再保存issue后会自动创建博客内容，片刻后可通过https://xxx.github.io/ 访问（可进入Actions页面查看构建进度）。

【手动全局生成】这个步骤只有在修改config.json 文件或者出现奇怪问题的时候，需要执行。

通过Actions->build Gmeek->Run workflow->里面的按钮全局重新生成一次

二、配置文件

config.json 文件就是配置文件，在创建的仓库内可以找到，对应修改为自己的即可。

{
    "title":"Meekdai",
    "subTitle":"童话是一种生活态度，仅此而已。",
    "avatarUrl":"https://github.githubassets.com/favicons/favicon.svg",
    "GMEEK_VERSION":"last"
}
以上是必须的字段，下面是可以自定义字段的描述，可以选择加入到config.json中。

"displayTitle":"Meekdai",
"homeUrl":"http://blog.meekdai.com",
"faviconUrl":"https://github.githubassets.com/favicons/favicon.svg",
"email":"meekdai@163.com",
"startSite":"02/16/2015",
"filingNum":"浙ICP备20023628号",
"onePageListNum":15,
"singlePage":["about"],
"iconList":{"music":"M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13Z"},
"exlink":{"music":"https://music.meekdai.com"},
"commentLabelColor":"#006b75",
"yearColorList":["#bc4c00", "#0969da", "#1f883d", "#A333D0"],
"i18n":"CN",
"UTC":8,
"themeMode":"manual",
"dayTheme":"light",
"nightTheme":"dark_colorblind",
"urlMode":"pinyin",
"style":"",
"script":"",
"head":"",
"allHead":"",
"indexStyle":"",
"indexScript":"",
"showPostSource":1,
"rssSplit":"sentence",
"bottomText":"转载请注明出处",
"ogImage":"https://cdn.jsdelivr.net/gh/Meekdai/meekdai.github.io/logo64.jpg",
"primerCSS":"<link href='https://mirrors.sustech.edu.cn/cdnjs/ajax/libs/Primer/21.0.7/primer.css' rel='stylesheet' />",
"needComment":0,