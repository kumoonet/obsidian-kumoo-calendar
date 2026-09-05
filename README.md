# Kumoo Calendar

> **English**
> A sidebar calendar view for Obsidian. Shows Gregorian + lunar dates side by side, and for the selected day displays a Chinese almanac (宜/忌, auspicious/inauspicious spirits, lucky directions, and a 12 double-hour luck table). It also maps every file's creation/modification date across your entire vault (attachments included) onto the calendar, so you can see at a glance what you worked on any given day.
>
> **Installation**
> **Option 1 — Community plugins (recommended)**
> 1. Settings → Community plugins → Browse
> 2. Search for "Kumoo Calendar"
> 3. Install → Enable
>
> **Option 2 — Manual**
> 1. Put `main.js`, `manifest.json`, `styles.css` into `.obsidian/plugins/kumoo-calendar/`
> 2. Restart Obsidian and enable the plugin

![Obsidian Downloads](https://img.shields.io/badge/dynamic/json?logo=obsidian&color=%23483699&label=downloads&query=%24%5B%22kumoo-calendar%22%5D.downloads&url=https%3A%2F%2Freleases.obsidian.md%2Fstats)

侧边栏日历视图：阳历 + 农历双历显示，选中日期查看黄历（宜/忌、吉神/凶煞、天神/喜财福神方位、12 时辰吉凶表），并把整个仓库的文件活动（创建/修改日期，含附件）映射到日历上——哪年哪月哪日做了什么，一目了然。

## 功能特性

1. **双历显示**：公历 + 农历日期，公历/农历假日、节气、调休班休标记，周数、季度显示
2. **黄历面板**：选中日期显示宜/忌、吉神/凶煞、天神/喜财福神方位、12 时辰吉凶表（黄道/黑道 + 各时辰宜忌）
3. **文件活动时间线**：全库所有文件（含附件）的创建/修改日期落在对应日期格子上（绿点=新增，蓝点=更新）；点击日期查看当天文件列表，点击条目直接打开文件
4. **扫描缓存**：扫描结果缓存到本地，重启秒开；文件增删改实时增量更新并落盘
5. **快速创建**：日记 / 周记 / 月度 / 季度 / 年度笔记一键创建，标题格式与保存路径各自独立配置

## 设置说明

- **关于**：版本号 + 更新日志（点击查看）
- **外观**：主题模式（跟随/深色/浅色）、一周起始日、周末色、主题色、跟随强调色、字体字号
- **黄历（Plus）**：黄历面板开关
- **显示**：公历假日、调休、农历日期、农历假日、节气独立开关
- **季度显示**：数字 / 春夏秋冬 / 自定义命名，首季起始月可调
- **五类笔记**：日记/周记/月度/季度/年度，各自标题格式与默认路径
- **笔记扫描目录**：限定只扫描某目录（留空=全库）

## 使用方法

- 点击 `‹‹` `‹` `›` `››` 切换月/年，「今」回到今天
- 点击任意日期查看当天文件活动与黄历
- 点击文件条目直接打开对应文件
- 列表顶部按钮 `[+ 周 月 季 年]` 快速创建笔记

## 安装

**方式一：社区插件市场**
1. 设置 → 社区插件 → 浏览
2. 搜索 "Kumoo Calendar"
3. 安装 → 启用

**方式二：手动安装**
1. 将 `main.js`、`manifest.json`、`styles.css` 放入 `.obsidian/plugins/kumoo-calendar/`
2. 重启 Obsidian，在社区插件中启用

## 更新日志

### v1.0.0 — 首个版本（2026-08-09）
- 基于 Note Calendar v1.3.1 (MIT) 改造，更名 Kumoo Calendar，作者 KuMoo
- 新增黄历面板：宜/忌、吉神/凶煞、天神/喜财福神方位、12 时辰吉凶表（lunar-javascript）
- 新增全库文件活动统计：所有文件（含附件）的创建/修改日期映射到日历
- 新增扫描结果磁盘缓存，重启秒开，文件变化增量更新
- 新增设置页关于区块，点击版本号可查看更新日志

## Credits

基于 [Note Calendar](https://github.com/Is-Ming/obsidian-note-calendar) v1.3.1（MIT）改造。农历数据由 [lunar-javascript](https://github.com/6tail/lunar-javascript)（MIT）提供。

作者：KuMoo
