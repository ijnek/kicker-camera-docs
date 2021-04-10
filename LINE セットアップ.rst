LINE セットアップ
##########################################


LINE Business アカウントを作成
********************************

LINEBusinessサインアップ画面_ から **メールアドレスで登録** を選択して、Line Businessのアカウントを作ります。



LINE Developers チャネル作成
********************************

.. image:: /images/line_dev_login.png

サインアップが終わったら、LineDevelopersページ_ にログインします。 **ビジネスアカウントでログイン** を選択して、開発用のアカウントを作ります。次の画面が開きます。

.. image:: /images/create_a_new_provider.png

Providersタブを開き、 **新規プロバイダーを作成** をクリックします。

.. image:: /images/provider_name.png

プロバイダー名は何でも良いです、上のようにKickerCameraで問題ありません。 **作成** をクリックします。

.. image:: /images/new_messaging_api.png

上の画面で、 **Messaging API** を選択して、MessagingAPIを作ります。

**チャネル名は、ユーザーの携帯に表示されるボットのラインアカウントの名前になります。** (例：キッカーカメラ)

チャネル説明、大業種、小業種は、適当に選択してチャンネルを作成します。



チャンネルシークレットとチャンネルトークンの取得
******************************************************

.. image:: /images/click-channel.png

[チャンネル基本設定]タブの **チャンネルシークレット** は後で使うので、メモアプリ等に控えておきます。

[Messaging API設定]タブの **チャンネルアクセストークン** を発行します。後で使うので控えておきます。




.. _LINEBusinessサインアップ画面: https://account.line.biz/signup?redirectUri=https%3A%2F%2Fmanager.line.biz%2F&_ga=2.259523146.1728940530.1617949361-1384753008.1617949361
.. _LineDevelopersページ: https://developers.line.biz/en/