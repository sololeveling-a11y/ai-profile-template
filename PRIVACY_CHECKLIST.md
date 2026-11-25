# 提交前与定期复查清单

在你自己的私有副本 `<your-username>/<your-private-repo>` 里使用这份清单。勾选可以留在本地，也可以提交。勾选本身不能代替你打开页面看过。

本仓库没有脚本，也没有 GitHub Actions。没有任何自动化会替你完成本清单。规则说明见 [AGENTS.md](AGENTS.md)，红线摘要见 [README.md](README.md) 与 [README_EN.md](README_EN.md)。

文档链接指向 GitHub 的英文文档。

## 每次提交前

- [ ] 这次提交的是我的私有档案 `<your-username>/<your-private-repo>`，不是公开模板 [sololeveling-a11y/ai-profile-template](https://github.com/sololeveling-a11y/ai-profile-template)
- [ ] 仓库可见性仍是 Private。若创建时无法选择 Private，先停下，不要建成 Public 再打算以后改
- [ ] Settings 里的 GitHub Pages 保持关闭
- [ ] 协作者和集成授权里没有我意料之外的账号。不再使用的 AI 连接已撤销
- [ ] 我看过本次 diff
- [ ] diff、提交说明和远程地址里没有密码、令牌、API 密钥、私钥、cookie 或会话标识
- [ ] 远程地址是 `git@github.com:<your-username>/<your-private-repo>.git` 或 `https://github.com/<your-username>/<your-private-repo>.git`，其中没有令牌
- [ ] 没有支付信息、银行卡号或证件号码
- [ ] 没有精确到门牌的住址
- [ ] 没有他人的私人信息
- [ ] 没有未经删减的原始聊天记录
- [ ] 没有把 [examples/demo-profile.md](examples/demo-profile.md) 里的虚构人物写成我的事实
- [ ] [projects.md](projects.md) 的状态没有写得比事实更满

写入档案时，先使用 [prompts/update.md](prompts/update.md)，看过变更计划再确认。

## 定期复查

- [ ] 在仓库 Settings 中再次确认可见性为 Private。说明见 [Setting repository visibility](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility)
- [ ] GitHub Pages 没有被打开
- [ ] 若账号或组织提供密钥扫描与推送保护，保持你期望的开启状态。说明见 [secret scanning](https://docs.github.com/en/code-security/concepts/secret-security/secret-scanning) 与 [push protection](https://docs.github.com/en/code-security/concepts/secret-security/push-protection)。未提供时，仍靠人工查看 diff
- [ ] 过时事实已标为历史，没有继续被当作现行规则
- [ ] 公开作品集仓库里没有误推这份私有档案
- [ ] `examples/` 若还留着，里面仍然只有标明虚构的内容

## 发现秘密已经写入之后

1. 停止继续推送。
2. 不要把秘密贴进 issue、聊天或新的提交说明来演示问题。
3. 作废并更换已经暴露的密钥。只在最新文件里删掉一行，并不能消除旧提交里的副本。
4. 按 GitHub 文档处理已进入历史的敏感数据：[Removing sensitive data from a repository](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository)。

相关：[prompts/update.md](prompts/update.md) · [prompts/migrate.md](prompts/migrate.md)
