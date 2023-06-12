# Alacritty.icns

一组 Alacritty 图标，包括

* 白色
* 粉色
* 绿色
* 蓝色

## 效果预览

![Preview](https://github.com/lewangdev/Alacritty.icns/blob/main/preview.png?raw=true)  

## 如何替换默认的应用图标

* 首先去 Releases 页面下载任一[图标](https://github.com/lewangdev/Alacritty.icns/releases/tag/v0.0.1)
* 在应用文件夹中找到 Alacritty.app 选中后，按快捷键 `command + i` 打开显示简介或点击右键选择“Get Info”
* 然后将下载的 icns 文件拖动到左上角图标上，即可完成替换
* 最后重新应用图标就会自动更新

## 使用 Figma 编辑

[Edit in Figma](https://www.figma.com/file/n9kCrWTrcB4NgJJhz6oMNp/alacritty-logo?type=design&node-id=0%3A1&t=maJgxvxN6LGsMCZC-1)

## 生成新图标

```sh
# 1. 修改颜色
# 2. 导出切图保存到 alacritty.iconset 目录
# 3. 使用命令生成 alacritty.icns
iconutil --convert icns --output alacritty.icns alacritty.iconset
````

## 参考

* [改良了下传说中最快的终端](https://tw93.fun/2023-02-06/alacritty.html)
