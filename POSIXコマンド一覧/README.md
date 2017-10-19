
POSIXコマンド一覧

PCがデフォルトの状態で、POSIXコマンドが入っているかどうかを調べる。

結果だけ見たい方はcommand_result.csvファイルに集計されているので、
ExcelかLibreOfficeCalcなどで開くとすぐ見れます。

構成

コマンド一覧.txt
	元になったリスト。

command_list.sh
	コマンド一覧.txtから作成したスクリプト。OKしか出力しない。

command_list2.sh
	コマンド一覧.txtから作成したスクリプト。OKまたはNGどちらかが
	すべて出力される。

POSIXコマンド結果OS個別フォルダ
	command_list.shを実行した結果が各OSごとに入っている。

command_result.csv
	POSIXコマンド結果OS個別フォルダのファイルの内容をまとめたもの。





