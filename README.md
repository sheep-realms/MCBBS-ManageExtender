# MCBBS-ManageExtender

## 简介
该脚本可以为MCBBS的版主管理面板提供便利功能。非管理人员使用这个脚本的话体验大概会很差。

## 功能
### 水贴检查
这个功能很鸡肋，仅供参考。会自动以红色背景标记水贴楼层，并在左下角计数。

### 回帖目录
在左侧生成一个回帖目录，点击用户名跳转到对应楼层。已知匿名用户无法被抓取。

### 帖子列表属性标记
识别在帖子列表识别帖子属性并标记颜色，做得很糟糕，被我注释掉了，建议使用Zapic的扩展。

### 快捷键
* <code>Alt</code> + <code>Z</code> —— 删除主题（打开操作面板）。
* <code>Alt</code> + <code>C</code> —— 关闭主题（打开操作面板）。
* <code>Alt</code> + <code>P</code> —— 主题评分。
* <code>Alt</code> + <code>Q</code> —— 评分自动填充：小麦-1，金粒-10。
** 再次按下自动填充理由：“请仔细阅读版规，不要灌水！”
** 其他管理操作模板按下此快捷键自动填充上述理由。
* <code>Alt</code> + <code>W</code> —— 评分自动填充：金粒-10。
** 再次按下自动填充理由：“请仔细阅读版规，不要灌水！”

### 左侧面板
左侧面板包含以下模块（按位置排序）：
* 消息模块（总是显示，但没有消息时不可见）
* 评分模块（在评分时显示）
* 目录模块（在帖内显示）
* 信息模块（总是显示）
* 控制台（按<code>Alt</code> + <code>`</code>显示，再次按下或执行命令后自动隐藏）

### 控制台
[Commands.md](Commands.md)
