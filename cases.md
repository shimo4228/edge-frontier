# cases — 限界突破事例の台帳

狙い: AI 活用の**やり方**が常識外な事例を集め、事例ごとに「なぜそうしたか / 何が可能になり / 何が壊れ / 人間の側に何が起きたか」の学びを抽出する。規模の大きさ単独では載せない — 自然発生の端(本人の目的で強度を上げた結果)を優先し、製造された端(順位表やネタ作りが端を目的化させたもの)は載せる場合その旨をメモに明記する。

主な流入元: daily-research `edge` line(毎日)。面白い事例が無い日はそれでよい(発見ノルマなし)。

## 収集状況

- 2026-08-20 開始、0 件から。既知の有名事例は網羅しない — 学びが抽出できるものだけを載せる
- 2026-08-20 初回 ingest (edge line レポート 2 本より): 台帳 4 件 — 突破+崩壊 1 / 境界例 (製造された端) 2 / 生活認知 1

## 台帳

| 発見日 | 発表日 | 主体・場 | 言語 | 型 | URL / メモ |
|---|---|---|---|---|---|
| 2026-08-20 | 2026-03-12 | RJ「The $200/Month CEO」(フィリピン・セブ、buttondown / DEV Community) | EN | 突破+崩壊 | https://buttondown.com/the200dollarceo/archive/grove-my-ai-venture-sent-240-emails-and-made-0-so/ — 月 $200 の Claude Max 1 契約で 7 体の agent に複数事業を運営させ、1 体 (Grove) に独自メールアドレスと成約までの全権を付与。3 週間・コールドメール 240 通・売上 $0 で撤退。**検死報告自体を Grove が執筆し本人未レビュー** (署名に明記) — 一人称の悔恨がありながら書き手が人間か判定不能。運用全体像は https://dev.to/the200dollarceo/i-run-my-businesses-with-7-ai-agents-for-200month-heres-what-actually-happens-5cdm (2026-02-21、03-12 改訂) |
| 2026-08-20 | 2026-04-09 | Meta 社内順位表「Claudeonomics」(Fortune 報道) | EN | 境界例 (製造された端) | https://fortune.com/2026/04/09/meta-killed-employee-ai-token-dashboard/ — 85,000 人超の消費を順位化、個人最高 281B トークン/30日 (Claude 価格換算 $1.4M 超)。"Token Legend" 等の称号が消費自体を報酬 → 端にいた理由が本人の言葉で読めず、報道 2 日後に順位表削除で追試不能。入場条件を満たさない標本として記録 |
| 2026-08-20 | 2026-05-29 | Amazon 社内順位表「Kirorank」(FT 初報、the decoder / BI 経由) | EN | 境界例 (製造された端) | https://the-decoder.com/amazon-kills-internal-ai-leaderboard-after-employees-gamed-it-with-pointless-tasks/ — 無意味タスクによる gaming で閉鎖。「Don't use AI just to use AI」(https://finance.yahoo.com/sectors/technology/articles/amazon-says-shut-down-token-161016125.html)。Claudeonomics と同型 2 例目 — 順位表が端を製造して自壊するパターン |
| 2026-08-20 | 2026-05-07 | なみすけ (note、2026-03-24 執筆) | JA | 生活認知 | https://note.com/namisuke_note/n/n62962d5684a4 — 「AI に人生を丸投げしそうになった」一人称。サムネイル/タイトル等の全面委譲で試行回数 (自分で試して外す経験) が消失した自覚と揺り戻し。日本語圏の生活認知系 1 例目 |

型の分類(仮 — 増えたら再編): **突破** = 常識外のやり方で成果を出している / **崩壊** = やりすぎの果ての failure mode・post-mortem / **生活認知** = 開発以外の全面 AI 委譲と人間側の変容。1 事例が複数型に跨がる場合は主たる学びの側に置く。**境界例** = 入場条件 (how が本人の言葉で読める) を満たさないが端の生態を示すため記録するもの — 製造された端など。その旨を必ずメモに書く。
