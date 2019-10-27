= auto-save 简介 =
这是来自 https://www.jianshu.com/p/998ceaf522d1 的插件，放在这里方便使用。

每当Emacs发现你停止敲键盘超过1s钟以后， 它就会把所有没有保存的文件全部保存一遍。
= 安装 =
下载auto-save.el，然后在~/.emacs 里面添加如下代码：

(require 'auto-save)            ;; 加载自动保存模块

(auto-save-enable)              ;; 开启自动保存功能
(setq auto-save-slient t)       ;; 自动保存的时候静悄悄的， 不要打扰我

或者同时下载 init-auto-save.el ，然后在~/.emacs 添加
(require 'init-auto-save)

