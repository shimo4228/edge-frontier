# Reading List — エッジ活用の先行論考

- 収集開始: 2026-08-20。一次照合できていないエントリは `[unverified]` を付け、照合でき次第外す
- LLM 界隈の論考は陳腐化が速い。日付ごと読むこと
- 2026-08-20 初回 ingest: edge line レポート 2 本 (metrics-manufactured-edge / agent-wrote-the-autopsy) より。URL は run 内 WebFetch 解決済み
- 2026-08-21 ingest: edge line レポート 1 本 (cognitive-surrender-selection-bias) より +7 本。URL は ingest run 内で再度 WebFetch 到達確認済み

## 1. 突破系実践記

- **I Run My Businesses With 7 AI Agents for $200/Month. Here's What Actually Happens.** — RJ「The $200/Month CEO」(2026-02-21、2026-03-12 改訂)
  https://dev.to/the200dollarceo/i-run-my-businesses-with-7-ai-agents-for-200month-heres-what-actually-happens-5cdm
  月 $200 の Max 契約 1 本で 7 体の agent に複数事業を運営させる個人の運用全体像。cases.md 台帳 1 件目の本体。newsletter 側 (buttondown) に agent 別のレポートが続く
- **Building a C compiler with a team of parallel Claudes** — Nicholas Carlini, Anthropic Engineering (2026-02-05)
  https://www.anthropic.com/engineering/building-c-compiler
  並列 Claude チームで C コンパイラを構築する実践記。組織相当の output を 1 人 + agent 群で出す型の一次記録
- **How AI Became My Production Company** — Dominic Frisby, The Flying Frisby (2026-05-31)
  https://www.theflyingfrisby.com/p/how-ai-became-my-production-company
  記事画像とミュージックビデオを Midjourney / Runway / Neural Frames で制作し、文章は ChatGPT 主力・Grok を時事と市況の感情分析に、Claude は調査拒否で降格と用途を書き分ける個人の制作パイプライン。ただし編集の "Goat" と歴史調査の Sam は人間として残す (「まだ機能する脳が必要だ」)。同じ書き手の生活認知系 (節 3) と対で読む

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
- **I've Outsourced My Judgement to AI. So Has Everyone Else.** — Dominic Frisby, The Flying Frisby (2026-05-24)
  https://www.theflyingfrisby.com/p/ive-outsourced-my-judgement-to-ai
  離別時の WhatsApp 全履歴投入を含む全面委譲の一人称。脳の萎縮と「間違った決定から学ぶ経験」の喪失を自分で数え上げたうえで、56 歳という残り時間を根拠に揺り戻さないと宣言する。cases.md 5 件目の本体
- **私が毎日3時間AIに人生相談している理由と、依存しないために決めていること** — とうら, note (2026-01-17)
  https://note.com/ra_riray/n/n2a2b3428744e
  HSP 気質による人間相手の思考制約を理由に AI を選んだ一人称と、依存回避の自作ルール 6 つ。「最後の『問い』は無視すること」は AI 側の継続利用誘導を名指しした対抗運用。cases.md 6 件目の本体
- **Thinking — Fast, Slow, and Artificial: How AI is Reshaping Human Reasoning and the Rise of Cognitive Surrender** — Steven Shaw & Gideon Nave, Wharton Executive Education (2026-05)
  https://executiveeducation.wharton.upenn.edu/thought-leadership/wharton-at-work/2026/05/thinking-fast-slow-and-artificially/
  cognitive surrender = 「自分の推論の代わりに AI の答えを吟味せず受け入れること」で、**転移が起きたと認識しないまま**自分の決定として採用する点が cognitive offloading (電卓・地図) との違い。参加者 1,300 人超・約 10,000 試行で、AI 正答時 +25pp / 誤答時 −15pp。**自覚の欠如が定義に入る**ため、生活認知系の一人称記録が誰を拾えて誰を拾えないかの理論的基準になる。論文本体 (SSRN abstract_id=6097646) は 403 で未取得
- **意思決定をAIに委ねる人々…「認知的降伏」に専門家が警鐘** — Thibault Spirlet, Business Insider Japan (2026-07-05)
  https://www.businessinsider.jp/article/2606-ai-reliance-decision-making-life-advice-cognitive-surrender/
  注意: **二次 (英語原文は本 run で取得不可、翻訳層あり)**。元ソフトウェアエンジニア Carolyn Yoo が業界離脱の判断を Claude に毎日 2〜3 時間相談し、その後 瞑想・日記・対話へ離脱した軌跡。生活認知系の 3 つ目の型 (委ねてから離脱) だが本人媒体に未到達のため cases.md には未収載
- **Wharton researchers coined 'cognitive surrender' to describe what happens when people let AI think for them** — Ana Maria Constantin, The Next Web (2026-06-20)
  https://thenextweb.com/news/wharton-cognitive-surrender-ai-chatbots-decisions-moot-app
  注意: **二次**。上記 BI と独立に Yoo を報じ、チャットボットを「セラピストとライフコーチの組み合わせ」と扱っていたとする。表記は "Carolyn Yoo" (BI 日本語版は「キャロリン・ユー」) — 翻訳層で固有名詞の同定可能性が落ちる例

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
- **Running multiple AI Agents in parallel reminds me of working in Myanmar** — Gijs Verheijke, Playbook Musings (2026-01-14)
  https://gijs.substack.com/p/running-multiple-ai-agents-in-parallel
  並列数は 1〜3 で**端ではない** (台帳の入場条件からは外れる) が、並列運用のコストを人間側から測る比喩として読む価値がある — ミャンマーで 6Mbps を 30 人で分け合っていた頃と同じ作業感で、「すべての agent の状態を頭の中に保持しなければならず、注意を要するものへ次々とプロンプトを打ちに戻る絶え間ない文脈切り替えは brutal だ」。自己評価も率直で「output は確実に増えている。それがどの程度 slop なのかは open question だ」。並列数を指標にすることへの一人称の反証材料
