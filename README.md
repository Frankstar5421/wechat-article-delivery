# 公众号推文一键交付 Skill

把一份源文档变成「双击打开、点一下按钮、Ctrl/⌘+V 就能直接粘贴进公众号后台」的成品工具页，配图单独产出。

## 能做什么

- 输入：一份源文档 + 品牌名 + 开场/收场语气
- 输出：单个「一键复制到公众号.html」（含图版与占位版双按钮）+ 独立配图文件
- 内置森林绿 / 乳白 / 金色的瑞士国际主义排版基线，全内联样式，专门适配公众号编辑器的样式清洗规则

详细规范见 SKILL.md。

## 安装

把 SKILL.md 放到本机用户级 skills 目录：

~/.dsh/skills/wechat-article-delivery/SKILL.md

Windows 示例：C:\Users\你的用户名\.dsh\skills\wechat-article-delivery\SKILL.md

安装后重启会话或重新扫描技能目录即可调用，触发指令为 /wechat-article-delivery。

## 使用

/wechat-article-delivery 这里粘贴源文档全文

按提示补一次品牌名与首尾语气即可，配色、排版、配图数量等写定项无需回答。
