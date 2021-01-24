---
layout: default
title: SQLiteFlow
description: SQLiteFlow for Mac release notes.
---

4.8.3 - 2021年1月24日
- SQLite バージョン 3.34.1 (2021-01-20) をサポート。

4.8.2 - 2021年1月10日
- 日本語のサポート。

4.8.1 - Dec 13, 2020
- Supports full-height sidebar in macOS 11.
- Additional bug fixes and stability improvements.

4.8.0 - Dec 11, 2020
- Add supports for Apple Silicon Mac.
- Data Editor, supports copy data as insert/update statement.
- Supports dump database to a SQL file.
- Supports SQLite version 3.34.0 (2020-12-01).
- Fix an issue that may cause user SQL file move to app's temp query session folder after a crash happen.
- Additional bug fixes and stability improvements.

4.7.0 - Nov 4, 2020
- Significant performance improvement to Data Editor and Query Results when there are large numbers (like hundreds) of columns exist.
- This version of SQLiteFlow requires macOS 10.14 or later.
- Additional bug fixes and stability improvements.

4.6.1 - Sep 15, 2020
- Fix an issue that may cause UI glitch when in full screen mode.
- Additional bug fixes and stability improvements.

4.6.0 - Sep 8, 2020
- Supports export data as JSON.
- Supports export data as Markdown.

4.5.1 - Aug 29, 2020
- Bug fixes and stability improvements.

4.5.0 - Aug 28, 2020
- Tabbing behavior changes. Previously, close a window means hide the window, and all tabs in this window still remain opened. Now, close a window means close all tabs in this window and close the window.
- Now SQLiteFlow use the system tab bar instead of the previous custom one to get the most out of system offered features.
- Supports customize toolbar and new toolbar icons.
- Query Editor's auto save feature has been improved.
- Supports SQLite version 3.33.0 (2020-08-14).
- Additional bug fixes and stability improvements.

4.3.1 - Jul 8, 2020
- Filter in Data Editor now supports "!=" and "not contains" operator.

4.3.0 - Jul 3, 2020
- Supports pick a journal mode when creating a database.
- Table Schema, supports reorder columns using drag and drop. 
- Table Schema, add support for setting a table to WITHOUT ROWID table.
- Supports export data through table/view's context menu in Database List.
- Add more Touch Bar supports.
- Additional bug fixes and stability improvements.

4.2.0 - Jun 28, 2020
- Add some basic Touch Bar supports.

4.1.1 - Jun 22, 2020
- Supports SQLite version 3.32.3 (2020-06-18).
- Additional bug fixes and stability improvements.

4.1.0 - Jun 19, 2020
- Allow user to choose the macOS embedded SQLite library or the latest SQLite library (currently SQLite 3.32.2) to work with.
- Additional bug fixes and stability improvements.

4.0.1 - May 25, 2020
- Add an option 'Allow select all file types' to Open Database panel to allow user opening database files with arbitrary extensions from the Open Database panel.
- Fix an issue that cause the value of 'Enable Foreign Key Constraints' and 'Tab Key Behavior' not display correctly in Preference.

4.0.0 - May 22, 2020
- Database List, supports right click a table name to rename a table.
- Format Query, allow user choose the prefer indent using Spaces or Tabs.
- Format Query, allow user to set indent width. Now the default indent width is 4 to match the default Tab Width which is also 4. The default indent width is 3 in previous versions when the value is not customizable.
- Format Query, allow user to set comma that split column definition style to leading or trailing.
- Text Editing, allow user to set tab width. The default tab width is 4.
- Text Editing, allow user to set the behavior of the Tab key to inserts tab character or inserts spaces.
- The setting 'Enable Foreign Key Constraints' now move from Data Editor to Preference - General, so now this setting will affects to Data Editor, Query Editor and Import CSV.
- Enhancement for Alter Table.
- Import/Export CSV now supports use semicolon(;) or tab as delimiter to import/export data.
- Import CSV, fix an issue that cause last row is not imported when the CSV text's last field on the last record is not populated.
- Additional bug fixes and stability improvements.

3.8.1 - Aug 22, 2019
- Change 'Set NULL' to 'Set NULL & Apply' in Hex Editor.
- Syntax Highlighting & Format Query now supports UPSERT clause and window function for compatible with the future version of macOS.
- Additional bug fixes and stability improvements.

3.8.0 - Aug 16, 2019
- Inside Explorer. Show inside data structure of SQLite database file, journal file, WAL file or WAL-Index file.
- Now when editing data in Data Editor, you can tap Tab key to switch column.
- Now when editing data in Data Editor, you can tap ESC key can undo changes in the editing field.
- Now when editing data in Data Editor, you can tap Enter key to finish editing data, then tap Enter key again can trigger saving the edited data to database.
- Add an extra column at the left edge of Data Editor for helping you select rows easily.
- Copy data as CSV in Data Editor and Query Result now will respect column order shows in UI.
- Add 'Export' button in Data Editor. So you can choose 'Selected Rows', 'Displaying Rows' or 'Whole Table' with/without 'Include Header' to export data from a table/view to a CSV file.
- Add 'Export' button in Query Result. So you can choose 'Selected Rows' or 'Displaying Rows' with/without 'Include Header' to export data from query result or query message to a CSV file.
- Refresh database in Database List now can trigger opened tabs be refreshed too.

3.7.0 - Jun 23, 2019
- Support for Chinese (Simplified), Chinese (Traditional).
- Additional bug fixes and stability improvements.

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
