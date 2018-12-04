# 安装开发环境
Weex 官方提供了 weex-toolkit 的脚手架工具来辅助开发和调试。

首先，你需要 Node.js 和 Weex CLi。
1. 安装 Node.js

  方式多种多样，最简单的方式是在 [Node.js官网](https://nodejs.org/) 下载可执行程序直接安装即可。推荐使用[10.14LTS](https://nodejs.org/dist/v10.14.1/node-v10.14.1-x64.msi)。

  更多安装方式可参考 [Node.js官方信息](https://nodejs.org/en/download/)

  安装完成后，可以使用以下命令检测是否安装成功：
  
  ![node info](resource/node_version.png)

  通常，安装了 Node.js 环境，npm 包管理工具也随之安装了。因此，直接使用 npm 来安装 weex-toolkit。
  ```
  $ npm install -g weex-toolkit
  $ weex -v //查看当前weex版本
  ```

  查看weex-cli是否安装成功：

  ![weex info](resource/weex_info.png)

ß2. 安装相关依赖

#
