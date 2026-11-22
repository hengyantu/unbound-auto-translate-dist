# Unbound Auto Translate — published build

Experimental community plugin for Unbound (Discord mobile client). Requires Unbound **3.0.0+**.

## Install from URL

In **Unbound → Plugins → + → Install from URL**, paste:

```text
https://raw.githubusercontent.com/hengyantu/unbound-auto-translate-dist/main/manifest.json
```

Then enable **Auto Translate Chinese**, open plugin settings, select **In the message**, set **Source language** to **Auto detect**, set **Target language** to **Chinese (Traditional)** (`zh-TW`) or Simplified (`zh-CN`), and enable **Auto-translate server messages**. Optionally enable **Show Chinese only**.

**Known limits:** this is an experimental, compiled build, not yet verified on a real iPhone. It tries up to 30 cached messages and new messages in the selected server channel; it excludes direct messages and skips Chinese. For troubleshooting, temporarily disable the official Unbound Translate plugin to avoid duplicate patches.

**Privacy:** the text of eligible Discord messages is sent to the translation service configured in the plugin. Don't use it in sensitive channels. Modified Discord clients may violate the service's terms and introduce additional security/account risks.

Sources are maintained separately in a private development repository. The public repository hosts only compiled plugin files and locale assets.
