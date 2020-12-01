---
layout: default
title: SQLiteFlow
description: SQLiteFlow for iOS release notes.
---

4.6.2 - 2020年11月30日
- 問題修復和穩定性更新。

4.6.1 - 2020年11月23日
- 匯入CSV，現在“CSV第一行為標題“的預設值為”是“，和匯出CSV功能一致。
- 匯入CSV，支援匯入前清空表資料。
- 新增捷徑支援。現在“執行查詢”和“匯入CSV“已經可以在捷徑應用中使用了。這個功能需要iOS 14.0+支援。

4.6.0 - 2020年9月18日
- 支援匯出資料到JSON。
- 支援匯出資料到Markdown。
- 此版本的SQLiteFlow現在需要iOS 13+支援。

4.3.6 - 2020年9月7日
- 問題修復和穩定性更新。

4.3.5 - 2020年8月6日
- 資料編輯器，支援用鍵盤方向鍵來選擇單元格。需要iOS 13.4+或者iPadOS 13.4+支援。
- 支援開啟能夠出現在「瀏覽」中的使用自定義拓展名的SQLite資料庫。

4.3.4 - 2020年7月8日
- 為資料編輯器中的過濾器新增「!=」和「不包含」操作符支援。

4.3.3 - 2020年7月3日
- 表列表中支援重命名錶。
- 新建資料庫時支援選擇日誌模式（WAL或者DELETE）。
- 修改表結構，支援使用拖拽來重新排序表列。
- 修改表結構，支援設定表的WITHOUT ROWID型別。

4.3.2 - 2020年6月19日
- 問題修復和穩定性更新。

4.3.1 - 2020年6月9日
- 問題修復和穩定性更新。

4.3.0 - 2020年6月8日
- 格式化查詢，支援選擇偏好縮排字元為空格或者Tabs。
- 格式化查詢，支援設定縮排寬度。現在預設的縮排寬度為4，與預設Tab寬度（同樣為4）相匹配。在之前版本中，這個值無法設定時，預設縮排寬度為3.
- 格式化查詢，支援設定分隔列定義的逗號的風格，可選擇在前或者在尾。
- 文字編輯，支援設定Tab寬度。
- 文字編輯，支援設定Tab鍵行為為插入tab字元或者插入空格。
- 「啟用外來鍵約束」這個設定從資料編輯器移到了「設定」中，所以這個設定現在對資料編輯器，查詢編輯器和匯入CSV都可以生效了。
- 匯入CSV現在支援了使用分號（;）來作為分隔符去匯入資料。

4.2.0 - 2020年4月28日
- 修改表結構支援預覽修改表結構的SQL。
- 改進修改表結構使用體驗。
- 改進連線實體鍵盤後，查詢編輯器的輸入體驗。需要iOS 13.4+或者iPadOS 13.4+支援。
- 合併查詢編輯器和查詢結果頁面。
- 其它問題修復與穩定性改善。

4.1.1 - 2020年3月28日
- 問題修復與穩定性改善。

4.1.0 - 2020年3月26日
- 在“資料編輯器”和“查詢結果”中支援單元格，行和列的多選。
- 在“查詢編輯器”中支援執行選中查詢。
- 修復一個可能導致標記外部檔案到”最近項目“列表失敗的問題。
- 其它問題修復與穩定性改善。

4.0.0 - 2020年1月1日
- “資料庫列表”重新命名為“瀏覽”。
- 在“瀏覽”中，支援開啟/新建本地資料夾，SQLite資料庫，SQL檔案，CSV檔案。
- 在“瀏覽”中，支援開啟過濾檔案。
- 在“瀏覽”中，支援開啟外部SQL檔案，CSV檔案，過濾檔案。
- 在“瀏覽”中，支援開啟外部資料夾。需要iOS 13.0+或者iPadOS 13.0+支援。
- 支援顯示最近使用檔案。
- 在查詢結果中支援以十六進位制來顯示Blob資料。
- 在資料編輯器和查詢結果中，支援長按顯示記錄預覽。需要iOS 13.0+或者iPadOS 13.0+支援。
- 在資料編輯器中增加啟用外間約束支援。
- 在資料編輯器中編輯資料時，螢幕上方增加“完成”按鈕來儲存編輯。
- 在資料編輯器和查詢結果中增加拷貝一行資料的功能。
- 現在，資料編輯器中的過濾已基於過濾檔案。
- 在資料編輯器中，支援輕觸過濾按鈕來開啟或者建立一個過濾檔案。
- 在資料編輯器中，開啟過濾檔案後，使用者可以編輯或者應用次過濾。
- 在資料編輯器中應用一個過濾後，使用者可以輕觸過濾按鈕來選擇“編輯過濾”，“移除過濾”或者“選擇其它過濾”。
- 修復了一個在匯入CSV檔案時可能導致匯入資料為亂碼的問題。
- 修復了無法在查詢結果中拷貝資料的問題。
- 其它問題修復與穩定性改善。

3.9.3 - 2019年9月30日
- 修復了在查詢編輯器中格式化查詢時可能會導致引號轉化為非ASCII編碼引號的問題。

3.9.2 - 2019年9月28日
- 修復了資料庫列表中分享選單顯示為空的問題。

3.9.1 - 2019年9月26日
- 為iPadOS 13支援多視窗。

3.9.0 - 2019年9月20日
- 在iOS 13中支援深色模式。
- 移除資料編輯器中的全域性編輯文字框，所以您現在可以直接在資料單元格中編輯資料了。

3.8.0 - 2019年8月23日
- 語法高亮與格式化查詢支援upsert分句和window function以相容未來版本的iOS。
- 修復了在某些場景下使用中文輸入法輸入異常的問題。
- 其它問題修復與穩定性改善。

3.7.0 - 2019年7月2日
- 支援簡體中文、繁體中文。
- 其它問題修復和穩定性更新。

3.6.0 - Jun 20, 2019
- Hex Editor now supports save blob data to a file.
- Hex Editor now supports drag and drop to import data from another app like Files.
- Hex Editor now supports drag and drop an image to export it to another app like Files.

3.5.0 - Jun 19, 2019
- Supports edit blob as hex.
- Supports show blob as image if possible.
- Supports IS NULL and IS NOT NULL filter in Data Editor
- Supports create sample database.
- Fix an issue that cause load database failed when a database contains virtual table that use an unknown module.

3.4.0 - May 8, 2019
- Supports export table/view data and query result to CSV format.

3.3.0 - Apr 19, 2019
- Supports import CSV data.

3.2.0 - Apr 12, 2019
- [Data Viewer] Supports sort records by tap on column title.
- [Database Statistics] Supports show records count of each table.
- [Database Statistics] Supports show total size of each table
- [Database Statistics] Supports show size of each table's content.
- [Database Statistics] Supports show size of each table's indexes. 
<br/> The feature Database Statistics may help you get more insight about your SQLite databases' data storage information, which may let you see if there're any chances to let SQLite working in a more effective way in your device.
- [Database Diff] Supports generate SQL text that can let you transform a database into another.
- [Database Diff] Supports show a summary of the differences between two databases.

3.1.0 - Apr 4, 2019
- Supports drag and drop to import or export SQLite databases and SQL files.
- Supports use a document picker to import SQLite databases and SQL files.
- Additional bug fixes and stability improvements.

3.0.3 - Mar 21, 2019
- Fix an issue that may cause 'Copy to SQLiteFlow' from Files app have no response.

3.0.2 - Mar 7, 2019
- Fix an issue that may cause duplicate purchase.

3.0.1 - Mar 7, 2019
- Fix an issue that cause loading spinner still shown when Restore Previous Purchase finished.

3.0.0 - Mar 6, 2019
- We offer 2 weeks of free trial now, feel free to come on in and take a try.

2.0.0 - Feb 11, 2019
- Start with version 2.0.0, to execute queries, creating or choosing an SQL file is needed. 
- Supports save queries.
- Supports long press a file item to rename a file.
- Supports long press a file item to duplicate a file.
- Additional bug fixes and stability improvements.

1.3.7 - Jan 11, 2019
- Supports work with SQLiteFlow(macOS) to handle remote import CSV file.

1.3.6 - Nov 7, 2018
- Supports work with SQLiteFlow(macOS) to handle remote database diff.
- Additional bug fixes and stability improvements.

1.3.5 - Sep 27, 2018
- Fix an issue that causes syntax highlighting incorrect when typing block style comment.
- Fix an issue that causes load database library failed when there's another app that declares it owns SQLite database file type.
- Additional bug fixes and stability improvements.

1.3.4 - Aug 22, 2018
- [Alter Table] Fix an issue that causes incorrect input behavior when using Pinyin keyboard.
- [Alter Table] When there's only one field in a table, disable 'Delete' field option, since SQLite does not allow a table has no field.

1.3.3 - Aug 10, 2018
- In table list, each table's row counts supports display in decimal style.

1.3.2 - Aug 9, 2018
- Table list supports display each table's row counts.

1.3.1 - Aug 2, 2018
- Fix an issue that cause unnecessary error 'The folder doesn't exist' appear.
- Fix an issue that cause back button not enabled when go into a folder.

1.3.0 - Jul 28, 2018
- Add 'About'. This feature can let you contact us conveniently.

1.2.1 - Jul 21, 2018
- Database list now supports display folder.

1.1.0 - Jul 4, 2018
- Initial public release.

[Home](./iOS)
