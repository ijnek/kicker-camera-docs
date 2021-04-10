LINEでWebhook URLを設定する
##########################################

LINE Developersに戻り、
LINE Developersコンソールで、Messaging APIチャネルの［Messaging API設定］タブをクリックします。

``https://{HEROKU_APP_NAME}.herokuapp.com/callback`` というURL形式で、Webhook URLを入力します。

例：アプリ名が「kicker-camera-test-1」の場合、Webhook URLは `https://kicker-camera-test-1.herokuapp.com/callback` になります。

.. image:: /images/webhook_url.png

[**Webhookの利用**］を有効にします。