![](https://socialify.git.ci/AIGC-Yunzai/siliconflow-plugin/image?font=KoHo&forks=1&issues=1&language=1&name=1&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Auto)

<img decoding="async" align=right src="resources/readme/girl.png" width="35%">

# SiliconFlow-PLUGIN 🍓

- 一个适用于 [Yunzai 系列机器人框架](https://github.com/yhArcadia/Yunzai-Bot-plugins-index) 的接入 SiliconFlow 的插件（Synaptic Fusion插件——对接万物）
- 为什么要接入？因为他众多免费的绘图模型~可以白嫖~

> [!TIP]
> 插件官网（施工中）：[SiliconFlow-插件](https://aigc-yunzai.dwe.me/)
> 
> 将逐步接入更多API

## 安装插件

#### 1. 克隆仓库

```
git clone https://github.com/AIGC-Yunzai/siliconflow-plugin.git ./plugins/siliconflow-plugin
```

> [!NOTE]
> 如果你的网络环境较差，无法连接到 Github，可以使用 [GitHub Proxy](https://mirror.ghproxy.com/) 提供的文件代理加速下载服务
>
> ```
> git clone https://mirror.ghproxy.com/https://github.com/AIGC-Yunzai/siliconflow-plugin.git ./plugins/siliconflow-plugin
> ```

#### 2. 安装依赖

```
pnpm install --filter=siliconflow-plugin
```

## 使用教程

- [配置教程](https://aigc-yunzai.dwe.me/siliconflow/%E5%A6%82%E4%BD%95%E9%85%8D%E7%BD%AE)🍈

## 插件配置

> [!WARNING]
> 非常不建议手动修改配置文件，本插件已兼容 [Guoba-plugin](https://github.com/guoba-yunzai/guoba-plugin) ，请使用锅巴插件对配置项进行修改

## 功能列表

<img decoding="async" align=right src="https://github.com/user-attachments/assets/9698e837-49e7-4c19-8dab-6aa17d1faed4" width="35%">

请使用 `#sf帮助` 获取完整帮助

<!-- - [x] 文生图 -->
- [x] 接入多项免费画图/语言模型
- [x] 支持图生图
- [x] 多keys同时并发
- [x] 接入MJ绘图
- [x] 接入Fishaudio语音合成 
- [ ] 接入更多LLM推理
- [ ] 接入更多语音合成
- [ ] TODO...

## 支持与贡献

如果你喜欢这个项目，请不妨点个 Star🌟，这是对开发者最大的动力。

有意见或者建议也欢迎提交 [Issues](https://github.com/AIGC-Yunzai/siliconflow-plugin/issues) 和 [Pull requests](https://github.com/AIGC-Yunzai/siliconflow-plugin/pulls)。

## 相关项目

- [vits-plugin](https://github.com/erzaozi/vits-plugin)：一个适用于 Yunzai 系列机器人框架 的的 AI 语音合成插件，让你能够在机器人中使用 AI 语音合成功能
- [Fish-Audio](https://fish.audio)：Brand new TTS solution

## 感谢
- [vits-plugin](https://github.com/erzaozi/vits-plugin)：Fishaudio语音同传的方式绝大部分参考了该项目的实现方法，Fish-Audio.json也是直接用的该项目的，很是感谢
- 所以fishaudio发音人名称可以看[发音人名称](https://github.com/erzaozi/vits-plugin#fish-audio)


## 许可证

本项目使用 [GNU AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) 作为开源许可证。
