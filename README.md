2015-07-14に、XEADの製品名がX-TEA(エクスティ)に変わりました

2015-07-14　のバージョンより、MS Accessの　accdbに対応しました。

skeleton　と　「CONCEPTWARE/受注生産」を、
Derbyデータベースから、accdbにコンバートしました。

skeleton.accdb
mfgorder.accdb


xtea Driver・Modeler　をインストールし、.xeafをクリックすれば
ご利用いただけます。

サンプルシステム
　accdbSkeketon.xeaf

「CONCEPTWARE/受注生産」
　accdbMfgOrder.xeaf


それぞれ、.xeafと.accdbファイルは、同じフォルダ内で動作します。

データベースへの接続文字列が＜CURRENT＞となっています。
場所を特定したい場合は、＜CURRENT＞ を C:\work\　に変更してください。

jdbc:ucanaccess://＜CURRENT＞\mfgorder.accdb;memory=false

修正例：
jdbc:ucanaccess://C:\work\mfgorder.accdb;memory=false
