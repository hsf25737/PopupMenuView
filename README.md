# PopupMenuView
基于https://github.com/minetsh/PopupMenuView 修改的PopupMenuView，解决Android9.0(android P)以上的圆角失效问题
参考链接：https://github.com/GcsSloop/rclayout/issues/37

此库主要实现了一个类似iOS中的`UIMenuController`控件的Popup控件。
主要控件如下：

- `PopLayout`继承自`FrameLayout`，用于实现控件的气泡化。
- `OptionMenuView`继承自`LinearLayout`，用于实现Menu控件。
- `PopupView`继承自`PopupWindow`，用于实现控件的指定方位弹出效果。
- `PopupMenuView`是上述三者的集合，实现了弹出气泡菜单的功能。

![预览图片](/screenshot/preview_image.jpg)
