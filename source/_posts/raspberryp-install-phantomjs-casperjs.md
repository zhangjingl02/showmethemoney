---
title: 树莓派安装 phantomjs&casperjs
tags: nodejs phantomjs casperjs
categories: nodejs
date: 2018-2-28
---

树莓派Debian 安装Phantomjs以及Casperjs 其实很简单,首先确保已经安装好nodejs
安装Phantomjs
然后执行一下命令：
```jshelllanguage
sudo apt-get install phantomjs
```

检查安装结果
```jshelllanguage
phantomjs --version
```

安装casperjs
```jshelllanguage
https://github.com/casperjs/casperjs.git 
cp -R casperjs/ /usr/local/src/
ln -sf /usr/local/src/casperjs/bin/casperjs /usr/local/bin/casperjs
```

检查安装结果
```jshelllanguage
casperjs --version
```

