# Poros — Stateful AI Job Search and Application Agent Skill

**Find a way. Follow it through.**

An end-to-end AI agent skill for job discovery, eligibility checks, CV tailoring, applications, and follow-ups.

一个从职业定位、找岗、资格核验、简历匹配，到真实投递与后续跟踪的统一 Agent Skill。它可以从任何阶段开始或恢复；不会在用户已经准备好投递时反复重做职业规划。

## Install / 安装

把这个仓库克隆或下载为 `poros` 文件夹，放入你所使用的 Agent 的 skills 目录，并按宿主平台的说明启用 `SKILL.md`。

> A skill defines agent behavior; it does not grant access to a browser, recruitment accounts, persistent storage, or external submission tools. Actual application actions require the host environment's capabilities and user authorization.

## What it covers / 功能范围

- Career direction and employer-oriented job targeting / 职业定位与真实岗位筛选
- Live job and regional eligibility checks / 实时岗位及跨地区资格核验
- Evidence-based CV selection and tailoring / 基于事实的简历匹配与定制
- Authorized form filling, submission, and status verification / 经授权的申请执行与提交状态核实
- Application tracking, interview preparation, and offer review / 投递追踪、面试准备与 Offer 比较

The skill emphasizes truthful identity and location information, candidate-led assessments, privacy and scam checks, evidence-based status reporting, and avoiding unnecessary preparation loops.

## Validation / 验证范围

Developed from a real-world job application workflow that successfully submitted three applications. The packaged skill itself has not yet been independently validated across agent environments.

基于一次实际求职流程整理，该流程成功提交了三份申请；封装后的 Skill 尚未经过跨 Agent 环境的独立验证。

## License

MIT — see [LICENSE](LICENSE).
