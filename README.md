memcache-dump
=============

Dump and restore your memcache information


Fist you must install the followings libraries (ubuntu/debian).

	apt-get install python-memcache
	apt-get install libmemcached-tools

## memcachedump

	python memcachedump.py -f memcachedumpfile -h 127.0.0.1 -p 11211

Options

	-f: output file (memcachedump defaults)
	-h: host of memcache machine (127.0.0.1 defaults)
	-p: port (11211 defaults)
