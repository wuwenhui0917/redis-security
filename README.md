Building Redis
--------------

Redis can be compiled and used on Linux, OSX, OpenBSD, NetBSD, FreeBSD.
We support big endian and little endian architectures, and both 32 bit
and 64 bit systems.

It may compile on Solaris derived systems (for instance SmartOS) but our
support for this platform is *best effort* and Redis is not guaranteed to
work as well as in Linux, OSX, and \*BSD there.

It is as simple as:

    % make

You can run a 32 bit Redis binary using:

    % make 32bit

After building Redis, it is a good idea to test it using:

    % make test

Fixing build problems with dependencies or cached build options


Running Redis
-------------

To run Redis with the default configuration just type:

    % cd src
    % ./redis-server

If you want to provide your redis.conf, you have to run it using an additional
parameter (the path of the configuration file):

    % cd src
    % ./redis-server /path/to/redis.conf




config securite-Redis
---------

redis.conf配置中
clientip配置项：主要配置白名单ip，可配置ip段如

clientip  192.168.23.131,192.168.23.12,192.168.192.34,192.168.234,10.233.238.*


note:
---------
此版本如有bug和需要请联系wuwenhui0917@163.com

