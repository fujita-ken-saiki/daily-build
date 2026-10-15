DAILY BUILD PWA — GitHub Pages用ファイル

GitHubリポジトリの最上位 (root) に、次のファイルをすべてアップロードしてください。
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- apple-touch-icon.png

GitHubで Add file > Upload files を選び、上記ファイルをまとめてアップロードします。ZIPそのものではなく、展開後のファイルをアップロードしてください。

公開設定:
Settings > Pages > Build and deployment > Deploy from a branch
Branch: main / Folder: /(root) > Save

公開URLが表示されたらSafariで開き、共有 > ホーム画面に追加。
初回起動時はオンラインにして、ページを一度読み込んでください。

重要:
- GitHub Pagesのサイトはインターネット上に公開されます。個人情報・秘密情報をコードに入れないでください。
- 記録データはGitHubではなく、利用中のiPhoneブラウザのlocalStorageに保存されます。
- SafariのWebサイトデータ削除などで記録が消える可能性があるため、アプリ内の「データを書き出す」でJSONを定期保存してください。
- 機種変更やブラウザ領域削除前は必ずJSONを保存し、「バックアップを読み込む」で復元を試してください。
- オフライン起動はService Workerによる補助機能です。初回はオンライン接続が必要です。
