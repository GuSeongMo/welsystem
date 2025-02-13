# 6.4. ロボット関節の手動解放

RainbowRobotics ロボットの各関節は-360から+360まで動くことができますが、\
オペレータにより強制的にその限界を超えてしまう場合があります。\
関節を動かすとアラームが発生し、その状態では起動できなくなります。\
これに対する対処方法です。

{% stepper %}
{% step %}
通信接続画面で右上の設定アイコンを押します。

<figure><img src="../img/chapter6/section6.4.1.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
左側の三角形のアイコンをクリックします。

<figure><img src="../img/chapter6/section6.4.2.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
ロボット各関節の角度を確認します。

<figure><img src="../img/chapter6/section6.4.3.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
該当する関節のブレーキを解除します。

<figure><img src="../img/chapter6/section6.4.4.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
手で関節の角度を修正します。

{% endstep %}

{% step %}
該当する関節が360以内に位置してから電源を切断します。

<figure><img src="../img/chapter6/section6.4.5.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
活性化を進めます。

<figure><img src="../img/chapter6/section6.4.6.jpg" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
