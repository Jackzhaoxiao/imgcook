English | [简体中文](https://github.com/imgcook/imgcook/blob/master/extensions/imgcook-vscode/README.zh-CN.md)

<h1 align="center">
  <br>
    <a href="https://www.imgcook.com"><img src="https://img.alicdn.com/tfs/TB1bbwkzY2pK1RjSZFsXXaNlXXa-128-128.png" alt="logo" width="100"></a>
  <br>
  imgcook for Visual Studio Code
  <br>
  <br>
</h1>
<h4 align="center">A intelligent tool that converts design to code.</h4>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=imgcook.imgcook"><img src="https://vsmarketplacebadge.apphb.com/version-short/imgcook.imgcook.svg" alt="Marketplace bagde"></a>
  <img src="https://vsmarketplacebadge.apphb.com/installs-short/imgcook.imgcook.svg" alt="Marketplace bagde">
  <img src="https://vsmarketplacebadge.apphb.com/downloads-short/imgcook.imgcook.svg" alt="Marketplace bagde">
  <img src="https://vsmarketplacebadge.apphb.com/rating-star/imgcook.imgcook.svg" alt="Marketplace bagde">
</p>

[imgcook](https://www.imgcook.com/) is an ingenious chef who specializes in cooking with various images (Sketch / PSD / static images). it will intelligently generate front-end codes, including view codes, data-binding codes, component codes as well as part of business logic codes from different kinds of design documents.

Our Website: [https://www.imgcook.com](https://www.imgcook.com/)

## Features

### Design to code

imgcook has no strict constraints and requirements on the design draft, but it can still make the reduction effect more friendly through some simple specifications. For example, divide the layers belonging to the same module into a group, and merge multiple drawings. Please refer to the basic specifications of the design draft for details.

After the plug-in is installed successfully, open the [content.Sketch] file, and click 「Plugins」 - 「imgcook」 - 「打开/关闭面板」 to call up the imgcook panel to assist visual adjustment.

<p align="center"><img src="https://gw.alicdn.com/imgextra/i2/O1CN01Yavnl51frWgbDTlcl_!!6000000004060-2-tps-2880-1800.png" alt=""></p>

### Visual editing

In the imgcook visual editor, we can edit views, such as supporting dynamic expression styles, setting loops, and modifying layouts. You can also write logic code, bind fields, and more. It is recommended that you read the editor introduction before starting.

<p align="center"><img src="https://gw.alicdn.com/imgextra/i3/O1CN01wriR2o26ryhWBtvWq_!!6000000007716-2-tps-2880-1750.png" alt=""></p>

### Generate code

Please click "save" before generating the code. If the page changes, the editor will also monitor and remind you. Click "导出" after saving to local folder.

<p align="center"><img src="https://gw.alicdn.com/imgextra/i3/O1CN01w4bGyE1rlp8wio9jZ_!!6000000005672-2-tps-2880-1750.png" alt=""></p>


From JSON description to code. We need to write DSL to analyze. We have official DSL. You can also [customize DSL](https://www.imgcook.com/docs?slug=dsl-dev).


[Learn more about imgcook](https://www.imgcook.com/tutorial)


## Getting Started

1. [Install the extension](https://marketplace.visualstudio.com/items?itemName=imgcook.imgcook)
2. Right click on any folder in the VSCode file explorer and select 「Open With imgcook studio」 to start developing.

## Using imgcook

- You can right click on any folder in the VSCode file explorer and select 「Open With imgcook studio」 to start developing. Or alternatively, you can execute `imgcook: Open With imgcook studio` in the Command Palette to using imgcook in the current project.

- To do a quick login, you can click the button 「点我输入 AccessId」 to enter the AccessId provided in the imgcook website.<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB1A2.zqHY1gK0jSZTEXXXDQVXa-2880-1754.png">

- Next, you can install our Sketch (or Photoshop) plugin from our [website](https://www.imgcook.com/).

- Once you have installed the plugin, you can export the sketch data and save it temporarily in the clipboard.<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB10CWAXW1s3KVjSZFAXXX_ZXXa-862-446.png" />

- After successfully exporting the data, you need to paste it in the imgcook studio.<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB1NSQuqQY2gK0jSZFgXXc5OFXa-2880-1754.png" alt="design to code">

- Here it is! The sketch is now completely transformed into managed imgcook format, and you can customize the styles, properties, or even events and data.<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB1IQQtqUT1gK0jSZFrXXcNCXXa-2880-1754.png" alt="design to code">

- Once you have done with your work, you save the project in the current workspace (local folder).<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB1yNoAqQT2gK0jSZFkXXcIQFXa-2880-1754.png" alt="design to code">

- By export the project, imgcook studio will elegantly generate a workable and readable code project for you.<br><br><img width="500" src="https://gw.alicdn.com/tfs/TB1Ad7yqQL0gK0jSZFxXXXWHVXa-2880-1754.png" alt="design to code">

## Community support

For general help using imgcook, please refer to [the documentation](https://www.imgcook.com/docs). For additional help, you can use one of these channels to ask a question:

### DingTalk

<img width="200" src="https://gw.alicdn.com/tfs/TB1UW5UcIVl614jSZKPXXaGjpXa-750-990.jpg" />

- [GitHub](https://github.com/taofed/imgcook/issues) (Bug reports)
- [Medium](https://medium.com/imgcook) (Get blogs and articles)
- [知乎专栏](https://zhuanlan.zhihu.com/imgcook) (Get blogs and articles in Simplified Chinese)
