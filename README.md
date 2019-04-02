memcached-dump
=============

Dump and restore your memcached information

## requeriments

Fist you must install the followings libraries (ubuntu/debian).

	apt-get install python-memcache
	apt-get install libmemcache-tools

## memcacheddump

Usage:

	python memcacheddump.py -f memdump -h 127.0.0.1 -p 11211

Options

	-f: output file (memdump defaults)
	-h: host of memcached machine (127.0.0.1 defaults)
	-p: port (11211 defaults)

## memcachedrestore

Usage:

	python memcachedrestore.py -f memdump -h 127.0.0.1 -p 11211

Options

	-f: output file (memdump defaults)
	-h: host of memcached machine (127.0.0.1 defaults)
	-p: port (11211 defaults)
