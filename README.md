# 全屏翻译

屏幕区域截图翻译工具，支持实时 OCR 识别和多语言翻译。

## 功能

- 截取屏幕任意区域进行翻译
- 支持 OCR 文字识别
- 翻译结果直接覆盖在原文字位置
- 翻译历史记录
- 支持中英日韩等多种语言互译

## 下载

前往 [Releases](../../releases) 页面下载最新版本的 `全屏翻译.exe`。

## 配置

1. 复制 `config.example.json` 为 `config.json`
2. 填入你的百度翻译 API 凭证：

```json
{
  "appid": "你的百度翻译API ID",
  "appkey": "你的百度翻译API密钥",
  "from_lang": "auto",
  "to_lang": "zh"
}
```

3. 百度翻译 API 申请地址：https://fanyi-api.baidu.com/

## 使用

1. 运行 `全屏翻译.exe`
2. 选择屏幕区域
3. 自动识别并翻译
4. 翻译结果覆盖显示在原文字位置

## 目录结构

```
全屏翻译/
├── 全屏翻译.exe          # 主程序（从 Releases 下载）
├── config.json            # API 配置（需自行创建，不要泄露）
├── config.example.json    # 配置模板
└── history/               # 翻译历史（运行后自动生成）
```

## 注意

- `config.json` 包含 API 密钥，切勿分享或上传
- API 密钥申请：[百度翻译开放平台](https://fanyi-api.baidu.com/)
