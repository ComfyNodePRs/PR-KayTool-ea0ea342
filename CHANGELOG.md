# Changelog

## [0.0.1] - 2024-10-19
### Added
- 实现自定义保存图像节点。
- 支持保存为 PNG 和 JPG 格式。
- 添加 JPG 质量调整选项。
- 支持嵌入作者和版权信息。
- 支持选择 sRGB IEC61966-2.1 和 Adobe RGB (1998) 颜色配置文件。
- 当选择 Adobe RGB 时，自动将图像转换为 Adobe RGB并保证色彩准确。
- 支持保存元数据到 PNG 文件，包括 `prompt` 和 `extra_pnginfo`。
- 自动生成唯一文件名。