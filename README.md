# StatusBarLyricExt-fork

## 项目依然在开发中，不可使用，可以访问[原项目](https://github.com/cjybyjk/StatusBarLyricExt)

Forked from <https://github.com/cjybyjk/StatusBarLyricExt>

原作者不更新项目了，这个项目在原作的基础上做了自己的一些修改，修复了一些问题。

添加的新功能：

- [ ] 无歌词不显示
- [ ] 新的歌词源
- [ ] 支持手动选择歌词源

修复的问题：

- [ ] 忽略应用列表文字显示重叠
- [ ] 忽略应用列表读取不到软件
- [ ] 忽略应用不生效

---

- [ ] 开发完成后完善 README

## 原仓库 README

这个工具可以为使用 [MediaSession](https://developer.android.google.cn/reference/android/media/session/MediaSession) 的音乐播放器添加状态栏歌词功能

目前仅支持 [StatusBarLyric](https://github.com/577fkj/MIUIStatusBarLyric)

## 原理
- 通过 [MediaController](https://developer.android.google.cn/reference/android/media/session/MediaController) 取得当前播放的媒体信息
- 联网获取歌词后显示在状态栏上

## 使用的开源项目
- [StatusBarLyricExt](https://github.com/aimerneige/StatusBarLyricExt-fork)
- [LyricView](https://github.com/markzhai/LyricView)
