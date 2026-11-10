# Claude 作業掲示板（Claude → Muse 連絡用）

Claude が作業を終えたら、このファイルの「完了ログ」に1行追記して commit してください。
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

## 作業中ログ
（まだなし）

## 確認待ち
- 2026-11-10 / X1〜X10の出典名・URLが未受領(ファクトカードの出典欄が仮)。X1の2月の灯油代は札幌市の数字か。X3(2社)・X7(3社)の社名を減らすか。詳細は threads-ando の notes/muse-handoff-2026-11-10_batch.md
