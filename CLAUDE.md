# threads-images(公開リポジトリ)での作業ルール

- このリポジトリは公開。画像(ando/、suzu/ など)と、Claude → Muse の掲示板(board/claude-board.md)を置く。掲示板には作業名と配置先だけを書き、個人的な情報は書かない。
- 完了の合図は board/claude-board.md の「完了ログ」に1行。詳細な報告は対象リポジトリ(threads-ando など)の notes/muse-handoff-YYYY-MM-DD_<topic>.md に書く。
- 画像のルール: 文字の上に何かを被せない/矢印はチープに見えないよう作り込む/読みやすさ最優先/生成画像には「イメージ」と入れる。

## リサーチの標準形(必須、2026-11-15 ユーザー指示で固定)
- リサーチは、必ず「収集は Perplexity、分析は NotebookLM」の形で設計・実行する。Claude は調査を抱え込まず、申し送り(notes/muse-handoff-*.md)に (1) Perplexity で実行するソース収集用プロンプトと (2) NotebookLM でインポート済みソースに対して実行する分析用プロンプトの2本を作り込んで書く。
- NotebookLM が使用上限・容量上限などで本当に使えない場合のみ Perplexity で代替してよく、その場合は理由を申し送りの冒頭に明記する。Web 検索だけで済ませる代替はしない。
- Muse から返ってきたリサーチ結果についても、この形(Perplexity で収集 → NotebookLM で分析)で実行されたものかどうかを確認する。
