# liuruoxi1990.github.io

职业展示型 GitHub Pages。页面模板与文字内容已经分离，日常更新只需编辑 Markdown。

## 修改网站文字

- 首页信息：`_sections/00-profile.md`
- 职业概述：`_sections/10-summary.md`
- 核心成果：`_sections/20-achievements.md`
- 技术能力：`_sections/30-skills.md`
- 工作经历：`_sections/40-experience.md`
- 教育背景：`_sections/60-education.md`
- 证书与语言：`_sections/70-credentials.md`
- 代表项目：每个项目对应 `_projects/` 中的一个 Markdown 文件

Markdown 文件开头的 `---` 区域用于标题、顺序和时间等配置，下面是正常的 Markdown 正文。

## 新增项目

复制 `_projects/` 中任意一个文件，修改 `order`、`title`、`role`、`period` 和正文即可。文件名建议使用数字排序，例如 `50-new-project.md`。

## 头像

将头像保存为 `assets/images/avatar.webp`，然后在 `_sections/00-profile.md` 中设置：

```yaml
avatar: "/assets/images/avatar.webp"
```
