# Claude 作業掲示板（Claude → Muse 連絡用）

Claude が作業を終えたら、このファイルの「完了ログ」に1行追記して commit してください。
- [決定] 2026-11-12 23:22 JST / LINEスタンプ第2弾はA ねむらし・C のびぴの2案で進める(ユーザー決定)。次は Muse が名前・類似の確認 → 制作依頼 / threads-ando: notes/muse-handoff-2026-11-12_stamp-wave2-design.md
- [完了] 2026-11-12 23:10 JST / すず新規12本(pending_approval)+system.mdのask/opinion掃除 / threads-autopilot: notes/muse-handoff-2026-11-12_new-drafts.md / ユーザーの判断が要る(商品名の本文表記・12本承認・ナチュリエ正式名・F026/F029の重複)
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
- 2026-11-12 すず承認後対応（正式名・規則追記・nd07/08表カード） threads-autopilot: notes/muse-handoff-2026-11-12_approval-followup.md
- 2026-11-12 縦動画ホタテ60秒FB完了（絵コンテ表・指摘リスト・台本363字・要追加調査プロンプト） threads-ando: notes/muse-handoff-2026-11-12_video-fb.md
- [完了] 2026-11-10 23:02 JST / KFC八戸・南郷 テキスト仕上げ・画像3枚 / threads-ando: queue/ando-kfc-nango.json(pending_approval)、notes/muse-handoff-2026-11-10_kfc.md、notes/facts.md F085 ・ threads-images: ando/202611/ando-20261112-kfc-{main,r3,map}.png / ユーザーの承認が要る(承認後に approved へ)
- [完了] 2026-11-10 23:13 JST / テキスト投稿案X1〜X10 仕上げ(承認待ち7本: X1灯油・X2焼津・X3千歳・X4ホンダ・X6八代・X7データセンター・X9早島) / threads-ando: queue/ando-x0{1,2,3,4,6,7,9}-*.json(pending_approval)、notes/muse-handoff-2026-11-10_batch.md、notes/facts.md F086〜F100 ・ threads-images: ando/202611/ando-x0{1..7,9}-*-main.png / ユーザーの承認が要る(出典名の補足と社名の数の判断を含む)
- [完了] 2026-11-10 23:13 JST / テキスト投稿案 保留3本(X5ミツバチ・X8印西・X10釜山) / threads-ando: drafts/2026-11-10_x05_bees.json・x08_inzai.json・x10_busan.json(queue には未投入) / 投稿するなら追加の根拠が要る(申し送り参照)
- [完了] 2026-11-11 00:15 JST / 止まっているもの・待ち状態の一覧とサイドチャットの提案 / threads-ando: notes/muse-handoff-2026-11-10_inventory.md / ユーザーの判断が要る(承認待ち8本・古いheldの扱いほか)
- [完了] 2026-11-11 00:25 JST / 週2回の発見回用プロンプト(収集Perplexity・分析NotebookLM) / threads-ando: prompts/neta-discovery.md、notes/muse-handoff-2026-11-11_neta-discovery.md / 軽い確認のみ(候補数と比率)
- [完了] 2026-11-11 00:55 JST / 出典補完を受けた直し(X1灯油の数字・X9稼働の表現・X7主体・X10を下書きへ・X5の年) / threads-ando: notes/muse-handoff-2026-11-11_source-fixes.md ・ threads-images: ando/202611/ando-x0{1,7,9}-*-main.png 差し替え / ユーザーの判断が要る(X1のフックの軸、X10下書き)
- [完了] 2026-11-11 01:10 JST / すず ask型3本・opinion型3本の書き直し(型C4・D1・A1) / threads-autopilot: queue/20261111-rw0{0..5}-*.json(pending_approval)、notes/muse-handoff-2026-11-11_ask-rewrite.md / ユーザーの承認が要る・単価は要追加調査
- [完了] 2026-11-12 00:50 JST / 新規下書き2件(神戸空港島US-2・明治の準チョコ化、画像なし) / threads-ando: notes/muse-handoff-2026-11-11_new-drafts.md、drafts/2026-11-12_us2_kobe.json・2026-11-12_meiji_junchoco.json / ユーザーの判断が要る(下書きのOK)
- [完了] 2026-11-12 01:40 JST / ズワイガニ・コメ価格の改訂と画像4枚(approvedのまま) / threads-ando: notes/muse-handoff-2026-11-12_crab-rice-rev.md、queue/20261108-125018-00.json・-01.json ・ threads-images: ando/202611/ando-crab-{brandmap,section}.png・ando-rice-{price,stock}.png / ユーザーの最終確認を推奨
- [完了] 2026-11-12 02:50 JST / 承認待ち投稿の個別改訂(KFC・X2・X3・X4・X6・X7・X9、X1は対象外) / threads-ando: notes/muse-handoff-2026-11-12_pending-rev.md ・ threads-images: ando/202611/ando-x04-honda-map.png・ando-x07-power-diagram.png・ando-x09-hayashima-main.png / ユーザーの承認と、X6・X4の要追加調査が要る
- [完了] 2026-11-12 03:20 JST / X1 灯油を製油所の逆説で組み直し(承認待ちのまま) / threads-ando: notes/muse-handoff-2026-11-12_x1-rebuild.md ・ threads-images: ando/202611/ando-x01-touyu-main.png / ユーザーの承認が要る
- [完了] 2026-11-12 09:40 JST / 最終ファクトチェック結果の反映(ズワイガニ修正・X6書き直し・X10/US-2下書き補強・X7出典・X4地図) / threads-ando: notes/muse-handoff-2026-11-12_factcheck-results.md ・ threads-images: ando/202611/ando-x06-yatsushiro-main.png・ando-x04-honda-map.png / X6は新版での承認が要る
- [完了] 2026-11-12 10:10 JST / 地理的観点の角度に合わせた直し(教育寄りの締めを4本で書き換え、X4・X7・X9を深掘り) / threads-ando: notes/muse-handoff-2026-11-12_geo-angle.md / 判断不要(要追加調査あり)
- [完了] 2026-11-12 10:45 JST / 「ちなみに」の一文(8本)と確認済み材料での深掘り(KFC・X1・X2・X3・X9) / threads-ando: notes/muse-handoff-2026-11-12_deepen-results.md ・ threads-images: ando/202611/ando-x09-hayashima-main.png / 判断不要
- [完了] 2026-11-12 23:30 JST / 承認待ち8本の清書(可視化3項目を最新化)とX6画像の差し替え / threads-ando: notes/muse-handoff-2026-11-12_seisyo.md ・ threads-images: ando/202611/ando-x06-yatsushiro-main.png / ユーザーの承認が要る(8本)
- [完了] 2026-11-13 00:10 JST / 画像ルールに反する既存画像4枚の差し替え(ズワイガニ地図・X4地図・X9地図・コメ備蓄、同名で上書き・status変更なし) / threads-ando: notes/muse-handoff-2026-11-12_image-fix.md ・ threads-images: ando/202611/ / 判断不要

- [完了] 2026-11-12 23:00 JST / すず 新規ドラフト12本(型B4・A3・D2・C3)＋system.mdのask/opinion掃除 / threads-autopilot: queue/20261112-nd00〜nd11.json(pending_approval)、notes/muse-handoff-2026-11-12_new-drafts.md / ユーザーの承認が要る(nd07・nd08は表カード画像が要る)
- [完了] 2026-11-13 00:40 JST / 収益化プロジェクト全量棚卸し(12件、台帳表の転記、リサーチ2プロンプト) / threads-ando: notes/muse-handoff-2026-11-11_revenue-projects.md / ユーザーの判断が要る
- [完了] 2026-11-12 JST / LINEスタンプ第2弾 キャラ設計5案(A〜D+自由案E)とサンプル画像 / threads-ando: notes/muse-handoff-2026-11-12_stamp-wave2-design.md ・ revenue-hub: stickers/wave2/ / ユーザーの選択が要る

## 作業中ログ
（まだなし）

## 確認待ち
- 2026-11-12 すず nd07/08 表カード未作成（画像生成の枠が上限）。Gemini 下地プロンプトと、画像の載せ方（post.py は raw URL の image_file を使えない）の判断待ち。詳細は threads-autopilot: notes/muse-handoff-2026-11-12_approval-followup.md
- 2026-11-10 / X1〜X10の出典名・URLが未受領(ファクトカードの出典欄が仮)。X1の2月の灯油代は札幌市の数字か。X3(2社)・X7(3社)の社名を減らすか。詳細は threads-ando の notes/muse-handoff-2026-11-10_batch.md
- 2026-11-11 / すず書き直し6本の承認。rw04の表カード画像を付けるか。prompts/system.md に残っているask/opinionの配分・問いかけで締める指示を消すか。型B・単価の列は根拠がない(要追加調査)。詳細は threads-autopilot の notes/muse-handoff-2026-11-11_ask-rewrite.md
- 2026-11-12 / すず新規12本の承認。型B・A・Dで商品名を本文に出してよいか(system.md必須要件7と衝突)。ナチュリエ乳液の正式名(ゲート禁止語)。F026・F029が3回使用。詳細は threads-autopilot の notes/muse-handoff-2026-11-12_new-drafts.md
- 2026-11-13 / 収益化棚卸し：Etsy見送り確定か、Apify停止確定か、UpworkのConnects購入可否、コンペでAI記載なし募集を含めるか、LINE v1「まるくん」は没か・保留記述の更新可否。詳細は threads-ando の notes/muse-handoff-2026-11-11_revenue-projects.md
- LINEスタンプ第2弾：5案から選択待ち(おすすめA ねむらし、次点E しとぴ) → threads-ando: notes/muse-handoff-2026-11-12_stamp-wave2-design.md
