# AutoAni-Floater

从免编译模版 v0.4 衍生出来的分支，增加了双栏和可设第几名起的功能，10月初用于9月粉丝总榜视频。

2018年11月初未做任何修改，12月初 merge 了加载背景图、键盘控制、空字符转换等简单功能。

- 20190102
  - 更新 floater 样式
  - 排名数字不动
  - 切换第几屏只需改 cfg[1][1] 其它参数自动填，cfg[1][0] 调整体宽度缩放
  - 过百万后 floater 右间距增加
  - merge 降频踩点功能

- 20190701
  - 嵌入粗细双字体
  - 对于特殊UP重置其起点名次
  - bug fix：之前阈值设为<7万则清除透明UP，看来还是图样…
  - 顺便修了进度条不准
  - 按 `R` 键立刻重载 config 并重启 dataLoaded（尚未搞定）

- 20190901
  - 清除透明UP改成阈值1…
  - 最后一列人物图片名带换行符bug

- 20191231
  - 增加config项目让模版同时兼容粉丝总榜和播放量总榜

- 20200101
  - 去掉小于多少就清除透明UP的功能（调低至<-999）

- 20200201
  - 星号排名可调（可能会做到top275）

- 20200218
  - 第一次做充电总榜，修好了排名大于225不显示rankbarplate的疏忽

- 20200602
  - 名次偏移值（让哔哩漫画为第零名）

