## 测试环境要求
- Mumu12模拟器
- 模拟器分辨率设置为 平板版-1280x720(DPI240),帧率设置60帧
- 游戏设置为 画质档位:省电模式,帧率:60,UI布局:触屏,镜头灵敏度:5,镜头自动跟随转动:关闭,棋盘镜头移动速度:1,游戏语言:简体中文

## 请严格遵照上述游戏设置

## 目前仅能以开发方式启动,无发布版
## 启动入口为 src/main.py

# ZenlessZoneZero-Copilot

</div>

本仓库基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 项目模板创建。

> **MaaFramework** 是基于图像识别技术、运用 [MAA](https://github.com/MaaAssistantArknights/MaaAssistantArknights) 开发经验去芜存菁、完全重写的新一代自动化黑盒测试框架。
> 低代码的同时仍拥有高扩展性，旨在打造一款丰富、领先、且实用的开源库，助力开发者轻松编写出更好的黑盒测试程序，并推广普及。


## 如何开发

1. 完整克隆本项目及子项目（地址请修改为您基于本模板创建的新项目地址）。

    ```bash
    git clone --recursive https://github.com/bamboo98/ZenlessZoneZero-Copilot.git
    ```

    **请注意，一定要完整克隆子项目，不要漏了 `--recursive`，也不要下载 zip 包！**

2. 下载 MaaFramework 的 [Release 包](https://github.com/MaaXYZ/MaaFramework/releases)，解压到 `deps` 文件夹中。

3. 配置资源文件。

    ```bash
    python ./configure.py
    ```

4. 打开Mumu12模拟器,按要求修改游戏设置,启动测试程序
   ```bash
   python ./src/main.py
   ```
   

## 生态共建

MAA 正计划建设为一类项目，而非舟的单一软件。

若您的项目依赖于 MaaFramework，我们欢迎您将它命名为 MaaXXX, MXA, MAX 等等。当然，这是许可而不是限制，您也可以自由选择其他与 MAA 无关的名字，完全取决于您自己的想法！

同时，我们也非常欢迎在 [最佳实践列表](https://github.com/MaaXYZ/MaaFramework#%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5) 中添加上您的项目！

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

感谢以下开发者对本项目作出的贡献（下面链接改成你自己的项目地址）:

<a href="https://github.com/MaaXYZ/MaaFramework/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=bamboo98/ZenlessZoneZero-Copilot&max=1000" />
</a>


### v0.1
- [x] 能跑
- [x] 搞定多点触控(战斗模块刚需)
- [x] 拿命验收自动化(1号位手动上一个妮可或比利)

# 饼

### v0.2
- [ ] GUI客户端和自动化打包发版
- [ ] 零号空洞自动化
- [ ] 降低CPU利用率,再跑下去赚的丁尼就真不够交电费了
