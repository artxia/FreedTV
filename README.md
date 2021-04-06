# FreedTV

同步[原项目](https://github.com/FreeDTV/FreeD)，增加自定义资源。<br>

File | Descriptions 
-- | -- 
public.json | 公共接口，会有些公共参数配置暂时用不到
searchUrl.json | 资源站/定制导航/搜索接口地址 对接苹果CMS10接口
sourceNavigation.json | 资源专题接口
webPlugNavigation.json | 云插件接口

<br>

- 在备份基础上添加了自定义功能，自定义内容会自动添加到核心接口文件中（仅 TV） <br>

File | Descriptions 
-- | -- 
custom/searchUrl.json | 自定义资源站接口
custom/webPlugNavigation.json | 自定义云插件接口

<br>

- 增加了收集功能，收集一些互联网上的接口文件，以便挑选后加入自定义 <br>

File | Descriptions 
-- | -- 
custom/exterior/list.txt | 收集地址列表，格式:url 重命名
custom/exterior/files/ | 收集到的文件

<br>

# Usage

[下载](https://wwi.lanzous.com/b025mpw7e) <br>
选择自建接口，输入 
- 默认：`https://github.com/artxia/FreedTV/raw/main/tv/`
- 大陆：`https://cdn.jsdelivr.net/gh/artxia/FreedTV@main/tv/`

<br>

也可以 fork 本项目，然后自己在自定义文件中修改自己喜欢的接口。（别忘了点 star）

<br>

# FreeD

- https://github.com/FreeDTV/FreeD
- https://gitee.com/freedTV/freed

---

## Logs

20210328 <br>
原项目在GitHub建立了项目，观察几天后发现作者已经把这边作为主要更新地 <br>
本项目修改拉取目标为GitHub

20210222 <br>
因为原项目只有gitee建立，所以在GitHub做了一个定时拉取的备份 <br>
在备份基础上增加了自定义资源+原项目资源合并的功能
