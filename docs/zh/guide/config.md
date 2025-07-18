# 简单配置

项目创建完成后，需要对项目进行简单的配置。比如APP 名称，要打包的网址，APP 标识 id，还有版本号等，当然前面四个是必填项，后面的可以根据自己的需求来配置。APP 名称支持中文/英文等，但是不支持空格。网站地址可以是本地地址，也可以是网络地址，但是必须是 http 或者 https 开头的地址，或者是你本地的 html 文件，以及 Vue/React 打包后的 dist 文件夹。软件唯一 id 是用来区分你的软件的，不能与其他项目重复。版本号是用来区分你的软件的版本的。

![](../../static/imgs/config1.webp)

简单配置后，就可以点击预览按钮来预览你的软件最终显示的时候长什么样子了。
确认无误后，点击发布，就可以开始打包了。

## 注意：

1. APP 名称：支持中文/英文等，但是不支持空格。
2. 网站地址：可以是本地地址，也可以是网络地址，但是必须是 http 或者 https 开头的地址，或者是你本地的 html 文件，以及 Vue/React 打包后的 dist 文件夹（单个文件大小最好不要超过 10M，因为 github 限制，例如视频或者图片最好全部使用外部链接的形式，或者使用压缩工具将文件压缩至 10M 以下）。
3. APP 标识：也就是 APP ID 是用来区分你的软件的，不能与其他项目重复。
4. APP 版本：是用来区分你的软件的版本的。
5. APP 图标：支持上传本地图片并且支持 Macos 的圆角切换，可不填，默认 PakePlus 图标。
6. 窗口保持：当你调整窗口大小或位置后，二次启动时是否保持窗口大小和位置。
7. 单例模式：当你多次点击桌面图标时，只允许打开一个软件。
8. 开发调试：是否启用开发调试模式，启用后可以在预览窗口中调试页面。
9. TauriApi：是否启用 TauriApi，启用后可以在 js 中调用 tauri 接口。
10. 脚本文件：支持任意 js 脚本文件，会在软件启动时执行注入（原子弹，不懂代码不要动）。
11. 窗口模式：支持桌面/iPhone/iPad/Android/自定义模式，也就是你的窗口长什么样子。
12. 过滤元素：支持过滤 selector 元素，也就是你的窗口里面哪些元素是不需要显示的，比如广告。
13. APP 描述：描述一下你这个软件是什么，有什么作用。
14. 右上角更多配置：支持更多自定义窗口配置，详细说明请见 tauri2 文档（核弹，不懂不要碰）。
15. 更多配置：支持 Json 格式配置，详细说明请见 tauri2 文档（核弹，不懂不要碰）。
16. 注入 JQ：支持注入 JQ 库，然后就可以在你的 js 脚本中使用 JQ 来操作 dom （手榴弹）。
