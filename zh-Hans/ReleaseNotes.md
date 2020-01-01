---
layout: default
title: SQLiteFlow
description: Mac SQLiteFlow 更新说明。
---

4.0.0 - 2020年1月1日
- “数据库列表”重命名为“浏览”。
- 在“浏览”中，支持打开/新建本地文件夹，SQLite数据库，SQL文件，CSV文件。
- 在“浏览”中，支持打开过滤文件。
- 在“浏览”中，支持打开外部SQL文件，CSV文件，过滤文件。
- 在“浏览”中，支持打开外部文件夹。需要iOS 13.0+或者iPasOS 13.0+支持。
- 支持显示最近使用文件。
- 在查询结果中支持以十六进制来显示Blob数据。
- 在数据编辑器和查询结果中，支持长按显示记录预览。需要iOS 13.0+或者iPasOS 13.0+支持。
- 在数据编辑器中增加启用外间约束支持。
- 在数据编辑器中编辑数据时，屏幕上方增加“完成”按钮来保存编辑。
- 在数据编辑器和查询结果中增加拷贝一行数据的功能。
- 现在，数据编辑器中的过滤已基于过滤文件。
- 在数据编辑器中，支持轻触过滤按钮来打开或者创建一个过滤文件。
- 在数据编辑器中，打开过滤文件后，用户可以编辑或者应用次过滤。
- 在数据编辑器中应用一个过滤后，用户可以轻触过滤按钮来选择“编辑过滤”，“移除过滤”或者“选择其它过滤”。
- 修复了一个在导入CSV文件时可能导致导入数据为乱码的问题。
- 修复了无法在查询结果中拷贝数据的问题。
- 其它问题修复与稳定性改善。

3.8.1 - 2019年8月22日
- 在十六进制编辑器中将”设置为NULL“改为”设置为NULL并应用“。
- 语法高亮与格式化查询支持upsert分句和window function以兼容未来版本的macOS。
- 其它问题修复与稳定性改善。

3.8.0 - 2019年8月16日
- 内部查看器，查看SQLite数据库文件，日志文件，WAL文件或者WAL-索引文件的内部结构。
- 现在数据编辑器编辑数据时，您可以使用Tab键来切换列。
- 现在数据编辑器编辑数据时，您可以使用ESC键来撤销对当前值的修改。
- 现在数据编辑器编辑数据时，您可以使用Enter键来完成编辑数据, 然后再使用Enter键来触发数据保存。
- 在数据编辑器中增加了左边栏来方便您选择行。
- 在数据编辑器中拷贝数据到CSV中列的顺序会根据UI中列的顺序变化而变化。
- 在数据编辑器中增加了“导出”按钮。您可以选择“已选行”，“显示中的行”或者“整个表”，以及是否“包含标题行”来从表/视图中导出数据到CSV文件。
- 在查询结果中增加了“导出”按钮。您可以选择“已选行”或者“显示中的行”，以及是否“包含标题行”来从查询结果或者查询消息中导出数据到CSV文件。
- 现在在数据库列表中刷新数据库会触发已打开的标签页一并刷新。

3.7.0 - 2019年6月28日
- 支持简体中文、繁体中文。
- 其它问题修复和稳定性更新。

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
