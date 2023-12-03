# Network_SetProgramについて
<br>

## 概要
<li>ネットワークの設定（IPv4）を動的に変更し、疎通確認（内外）を実施
<li>ログオンバッチや各ユーザーに実施いただくなど、業務負担軽減のために利用
<br>
<br>

## 注意点
<li>"Net_Setting_2.bat"のみ実行する場合はローカルで実行すること
<li>サンプルはDHCP設定変更を想定して作成していますので、固定アドレスを設定する場合はプログラムを改変すること
 
<br>
<br>

## Net_Setting_1.bat
<li>サーバなど、ネットワーク経由で実行する場合を想定してローカルに”Net_Setting_2.bat”をコピーするもの
 
<br>
<br>

## Net_Setting_2.bat
<li>設定順序は下記の通り
<p>1. IPv4の設定
<p>↓
<p>2. DNSの設定
<p>↓
<p>3. 疎通確認（内）
<p>↓
<p>4. 疎通確認（外）
