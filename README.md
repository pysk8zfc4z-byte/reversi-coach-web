# Reversi Coach（ビルド成果物）

初心者育成型のリバーシ。**先に考えて、あとで評価する。**

打つ場所を自分で選ぶまで、順位も評価値も最善手も表示しません。
選んだ瞬間に全ての手の順位が出るので、自分の読みと見比べられます。

**遊ぶ:** https://pysk8zfc4z-byte.github.io/reversi-coach-web/

## このリポジトリについて

**ビルド成果物だけを置いています。**ソースコードは含みません。

## 動作について

- **端末内で完結します。**外部への通信を一切行いません
- 対局の記録はブラウザの localStorage にだけ保存されます。サーバーへは送りません
- ログイン・課金・広告・アクセス解析はありません
- オンライン対戦はありません。AI との対局と、同じ端末での二人対戦だけです

## 同梱物のライセンス

### Noto Sans JP

- 出典: https://github.com/google/fonts/tree/main/ofl/notosansjp
- ライセンス: SIL Open Font License 1.1 — [NotoSansJP-OFL.txt](NotoSansJP-OFL.txt)
- 著作権表示: Copyright 2014-2021 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'
- 改変: 太さを 400 / 700 に固定し、このアプリが使う文字だけを残すサブセット化を
  行っています。Reserved Font Name を避けるため `NotoSansJP-Subset-*` という名前です

### Flutter / CanvasKit

Flutter SDK（BSD-3-Clause）と CanvasKit（Skia, BSD-3-Clause）を含みます。
全文はアプリ内の「ルール・設定 → OSSライセンス」で読めます。

## 名称について

仮称です。「オセロ」「Othello」は登録商標のため、名称もロゴも使用していません。
