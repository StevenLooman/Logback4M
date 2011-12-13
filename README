Quick intro
===========

1)	_block
2) 		logback4m:xml_configurator.read_configuration()
3) 		_local l_logger << logback4m:logger_factory.get_logger(:example_logger)
4) 		l_logger.debug("log message")
5)	_endblock
$

Line 2 reads config.xml and configures the logger. Config.xml is found the resources directory of the logback4m module. The options/format for this file can be found at [Logback manual - configuration](http://logback.qos.ch/manual/configuration.html).

Line 3 creates a new logger with the name example_logger. Default log levels (for the root-logger) are defined in config.xml.

Line 4 logs a debug message. If the default (root logger) level is high enough, the message will be logged, otherwise not.
