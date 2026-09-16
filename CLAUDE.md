# CLAUDE.md

このファイルはClaude Codeが本プロジェクトのセッション開始時に自動で読み込む、作業用コンテキストです。

## セッション開始時の必須アクション

**仕様の正本はObsidianです。** セッション開始時に `mcp__obsidian__read_note` で以下を必ず読み込み、最新の仕様を把握してから作業を始めること。

- パス: `10_Projects/claude_animation/仕様.md`

このCLAUDE.md・README.mdは補助的な要約に過ぎない。**仕様に変更が生じた場合は、CLAUDE.md/README.mdではなく上記Obsidianノートを更新する。**

## プロジェクト概要

Claude Code CLI用の常駐デスクトップペットウィジェット。Claude Codeが応答生成中は「考え中」、応答完了で「笑顔」になるキャラクターを画面右下に表示する。OpenAI Codex CLIの公式ペット機能（`/pet`）に相当する体験を自作するのが目的。キャラクター画像（GIF）はCodex側で用意し、Claude側はElectronアプリ本体を実装する分担。

## 現在のステータス

仕様確定フェーズ（詳細はObsidianノート参照）。コードは未着手。

## 作業時の留意事項

- ユーザーとのやり取りは日本語で行う
- 大きな設計判断（フレームワーク選定など）は実装前にユーザーに確認する
- 仕様の変更・追記はObsidianノート（`10_Projects/claude_animation/仕様.md`）に反映する
