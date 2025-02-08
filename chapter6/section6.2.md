# 6.2. TCP 設定方法

#### ■ TCP(Tool Center Point)

#### ロボットに装着されたツールの作業中心点を意味し、本機の場合溶接ワイヤの端点をTCPに設定します。

{% hint style="warning" %}
本機は製品生産時にTCP設定を完了して出荷が進んでおり、下記の場合その他の変更はお控えください。\
• 衝突または外力によって座標原点が歪んだ場合\
• ロボットツールの角度や位置が変更された場合

TCP設定変更時には、保存されたプログラム教示位置が変更されることに注意が必要です。画面右側の「設定ボタン」を押します。
{% endhint %}

{% stepper %}
{% step %}
<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
機能リストから「自動TCP設定」を選択します。

<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
「アクティベート」をチェックします。

<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
TCPツールなどを使用してワイヤの端をツールの端に合わせます。

<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
「取得」を押して現在値を記録します。\
4回繰り返した後、「TCP情報変更」を押してTCP設定を完了します。

<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Global座標系のRX・RY・RZを操作し、設定したTCPを基準にツールが動いていることを確認します。

<figure><img src="../images/jp/chapter5/section5.1.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
