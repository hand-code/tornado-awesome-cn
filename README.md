Awesome Tornado [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hand-code/tornado-awesome)
=============

> 通用Tornado 的资源
---------

- 网站资源
 - [Tornado构建的站点列表](http://tornado.poweredsites.org)
 - [Tornado 相关的一些snippets code](http://tornadogists.com/)
 - [中文镜像Tornado站](http://www.tornadoweb.cn)

> 用tornado.ioloop构建的异步客户端
---------
- [Amazon DynamoDB](http://aws.amazon.com/dynamodb/)
 - [asyncdynamo](https://github.com/bitly/asyncdynamo)
- [Amazon Web Services](http://aws.amazon.com)
 - [tornado-botocore](https://github.com/nanvel/tornado-botocore)
- [AMQP](http://www.amqp.org/)
 - [stormed-amqp](https://github.com/paolo-losi/stormed-amqp)
 - [amqp](http://www.amqp.org/)
- [Beanstalkd](http://kr.github.com/beanstalkd/)
 - [beanstalkt](https://bitbucket.org/nephics/beanstalkt)
- [CouchDB](http://couchdb.apache.org/)
 - [trombi](http://github.com/inoi/trombi)
 - [corduroy](http://samizdat.cc/corduroy)
 - [tornado-couchdb](https://bitbucket.org/nephics/tornado-couchdb/overview)
- DNS
 - [tornado-dns](https://github.com/eklitzke/tornado-dns)
- [HBase](http://hbase.apache.org/)
 - [pyhbase](https://github.com/mjrusso/pyhbase)
- [Memcached](http://memcached.org/)
 - [tornado-memcache](https://github.com/dpnova/tornado-memcache)
 - [asyncmc](https://github.com/jeffhodsdon/asyncmc)
 - [asyncmc](https://github.com/ErDmKo/asyncmc)
 - [memnado](https://github.com/clofresh/memnado)
- [MongoDB](http://www.mongodb.org/) 
 - [asyncmongo](http://github.com/bitly/asyncmongo)
 - [Motor](http://github.com/mongodb/motor/)
 - [PyEnty](https://github.com/leodesouza/pyenty/)
- [MySQL](http://www.mysql.com/)
 - [amysql](https://github.com/abael/amysql) pure C language, base on Python native socket(support Python async).
 - [adb](https://github.com/ovidiucp/pymysql-benchmarks) 
 - [adisp](http://mysql-python.sourceforge.net/)
 - [TorMySQL](https://github.com/snower/TorMySQL) Tornado asynchronous MySQL Driver by PyMySQL
 - [Tornado-MySQL](https://github.com/PyMySQL/Tornado-MySQL) PyMySQL fork for Tornado
* [[NATS|http://nats.io/]]
  * [[python-nats|https://github.com/nats-io/python-nats]] A Python async client for the NATS messaging system.
* [[PostgreSQL|http://www.postgresql.org/]]
  * [[momoko|https://github.com/FSX/momoko]] - [[psycopg|http://initd.org/psycopg/]] wrapper.
  * [[adb|https://github.com/ovidiucp/pymysql-benchmarks]] - 
[[adisp|https://launchpad.net/adisp]]/[[psycopg|http://initd.org/psycopg/]] based
  * [[queries|https://github.com/gmr/queries]] - [[psycopg|http://initd.org/psycopg/]] wrapper with an eye on ease of use.
* [[PrestoDB|https://prestodb.io/]]
  * [[prestornado|https://github.com/jianingy/prestornado]] Asynchronous PrestoDB (forked from PyHive.presto)
* [[RabbitMQ|http://www.rabbitmq.com]]
  * [[Pika|https://github.com/pika/pika]]
* [[Redis|http://redis.io/]]
  * [[tornado-redis|https://github.com/leporo/tornado-redis]] (fork of [[brukva|https://github.com/evilkost/brukva]])
  * [[tornadis|https://github.com/thefab/tornadis]]
* [[RethinkDB|https://www.rethinkdb.com/]] 
  * [[rethinkdb|https://www.rethinkdb.com/docs/async-connections/#python-with-tornado-or-twisted]]
* Schedule
  * [[chronos|https://github.com/thomashuang/chronos]]
* [[Socket.IO|http://socket.io/]]
  * [[tornadio2|https://github.com/MrJoes/tornadio2]]
* Socks5 Proxy Server
  * [[Fukei|https://github.com/thomashuang/Fukei]]
* [[Solr|http://lucene.apache.org/solr/]]
  * [[pysolr-tornado|https://github.com/nieldomingo/pysolr-tornado]] based on [[pysolr|https://github.com/toastdriven/pysolr]]
* [[subprocess|http://docs.python.org/library/subprocess.html]] (local)
  * [[AsyncProcessMixIn|https://gist.github.com/pplante/489093]]
* [[SMTP|http://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol]]
  * [[smtp|https://gist.github.com/1358253]]
* XML-RPC/JSON-RPC
  * [[tornadorpc|https://github.com/joshmarshall/tornadorpc]]
  * [[tornado-fastrpc|https://github.com/seznam/tornado-fastrpc]] XML-RPC and FastRPC (see FastRPC [[https://github.com/seznam/fastrpc]]) client
* [[Server-sent events (EventSource)|http://dev.w3.org/html5/eventsource/]]
  * Python/Tornado's [[event-source-library|https://github.com/guyzmo/event-source-library]]
  * [Tornado-sent events](https://github.com/mivade/tornadose)

## Web API Libraries
* [[async_dropbox|https://github.com/bdarnell/async_dropbox]] - Asynchronous python interface to the Dropbox API.
* [[tornado_dropcache|https://github.com/singerb/tornado_dropcache]] - High-level, caching Dropbox interface built on top of async_dropbox.
* [[asyncboto|https://github.com/almost/asyncboto]] - PoC/alpha async version of [[boto|http://code.google.com/p/boto/]] (for [[AWS|http://aws.amazon.com/]]).
* [[async-python-twitter|https://github.com/kzk/async-python-twitter]] - Asynchronous version of (an outdated 0.6-devel version) of [[python-twitter|http://code.google.com/p/python-twitter/]].
* [[greplin-tornado-kissmetrics|https://github.com/Greplin/greplin-tornado-kissmetrics]] - A client for the Kissmetrics API.
* [[greplin-tornado-mixpanel|https://github.com/Greplin/greplin-tornado-mixpanel]] - A client for the Mixpanel API.
* [[greplin-tornado-ses|https://github.com/Greplin/greplin-tornado-ses]] - An asynchronous client for Amazon SES.
* [[greplin-tornado-sendgrid|https://github.com/Greplin/greplin-tornado-sendgrid]] - A client for the Sendgrid API.
* [[greplin-tornado-stripe|https://github.com/Greplin/greplin-tornado-stripe]] - Tornado bindings for Stripe's API.
* [[sso|https://github.com/liftoff/GateOne/blob/master/gateone/auth/sso.py]] - Tornado authentication handler to perform Single Sign-On (SSO) via Kerberos.
* [[TweetStream|https://github.com/joshmarshall/TweetStream]] - Simple Twitter Streaming client for Tornado.
* [[lastfmclient|https://github.com/jakubroztocil/lastfmclient]] - A client for the Last.fm API. Includes an async client for Tornado.
* [[tornado_apns|https://github.com/kernel1983/tornado_apns]] - Async APNS for iOS device push notification.
* [[tornado_s3|https://github.com/kernel1983/tornado_s3]] - Async library for AWS S3.
* [[tornado_ses|https://github.com/kernel1983/tornado_ses]] - Async library for AWS SES email sending.

## Helper Libraries / Frameworks
* [[AsyncMongo-Sessions|https://github.com/joerussbowman/AsyncMongo-Sessions]] - A sessions library for Tornado using AsyncMongo
* [[userapp.tornado|https://github.com/userapp-io/userapp-tornado]] - Tornado specific decorators for easy user authentication using [[UserApp|https://www.userapp.io/]].
* [[dustdevil|https://github.com/inviscid/dustdevil]] - Lightweight session handling class w/ multiple backends
and MongoDB.
* [[greenado|https://github.com/virtuald/greenado]] - Greenlet-based coroutines for Tornado
* [[handlerbag|https://github.com/parente/handlerbag]] - A little layer on top of Tornado to manage a bag of dynamic utility handlers
* [[OpenCoweb|http://github.com/opencoweb/coweb]] - Framework for building cooperative web apps; includes a Tornado coweb server based on the [[cometd|http://cometd.org/]] [[Bayeux|http://cometd.org/documentation/bayeux/spec]] protocol
* [[pycket|https://github.com/diogobaeder/pycket]] - session library, written for use with Redis or Memcached, and Tornado
* [[Shelter|https://github.com/seznam/shelter]] - tool for creation new application skeleton, management commands or service processes.
* [[shrapnel|https://github.com/kurtiss/shrapnel]] -  a set of tools for building webapps on top of Tornado
* [[Swirl|http://code.naeseth.com/swirl/]] - async decorator (made redundant in Tornado 2.1+ by tornado.gen?)
* [[Tinman|http://github.com/gmr/tinman]] - support package including an application wrapper/runner and a set of handy decorators
* [[Tornado Add-ons|http://github.com/nod/tornado_addons]] - Small library of useful addons, including a @route decorator.
* [[tornado-routes|https://github.com/troolee/tornado-routes]] — @route decorator. Supports `include`, `reverse_url` by name and/or handler class name.
* [[tornado-util|https://github.com/hhru/tornado-util]] - helpers functions that emerged from production
use of Tornado in hh.ru
* [[tornado-utils|https://github.com/peterbe/tornado-utils]] - A bunch of Tornado specific python utilities originally used on Kwissle.com
* [[Tornado Tracing|http://github.com/bdarnell/tornado_tracing]] - Performance tracing library for Tornado
* [[Tornado Tools|http://truemped.github.com/tornadotools/]] - This is a small library integrating other libraries as well as providing smaller tools for working with Tornado
* [[Torneira|https://github.com/marcelnicolay/torneira]] - Torneira is a lightweight and rapid web framework build on top of Tornado
* [[tornado-celery|https://github.com/mher/tornado-celery]] - Celery task queue integration with Tornado
* [[tornado-spdy|https://github.com/alekstorm/tornado/tree/spdy]] - Fork of Tornado providing experimental SPDY v2 support.
* [[Toro|http://toro.readthedocs.org/]] - Locks and queues for Tornado before 4.2 (beginning in version 4.2, [[Toro's locks and queues are included in Tornado itself|http://www.tornadoweb.org/en/stable/releases/v4.2.0.html#new-modules-tornado-locks-and-tornado-queues]])
* [[Mojo|https://github.com/lonelycode/Mojo]] - A django-like framework for Tornado, with lightweight ORM and backend support
* [[tornado-encookie|https://github.com/whardier/tornado-encookie]] - Encrypted cookie support for Tornado (quick session replacement)
* [[twork|https://github.com/bufferx/twork]] - twork is a Tornado app frameWork
* [[mownfish|https://https://github.com/Ethan-Zhang/mownfish]] - A productional skeleton for Tornado
* [[Tornado-JSON|https://github.com/hfaran/Tornado-JSON]] - A simple JSON API framework based on Tornado
* [[Torngas|https://github.com/mqingyn/torngas]] - A Django like framework based on Tornado
* [[Tokit|https://github.com/manhgd/tokit]] - A library for bootstrap project based on Tornado
* [[tortik|https://github.com/glibin/tortik]] - A microframework atop of Tornado for easier develop of SOA-based (microservices) applications
* [[app-turbo|https://github.com/wecatch/app-turbo]] - A web framework based on Tornado for easier develop, scaling up and maintenance
* [[Blackgate|https://github.com/soasme/blackgate]] - An API gateway application based on Tornado

## Projects Built on Tornado
* [[dillinger|https://github.com/ExtensionFM/dillinger]] - Tornado + ZMQ proof of concept.
* [[Eucalyptus User Console|http://coderslike.us/2012/11/11/installing-the-eucalyptus-console-from-source-and-packages/]] - User Console using Tornado, boto, jQuery.
* [[Gate One|https://github.com/liftoff/GateOne]] - Web-based Terminal Emulator and SSH Client.
* [[GraphTerm|https://github.com/mitotic/graphterm]] - A "graphical terminal interface" that extends xterm by adding GUI-like features and session sharing
* [[hbase-tornado-demo|https://github.com/hammer/hbase-tornado-demo]] - A demonstration of how to use HBase and Tornado to build a web application.
* [[Image Resizing Server|https://github.com/noony/ImageResizingServer/]] - This server provides a service to resize and crop images with a simple API GET.
* [[iPython Notebook|http://ipython.org/ipython-doc/dev/interactive/htmlnotebook.html]] - interactive notebook for running/sharing Python code w/ rich data display (plotting, math symbols, etc)
* [[protocolbuf-rpc-server|http://code.google.com/p/protocolbuf-rpc-server/source/browse/#svn%2Ftrunk%2Fprotocolbuf-rpc-serverhttps]] - RPC server using protobuf
* [[tornado-protobuf-utils|https://github.com/hhru/tornado-protobuf-utils]] - Protobuf over http client
* [[ragechats|https://github.com/ragechats/ragechats]] - Reddit themed real-time chats using Tornado, WebSockets, and Redis.
* [[redqueue|https://github.com/superisaac/redqueue]] - A light-weight queue server in python tornado, it uses memcache protocol and store queues persistently.
* [[Scale0|https://github.com/joerussbowman/Scale0]] - A proxy server using zeromq and Tornado.
* [[selene|https://github.com/puentesarrin/selene]] -  A simple CMS for blogging built with Tornado and MongoDB
* [[spotnado|https://github.com/mkjones/spotnado]] - A Tornado webserver for controlling Spotify.
* [[Spyder|http://retresco.github.com/Spyder/]] - Spyder is a scalable web-spider written in Python using the non-blocking Tornado library and ZeroMQ as messaging layer. The messages are serialized using Thrift.
* [[tornado-blog|https://github.com/bgolub/tornado-blog]] - Blog system (more involved than the demo).
* [[tornadio-chat|https://github.com/gabrielfalcao/tornadio-chat]] - socket.io + tornado chat example.
* [[tornado-couchdb-pubsubhubbub-aggregator|https://github.com/bsstoner/tornado-couchdb-pubsubhubbub-aggregator]] - Simple Tornado app that accepts posts from PubSubHubBub feeds, saves the entries to couchdb and streams them live to the page as they come in.
* [[torque|https://github.com/thruflo/torque]] - A web hook task queue based on tornado and redis.
* [[tweetwatcher|https://github.com/joshmarshall/tweetwatcher]] - Tiny Tornado site for monitoring Twitter Streaming API with Websockets / long polling.
* [[uploadr|https://github.com/nbarrientos/uploadr]] - Simple file hosting service written on top of Tornado.
* [[toocool|https://github.com/peterbe/toocool]] - Twitter app http://TooCoolFor.Me (redis, Celery, MongoDB).
* [[restful-distributed-lock-manager (RDLM)|https://github.com/thefab/restful-distributed-lock-manager]] - A RESTful Distributed Lock Manager
* [[ spiro|https://github.com/koblas/spiro]] - A Tornado Web Crawler (Distributed) 
* [[ blackhole|http://blackhole.io]] - Tornado powered MTA (mail transport agent) that is designed for handling large volumes of email without handling any of the messages and doing no disk bound I/O.
* [[hoard|https://github.com/kura/hoard]] - A Tornado powered honey pot MTA built on top of Blackhole
* [[torelp|https://github.com/whardier/torelp]] - Tornado based RELP server (Reliable Event Logging Protocol) designed to receive logs from RELP capable log servers (rsyslog)
* [[Wpull|https://github.com/chfoo/wpull]] - Wget-compatible web downloader.
* [[graphite-beacon|https://github.com/klen/graphite-beacon]] - Graphite Alerting application.
* [[ohmyrepo|https://github.com/no13bus/ohmyrepo]] - It use github webhook and highchart to analysis and show that who star your repository, where are they and show the top 5 followers. And you can fellow some users.

## Tornado Ports
* [[Cyclone|http://github.com/fiorix/cyclone]] - Tornado ported to the Twisted event loop.
* [[gtornado|https://github.com/wil/gtornado]] - Monkey-patched module to use gevent.

## Tornado Powered Sites
