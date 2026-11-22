# Muse 命令行直做 · Muse CLI Direct

## 核心原则

- 把技能当作一份给 Muse 读的 Markdown 说明书，而不是软件。

- 直接调用 Muse 已连接的命令行工具完成任务，不要先装别人写的技能包。

- 每做一步都先核对原始来源，再给结论。

- 对外分享之前先脱敏，删掉身份证号、电话、地址和卡号这类信息。

## 八个功能

### 重要邮件检查

- 查 Gmail 和 Hotmail 当天的新邮件，跳过促销，只留需要回复的。

- 用 Gmail 连接器查 Gmail，用 Outlook Mail 连接器查 Hotmail。

- 先报结论，再列每封要回的邮件和下一步。

### 每周复盘

- 列出本周待办、截止日和等回音的线程，逐项核对最新状态。

- 沉默当作未确认，不要因为对方没回就断定已处理。

- 截止日已过但状态未确认时，如实写状态未知。

### 对外分享先脱敏

- 发文件或截图之前，全文搜一遍身份证号、电话、地址和卡号。

- 搜到就删掉或打码，删完再发。

- 只举类别，不在正文里写真实号码。

### 发货和交付前核验

- 按清单逐项核对，不凭记忆说已经发了。

- 每一项都要有证据，例如快递单号、签收记录或回信原文。

- 对不上的地方先标出来，再问用户。

### 财务对账

- 把发票、收据和银行流水三方对上，差额标出来。

- 先算到手总价，再给购买或付款结论。

- 金额、日期和商家名称以原始单据为准。

### 历史价检查

- 查历史价、现价和到手总价，判断现在是不是高点。

- 报价要验到结账页或原始来源，半路结论标为未核实。

- 报错时公开更正，不要悄悄改掉。

### 记忆整理

- 删过期、冲突和重复的旧记录，只留还有效的。

- 改掉的说法要注明原来写错了什么，现在改成什么。

- 不把证件号码、密码和卡号写进记忆。

### 发布前核实

- 每个说法回原出处核对一次，没来源就不写。

- 网址、仓库名和邀请码不要直接放进公开发布的内容。

- 发布前再通读一遍全文，确认没有敏感信息。

## 直接复制用的提示词

- 查 Gmail 和 Hotmail 今天的新邮件，跳过促销。

- 把这份文件发前脱敏，搜身份证、电话、地址。

- 核对这三个价格，算到手总价再给结论。

## 避坑

- 带 --dangerously-skip-permissions 的不要装。

- 满篇邀请码和推广链接的不要装。

- 教导出登录 Cookie 或自动对外发消息的不要装。

- 技能包省的是写提示词的功夫，不是能力，能力本来就在命令行里。

## Available connectors

- [Gmail](/opt/hatch/connectors/gmail/CONNECTOR.md) for searching and reading Gmail.

- [Outlook Mail](/opt/hatch/connectors/outlook_mail/CONNECTOR.md) for searching and reading Hotmail and Outlook mail.

- [Google Drive](/opt/hatch/connectors/google_drive/CONNECTOR.md) for finding and reading files in Google Drive.

- [Dropbox](/opt/hatch/connectors/dropbox/CONNECTOR.md) for finding and reading files in Dropbox.

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Alternatives for better results

- 当一件事要反复做时，先把方法存成这份 skill，再让每次对话直接调用它。

- 当只需要做一次时，直接在对话里做，不要为了存档多绕一步。
