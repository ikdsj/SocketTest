■プラグインインストール手順
    �@Chromeから以下URLを開きます。
   chrome://settings/
    �A「拡張機能」を選択します。
    �B開いた画面に、以下二つのプラグインをDrag&Dropします。
   TcpBackgroundScript.crx
   TcpContentScript.crx

   以上の操作でプラグインのインストールは完了です。

■動作確認手順
   �@プロジェクトに配置した以下のHTMLファイルを開きます。
     ※URL例:http://localhost/SocketTest/html/test.html
   �A池田さんサンプルを開き、<listen>ボタンをクリックします。
   �BChromeから以下URLを開き、Tcp Background Script をクリックします。
  chrome://apps/

   以上で、池田さんツールと、chromeプラグイン間でソケット通信が開始されます。

■開発手順
    �@Chromeから以下URLを開きます。
   chrome://settings/
    �A「拡張機能」を選択します。
    �B<パッケージ化されていない拡張機能を読み込む>をクリックします。
    �CSocketTestプロジェクト下の、以下2つのフォルダを指定して読み込みます。
   TcpBackgroundScript
   TcpContentScript
    
   こちらの手順でプラグインをインストールすると、コードの修正が即座に反映されるようになります。
 