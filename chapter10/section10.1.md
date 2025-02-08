# 10.1. 溶接プログラムの修正機能

#### ■ 位置移動

教示されている位置にロボットを移動させる機能です。\
教示位置の確認、中途実行のための移動のとき使用します。\
位置移動ボタンを押している間に動くので、安全関連の注意が必要で、手を離した瞬間に停止します。　（実行画面での使用も可能です。）

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
移動する位置を選択します。
{% endstep %}

{% step %}
番号確認後、位置移動ボタンを押します。
{% endstep %}

{% step %}
位置が変更されると赤線が緑に変わります。
{% endstep %}

{% step %}
教示が完了したら「実行画面」ボタンを押して実行画面に戻ります。
{% endstep %}
{% endstepper %}

***

#### ■ 位置修正

選択された番号の位置に現在のロボットの位置を上書きし修正します。\
（実行画面での使用も可能です。）

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
修正する位置を選択します。
{% endstep %}

{% step %}
番号確認後、位置修正ボタンを押します。
{% endstep %}

{% step %}
再度確認のメッセージを確認します。
{% endstep %}

{% step %}
位置が変更されると赤線が緑に変わります。
{% endstep %}

{% step %}
教示が完了したら「実行画面」ボタンを押して実行画面に戻ります。
{% endstep %}
{% endstepper %}

***

#### ■ 教示開始点変更

ある位置から連続で位置の変更を行う場合、変更の開始位置を選択して修正していくことができます。

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
修正を始める位置を選択します。
{% endstep %}

{% step %}
番号確認後、教示開始点変更ボタンを押します。
{% endstep %}

{% step %}
変更区間を連続で教示を行います。
{% endstep %}

{% step %}
教示が完了したら「実行画面」ボタンを押して実行画面に戻ります。
{% endstep %}
{% endstepper %}

***

#### ■ 溶接条件の修正

{% stepper %}
{% step %}
実行画面の左下の修正ボタンを押します。

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
プログラム作成の画面に戻ります。

IMG
{% endstep %}

{% step %}
修正が必要な位置を選択します。

IMG
{% endstep %}

{% step %}
変更を望む条件の数字をダブルタッチし、キーパッドを開きます。

IMG
{% endstep %}

{% step %}
変更する数字を入力後、エンターを押します。

IMG
{% endstep %}

{% step %}
修正ボタンを押し、条件が変更されたか確認します。

IMG
{% endstep %}

{% step %}
設定完了を押して変更を終了します。

IMG
{% endstep %}
{% endstepper %}
