# RK3399 QT MPP RGA解码RTSP流并显示

## 项目简介

本项目专为基于RK3399平台的开发者设计，旨在实现通过Qt界面，利用FFmpeg库高效地从RTSP流中拉取视频数据，随后借助RK3399的Media Processing Pipeline (MPP)进行硬件加速解码。解码后的视频数据将进一步通过RGA（Rockchip Graphics Accelerator）进行格式转换和渲染，最终实现在Qt应用程序中的流畅显示。这一方案充分利用了RK3399的强大多媒体处理能力，为视频播放应用提供了高性能、低延迟的解决方案。

## 技术栈

- **处理器**: RK3399，一款高性能六核处理器，支持多种编解码标准。
- **框架**: Qt，用于构建跨平台用户界面。
- **媒体处理**: FFmpeg，强大的音视频处理库，负责网络流获取和预处理。
- **硬解码**: RK3399自带的MPP，实现视频的硬件加速解码。
- **图形加速**: RGA，用于快速完成图像的转换和显示任务。

## 功能特点

1. **RTSP流解码**：无缝对接RTSP视频流，支持常见的视频编码格式如H.264/H.265等。
2. **硬件加速**：充分发挥RK3399 MPP特性，减轻CPU负担，提升解码效率。
3. **RGA图形处理**：优化图像显示质量，实现流畅的视频播放体验。
4. **Qt界面集成**：创建用户友好的GUI，便于监控和控制视频播放过程。
5. **跨平台潜力**：虽然主要针对Linux环境下的RK3399，但Qt的特性使其具备一定的移植性。

## 快速入门

1. **环境准备**：确保你的开发环境已经安装了Linux操作系统，适合RK3399的交叉编译环境，FFmpeg库以及Qt开发环境。
2. **克隆仓库**：从GitHub上克隆本项目到本地。
3. **配置与编译**：根据提供的说明文档配置项目，包括必要的路径设置和依赖项链接。
4. **运行示例**：在目标设备(RK3399)上部署编译好的程序，并执行以查看RTSP流的解码与显示效果。

## 注意事项

- 请确保你的开发板已经正确安装了所有必需的驱动程序，特别是MPP和RGA的相关驱动。
- RTSP流的URL需要在代码中正确配置或动态输入，以适应不同的视频源。
- 项目可能需要根据具体的系统配置和FFmpeg版本进行适当的调整。

## 贡献与反馈

欢迎各位开发者提交Pull Request，修复bug或增加新功能。如果在使用过程中遇到问题，可以在项目Issue页面提问，社区会尽力提供帮助。

加入我们，共同探索更多关于嵌入式多媒体应用的可能性！

---

这个README.md为RK3399平台上结合Qt、FFmpeg、MPP和RGA进行RTSP流解码与显示项目的简要介绍，希望能够为你提供清晰的项目概览和快速入门指导。

## 下载链接

[RK3399QTMPPRGA解码RTSP流并显示](https://pan.quark.cn/s/89b02c3e677c)