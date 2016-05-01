# domino-module-sd80
This is sound module definition file of Domino for Roland SD-80.  
フリーソフト「DOMINO」のRoland SD-80向け音源定義ファイルです。

* You can controll each parameter of MFX from DOMINO only the case when "SOURCE" is "COMMON".
* MFXの各パラメーターはSOURCEがCOMMONの場合のみDOMINOから操作可能です。SOURCEが各パートに設定されていると操作できません。
* Maybe this is no compatibility with the sound module file which Mr.Mist is publishing. Because I was created uniquely when DOMINO was started to develop.
* ミストさんの公開されているSD-80用音源定義ファイルとは多分互換性がありません。DOMINO開発初期から自力で作っていたためです。

## Quick Start
1.) Install DOMINO  
Download DOMINO from following link and unzip.  
DOMINOをダウンロード、解凍します。  
http://takabosoft.com/  

2.) Add module definition file  
Copy "SD-80partA.xml" and "SD-80partB.xml" from this project into "Module" folder of DOMINO.  
このプロジェクトの 「SD-80partA.xml」と「SD-80partB.xml」をDOMINOの「Module」フォルダーにコピーします。  

3.) Set up DOMINO  
Execute domino.exe.  
domino.exeを実行します。  
Then, push "F12" key, choose "MIDI-OUT" from left pain and choose "MIDI OUT DEVICE" and "MODULE(MODULE DEFINITION FILE)" as same as following.  
そして「F12」キーを押下し、左のペインから[MIDI-OUT]を選択し、[MIID OUT デバイス]と[音源(音源定義ファイル)]を下記のように選択します。  

| MIDI OUT DEVICE | MODULE(MODULE DEFINITION FILE) |
|:---------------:| ------------------------------:|
| SD-80 PART A    | SD-80 PART A                   |
| SD-80 PART B    | SD-80 PART B                   |

4.) Restart DOMINO  
Restart DOMINO.  
DOMINOを再起動します。  
