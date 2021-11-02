# art_activity_analysis


## 說明
* 使用 政府資料開放平台 的 藝文活動  作為來源資料
*  資料 api 說明文件:https://opendata.culture.tw/upload/dataSource/2021-02-18/9bee99c4-0732-4abd-b8c6-1a4bd0b62e64/db83c7223217e1d9947778256768153f.pdf


## 環境
*  使用的lib可由requirement.txt 匯入
*   conda install --yes --file requirements.txt
*  使用 mysql 作為 db ，建立 名稱為 test 的db，並匯入category_type.sql 
*  修改連線資訊 'mysql+pymysql://testadmin:testadmin@localhost:3306/test?charset=utf8mb4'
輸入連線資訊

## jupyter book  介紹
* deal_all_event.ipynb 處理所有活動場次的資料
* deal_all_category.ipynb 處理所有活動資料(不包含場次資料)
* deal_category_analysis.ipynb 資料類別的處理
* location_activity_analysis.ipynb 資料地區的處理
* month_activity_analysis.ipynb  資料月份處理
* music_month_analysis.ipynb 音樂類型與月份處理
