# AndroidのUIデザインとかどないすん？

# そもそもどんな作業になるん？

* 「各UI部品のデザインを個別に作って」「アプリに適用する」
   * ↓資料の意図は違うけど作業の概観が分かりやすい
   * https://www.slideshare.net/asamieee7/sketchandroidui-76429554

# 何考えたらいいの？

* ボタンやアイコンとかの**データのテンプレート**はあったりするか？
* どんなUI配置にするべきか？の様な**デザイン論** (UX)

# 結論

* 2020.03.06
   * 世にテンプレートはそれなりにありそうだが、**特定のデザインツール向け**になっていそうである
      * `Sketch android template`、`Figma android template`で検索
   * 「デザインツール⇒実装」は、アイコンや色程度なら簡単
   * **レイアウト自体の取り込み**は簡単な方法は見つからなかった
      * 世のプログラマは手動で頑張ってるのか・・・？

# ツールの話

やっぱりふぉとしょみたいにプロジェクト形式での提供が多い。
ので、ぱっと使い始められそうなツールは？を探したい。

## 有名どころ

* Scketch
   * https://www.sketch.com/
   * 有名。
   * **free版は30日限定**
* Adobe XD
   * https://www.adobe.com/jp/products/xd/details.html
   * 有名でしょうきっと。
   * **Adobe税を払うかどうか**
* Figma
   * https://www.figma.com/files/recent
   * **制限付きながら無料プラン**あり。
   * webアプリとデスクトップアプリの両方ある
   * **Android/iOSのコードを出力できる**
   * アイコンをエクスポートする
      * https://www.figma.com/community/plugin/735452896889481850/Android-Resources-Export

総じて「やっぱりSketchだろうけどFigmaの人気も出てきてるかも」という印象


## 変わり種

* https://icons8.jp/lunacy
   * sketchのファイル形式をフルサポート（らしい）無料のツール
   * 悪くなさそうだが、まずはSketchなり**王道**で流れを把握してからの方が使えると思う
   * 慣れてきたら移る先、かなと。

* SuperNova Studio
   * https://supernova.io/
   * SketchやAdobe XDのデータからコードを出力！！！
   * らしいけど **MacOSしかサポートしてない**

# データテンプレート

ぱっと探すだけでもアレコレ出てくる

## 無料でもいける

* https://materialdesignkit.com/templates/
   * 落とせるデータが各種デザイン用ツールのプロジェクト形式になってる・・・
* https://www.sketchappsources.com/category/mobile.html

## 有料のみ

* https://elements.envato.com/
   * https://elements.envato.com/spojeeto-mobile-app-ui-kit-DS7238U

# デザイン論

* んー、、さすがに何か本でも読む？

# データテンプレートの使い方

## Figma

* プロジェクトファイル(\*.fig)をとってきて開くことはできる。
* アイコンのエクスポートはそんなに難しくなさそう
   * https://www.figma.com/community/plugin/735452896889481850/Android-Resources-Export
* **レイアウト自体をandroidのcodeに落とし込む方法がよくわからない**

