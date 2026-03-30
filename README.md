# AutoFlow 社区语言包仓库

[English](#english) | [中文](#中文)

---

## 中文

这是 [AutoFlow](https://github.com/XinyuCraft-XYHC/autoflow-windows) 的社区语言包仓库。

### 如何在 AutoFlow 中下载语言包

1. 打开 AutoFlow → 设置 → 外观
2. 点击「🌐 语言包市场」按钮
3. 浏览可用语言，点击「下载」安装
4. 语言包安装后即刻出现在语言选择列表中

### 已有语言包

| 语言 | 代码 | 作者 | 状态 |
|------|------|------|------|
| 日本語 | `ja_JP` | AutoFlow Community | ✅ 可用 |
| 한국어 | `ko_KR` | AutoFlow Community | ✅ 可用 |
| Français | `fr_FR` | AutoFlow Community | ✅ 可用 |
| Deutsch | `de_DE` | AutoFlow Community | ✅ 可用 |
| Русский | `ru_RU` | AutoFlow Community | ✅ 可用 |

### 贡献语言包

欢迎提交 Pull Request 添加新语言包！

**步骤：**

1. Fork 本仓库
2. 在 `languages/` 目录下新建 `<语言代码>/` 文件夹（如 `es_ES`）
3. 创建 `<语言代码>.json` 文件，参考 [翻译键列表](#翻译键参考)
4. 在 `index.json` 中添加你的语言包条目
5. 提交 Pull Request

**语言代码格式：** `语言_地区`（如 `es_ES`、`pt_BR`、`ar_SA`）

**JSON 格式示例：**
```json
{
  "app.name": "AutoFlow",
  "app.subtitle": "你的翻译",
  "btn.ok": "你的翻译",
  ...
}
```

**重要：** 
- 文件必须使用 UTF-8 编码
- 所有键必须存在（缺失的键会回退到简体中文）
- 请在 JSON 中加入 `"settings.language.<你的语言代码>": "语言显示名称"` 这一键

### 翻译键参考

参考 [AutoFlow 内置翻译文件](https://github.com/XinyuCraft-XYHC/autoflow-windows/blob/master/src/i18n.py) 获取所有可翻译的键列表。

---

## English

This is the community language pack repository for [AutoFlow](https://github.com/XinyuCraft-XYHC/autoflow-windows).

### How to download language packs in AutoFlow

1. Open AutoFlow → Settings → Appearance
2. Click the "🌐 Language Market" button
3. Browse available languages and click "Download" to install
4. The language will appear in the language selection list immediately

### Contributing a Language Pack

1. Fork this repository
2. Create a new folder `languages/<language-code>/` (e.g. `es_ES`)
3. Create `<language-code>.json` with translations
4. Add your entry to `index.json`
5. Submit a Pull Request

### index.json Format

```json
{
  "code": "es_ES",
  "name": "Español",
  "name_en": "Spanish",
  "author": "Your Name",
  "version": "1.0.0",
  "description": "Spanish language pack for AutoFlow",
  "download_url": "https://raw.githubusercontent.com/XinyuCraft-XYHC/autoflow-languages/main/languages/es_ES/es_ES.json",
  "updated": "2026-03-30",
  "stars": 0,
  "verified": false
}
```
