[F] Fix Bug.
[S] Style Change.
[A] Add Feature.
[U] Update Config.
[Doc] Update DOC.

## 2019/11/23

[F] #27

- php5 not support <?

## 2019/11/7

[A]: add instantclick
[DOC]: CN README

## 2019/11/4

[S] video style at mobile.
[F] Change the distance of scroll2post(-50px).

## 2019/11/4

[A] Add video Short Code Support.

## 2019/11/3

[A] You need add the truncation `<!-- more -->` control output (Home Article & ...).

## 2019/11/3 (V1.1.4)

- [S] replace Site Title animation.
  移除 Title 动画。
- [S] Banner height -> 550px -> 350px (PC)
- [F] fix topView post order.

## 2019/11/2

- [F] Fix when the article title is too much, the Toc display error(layout).
  修复文章标题过多时，目录显示错位
- [A] add jp & zh_tw lang.
- [F] Replace DB insert with typecho custom field.
  使用自定义字段替换数据库操作（不会破坏原有数据库结构）
- [F] fix site title position (mobile)

<!--  -->

## 2018/10/13 v1.1

- [U]: 重构 JS

## 2018/5/2 v1.0.3

- [remove]: remove auto load article & unused code & DNS Prefetch .

## 2018/5/1

- fix [#17](https://github.com/shiyiya/typecho-theme-sagiri/issues/17)
- configurable article thumbnails.

## 2018/2/11

-[fix]图片懒加载

## 2018/1/28

- [fix] header 头配置错误。
- [feature] 可选 banner 是否显示。
- [bug]fix any bugs.

<!-- more -->

## 2018/10/30

- 修复 archive 页下缩略图问题
- 调整标题前置 `#` 位置
- 添加块级代码背景颜色
- 更改友链样式
- 其他颜色协调性修正
- Readme 文档更新

## 2018/11/5

- 图片懒加载
- 目录树更换获取方式（浪费性能，暂不支持嵌套目录
- 文章侧栏相关文章添加
- gulp 配置更改，路径引用使用 min 文件
- 其他

## 2018/11/18

- [feature]图片懒加载 background-image 方式加载错位 --> 自适应
- [feature]侧栏热门文章、热评文章添加
- [feature]supported >= ie10
- [fix]修复手机头部滑动到文章内容背景距离错误 500 --> 200
- [fix]修复文章卡片内容超出 --> ...
- [fix]修复浏览量 php7+ 不显示，自定义字段 --> insert Db //与旧方法不兼容
- [fix]禁止评论不加载 OwO 表情

## 2018/12/09

- [feature]Fastclick ——FastClick is a simple, easy-to-use library for eliminating the 300ms delay between a physical tap and the firing of a click event on mobile browsers.
- [feature]指定一个图片链接作为头图。
- [bug]fix any bugs.

## todo
