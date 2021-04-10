LINE Developers チャネル作成
####################################

ログイン
***********************************

サインアップが終わったら、LineDevelopers_ にログインします。 **ビジネスアカウントでログイン** を選択して、Developer用のアカウントを作ります。

.. image:: /images/line_dev_login.png


プロバイダー作成
***********************************

**プロバイダー** タブを開き、 **新規プロバイダーを作成** をクリックします。

.. image:: /images/create_a_new_provider.png

次のような画面が開きます。プロバイダー名は **KickerCamera** にします。

.. image:: /images/provider_name.png

**作成** をクリックします。

MessagingAPI作成
***********************

下の画面で、 **Messaging API** を選択します。

.. image:: /images/new_messaging_api.png


チャネル作成画面が出ます、項目を以下のように入力してください。

* チャネルの種類：　Messaging API
* プロバイダー：　KickerCamera
* チャネルアイコン： 下の画像を右クリックからダウンロードして使ってください

    .. image:: /images/line_icon.png
        :width: 100
        :height: 100

* チャネル名：　キッカーカメラ（〇〇スキー場） 
* チャネル説明： 〇〇スキー場に設置しているキッカーカメラです
* 大業種：　スポーツ施設
* 小業種：　スキー場


.. note:: 
    **チャネル名はユーザーの携帯に表示されるラインアカウントの名前になります。** 
    「〇〇スキー場」を利用するスキー場の名前に変更してください。
    チャネル名例：「キッカーカメラ(Hakuba47)」

契約に同意して **作成** をクリックします。


チャネルシークレットの取得
******************************************************

先ほど作ったチャネルのページに行きます。

.. image:: /images/click-channel.png

**チャネル基本設定** を開きます。

.. image:: /images/kihon_settei.png

**チャネルシークレット** を後で使うので、下の図の「コピー」ボタンを押して、メモアプリ等に控えておきます。

.. image:: /images/channel_secret.png

チャネルトークンの取得
******************************************************

**Messaging API設定** を開きます。

.. image:: /images/message_api_settei.png

**チャネルアクセストークン** を発行します。
後で使うので、下の図の「コピー」ボタンを押して、メモアプリ等に控えておきます。

.. image:: /images/channel_token.png


.. _LineDevelopers: https://developers.line.biz/en/