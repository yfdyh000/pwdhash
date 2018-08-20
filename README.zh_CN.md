# PwdHash Sidebar
出自斯坦福大学的 [PwdHash](https://crypto.stanford.edu/PwdHash/) 通过网站地址与密码组合计算散列（Hash）来生成防范攻击的独立密码。
本扩展目前在([Firefox](https://addons.mozilla.org/firefox/addon/pwdhash/)、[Chrome](https://chrome.google.com/extensions/detail/dnfmcfhnhnpoehjoommondmlmhdoonca)、[Opera <12](https://www.coredump.gr/pwdhash-for-opera/)) 上可用，以及提供有 ([Android](https://play.google.com/store/apps/details?id=com.uploadedlobster.PwdHash)、[iOS](https://itunes.apple.com/app/keygrinder/id354763605) 和 [Windows](https://github.com/mgutekunst/WP8-PwdHash)) 应用程序，以及 [Ruby](https://github.com/kizzx2/pwdhash.rb) 或 [Python] 脚本(https://pypi.python.org/pypi/pwdhash.py))，或简单的一个使用 Javascript 的网页。

尚不支持：
_剑桥大学的 [PwdHash](https://www.cl.cam.ac.uk/~dl551/pwdhash/) 基于斯坦福大学 PwdHash 的概念，但做了一些避免原版弱点的改进。
PwdHash-PoC 使用 PBKDF2-SHA512 的 Forge 实现生成散列值。_

此 PwdHash 版本是一个适用于常用浏览器（如 [Firefox](https://addons.mozilla.org/de/firefox/addon/pwdhash-sidebar/)、Chrome 和 Edge）的浏览器扩展，以及提供一个[简单的网页版](https://quassy.github.io/pwdhash/)。
您可以将它安装为浏览器扩展，或者将网页保存到本地来使用。

## 使用方法

**Web**: 
您可以直接使用网页版，还可以按下 `Ctrl`+`S` 来将整个网页保存到本地并供离线使用。
输入一个地址和一个密码即可。在密码框中按下回车键（Enter），密码就复制到您的剪贴板了。

**Firefox**: 
首先将 ![](icon_16.png) 按钮装到您的工具栏。然后，点击它或按下 `F8` 打开该工具栏。
地址已自动填写（仍可手动修改）。
在密码框中按下回车键，散列密码自动复制到您的剪贴板。
您还可以按下 `Ctrl`+`F8` 打开侧栏版本。

**Chrome** (尚未发布): 
点击按钮 ![](icon_16.png) or press `Alt`+`P` to open the toolbar menu. 
The address is prefilled (but can be modified). 
After pressing return on the password field, the hash is copied to your clipboard.

**Edge** (尚未发布): 
Click on the button ![](icon_16.png) to open the toolbar menu. 
The address is prefilled (but can be modified). 
After pressing return on the password field, the hash is copied to your clipboard.

## 屏幕截图

![Enter your password to generate a hash for the respective page by opening the sidebar by pressing Ctrl+F8](screenshots/firefox-sidebar.png)

## 作者
本软件由 quassy 创造，根据 BSD 许可证发布。

它基于一些作者以前的工作：
[Standford PwdHash](https://crypto.stanford.edu/PwdHash/): Blake Ross, Collin Jackson, Nicholas Miyake, Dan Boneh, John C. Mitchell (BSD)  
[md5.js](http://pajhome.org.uk/crypt/md5): Paul Johnston & Greg Holt, Andrew Kepert, Ydnar, Lostinet (BSD)  
[genpass](http://genpass.supergenpass.com/), domain extractor: Chris Zarate (public domain)