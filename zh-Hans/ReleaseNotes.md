---
layout: default
title: SQLiteFlow
description: Mac SQLiteFlow 更新说明。
---

4.5.1 - 2020年8月29日
- 问题修复与稳定性改善。

4.5.0 - 2020年8月28日
- 标签页行为改动。改动前，关闭窗口的意思是隐藏窗口，所有的标签页保持打开。现在，关闭窗口的意思是关闭这个窗口中的所有标签页并且关闭窗口。
- 现在SQLiteFlow使用系统提供的标签栏来取代之前的标签栏，以获得更多系统提供的功能。
- 支持自定义工具栏，并且设计了新的工具栏图标。
- 改进了查询编辑器的自动保存功能。
- 支持SQLite version 3.33.0 (2020-08-14)。
- 其它问题修复与稳定性改善。

4.3.1 - 2020年7月8日
- 为数据编辑器中的过滤器添加“!=“和“不包含”操作符支持。

4.3.0 - 2020年7月3日
- 新建数据库时支持选择日志模式。
- 修改表结构，支持使用拖拽来重新排序表列。
- 修改表结构，支持设置表的WITHOUT ROWID类型。
- 数据库列表中的表/视图的右键菜单支持导出数据。
- 添加更多触控栏支持。
- 其它问题修复与稳定性改善。

4.2.0 - 2020年6月28日
- 添加一些基本的触控栏支持。

4.1.1 - 2020年6月22日
- 支持SQLite 3.32.3 (2020-06-18)。
- 其它问题修复与稳定性改善。

4.1.0 - 2020年6月19日
- 支持选择使用macOS内嵌SQLite库，或者选择使用最新SQLite库（目前是SQLite 3.32.2）来工作。
- 其它问题修复与稳定性改善。

4.0.1 - 2020年5月25日
- 在打开数据库对话框中添加了一个“允许选择所有文件类型”的选项，来让用户能够在打开数据库对话框中，打开拥有自定义拓展名的数据库。
- 修复偏好设置中“启用外键约束“和”Tab键行为“的值没有显示正确的问题。

4.0.0 - 2020年5月22日
- 在数据库列表中，支持右键表名-重命名表名。
- 格式化查询，支持选择偏好缩进字符为空格或者Tabs。
- 格式化查询，支持设置缩进宽度。现在默认的缩进宽度为4，与默认Tab宽度（同样为4）相匹配。在之前版本中，这个值无法设置时，默认缩进宽度为3.
- 格式化查询，支持设置分隔列定义的逗号的风格，可选择在前或者在尾。
- 文本编辑，支持设置Tab宽度。
- 文本编辑，支持设置Tab键行为为插入tab字符或者插入空格。
- “启用外键约束”这个设置从数据编辑器移到了“偏好设置” - “通用”中，所以这个设置现在对数据编辑器，查询编辑器和导入CSV都可以生效了。
- 改进修改表结构。
- 导入/导出CSV现在支持了使用分号（;）或者tab来作为分隔符去导入/导出数据。
- 导入CSV，修复了一个当CSV文本的最后一行的最后一个值没有提供时，导入时无法导入最后一行的问题。
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
