LINEでWebhook URLを設定する
##########################################

LineDevelopersConsoleページ_ に戻り作成したチャネルの **Messaging API設定** を開きます。

.. image:: /images/message_api_settei.png

Webhook設定まで移動します。

.. image:: /images/webhook_url.png

``https://｛APP_NAME}.herokuapp.com/callback`` というURL形式で、Webhook URLを入力します。

{APP_NAME}の部分にメモしておいたHerokuの **App name** に置き換えます。

.. note::
    上の画像は、HerokuのApp nameが「kicker-camera」だった場合のURLです。

.. warning::
    **Webhookの利用** を **有効** にします。

.. _LineDevelopersConsoleページ: https://developers.line.biz/console/