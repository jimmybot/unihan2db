# unihan2db

Python 3 script that converts unihan text data files into sqlite3 db tables for easy querying

1. Run ```./init``` to wget the Unihan data archive
2. Run ```python unihan2db.py``` will create an sqlite database in ```data/derived```

For convenience, source and output data files are included in this repo for easy download.
No guarantees that it is up to date with any unihan source data revisions.

- Input Unihan archive: https://github.com/jimmybot/unihan2db/blob/master/data/source/Unihan.zip?raw=true
- Output Sqlite DB: https://github.com/jimmybot/unihan2db/blob/master/data/derived/unihan.db?raw=true

