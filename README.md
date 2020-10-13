# RegattaRecordについて

ここではボート競技の記録を更新していきます。  
ここに上がっている情報は公式記録ではありません。  
ここでは次の大会(レガッタ)記録を扱います。  

- 全日本選手権
- 全日本軽量級選手権(2019年を除く)
- 全日本大学選手権
- 全日本新人選手権(2000年と2016年を除く)

期間: 2000年から2019年まで  

## 情報源

ここに上がっている記録の情報源は日本ボート協会のWebサイトです。  

日本ボート協会Webサイト  
https://www.jara.or.jp/  

## 見本

### JSON

Encoding: UTF-8  

```json
[
	{
		"year":2000,
		"tournament":"全日本軽量級選手権",
		"event":"男子シングルスカル",
		"raceNo":1,
		"startDateTime":"06/30 10:00",
		"group":"予選A組",
		"resultByRank":[
			{"rank":1, "crew":"ゲキサルRC", "lap500":"01:55.91", "lap1000":"03:56.27", "lap1500":"06:00.51", "goalTime":"07:54.77", "laneNo":3, "qualify":"->Semi-Final"},
			{"rank":2, "crew":"住友金属鉄ッ子", "lap500":"02:00.22", "lap1000":"03:59.34", "lap1500":"06:01.14", "goalTime":"07:55.00", "laneNo":2, "qualify":""},
			{"rank":3, "crew":"東海大学", "lap500":"01:57.01", "lap1000":"03:57.19", "lap1500":"06:02.17", "goalTime":"08:06.88", "laneNo":6, "qualify":""},
			{"rank":4, "crew":"東京水産大学", "lap500":"02:01.33", "lap1000":"04:04.96", "lap1500":"06:11.02", "goalTime":"08:13.29", "laneNo":4, "qualify":""},
			{"rank":5, "crew":"兵庫大学", "lap500":"02:01.10", "lap1000":"04:05.25", "lap1500":"06:14.62", "goalTime":"08:18.46", "laneNo":5, "qualify":""},
			{"rank":6, "crew":"防衛大学校", "lap500":"02:11.67", "lap1000":"04:24.90", "lap1500":"06:41.68", "goalTime":"08:51.96", "laneNo":1, "qualify":""}
		]
	},
	{
		"year":2000,
		"tournament":"全日本軽量級選手権",
		"event":"男子シングルスカル",
		"raceNo":2,
		"startDateTime":"06/30 10:10",
		"group":"予選B組",
		"resultByRank":[
			{"rank":1, "crew":"BOMBERS", "lap500":"01:53.34", "lap1000":"03:50.05", "lap1500":"05:48.15", "goalTime":"07:43.91", "laneNo":5, "qualify":"->Semi-Final"},
			{"rank":2, "crew":"日本大学", "lap500":"01:50.27", "lap1000":"03:48.24", "lap1500":"05:48.96", "goalTime":"07:46.54", "laneNo":4, "qualify":""},
			{"rank":3, "crew":"東京医科歯科大学", "lap500":"01:54.11", "lap1000":"03:53.94", "lap1500":"05:57.78", "goalTime":"08:00.26", "laneNo":2, "qualify":""},
			{"rank":4, "crew":"大丸京都艇友会", "lap500":"01:51.99", "lap1000":"03:56.10", "lap1500":"06:06.64", "goalTime":"08:15.33", "laneNo":3, "qualify":""},
			{"rank":5, "crew":"浜寺RC", "lap500":"02:04.72", "lap1000":"04:16.94", "lap1500":"06:33.31", "goalTime":"08:39.17", "laneNo":1, "qualify":""},
			{"rank":6, "crew":"東京商船大学", "lap500":"02:10.47", "lap1000":"04:22.76", "lap1500":"06:34.39", "goalTime":"08:41.99", "laneNo":6, "qualify":""}
		]
	}
]
```

### CSV

Encoding: Shift-JIS  

** Column name **  
year, tournament, raceNo, event, group, startDateTime, rank, crew, lap500, lap1000, lap1500, goalTime, laneNo, qualify  

```csv
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,1,明治生命,01:40.62,03:25.77,05:11.98,06:56.96,3,->Semi-Final
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,2,茨城大学,01:46.32,03:32.99,05:21.61,07:10.31,4,""
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,3,東北学院大学,01:39.24,03:27.20,05:22.74,07:18.75,2,""
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,4,立教大学,01:43.88,03:35.25,05:27.77,07:20.40,5,""
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,0,"","","","","",1,""
2000,全日本軽量級選手権,19,男子ダブルスカル,予選C組,06/30 13:50,0,"","","","","",6,""
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,1,明治大学,01:38.84,03:23.54,05:12.51,06:59.98,4,->Semi-Final
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,2,東京経済大学,01:45.02,03:34.17,05:26.16,07:17.46,2,""
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,3,青山学院大学,01:48.16,03:40.06,05:35.08,07:27.84,3,""
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,4,東京大学,01:47.95,03:39.65,05:38.13,07:34.80,5,""
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,0,"","","","","",1,""
2000,全日本軽量級選手権,20,男子ダブルスカル,予選D組,06/30 14:00,0,"","","","","",6,""
```

## 更新履歴

| 日付 | 種類 | 内容 |
|:---|:---|:---|
|2020-10-13 |追加 |jara2020.jsonとjara2020.csvに全日本選手権の結果を追加 |
|2019-11-01 |追加 |jara2019.jsonとjara2019.csvに全日本新人選手権の結果を追加 |
|2019-09-11 |追加 |jara2019.jsonとjara2019.csvに全日本大学選手権の結果を追加 |
|2019-07-07 |修正 |jara2012.jsonデータが途切れていたので残りのデータを追加 |

## License

MIT  

## Author

@rowing_fan  
https://twitter.com/rowing_fan  
