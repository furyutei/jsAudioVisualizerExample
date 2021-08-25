JavaScriptによるAudio Visualizer実装例
===

■ これは何？
---
音源ファイルの再生時に周波数帯毎のレベルを表示するみたいなやつ（Visualizer）をJavaScriptでも簡単にできるらしいときいたので試してみました。  
なんとか動きましたが、自分にとっては難しかったです……例によってブラウザやOSによってWeb Audio API（AudioContext）動作が異なるみたいですし。  

![動作イメージ](https://furyutei.github.io/jsAudioVisualizerExample/img/screenshot.01.png "動作イメージ")

■ サンプル
---

> [Audio Visualizer実装例](https://furyutei.github.io/jsAudioVisualizerExample/trial/)  

を開き、とりあえず再生ボタン▶を押せば音楽再生＆表示がされると思います。  
別の音源ファイルを試したい場合には、緑色の矩形のところにドラッグ＆ドロップしてみてください。  

■ その他
---
- サンプルで使用している音源ファイル（「Overtune!」）は[フリーBGM・音楽素材｜H/MIX GALLERY](http://www.hmix.net/)のものを使わせていただいております
- 習作ですのでソースコードについては著作権は主張しません。抜粋・改変等、ご自由にお使いください（当然ながら動作保証やサポートもありません）
