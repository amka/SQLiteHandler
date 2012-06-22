SQLite handler
=============

SQLite handler allow your application to write log messages directly to sqlite database.

Usage
-----
	logger = logging.getLogger('LoggerName')
	logger.setLevel(logging.DEBUG)
	logger.addHandler(SQLiteHandler('debug_log.sqlite'))
	logger.debug('Debug message')
