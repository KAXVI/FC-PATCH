# FC-PATCH

## Captain Tsubasa Vol. II save & fastforward-jp

・vhernandezm 氏の [Captain Tsubasa Vol. II: Super Striker - PLUS](https://www.romhacking.net/hacks/10127/) から、セーブ・ロード機能をオリジナル版に移植\
・試合中にセレクトボタンを押している間、早送りできる機能を追加

セーブ時\
<img src="docs\image/t2_2_1.png" width="30%"> <img src="docs\image/t2_2_2.png" width="30%">

ロード時\
<img src="docs\image/t2_1_1.png" width="30%"> <img src="docs\image/t2_1_2.png" width="30%">

Database match: Captain Tsubasa Vol. II - Super Striker (Japan).nes\
File/ROM SHA-1: 43c26781d88e062afa81c1a32f8345011fe53b8c\
※NESエミュレータ／Mister FPGA NESコア／EverDrive N8 PRO Fami にて確認済み


## Dragon Quest III dash & record-jp

・コマンドを拡張して、きろく（どこでもセーブ）機能を追加\
　王様セーブと併用可（王様セーブの場合は、後述移動速度モードはリセットされる）\
・コマンドを拡張して、あるく／はしる（内部移動速度モード切替）機能を追加\
　コマンドが「あるく」の時：内部は倍速の走りモード\
　コマンドが「はしる」の時：内部は通常の歩きモード\
・移動中にBボタンを押しながら移動すると、移動速度が変化になる機能を追加\
　Bボタンを押している間、内部移動速度モードが反転する\
　コマンドが「あるく」の時：内部は倍速の走りモード → Bボタンを押している間歩く\
　コマンドが「はしる」の時：内部は通常の歩きモード → Bボタンを押している間走る

どこでもセーブ\
<img src="docs\image/dq3_s.png" width="30%">

内部移動速度モード切替\
<img src="docs\image/dq3_d1.png" width="30%"> <img src="docs\image/dq3_d2.png" width="30%">

Database match: Dragon Quest III - Soshite Densetsu e... (Japan) (Rev B).nes\
File/ROM SHA-1: 9c3c5db50c7c56ffe054469bdbaee3edf1c424c5\
※NESエミュレータ／Mister FPGA NESコア／EverDrive N8 PRO Fami にて確認済み


## WreckingCrew 2P CO-OP

・Q____, puchiedarcy 氏の [Wrecking Two](https://www.romhacking.net/hacks/3824/) から、2P同時協力プレイをオリジナル版に移植\
・1P側はマリオ、2P側はブラッキー\
　ブラッキーは常に裏にいて、敵に触れても画面外に出ても死なないため、マリオをサポートしてプレイ

2P同時協力プレイ\
<img src="docs\image/wc_2p_1.png" width="30%"> <img src="docs\image/wc_2p_2.png" width="30%">

Database match: Wrecking Crew (World).nes\
File/ROM SHA-1: 31635f1a5255fe8954c5a275b067f603bb7af408\
※NESエミュレータ／Mister FPGA NESコア／EverDrive N8 PRO Fami にて確認済み


## Wizardry I - Gold

▽追加機能

・ダンジョン内の移動時にアニメーションを追加\
　（ダンジョンの描画は「面画」に固定される）

<img src="docs\image/wiz_0101.png" width="30%">

・戦闘開始時にモンスターのプレビュー表示を追加\
　モンスターとの通常エンカウント時に、先頭3種までのモンスターグラフィックを表示\
　（敵が先制した場合や、敵がこちらに気づいていない場合は、プレビューは省略される）

<img src="docs\image/wiz_0201.png" width="30%">

・訓練場メニューの「じゅんばんを　かえる」を追加\
　SFC版ウィザードリィV基準のキャラクターの並び替え機能

<img src="docs\image/wiz_0301.png" width="30%"> <img src="docs\image/wiz_0302.png" width="30%">

・デュマピック使用時のマップ表示、および踏破マスのオートマップ機能を追加\
　マロール使用時は同様のマップを使用してマス指定が可能

<img src="docs\image/wiz_0401.png" width="30%"> <img src="docs\image/wiz_0402.png" width="30%">

▽パッチの反映

・Chaotic Gate 氏の [Wizardry I - Resolution](https://advent.ivory.ne.jp/gate/wizardry/index.html) を組み込み反映

▽調整

・タイトル画面のSELECT SWITCH内の選択項目について、\
　現在選択されているフォントカラーを白に変更し、わかりやすいように調整

<img src="docs\image/wiz_0501.png" width="30%">

・後発のシリーズタイトルにあわせ、\
　まちはずれメニューの「ちかめいきゅうに　はいる」を、リストの一番上に移動

<img src="docs\image/wiz_0502.png" width="30%">

Database match: Wizardry - Proving Grounds of the Mad Overlord (Japan).nes\
File/ROM SHA-1: dbc6bd22f79055f48347707c8f0281a49ad777a6\
※NESエミュレータ／Mister FPGA NESコア／EverDrive N8 PRO Fami にて確認済み


