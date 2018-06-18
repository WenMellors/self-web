# README

# 06.18
  * 建立了missions的模型以及user的模型
  * 安装了bcrypt的gem源

  * 遇到的一些小问题：
      1. rails版本不能在已建好的项目上随意更新，会出现一些意料之外版本差之间的bug，按官网指南上建议一步一步更新，虽然也不怎么懂，[更新说明] (http://guides.rubyonrails.org/upgrading_ruby_on_rails.html)
      1. 并不是所有model都用脚手架来搭方便，因为会产生一些多余的view以及controller
      1. date与datetime的区别在于前者精确到日，后者精确到时刻

  * 接下来的任务
      1. 完善index页面，美化以及将登陆的图标放进来
      1. 完善user登陆、登出的页面以及初始化一个user
      1. 希望新建一个mission的时候，我是能够在一个日历的界面上去选的
      1. 完成能够根据当前日期，筛选当日应作的任务，设想是做一个表格出来，最好能够查看下一天，或者下几天的
