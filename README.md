# LoadingLayout
集成于加载和空页面展示的控件
使用 说明

一般情况 此布局为主布局使用 ，  LoadingLayout 继承 RelativeLayout 。 支持 DataBinding

xml 属性

is_full : 是否全屏  ,默认false   (一般情况下  Activity 是 false , fragmetn true)
title_height ：预留顶部高度，此属性必选才is_full 为false 的情况下生效  （一般情况下是 给 title留位置的  默认高度 44dp）
loading_backgroun_color ：loading 背景控件背景颜色 （不是loading 控件的颜色  是主背景颜色）
loading_backgroun_alpha loading 背景控件背景透明度  0.0 -- 1 （和loading_backgroun_color 说明一样）
empty_backgroun_color   empty 背景控件背景颜色  和loading_backgroun_color 说明一样）
onEmptyClikcCommand  此属性是 给 DataBinding 用的 绑定ViewModel  是 重新加载的点击事件
