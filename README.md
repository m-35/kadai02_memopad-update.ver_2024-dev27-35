# 課題① 課題番号-プロダクト名
- 課題番号：js02_memopad.
- プロダクト名：「ノートパッシング」
- キャッチフレーズ:「指１本。キモチ交換」

## ②課題内容（どんな作品か）
- 耳の不自由な人（以下、「利用者」といいます）が、緊急時や困った時にすぐ使える実用型筆談アプリ。
- 現行は個人用アプリだが、今後、医療機関、交通機関、自治体、施設等が利用者に対して使えるアプリとしてもプロダクト構築することを想定。

## ③DEMO
- https://drive.google.com/file/d/1h43p2x2qLSE7UK0xSo5n_aeUoinfo5s3/view?usp=sharing

## ④工夫した点・こだわった点
- 【工夫した点】
- htmlのcanvas要素とjsでお絵描きアプリができることを筆談に活用した。
- 筆談した内容を、ローカルストレージで画像として保存、削除、呼び出しができるようにした。
- 【こだわった点】
- 利用者が質問を書く手間や、他人への気兼ねなどの負担を減らし、耳が聞こえる人同士の会話と比べても時間的差異がないように、以下の２点にこだわった。
- ①とっさにすぐ聞けない（時間がかかる）質問をテンプレ化（生活に合わせてカスタマイズ）。
- ②画面を見せられた側が瞬時に意味を理解して、指一本で短くさっと書ける内容に絞り、相互コミュニケーションのハードルを下げる。

## ⑤難しかった点・次回トライしたいこと（又は機能）
- 【難しかった点（未解決）】
- canvas機能と各タブが連動しない（最初のタブしか筆談が機能しない）
- 【今後トライしたいこと】
- ①上記問題の解消
- ②スマホやタブレット利用を前提とするデザインの再考
- ③質問をカスタマイズできる入力フォームの構築
- ④呼び出し機能の工夫（現状は直前の画像のみ表示）
- ⑤保存した画像をメール添付できる「共有」機能の追加
- 今の自分の技能で翌週に全部できるとは思えないが頑張って近づきたい…

## ⑥質問・疑問・感想、シェアしたいこと等なんでも
- 【感想】
- 森田先生の講義終盤で教えて頂いたcanvas機能をもとに、自分が実現したいイメージを膨らませて、googleやcopilotを利用しながら作りました。
- jsに、コピペで利用したコードのコメントに「ローカルスコープ」なる概念が出てきて、htmlのエラーと関連していると推測しているのですが、「ローカルスコープとは」を調べ始めたら沼にはまって時間がどろどろに溶けたので、とりあえず保留にしています。今後整理していきたいです。

## ⑦前回(5/24提出期限分)から改良できたこと
- 結果的には前回と変わりありません。進歩できませんでした。残念です。

## ⑧前回(5/24提出期限分)以降に、試みたこと
- ⑤の未解決だった「複数のタブごとにcanvasが機能する」挙動を実装しようとして、それだけで未解決のままタイムアップでした。
- やり方としては、タブとお絵描きが連動できるコードを色々調べ別のhtmlを作り「sanko.html」で保存。それを元に、課題用の「index.html」に落とし込むべく、classやidを作り変えたり、一度全部消して「sanko.html」から作り直したり試行錯誤したが、今のところどうやっても挙動しない。
## 以上
