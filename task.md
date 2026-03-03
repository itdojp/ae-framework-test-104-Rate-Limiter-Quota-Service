# Task (Benchmark) — Rate Limiter / Quota Service

本リポジトリは input-only spec repo です。  
この `task.md` は、別リポジトリ/別工程（出力側）で生成・実装すべき内容を定義します。

## Inputs (this repo)

- `spec/`
- `assumptions.md`

## Outputs (generated elsewhere)

- 仕様に基づく Rate Limiter / Quota Service の実装
- 機械可読な API 契約（例: OpenAPI）
- （任意）テスト/CI

## Acceptance Criteria (minimum)

- Token Bucket + Fixed Window の基本要件が成立する（仕様の範囲）
