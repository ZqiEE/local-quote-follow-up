[English](./README.md) | [中文](./README.zh-CN.md)

# Local Quote Follow-up

**一款面向服务型团队的本地优先找客与报价推进软件。**

找客户，推进跟进，把数据留在本机。

## 它在做什么

Local Quote Follow-up 帮服务型团队：

- 找到看起来值得联系的公司官网
- 把选中的 lead 写进本地 pipeline
- 自动接到 Customer / Quote / Task 结构
- 从一个工作台里持续推进跟进和报价

## 为什么强调本地 / 隐私

- 数据默认保存在你的电脑本机
- 默认不连接外部 AI API
- 本地模型运行环境可以在 Settings 里直接看到
- 数据路径、模型路径、运行模式都可以自己检查

## 主路径

1. 在 **Lead Capture** 里搜索
2. 判断哪些 lead 真值得联系
3. 点击 **Move to Follow-up**
4. 让系统创建或复用 **Customer / Quote / Task**
5. 回到 **Today Queue**
6. 用 **Quick Follow-up** 持续推进报价
7. 在 **Timeline** 里查看历史
8. 必要时用 **Undo Last AI Update**

## 核心能力

- 按 ICP 找客
- 本地 lead 写回 pipeline
- 报价聚合视角的 Today Queue
- Quick Follow-up
- Timeline + Undo
- 本地运行环境可见

## 截图 / 演示

预留位置：

- Today Queue
- Lead Capture
- Move to Follow-up
- Quote Detail + Timeline
- Desktop Settings / 本地运行环境

## 安装

### Windows 桌面版

1. 从 Releases 下载最新安装包
2. 安装软件
3. 打开 **Local Quote Follow-up**

### 本地开发运行

后端：

```powershell
cd /d F:\vendor_eval\idurar-erp-crm\backend
npm run start
```

前端：

```powershell
cd /d F:\vendor_eval\idurar-erp-crm\frontend
npm run dev -- --host 127.0.0.1
```

打开：

```text
http://127.0.0.1:3001
```

## 首次启动

首次启动建议这样走：

1. 安装本地模型运行环境
2. 安装推荐模型
3. 进入软件

你也可以在 Settings 里查看：

- 数据目录
- 模型目录
- 运行模式
- Ollama 路径

## 当前阶段 / 当前限制

当前阶段：

- 内部测试 / 小范围闭测

当前限制：

- Lead Capture 第一版已经可用，但还需要更多真实用户验证
- Lead 质量还没到完全可放量的程度
- 桌面版首次启动链路还需要更广的实机安装验证
- 低频页面还没有完整英文化

## Roadmap

- 用真实用户继续验证 lead 质量
- 继续提高“值不值得联系”的判断
- 提高 lead 到 follow-up 的真实转化效率
- 继续收口安装体验和信任感

## 反馈 / 联系

最有价值的反馈是：

- 你用了什么搜索输入
- 返回了多少 lead
- 其中多少条你真愿意联系
- 你点了哪些进入跟进
- 哪一步最慢、最不清楚、最不放心

