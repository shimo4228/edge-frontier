# Plan: 今朝の自動 ingest commit を push

## Context
2026-08-22 08:30 の launchd 無人実行（初回）が成功し、commit `e9d2835`
"Ingest edge-line reports 2026-08-22 (auto, opus)" がローカル main に `ahead 1` で残っている。
内容: cases.md +1（Brett Codes、崩壊+生活認知）、reading-list.md +4。fact-check pass
（19 主張 / inaccurate 0 / unverifiable 1 = 引用の verbatim 未確定のみ）。
設計どおり push は人間の判断で、ユーザーが「PUSH」と指示した。

## Steps
1. `git -C ~/MyAI_Lab/edge-frontier push origin main`
   （sandbox 無効化が必要 — skill git-workflow の既知事項）

## Verification
- `git status -sb` が `## main...origin/main` と同期を示す
