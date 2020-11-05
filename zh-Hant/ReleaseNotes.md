---
layout: default
title: SQLiteFlow
description: Mac SQLiteFlow 更新說明。
---

4.7.0 - 2020年11月4日
- 極大的提高了資料編輯器和查詢結果的效能，展示列數越多，效果越明顯。
- 此版本的SQLiteFlow需要macOS 10.14支援。
- 其它問題修復與穩定性改善。

4.6.1 - 2020年9月15日
- 修復了一個在全屏模式中可能導致UI顯示不正常的問題。
- 其它問題修復與穩定性改善。

4.6.0 - 2020年9月8日
- 支援匯出資料到JSON。
- 支援匯出資料到Markdown。

4.5.1 - 2020年8月29日
- 問題修復與穩定性改善。

4.5.0 - 2020年8月28日
- 標籤頁行為改動。改動前，關閉視窗的意思是隱藏視窗，所有的標籤頁保持開啟。現在，關閉視窗的意思是關閉這個視窗中的所有標籤頁並且關閉視窗。
- 現在SQLiteFlow使用系統提供的標籤欄來取代之前的標籤欄，以獲得更多系統提供的功能。
- 支援自定義工具欄，並且設計了新的工具欄圖示。
- 改進了查詢編輯器的自動儲存功能。
- 支援SQLite version 3.33.0 (2020-08-14)。
- 其它問題修復與穩定性改善。

4.3.1 - 2020年7月8日
- 為資料編輯器中的過濾器新增「!=」和「不包含」操作符支援。

4.3.0 - 2020年7月3日
- 新建資料庫時支援選擇日誌模式。
- 修改表結構，支援使用拖拽來重新排序表列。
- 修改表結構，支援設定表的WITHOUT ROWID型別。
- 資料庫列表中的表/檢視的右鍵選單支援匯出資料。
- 新增更多觸控欄支援。
- 其它問題修復與穩定性改善。

4.2.0 - 2020年6月28日
- 新增一些基本的觸控欄支援。

4.1.1 - 2020年6月22日
- 支援SQLite 3.32.3 (2020-06-18)。
- 其它問題修復與穩定性改善。

4.1.0 - 2020年6月19日
- 支援選擇使用macOS內嵌SQLite庫，或者選擇使用最新SQLite庫（目前是SQLite 3.32.2）來工作。
- 其它問題修復與穩定性改善。

4.0.1 - 2020年5月25日
- 在開啟資料庫對話方塊中添加了一個「允許選擇所有檔案型別」的選項，來讓使用者能夠在開啟資料庫對話方塊中，開啟擁有自定義拓展名的資料庫。
- 修復偏好設定中「啟用外來鍵約束」和「Tab鍵行為」的值沒有顯示正確的問題。

4.0.0 - 2020年5月22日
- 在資料庫列表中，支援右鍵表名-重命名錶名。
- 格式化查詢，支援選擇偏好縮排字元為空格或者Tabs。
- 格式化查詢，支援設定縮排寬度。現在預設的縮排寬度為4，與預設Tab寬度（同樣為4）相匹配。在之前版本中，這個值無法設定時，預設縮排寬度為3.
- 格式化查詢，支援設定分隔列定義的逗號的風格，可選擇在前或者在尾。
- 文字編輯，支援設定Tab寬度。
- 文字編輯，支援設定Tab鍵行為為插入tab字元或者插入空格。
- 「啟用外來鍵約束」這個設定從資料編輯器移到了「偏好設定」中，所以這個設定現在對資料編輯器，查詢編輯器和匯入CSV都可以生效了。
- 改進修改表結構。
- 匯入/匯出CSV現在支援了使用分號（;）或者tab來作為分隔符去匯入/匯出資料。
- 匯入CSV，修復了一個當CSV文字的最後一行的最後一個值沒有提供時，匯入時無法匯入最後一行的問題。
- 其它問題修復與穩定性改善。

3.8.1 - 2019年8月22日
- 在十六進位制編輯器中將「設定為NULL」改為「設定為NULL並應用」。
- 語法高亮與格式化查詢支援upsert分句和window function以相容未來版本的macOS。
- 其它問題修復與穩定性改善。

3.8.0 - 2019年8月16日
- 內部檢視器，檢視SQLite資料庫檔案，日誌檔案，WAL檔案或者WAL-索引檔案的內部結構。
- 現在資料編輯器編輯資料時，您可以使用Tab鍵來切換列。
- 現在資料編輯器編輯資料時，您可以使用ESC鍵來撤銷對當前值的修改。
- 現在資料編輯器編輯資料時，您可以使用Enter鍵來完成編輯資料, 然後再使用Enter鍵來觸發資料儲存。
- 在資料編輯器中增加了左邊欄來方便您選擇行。
- 在資料編輯器中拷貝資料到CSV中列的順序會根據UI中列的順序變化而變化。
- 在資料編輯器中增加了“匯出”按鈕。您可以選擇“已選行”，“顯示中的行”或者“整個表”，以及是否“包含標題行”來從表/檢視中匯出資料到CSV檔案。
- 在查詢結果中增加了“匯出”按鈕。您可以選擇“已選行”或者“顯示中的行”，以及是否“包含標題行”來從查詢結果或者查詢訊息中匯出資料到CSV檔案。
- 現在在資料庫列表中重新整理資料庫會觸發已開啟的標籤頁一併重新整理。

3.7.0 - 2019年6月28日
- 支援簡體中文、繁體中文。
- 其它問題修復和穩定性更新。

3.6.2 - Jun 23, 2019
- Fix an issue that if a database file has .sql file extension, it be recognized as a malformed sql script file instead of a database file.

3.6.1 - Jun 20, 2019
- Supports save blob data to a file.
- Supports create sample database.
- Additional bug fixes and stability improvements.

3.6.0 - May 30, 2019
- Supports IS NULL and IS NOT NULL filter in Data Editor
- Supports automatically reload a row from database if one of the row's field be updated in Data Editor in Data Editor.
- Supports edit blob as hex.
- Supports display blob as image if blob data is an image.
- Fix an issue that may cause auto adjust column width for query results Message tab's sql column sometimes shorter than expected.
- Fix an issue that cause load database failed when a database contains virtual table that use an unknown module.

3.5.6 - May 23, 2019
- Fix an issue that cause 'Set NULL' when editing data takes no effect.

3.5.5 - May 10, 2019
- Additional bug fixes and stability improvements.

3.5.4 - May 1, 2019
- Performance improvements for format query.
- Performance improvements for syntax highlighting.
- Fix an issue that may cause click to open files from Finder may have no effect.
- Additional bug fixes and stability improvements.

3.5.3 - Apr 27, 2019
- Fix an issue that cause sorting by clicking on column in Data Viewer not working.
- Improvements in Dark Mode.
- Let the free trial feature's description more clearer.

3.5.2 - Apr 26, 2019
- Fix an issue that may cause Data Viewer showing empty records.

3.5.1 - Apr 25, 2019
- Fix an issue that may cause paid users see getting trial or getting full unlock screen.

3.5.0 - Apr 24, 2019
- We offer 2 weeks of free trial now, feel free to come on in and take a try.

3.3.1 - Mar 6, 2019
- Add shortcut Cmd + Shift + R to 'Run selected query'.
- Additional bug fixes and stability improvements.

3.3.0 - Jan 28, 2019
- Supports 'Show Previous Tab (Ctrl+Shift+Tab)'
- Supports 'Show Next Tab (Ctrl+Tab)'
- Supports 'Merge Tabs of This Database into New Window'
- Supports 'Move Tabs to Main Window'
- Supports 'Exchange Tabs with Main Window Tabs'
- Fix an issue that cause window size not remembered.
- Fix an issue that cause open FTS table failed.

3.2.0 - Jan 18, 2019
- Supports filter tables and views in database list.
- Additional bug fixes and stability improvements.

3.1.0 - Jan 11, 2019
- Supports sorting by click on column in Data Viewer.
- Supports import CSV data.
- Additional bug fixes and stability improvements.

3.0.2 - Dec 19, 2018
- Additional bug fixes and stability improvements.

3.0.1 - Dec 13, 2018
- Supports REGEXP operator for local SQLite databases when running query. Go Preferences - General - 'REGEXP operator' to enable or disable it.
- Data Viewer Filter also supports REGEXP if 'REGEXP operator' is enabled in Preferences.

3.0.0 - Dec 9, 2018
- Supports multiple windows.
- Supports Cmd + W to close selected tab.
- Additional bug fixes and stability improvements.

2.2.1 - Nov 12, 2018
- Display two groups in Paste Recent menu: Recent Files group and Recent Temporary Sessions group.
- Additional bug fixes and stability improvements.

2.2.0 - Nov 8, 2018
- [Database Diff] Supports generate SQL text that can let you transform a database into another.
- [Database Diff] Supports show only a summary of the differences between two databases.
- [Query Editor] Supports paste recent query sessions.
- [Query Editor] Supports save the query to a file.
- [Query Editor] Supports load the query from a file.

2.1.0 - Sep 26, 2018
- Supports Dark Mode for macOS Mojave.
- Supports customize syntax highlighting. 
- Add two default themes which are Light and Dark.
- In Query Editor, Use Cmd+ to make the font bigger, Cmd- to make the font smaller.
- Format Query, Toggle Comments, Toggle Wrap Lines have been moved to Editor menu.
- Fix an issue that causes syntax highlighting incorrect when typing block style comment.

2.0.1 - Sep 5, 2018
- [Database Statistics] Display table counts and each table's record count.
- [Database Statistics] Display each table's storage consumed and storage consumed detail, including table data storage consumed and indexes storage consumed. [* Available on macOS 10.13+]
- [Query Editor] Supports wrap lines. To toggle it on or off, go to Menu - Edit - Structure - Toggle Wrap Lines, or use shortcut Option + Cmd + L.
- [Query Editor] Improved SQL auto-completion.
- [Query Editor] Improved context menu.
- [Query Editor] Improved line number.

1.3.3 - Aug 10, 2018
- Additional bug fixes and stability improvements.

1.3.2 - Aug 10, 2018
- [Database Statistics] Supports adjust each column's width based on its content automatically.
- [Database Statistics] Display 'Records' in decimal style.

1.3.1 - Aug 8, 2018
- Supports show database statistics. For now, the statistics include each table's name and record count.

1.3.0 - Jul 29, 2018
- Additional bug fixes and stability improvements.

1.2.1 - Jul 20, 2018
- Fix a remote database connection issue when remote database's path contains special charachers.
- Shortcuts in Query Editor: Cmd + R to run query, Cmd + . to stop query, Cmd + I to format query.

1.1.0 - Jul 4, 2018
- Supports open remote SQLite database on iPhone or iPad with SQLiteFlow[iOS] installed.

1.0.5 - Jun 15, 2018
- Fix an issue that cause read database failed when database be replaced.
- Fix an issue that cause generate alter table script inaccurate.

1.0.4 - Jun 7, 2018
- Fix an issue that cause can't copy query results message to CSV.
- Additional bug fixes and stability improvements.

1.0.3 - May 11, 2018
- Toggle comments in Query Editor.
- Improvement for Format Query.
- Improvement for Syntax Highlighting.

1.0.2 - May 8, 2018
- Attach opened databases.
- Press enter to open Data Viewer for selected table.

1.0.1 - May 4, 2018
- Initial public release.

[Home](./)
