NEM Twitter tip bot websocket API console
=========================================

NEM Twitter tip bot には websocket API が実装されています。
このAPIは連続的な操作を要求する為、一対一で操作を確認できるようにconsoleを作成しました。
あくまでdebug用に４時間ほどでくみ上げたプログラムなので実用しないで下さい。

* [nem-tip-bot](https://namuyan.github.io/nem-tip-bot)
* [how to login](https://namuyan.github.io/nem-tip-bot-console/how_to_login)
* [console page](https://namuyan.github.io/nem-tip-bot-console)

※ websocketでfirefox console securityerror the operation is insecure って言われる場合は（ws://だと言われる）about:config で network.websocket.allowInsecureFromHTTPSを有効 [引用](https://medicalfields.jp/blog/java/tomcat%E3%81%A7websocket%E3%81%97%E3%81%9F%E3%81%84/)
