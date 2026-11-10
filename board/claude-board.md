# Claude 作業掲示板（Claude → Muse 連絡用）

Claude が作業を終えたら、このファイルの「完了ログ」に1行追記して commit してください。
- 2026-11-11 01:3x 縦動画FB相談の依頼プロンプト作成 完了 → threads-ando: notes/muse-handoff-2026-11-11_video-fb-prompt.md
Muse がこのファイルの変更を検知して、新しい完了ログがあればユーザーに知らせます。

注意：このリポジトリ（threads-images）は公開です。個人的な情報や未公開の認証情報は書かず、作業名と配置先だけを書いてください。

## 書き方
- 完了した瞬間に、その作業について1行で追記する
- 形式：`- [完了] YYYY-MM-DD HH:MM JST / 作業名 / 配置先や成果物の場所 / ユーザーの確認が要るかどうか`
- 詳細な完了報告は、対象リポジトリの `notes/muse-handoff-YYYY-MM-DD_<topic>.md` に必ず書く（成果物・変更点・保留・確認事項・次に Muse がやること）。完了ログの行には、そのリポジトリ名と申し送りファイルのパスを含める
- claude.ai のチャット返信は短くし、長い報告は申し送りファイルに書く
- 作業中は「作業中ログ」に書いてよい。終わったら完了ログへ移す
- 質問や確認待ちが発生したら「確認待ち」に書く

## 完了ログ
- [完了] 2026-11-10 23:02 JST / KFC八戸・南郷 テキスト仕上げ・画像3枚 / threads-ando: queue/ando-kfc-nango.json(pending_approval)、notes/muse-handoff-2026-11-10_kfc.md、notes/facts.md F085 ・ threads-images: ando/202611/ando-20261112-kfc-{main,r3,map}.png / ユーザーの承認が要る(承認後に approved へ)
- [完了] 2026-11-10 23:13 JST / テキスト投稿案X1〜X10 仕上げ(承認待ち7本: X1灯油・X2焼津・X3千歳・X4ホンダ・X6八代・X7データセンター・X9早島) / threads-ando: queue/ando-x0{1,2,3,4,6,7,9}-*.json(pending_approval)、notes/muse-handoff-2026-11-10_batch.md、notes/facts.md F086〜F100 ・ threads-images: ando/202611/ando-x0{1..7,9}-*-main.png / ユーザーの承認が要る(出典名の補足と社名の数の判断を含む)
- [完了] 2026-11-10 23:13 JST / テキスト投稿案 保留3本(X5ミツバチ・X8印西・X10釜山) / threads-ando: drafts/2026-11-10_x05_bees.json・x08_inzai.json・x10_busan.json(queue には未投入) / 投稿するなら追加の根拠が要る(申し送り参照)
- [完了] 2026-11-11 00:15 JST / 止まっているもの・待ち状態の一覧とサイドチャットの提案 / threads-ando: notes/muse-handoff-2026-11-10_inventory.md / ユーザーの判断が要る(承認待ち8本・古いheldの扱いほか)
- [完了] 2026-11-11 00:25 JST / 週2回の発見回用プロンプト(収集Perplexity・分析NotebookLM) / threads-ando: prompts/neta-discovery.md、notes/muse-handoff-2026-11-11_neta-discovery.md / 軽い確認のみ(候補数と比率)
- [完了] 2026-11-11 00:55 JST / 出典補完を受けた直し(X1灯油の数字・X9稼働の表現・X7主体・X10を下書きへ・X5の年) / threads-ando: notes/muse-handoff-2026-11-11_source-fixes.md ・ threads-images: ando/202611/ando-x0{1,7,9}-*-main.png 差し替え / ユーザーの判断が要る(X1のフックの軸、X10下書き)
- [完了] 2026-11-11 01:10 JST / すず ask型3本・opinion型3本の書き直し(型C4・D1・A1) / threads-autopilot: queue/20261111-rw0{0..5}-*.json(pending_approval)、notes/muse-handoff-2026-11-11_ask-rewrite.md / ユーザーの承認が要る・単価は要追加調査

## 作業中ログ
（まだなし）

## 確認待ち
- 2026-11-10 / X1〜X10の出典名・URLが未受領(ファクトカードの出典欄が仮)。X1の2月の灯油代は札幌市の数字か。X3(2社)・X7(3社)の社名を減らすか。詳細は threads-ando の notes/muse-handoff-2026-11-10_batch.md
- 2026-11-11 / すず書き直し6本の承認。rw04の表カード画像を付けるか。prompts/system.md に残っているask/opinionの配分・問いかけで締める指示を消すか。型B・単価の列は根拠がない(要追加調査)。詳細は threads-autopilot の notes/muse-handoff-2026-11-11_ask-rewrite.md
