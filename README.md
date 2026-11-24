<h1 align="center">JOB//OS</h1>
<p align="center"><strong>把职位、简历和申请回执放在同一个本地工作台。</strong></p>
<p align="center"><a href="#windows-安装">Windows 安装</a> · <a href="#从第一个岗位开始">快速上手</a> · <a href="docs/agent/AGENT_README.md">Agent 使用说明</a> · <a href="https://github.com/bowen-rgb/job-apply-assistant/releases">发行记录</a></p>

当同一个岗位同时出现在招聘平台、公司官网和邮件里，JOB//OS 帮你保留一条申请记录。打开这条记录，就能核对岗位来源、选用的简历、提交进度和回执。

## Windows 安装

桌面版 **0.3.0** 面向 Windows x64。安装包已完成本地验证，公开附件以上方发行记录为准。旧版源码用户可继续查阅[原版使用手册](https://github.com/bowen-rgb/job-apply-assistant/blob/aa33e47/USER_GUIDE.md)。

1. 在发行页的 **Assets** 中选择 `JOB-OS-Setup-0.3.0.exe`。同页的 `.sha256` 用于校验下载。
2. 双击安装，选择安装位置。首次打开时，选择「开始教程」，或勾选「不再提示」。
3. 需要 agent 时，在引导里配置 DeepSeek Harness，保存并测试连接。也可以跳过这一步，先管理岗位和简历。

## 从第一个岗位开始

| 在工作台里 | 你可以做什么 |
| --- | --- |
| 档案与简历 | 填写地区、可入职时间和求职偏好，导入适合不同方向的简历版本。 |
| 岗位库 | 保存原始招聘入口，核对资格，合并重复发现的职位。 |
| 执行台 | 选择本次申请的材料，预填表单，把缺失的信息留给本人确认。 |
| 反馈 | 将确认页面、邮件回执和后续回复关联到岗位。没有确认的提交保留为待核实，避免重复投递。 |

## 本地数据与外部连接

候选人档案、材料和申请历史保存在本机，卸载程序会保留用户数据。启用招聘网站、邮箱或模型服务时，所选服务会处理相应操作。公开问题报告请隐去联系方式、简历内容和凭据。

## 为 agent 接入工作区

[Agent 使用说明](docs/agent/AGENT_README.md)覆盖连接验证、去重、草稿授权和回执记录。只做材料准备时，agent 可以停在草稿阶段，留给用户核对岗位、收件方和附件。
