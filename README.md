# Hand Signaling for WebRTC
WebRTCのシグナリングを手動で行うサンプルです

こちらから実際に試すことができます。
https://mganeko.github.io/hand/

## Hand signaling vanilla ICE
https://mganeko.github.io/hand/signaling_vanilla.html
### 使い方
* Chrome または Firefoxで、リンク先のページを2つ開きます
 * この際に別ウィンドウで開き、横に並べるのがオススメです
* 両方のウィンドウで、[Start video]ボタンをクリックし、カメラを取得します
 * 許可を求めるダイアログが表示されたら、カメラ等へのアクセスを許可してください
 * 左上にカメラの映像が表示されます
*  片方のウィンドウで、[Connect]ボタンをクリックします
 * [SDP to send:]のテキストエリアに、OfferのSDPが表示され選択されます
 * そのテキストをコピーしてください
* もう一方のウィンドウで[SDP to receive:]のテキストエリアをクリックし、先ほどの内容をペーストします
* [Reveive SDP]ボタンをクリックします
 * [SDP to send:]のテキストエリアに、AnswerのSDPが表示され選択されます
 * そのテキストをコピーしてください
* 最初ののウィンドウで[SDP to receive:]のテキストエリアをクリックし、先ほどの内容をペーストします
* [Reveive SDP]ボタンをクリックします
 * しばらくするとP2Pの通信が確立し、右上に通信で受け取った映像が表示されます


