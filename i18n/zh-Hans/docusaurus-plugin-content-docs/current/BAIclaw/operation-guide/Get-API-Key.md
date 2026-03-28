---
sidebar_position: 2
---
# 获取 API 密钥

要使用 BAIclaw，你需要从 [BAI](https://chat.b.ai/chat) 获取 API 密钥。该密钥用于验证你的请求并授予访问大语言模型能力的权限。

## 所需条件

- 一个 [BAI](https://chat.b.ai/chat) 账号（免费注册）

## 步骤 1：登录 BAI

1. 打开浏览器，访问 [BAI](https://chat.b.ai/chat)
2. 使用现有账号登录，或注册一个新账号

## 步骤 2：创建 API 密钥

1. 在左侧边栏找到 **API** 部分
2. 点击打开 API 管理页面
3. 点击 **Create API Key** 按钮
4. 为你的密钥起一个描述性名称（例如："BAIclaw Desktop"）
5. 立即复制生成的密钥 —— 它只会显示一次

![](./assets/BAI.jpeg)

## 步骤 3：在 BAIclaw 中配置

1. 打开 BAIclaw，进入 **Models** 页面
2. 将复制的 API 密钥粘贴到 BAI API Key 字段中
3. 点击 **Save** 或 **Verify** 确认连接

:::danger[安全警告]
**请始终妥善保管你的 API 密钥：**
- API 密钥是访问 BAI 模型接口的重要凭证，切勿与第三方分享。
- 如果泄露，未授权方可能会消耗你的配额，导致意外费用。账户持有人需承担由此产生的任何损失。
- 如果你怀疑 API 密钥已被泄露，请立即在 BAI 控制台中删除该密钥，创建新密钥，并在 BAIclaw 中更新。
:::

## 验证

要验证你的 API 密钥是否正常工作：

1. 进入 BAIclaw 的 **Chat** 页面
2. 发送一条简单的测试消息（例如："Hello"）
3. 如果收到回复，说明你的 API 密钥已正确配置

:::tip[连接问题？]
如果测试时遇到错误：
- 仔细检查 API 密钥是否复制完整（没有多余空格）
- 确保网络连接稳定
- 确认你的 BAI 账户有可用额度
:::

## 下一步

配置好 API 密钥后：
- [设置你的第一个智能体](../BAIclaw-Introduction.md#multi-agent-collaboration)
- 探索可用于扩展能力的 [技能](../BAIclaw-Introduction.md#plug-and-play-skills)
kills)
