# unihan2db

**WIP**

Python 3 script that converts unihan text data files into sqlite3 db tables for easy querying

First run ```./init``` to wget the Unihan data archive
Then run ```python unihan2db.py``` will create an sqlite database in ```data/derived```

For convenience, source and output data files are included in this repo for easy download.
No guarantees that it is up to date with any unihan source data revisions.

- input Unihan archive: https://github.com/jimmybot/unihan2db/blob/master/data/source/Unihan.zip?raw=true
- output Sqlite DB: https://github.com/jimmybot/unihan2db/blob/master/data/derived/unihan.db?raw=true

