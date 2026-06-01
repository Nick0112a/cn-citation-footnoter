# cn-citation-footnoter

> WorkBuddy AI 助手技能：中文学术论文引注转 Word 脚注

自动识别正文中的 `[1]` `[1-3]` `[1,2,3]` 等引用标记，转换为 Word 原生脚注（非伪脚注），支持《法学引注手册》等标准格式。

## 功能

- ✅ 识别中文全角 `［］` 和英文半角 `[]` 引用标记
- ✅ 自动生成 Word 原生脚注（WPS/Word 均可正常显示）
- ✅ 支持重复引用自动合并
- ✅ 支持从不同来源标准化引用格式

## 安装

```bash
pip install python-docx lxml
```

## 使用

调用 `scripts/` 目录下的脚本对 `.docx` 文件进行处理。

## 作为 WorkBuddy Skill 使用

```bash
cp -r . ~/.workbuddy/skills/cn-citation-footnoter/
```

## 许可

MIT
