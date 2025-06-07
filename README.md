# Purpose
「風景に触れる」をコンセプトとしたゲームです。  
interactive-sound-sceneをWeb上で遊べるように進化させました。

# Usage
https://heita-kato.github.io/prototype/  
スマホでこちらのリンクを踏んで遊んでいただければ！
(PCではお使いいただけません)  
最初に3つの風景から1つ選んでタップしてください。
タップやドラッグに応じて音が鳴ります。  
Androidであればバイブレーションもご体験いただけます。

# Detail
interactive-sound-sceneを用いて作成した領域・深度情報をもつjsonマップをあらかじめ用意し、
風景をタッチした部位に応じて音を鳴らし分けています。  
領域分類モデル：SegFormerB2  
深度推定モデル：DepthAnythingV2
