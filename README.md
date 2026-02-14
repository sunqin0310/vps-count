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

## 一键部署（Cloudflare Pages）
点击下方按钮，快速将项目部署到你的 Cloudflare Pages（需登录 Cloudflare 账号）：

[![Deploy to Cloudflare Pages](https://camo.githubusercontent.com/5f09276816885000f1f94c081884991792fdbc89822991c51f779d424996d19c8/68747470733a2f2f6465706c6f792e636c6f7564666c6172652e636f6d2f627574746f6e3f70726f6a6563743d7061676573)](https://deploy.cloudflarepages.com/?url=https://github.com/sunqin0310/vps-count)

## 本地使用
1. 克隆仓库：
```bash
git clone https://github.com/sunqin0310/vps-count.git
cd vps-count
```
2. 直接打开 index.html 文件即可使用（无需额外依赖，纯前端静态项目）
