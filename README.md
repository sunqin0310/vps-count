# VPS剩余价值计算器

一个轻量、易用的 VPS 剩余价值计算工具，支持多币种换算、实时汇率获取，可一键复制计算结果为 Markdown 格式，方便分享和记录。

## 核心功能
1. **精准价值计算**：根据购买价格、续费周期、起止时间，自动计算 VPS 剩余使用时间和剩余价值
2. **多币种换算**：支持 USD/CNY/EUR 等 8 种货币，对接实时汇率接口，自动完成币种转换
3. **出让收益评估**：输入出让价格，自动计算溢价/亏损金额，直观评估转让收益
4. **一键清空重置**：输入区域右上角的「清空所有」按钮，可一键清除输入内容和计算结果，方便重复使用
5. **Markdown 一键复制**：计算结果支持一键复制为标准化 MD 表格，直接粘贴到文档/论坛/笔记中

## 界面展示
#### 输入界面
![输入界面示例](https://raw.githubusercontent.com/sunqin0310/vps-count/main/in.png)

#### 输出结果界面
![输出结果示例](https://raw.githubusercontent.com/sunqin0310/vps-count/main/out.png)

#### Markdown 复制结果
![MD语法结果示例](https://raw.githubusercontent.com/sunqin0310/vps-count/main/copy.png)

## 部署教程（Cloudflare Pages）
1. 将本仓库 Fork 到你的 GitHub 账号下
2. 登录 Cloudflare 控制台，进入 Pages 模块，选择「连接到 Git」
3. 选择已 Fork 的 `vps-count` 仓库，直接完成部署（默认配置无需修改）

## 本地使用（无需部署/无需Git）
1. 打开本仓库主页，点击「Code」→「Download ZIP」下载完整源码包
2. 解压下载的 ZIP 文件
3. 双击解压后的 `index.html` 文件，直接在浏览器中打开即可使用
