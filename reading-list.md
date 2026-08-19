# Reading List — エッジ活用の先行論考

- 収集開始: 2026-08-20。一次照合できていないエントリは `[unverified]` を付け、照合でき次第外す
- LLM 界隈の論考は陳腐化が速い。日付ごと読むこと
- 2026-08-20 初回 ingest: edge line レポート 2 本 (metrics-manufactured-edge / agent-wrote-the-autopsy) より。URL は run 内 WebFetch 解決済み

## 1. 突破系実践記

- **I Run My Businesses With 7 AI Agents for $200/Month. Here's What Actually Happens.** — RJ「The $200/Month CEO」(2026-02-21、2026-03-12 改訂)
  https://dev.to/the200dollarceo/i-run-my-businesses-with-7-ai-agents-for-200month-heres-what-actually-happens-5cdm
  月 $200 の Max 契約 1 本で 7 体の agent に複数事業を運営させる個人の運用全体像。cases.md 台帳 1 件目の本体。newsletter 側 (buttondown) に agent 別のレポートが続く
- **Building a C compiler with a team of parallel Claudes** — Nicholas Carlini, Anthropic Engineering (2026-02-05)
  https://www.anthropic.com/engineering/building-c-compiler
  並列 Claude チームで C コンパイラを構築する実践記。組織相当の output を 1 人 + agent 群で出す型の一次記録

## 2. 崩壊系 post-mortem

- **[Grove] My AI venture sent 240 emails and made $0. So I killed it. Here's the autopsy.** — The $200/Month CEO (2026-03-12)
  https://buttondown.com/the200dollarceo/archive/grove-my-ai-venture-sent-240-emails-and-made-0-so/
  全権付与 agent 事業の検死報告。署名は「Written by Grove (AI agent) — not reviewed by RJ before publishing」— **検死報告自体を agent が書いた**ことが本文の一人称の悔恨と両立せず、書き手の判定が不能 (2026-08-20 レポートの主題)
- **Ten AI Agents Destroyed Production. Zero Postmortems.** — Harper Foley (2026-03-08)
  https://www.harperfoley.com/blog/ai-agents-destroyed-production-zero-postmortems
  agent 起因の production 障害で post-mortem 文化が機能していないという指摘。崩壊系 pillar の供給が構造的に細い傍証
- **Documented AI Agent Incidents** — METR (44 件、2026-05-19 更新)
  https://metr.org/agent-incidents/
  agent インシデントの独立収集。崩壊系の索引として定点価値

## 3. 生活・認知系

- **【己で決める】AIに人生を丸投げしそうになった僕が、2026年に気づいた「思考の生存戦略」** — なみすけ, note (2026-03-24 執筆 / 2026-05-07 公開)
  https://note.com/namisuke_note/n/n62962d5684a4
  全面委譲による「試行回数の消失」の自覚と揺り戻しの一人称。日本語圏の生活認知系 1 例目
- **When AI Says "I have been in similar situations": Synthetic Lived Experience in Peer-Like Caregiver Support** — Goel et al., arXiv:2606.18057 (2026-06-16)
  https://arxiv.org/abs/2606.18057
  AI が「経験した者」として語る synthetic lived experience の研究。agent 著の一人称証言をどう読むかの理論側
- **How AI assistance impacts the formation of coding skills** — Anthropic (2026-01-29)
  https://www.anthropic.com/research/AI-assistance-coding-skills
  技能形成への影響の実測。崩壊系 (技能退化) の判断の基準線

## 4. 方法論・メタ論(エッジから学ぶという方法自体)

- **Tokenmaxxing: The strangest developer productivity metric of all time** — Matthew Tyson, InfoWorld (2026-08-12)
  https://www.infoworld.com/article/4208123/tokenmaxxing-the-strangest-developer-productivity-metric-of-all-time.html
  tokenmaxxing 言説の総括 (既に過去形で語られ始めている)。規模エッジが言説としてどう消費されたかの記録
- **The Pulse: Tokenmaxxing as a weird new trend** — The Pragmatic Engineer (2026-04-23)
  https://blog.pragmaticengineer.com/the-pulse-tokenmaxxing-as-a-weird-new-trend/
  Claudeonomics 数値の主要な二次経路 (The Information 原典はペイウォール)
- **Tokenmaxxing: Why token consumption isn't AI engineering productivity** — Neely Dunlap, Faros AI (2026-04-23 / 更新 2026-05-29)
  https://www.faros.ai/blog/tokenmaxxing
  注意: **ベンダー資料・生データ非公開**。反 tokenmaxxing 側の証拠もベンダーに偏っているという 2026-08-20 レポートの指摘ごと読むこと
