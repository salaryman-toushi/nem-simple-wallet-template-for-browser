# nem-simple-wallet-template-for-browser
nem-simple-wallet-template-for-browserは、NEM-sdkとブラウザのみの環境で、NEMの各種機能をできるだけシンプルに利用できる雛型を目指しています。webアプリケーション作成初心者が独習しつつ作成している、html, javascriptで動作しているwebアプリです。このwebアプリが、NEMに初めて触れるwebエンジニアにとって理解の助けになれば幸いです。
nem-simple-wallet-template-for-browser is simple template of web application worked with Google Chrome and NEM-sdk. This application's developper( = me = salaryman-toushi) is an amature programmer. Now I am studying NEM-sdk, javascript, html etc. I am happy that this application code is helpful for web engineers who have experienced NEM service development for the first time.
## 免責事項 Disclaimer
このアプリでは、秘密鍵を端末内のブラウザのローカルストレージに暗号化せずに保存します。本番環境でのこのような運用は極めてリスクが高いため、このアプリの利用はあくまでも検証目的に留めて頂き、試用後は確実にブラウザのローカルストレージから秘密鍵等のアカウント情報を削除するよう心がけてください。ブラウザのローカルストレージから秘密鍵をワンクリックで削除する機能は実装されています。
また、このアプリは初心者が作成しているため、予期せぬバグを多く含んでいる可能性があります。NEMのサービスを扱う場合、基本的には、他の信頼性の高いNEMのウォレットをご使用頂き、このアプリはエンジニアのハンズオン等の限定的な目的で活用して頂くのが良いと思います。(例えばRaccoon Wallet、NEMの公式ウォレット、coinomiウォレット等。)
このプログラムの利用によるいかなる結果に対しても当方は責任を負いません。ご利用は自己責任でお願いします。
This application saves your privateKey in your browser localStorage of your hardware without encrypting. In production environment, such a operation is very risky. So you should use this application for only test purpose. And you should definitely and manually delete your account information before closing this application. (You can do it with one click in this application.)
This application developper is amature programer, so it may contain various bugs. Basically, when you use NEM service, you should use highly trusted NEM wallet. (For example, Raccoon wallet, NEM official wallet, coinomi wallet etc.). Strongly I recomend you syould use this application in only test purpose.
I cannot guarantee any result from these programs. You will need to take full responsibility for your action.
## このアプリでできることとできないこと
他のウォレットアプリで生成したアカウントの秘密鍵を登録することで以下のような機能をGoogle Chromeから実行できます。
If you import privateKey generated with other NEM wallet application, you can use below function with this application and Google Chrome.
* 扱えるNEMアカウントは一つのみ。You can only manage only one NEM account.
* 登録したアカウントの秘密鍵、公開鍵、アドレスの表示、非表示、削除。You can show, hide and delete your privateKey, publicKey and Address.
* 保有しているXEM、モザイクの残高表示。You can show balances of XEM and any Mosaics.
* 直近25件までのトランザクション履歴の表示。You can show latest 25 transaction history.
** xemのみのトランザクションの残高等の表示は可能。You can show XEM balances in the transaction history window.
** mosaicを含むトランザクションは適切な残高の表示は不可能(全て1mosaicsと表示される)。You can't show right mosaic balances in the transaction history window.
** メッセージの暗号化がされたトランザクションが直近25件のトランザクションに含まれる場合はエラーとなる可能性あり。If there are some transactions contained mosaics in your latest 25 transactions, error may occur. 
## ご利用方法 Setup
このレポジトリ上のファイルを全て適当な単一フォルダに配置し、index.htmlファイルをGoogle Chromeで起動してください。
## NEMが切り開いていくより良い世界の可能性を楽しみにしています。 I am looking forward to wonderful new world achieved by NEM. Thank you!
