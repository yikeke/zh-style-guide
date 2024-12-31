# 中文技术文档写作风格指南

网页浏览地址：<https://zh-style-guide.readthedocs.io>

本仓库存储的是《中文技术文档写作风格指南》的源文件，欢迎任何人进行贡献！

## 如何贡献

所有的源文件都存放在 /source 文件夹下：

- 配置文件为 conf.py 文件
- 各章节目录为各个 index.rst 文件
- 各章节页面为各个 xxx.md 文件

如需贡献，**请直接修改 /source 文件夹下的相应文件。**

### 具体步骤

1. Fork 本仓库到你的 GitHub 账号
2. 克隆你 fork 的仓库到本地：
    ```bash
    git clone https://github.com/你的用户名/zh-style-guide.git
    cd zh-style-guide
    ```
3. 在本地部署测试环境：
    - 确保已安装 Python 3.12 或更高版本
    - 确保已安装 pip 包管理器
    - 创建并激活虚拟环境：
        ```bash
        python3 -m venv venv
        # Windows 系统使用：
        # venv\Scripts\activate
        # Unix/MacOS 系统使用：
        source venv/bin/activate
        ```
    - 安装项目依赖：
        ```bash
        pip install -r requirements.txt
        ```
    - 启动本地预览服务：
        ```bash
        sphinx-autobuild source build/html
        ```
    - 在浏览器中访问 http://127.0.0.1:8000 查看文档
    - 修改源文件后，网页会自动刷新重建
4. 修改 /source 文件夹下的相关文件
5. 提交变更：
    ```bash
    git add .
    git commit -m "描述你的修改"
    git push origin main
    ```
6. 在 GitHub 上创建 Pull Request

## 为自己的公司创建一份风格指南

你可以点击右上角的 Fork 按钮，将该风格指南克隆到自己的仓库下，接着就可以按需自行修改了。

如果你成功在公司内部推广了这份风格指南，鼓励你在 [zh-style-guide 的使用者列表（完善中）](https://github.com/yikeke/zh-style-guide/discussions/26) 讨论区留下你的足迹。

每位 zh-style-guide 项目的实际使用者，都是社区的宝贵财富。每次与他人的连接，都会产生意想不到的价值！

## 相关博客文章

<img align="right" src="qrcode.jpg" alt="微信公众号二维码：阿狍杂谈" height="150" />

- [30 页的开源版中文技术文档写作风格指南，Web 端开放访问！](https://mp.weixin.qq.com/s/5znjT8FKJU08YS5lKFJvDA)
- [《风格指南》站的实现篇——如何在 30 分钟内制作一个美观的在线文档网站](https://mp.weixin.qq.com/s/7hfOOmhtJURewq8Fz7NhKg)

欢迎扫码关注我的微信公众号『阿狍杂谈』👉

介绍：我在互联网/IT/开源世界玩大冒险，在英语/心理/哲学世界学真心话。我所有的输赢得失，都在这儿讲给你听 :-)

## Repo stars

[![Stargazers over time](https://starchart.cc/yikeke/zh-style-guide.svg)](https://starchart.cc/yikeke/zh-style-guide)

## License

MIT

## Reference

- [Readthedocs 项目控制台](https://readthedocs.org/projects/zh-style-guide/builds)

- [Sphinx 入门 — Sphinx 1.8.5 文档](https://sphinx-doc.readthedocs.io/zh_CN/master/usage/quickstart.html#adding-content)

<!-- - [readthedocs/recommonmark: A markdown parser for docutils](https://github.com/readthedocs/recommonmark#linking-to-headings-in-other-files) -->

- [Specifying Dependencies — Read the Docs 5.4.3 documentation](https://docs.readthedocs.io/en/latest/guides/specifying-dependencies.html)

- [reStructuredText — Sphinx 1.8.5 文档](https://sphinx-doc.readthedocs.io/zh_CN/master/usage/restructuredtext/index.html)
