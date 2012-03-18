---
date: '2011-04-09 21:48:18'
layout: post
slug: linux-study-1
status: publish
title: Linux学习笔记(1)
wordpress_id: '335'
categories:
- linux
tags:
- Fedora
- linux
- Ubuntu
- 初学
- 学习
- 笔记
---

现在使用的笔记本是二手的IBM Thinkpad X30，上学期几百块钱从淘宝淘过来的，当初买这本子的时，根本没想到现在还会用着（第一学期学校不让带电脑，买这台凑合着用，1.2GHzCPU+512RAM+40GHDD）。虽然零件什么的都不怎么纯的样子，不过挺好用的我觉得，寒假在家里很多时间都是用这台笔记本上网，它已经可以满足我日常电脑的使用（我不怎么看电影，不玩大型游戏，最多也就超级玛莉~）。目前我所知道的笔记本品牌里，相对来说Thinkpad系列是最好的，它很照顾键盘党，TrackPoint很给力，占用空间小且好用，有了它我都没使用鼠标了，以后再买笔记本，也会是Thinkpad。
在这台笔记本里，装过win2003,winxp,ubuntu,linuxmint,lubuntu再到现在的fedora14，当然也尝试安装了其他的linux发行版，比如说debian，archlinux等，其实目前最想装的是archlinux，可惜自己还没那能力，或许可以吧，只是要折腾，所以还是好好学好基础再说。对于linux，要学的还有很多，我只是一只刚踏入linux道路的笨鸟，我在图书馆借到了一本《鸟哥的Linux私房菜》，很庆幸学校图书馆有这本Linux基础教程。一切都是折腾，网络环境一直不怎么样，又没光驱，usb还是1.1的。现在的它，6g给了windows（宿舍局域网下，6g足以），其余都属于linux，个人数据等都在ext3分区。
确实，windows下面有很多精品软件，可是作为载体的它是盗版的，下面的软件：office,adobe...既然自己没有能力去支付昂贵的软件费用，何不转而使用免费正版的linux系统呢？现在我日常使用都在linux下，用着linux很舒服，操作习惯已慢慢养成，现在回到windows，反而感到陌生了。在windows下，我一般不会用cmd，因为大部分软件都是图形化操作，设置也一样，根本用不着；到了linux，感觉不得不用CLI的时候，一开始我是强迫自己去学习那些命令的，到后来温习命令已经成为一种习惯，原因是感觉到CLI的自由，方便，安全。现在回想起来，在国内的环境下，在windows上使用软件不是一般的危险，虽然容易上手，使用较为方便，但是有危险，当你在前台操作的时候，可能后台的木马已经猖狂已久，这是不可避免的，可能随着使用时间的推移，使用经验的提升，预防的能力越来越强，可还是不能保证下次不再遇到；而在linux下，很多操作我们都用CLI，运行什么完全由自己掌握。其实我不是想说linux比windows好，在娱乐上，易用程度上，linux还是比windows差，所以现在的家用PC机还是windows比较适合，如果用电脑只是娱乐办公，windows是最合适不过了，只不过它需要费用。
记得自己第一次使用linux的时候是08年，那个时候使用的不是ubuntu，而是国产红旗linux，现在已经没什么印象了，第一次使用ubuntu是8.04，不过那时候没时间慢慢体验，也因为是家用机，所以不能整天折腾，当然ubuntu更新的时候会凑凑热闹，真正的进入linux的学习是从这一学期开始的。
记得ubuntu或基于ubuntu的发行版的livecd，用来硬盘安装是最简单的，基本上是这样的：准备好自由空间，然后在windows下提取iso文件里的initrd.lz及vmlinuz文件，然后配置好grub for dos及menu.lst文件，然后进入livecd环境，打开终端输入"sudo umount -l /isodevice"，回车，然后双击桌面上的“安装到硬盘”的图标，分区设置安装自动化，进入系统后再"sudo update-grub"，windows和linux的双系统就这样诞生了，这是第一步。当然对于其他的发行版来说，硬盘安装稍微比ubuntu的livecd复杂点，比如说debian，initrd和vmlinuz不能直接使用其iso里的。不过都是大同小异，必须先引导，然后挂载iso，再进行安装。各发行版wiki一般都会都有详细的安装说明。
因为电脑配置低，所以在linux下我会尝试各种占用内存低的软件，比如说听歌，看电影，直接使用mplayer，用惯了感觉很舒服，想实现什么就一条命令，简单清晰，听歌我一般是"mplayer -shuffle ~/Music/*/* "，看电影有时候会"mplayer -zoom -ontop -fs * "。我认为一款软件，如果要使用它，还要经过学习，那它一定是一款好软件，需要学习的时间越多，软件越好；比如说Vim,Emacs，已经是神器了！命令行下的软件，如果你不会用它，你会觉得很烦，当你学会用一款CLI软件的时候，知道它是多么好用多么强大，可能你就会拼命寻找其他类型软件的命令行替代品。这是我的亲身经历，我相信会有很多linux初学者和我一样的，学了命令行处理日常，才知道什么叫做高效。
目前我所知道的，最好的入门教程还是[《鳥哥的 Linux 私房菜》](http://linux.vbird.org/)，注意原版和大陆改编版有区别，原版语言活泼生趣；论坛首推[Ubuntu中文论坛](http://forum.ubuntu.org.cn/)；桌面发行版推荐[Ubuntu Linux](http://www.ubuntu.com/)和[Linux Deepin](http://linux.deepin.org/)。

[![Ubuntu_Linux](http://i951.photobucket.com/albums/ad353/Fooleap/Blog/Fooleap/Ubuntu_Linux_by_Designologer_660.jpg)](http://www.ubuntu.org.cn)

**本文历史**
2011年04月09日 创建文章
