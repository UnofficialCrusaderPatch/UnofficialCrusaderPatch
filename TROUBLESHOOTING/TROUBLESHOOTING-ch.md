## UCP3 启动器无法运行（打开后秒退）
请确保你已经安装了 [webview2 运行库](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)。
如果这未能解决问题，请尝试在你的[已安装应用](https://support.microsoft.com/zh-cn/windows/repair-apps-and-programs-in-windows-e90eefe4-d0a2-7c1b-dd59-949a9030f317)列表中修复 webview2 运行库。
如果以上方法均无效，你可以试试[这个解决方案](https://superuser.com/a/1751710)。

---

## 使用模组框架时，游戏完全无法启动（看不到游戏窗口）

1.  请确保你已经安装了[这个版本的微软 Visual C++ x86 运行库](https://aka.ms/vs/17/release/vc_redist.x86.exe)。

2.  问题依旧？请尝试使用命令行来启动游戏。使用此命令：
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3.  如果命令行没有显示任何警告或错误信息，请到 GitHub 上联系我们，或加入[我们的 Discord 服务器](https://discord.gg/P9dkF38Q2t)！

---

## 启动游戏时出现错误

如果错误信息中包含 **“AOB”** 字样，那么你很可能在使用一个不兼容的游戏版本。

-   本补丁官方支持 **1.41** 和 **1.41.1**（拉丁语系）版本。
-   如果你使用的是其他版本，可以通过 Firefly 官方的[十字军高清补丁](http://www.strongholdcrusaderhd.com/patch.html)免费升级到 1.41 版本，或者在 Steam 上购买正版游戏。

### 如何在 Steam 上更改游戏语言
请遵循[此 Steam 页面](https://help.steampowered.com/zh-cn/faqs/view/4984-C127-121D-B3F2)底部的指引。

---

## 为什么我最喜欢的扩展不生效？🤔

请确保你想要优先使用的扩展位于“已激活扩展”列表的**最顶端**。

-   **这是为什么呢？** 列表中的扩展是**从下往上**依次加载的。
-   因此，列表中位置越高的扩展，会**覆盖**掉位置较低的扩展所做的修改。

---

## “AI 扩展”和“AI 应用扩展”有什么区别？

-   **AI 扩展**（不带“应用”字样）：这类扩展负责添加新的 AI 文件（即新的 AI 领主内容）。
-   **“AI 应用扩展”**：这类扩展负责将新的 AI 配置应用到特定的 AI 位置上。
    例如：用一个新的耗子 AI 来替换掉旧的耗子 AI。

### 想要亲自自定义 AI 文件吗？
如果你只需要新的 AI 内容，那么仅激活 **AI 扩展**（不带“应用”字样）即可。
举个例子，你可以把一个新的耗子 AI 放到原本属于蛇的 AI 位置上，这样就能实现两只耗子同场竞技了。

---

## 战争宝箱战役（Warchest Trail）导致游戏崩溃
请查阅[此处的讨论](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/)。

## 其他问题

如果你遇到了其他问题，请随时到 GitHub 上反馈，或加入[我们的 Discord 服务器](https://discord.gg/P9dkF38Q2t)！