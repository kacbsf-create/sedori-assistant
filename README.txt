せどり仕入れアシスタント v2.4.5
JAN読み取りエンジン修正版

・iPhoneで読み取り成功したテスト版と同じBarcodeDetectorPolyfillを使用
・撮影File/BlobをHTMLImageElementへ変換してから検出
・EAN-13/EAN-8/UPC-A/UPC-Eに限定して解析
・JANチェックデジット検証で誤読を除外
・元画像→複数クロップ→グレー/コントラスト/2値化/シャープの順で再解析
・従来のhtml5-qrcodeを最終フォールバックとして維持
・商品名自動取得・利益計算・在庫機能は維持
