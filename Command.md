# 控制台

## 控制台的基本操作
按 <code>Alt</code> + <code>`</code> 打开左下角的控制台，按 <code>Enter</code> 执行命令。

## ./ 和 /.
* <code>./</code> - 加长控制台输入框。
* <code>/.</code> - 复位控制台输入框。

## cd
用于打开指定页面。

### 语法
<code>cd <*类型*> <*值*> [*是否在新窗口打开*]</code>

### 参数
#### *类型*

| 参数              | 描述                      | 接受的值                                             |
|-------------------|---------------------------|-----------------------------------------------------|
| <code>*</code>    | 首页                      | （无） |
| <code>a</code>    | 文章                      | 文章AID |
| <code>f</code>    | 论坛                      | 版块FID<br>若值为<code>*</code>则打开论坛 |
| <code>p</code>    | 帖子                      | 帖子PID |
| <code>pg</code>   | 特殊页面                   | （待补充）
| <code>t</code>    | 主题                      | 帖子TID<br>若值为<code>*</code>则打开导读-最新发表 |
| <code>tag</code>  | 标签                      | 标签ID<br>若值为<code>*</code>则打开标签列表 |
| <code>tagn</code> | 标签                      | 标签名称<br>若值为<code>*</code>则打开标签列表 |
| <code>u</code>    | 用户页                    | 用户UID<br>若值为<code>~</code>则自动填写登录者的UID。 |
| <code>un</code>   | 用户页                    | 用户名 |
| <code>unm</code>  | 管理面板-帖子管理          | 用户名 |
| <code>uns</code>  | 用户搜索                  | 用户名 |
| <code>unops</code>| 站点统计-用户搜索          | 用户名 |
| <code>us</code>   | 用户空间                  | 用户UID |
| <code>usr</code>  | 访问用户空间并清除访问记录  | 用户UID |

#### *值*
见上文。

#### *是否在新窗口打开* （可选）
<code>t|f</code> - 默认为t。

### 效果
如果参数正确，则会打开指定的页面。

## cls
用于清除左侧面板消息。

## date
输出当前日期与时间。

## err
见[#msg](#msg)。

## help
*此命令为独立控制台版本独有。*

输出本帮助页面的地址。

## msg
输出消息。

### 语法
<code>msg <*消息...*></code>

另有两个变种：

<code>err <*消息...*></code>

<code>rit <*消息...*></code>

### 参数
#### *消息...*
任意字符串。

### 效果
* msg - 输出一条普通消息。
* err - 输出一条“[ERROR]”前缀的错误报告，消息框为红色。
* rit - 输出一条成功报告，消息框为绿色。
* 内容越多，消息停留时间越长。

## open
打开网页。

### 语法
<code>open <*URL...*></code>

### 参数
#### *URL...*
网页URL地址。

### 效果
在新窗口打开指定网页。

## ps
列出当前所有已加载的面板ID。

## rit
见[#msg](#msg)。