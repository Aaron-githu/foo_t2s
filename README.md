# foo_t2s - 繁体转简体转换器

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![foobar2000](https://img.shields.io/badge/foobar2000-1.6+-orange.svg)](https://www.foobar2000.org/)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.foobar2000.org/)

## 📖 简介
foo_t2s 是一个 foobar2000 音频播放器的插件，用于实时将繁体中文标签转换为简体中文。无论你的音乐文件标签是繁体中文，还是从香港、台湾地区获取的音乐资源，这个插件都能帮你自动转换为简体显示。

## ✨ 功能特性
- **实时转换**：自动将播放列表、媒体库中的繁体中文标签转换为简体
- **支持标签**：标题、艺术家、专辑、风格等所有元数据标签
- **高性能**：采用高效的转换算法，不影响播放性能
- **可开关**：可以在设置中随时启用/禁用转换功能
- **批处理**：支持批量转换现有音乐文件的标签

## 🔧 安装方法
1. 从 [Releases](https://github.com/Aaron-githu/foo_t2s/releases) 页面下载最新的 `foo_t2s.fb2k-component` 文件
2. 双击下载的文件，foobar2000 会自动安装
3. 或者在 foobar2000 中点击 `File` -> `Preferences` -> `Components` -> `Install`，选择下载的文件
4. 重启 foobar2000 完成安装

## ⚙️ 使用方法
安装后，插件会自动工作。你可以通过以下方式配置：

1. 打开 foobar2000 的 `Preferences`（快捷键 `Ctrl+P`）
2. 找到 `Tools` -> `T2S Converter`
3. 在这里可以：
   - ✅ 启用/禁用自动转换
   - ✅ 选择要转换的标签字段
   - ✅ 执行批量标签转换

## 🛠️ 编译指南
如果你想从源代码编译：

### 依赖项
- Visual Studio 2019 或更高版本
- foobar2000 SDK
- Windows SDK 10.0+

### 编译步骤
```bash
git clone https://github.com/Aaron-githu/foo_t2s.git
cd foo_t2s
# 打开解决方案文件进行编译
