# AIコーディングエージェントの推奨案

先に結論です。  

**Claude Code (Anthropic) または Codex CLI (OpenAI) のどちらかを導入し、任意で GitHub Copilot CLI を使えるようにする**

- 選定のポイント
    - 高機能なモデルが利用できること
    - 現在主流である高速なCLI型エージェントの機能を重視
        - [AIコーディングエージェントの歴史と進化](/docs/history_of_ai_agents.md)
    - ハーネスエンジニアリングを実現できる機能が揃っていること
        - [AIエージェントのシステム要件とハーネス・エンジニアリング](/docs/harness_engineering.md)
    - メインの利用制限回避目的、IDE型のサジェストが欲しい、メインモデル以外を使いたいなどの要望のため、GitHub Copilotを任意で利用可能とする
- 選定されなかったツールについて
    - Cursor, Devin
        - コーディング専用のイメージでビジネスチーム側に展開がしづらい
        - 金額を払うならコーディングエージェントだけでなくAnthropic, OpenAIのように他の注目機能があった方が良い
    - Gemini CLI / Gemini Code Assist
        - Anthropic, OpenAIと比べるとモデルのコーディング性能が低い
        - Gemini APIは安いと言われているが、Geminiの個人プランはコストパフォーマンスが悪い（但し、Gemini Code Assistは不明）
- その他参考情報
    - [AIコーディングCLIツール ロングリスト評価レポート](/docs/longlist.md)

