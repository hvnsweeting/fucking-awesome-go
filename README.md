# Fucking Awesome Go

 A curated list with Github stars and forks stats based on awesome [awesome-go](https://github.com/avelino/awesome-go)

# Awesome Go [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

[Join us on Slack](https://gophers.slack.com/messages/awesome/) to chat with other awesome-go maintainers!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*


### Contents

- [Awesome Go](#awesome-go)
    - [Audio & Music](#audiomusic)
    - [Authentication & OAuth](#authentication--oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date & Time](#date--time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation & Generics](#generation--generics)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
    - [Windows](#windows)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)


## Audio/Music

*Libraries for manipulating audio.*

* [:octocat: flac](https://github.com/eaburns/flac) - A native Go FLAC decoder. :star: 40 :fork_and_knife: 5
* [:octocat: go-sox](https://github.com/krig/go-sox) - libsox bindings for go. :star: 31 :fork_and_knife: 4
* [PortAudio](https://code.google.com/p/portaudio-go/) - Go bindings for the PortAudio audio I/O library.
* [:octocat: portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. :star: 68 :fork_and_knife: 14
* [:octocat: taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. :star: 33 :fork_and_knife: 13
* [:octocat: vorbis](https://github.com/mccoyst/vorbis) - A "native" Go Vorbis decoder (uses CGO, but has no dependencies). :star: 6 :fork_and_knife: 1
* [:octocat: waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. :star: 88 :fork_and_knife: 8


## Authentication & OAuth

*Libraries for implementing authentications schemes.*

* [:octocat: Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library. :star: 82 :fork_and_knife: 16
* [:octocat: go-jose](https://github.com/square/go-jose) - A fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. :star: 406 :fork_and_knife: 41
* [:octocat: go.auth](https://github.com/bradrydzewski/go.auth) - Authentication API for Go web applications. :star: 273 :fork_and_knife: 24
* [:octocat: gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. :star: 222 :fork_and_knife: 41
* [:octocat: goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple provides out of the box. :star: 492 :fork_and_knife: 39
* [:octocat: httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. :star: 78 :fork_and_knife: 10
* [:octocat: jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). :star: 755 :fork_and_knife: 96
* [:octocat: oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. :star: 527 :fork_and_knife: 151
* [:octocat: osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library. :star: 663 :fork_and_knife: 129
* [:octocat: permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. :star: 118 :fork_and_knife: 8
* [:octocat: yubigo](https://github.com/GeertJohan/yubigo) - a Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application. :star: 37 :fork_and_knife: 4


## Command Line


### Standard CLI

*Libraries for building standard or basic Command Line applications*

* [:octocat: cli-init](https://github.com/tcnksm/cli-init) - The easy way to start building Golang command line application. :star: 377 :fork_and_knife: 30
* [:octocat: cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions :star: 1211 :fork_and_knife: 114
* [:octocat: codegangsta/cli](https://github.com/codegangsta/cli) - A small package for building command line apps in Go. :star: 3381 :fork_and_knife: 292
* [:octocat: go-flags](https://github.com/jessevdk/go-flags) - go command line option parser :star: 496 :fork_and_knife: 72
* [:octocat: kingpin](https://github.com/alecthomas/kingpin) - A command line and flag parser supporting sub commands. :star: 404 :fork_and_knife: 31
* [:octocat: liner](https://github.com/peterh/liner) - A Go readline-like library for command-line interfaces. :star: 234 :fork_and_knife: 36
* [:octocat: mitchellh/cli](https://github.com/mitchellh/cli) - A Go library for implementing command-line interfaces. :star: 330 :fork_and_knife: 24
* [:octocat: readline](https://github.com/chzyer/readline) - A pure golang implementation that provide most of features in GNU-Readline under MIT license. :star: 385 :fork_and_knife: 15
* [:octocat: ukautz/clif](https://github.com/ukautz/clif) - A small command line interface framework. :star: 57 :fork_and_knife: 2


### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces*

* [:octocat: chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. :star: 131 :fork_and_knife: 9
* [:octocat: color](https://github.com/fatih/color) - Versatile package for colored terminal output. :star: 551 :fork_and_knife: 42
* [:octocat: go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. :star: 118 :fork_and_knife: 8
* [:octocat: gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. :star: 303 :fork_and_knife: 22
* [:octocat: gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text. :star: 81 :fork_and_knife: 3
* [:octocat: termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. :star: 1182 :fork_and_knife: 118
* [:octocat: termtables](https://github.com/apcera/termtables) - A Go port of the Ruby library [terminal-tables](https://github.com/visionmedia/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output :star: 31 :fork_and_knife: 4
* [:octocat: termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). :star: 4027 :fork_and_knife: 159


## Configuration

*Libraries for configuration parsing*

* [:octocat: config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. :star: 45 :fork_and_knife: 9
* [:octocat: env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). :star: 63 :fork_and_knife: 4
* [:octocat: envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. :star: 72 :fork_and_knife: 2
* [:octocat: envconf](https://github.com/ian-kent/envconf) - Configuration from environment :star: 2 :fork_and_knife: 1
* [:octocat: envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. :star: 78 :fork_and_knife: 3
* [:octocat: gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections :star: 14 :fork_and_knife: 6
* [:octocat: gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy :star: 28 :fork_and_knife: 1
* [:octocat: ini](https://github.com/go-ini/ini) - Go package for read and write INI files :star: 126 :fork_and_knife: 9
* [:octocat: mini](https://github.com/FogCreek/mini) - A golang package for parsing ini-style configuration files :star: 82 :fork_and_knife: 7
* [:octocat: viper](https://github.com/spf13/viper) - Go configuration with fangs :star: 874 :fork_and_knife: 95

## Continuous Integration

*Tools for help with continuous integration*

* [:octocat: goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. :star: 163 :fork_and_knife: 33
* [:octocat: overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls :star: 8 :fork_and_knife: 1

## CSS Preprocessors

*Libraries for preprocessing CSS files*

* [:octocat: c6](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go :star: 291 :fork_and_knife: 11
* [:octocat: gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. :star: 318 :fork_and_knife: 15

## Data Structures

*Generic datastructures and algorithms in Go.*

* [:octocat: bitset](https://github.com/willf/bitset) - Go package implementing bitsets. :star: 168 :fork_and_knife: 40
* [:octocat: bloom](https://github.com/surge/bloom) - Bloom filters implemented in Go. :star: 67 :fork_and_knife: 10
* [:octocat: boomfilters](https://github.com/tylertreat/BoomFilters) - probabilistic data structures for processing continuous, unbounded streams :star: 626 :fork_and_knife: 26
* [:octocat: cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. :star: 122 :fork_and_knife: 5
* [:octocat: encoding](https://github.com/surge/encoding) - Integer Compression Libraries for Go. :star: 35 :fork_and_knife: 7
* [:octocat: go-datastructures](https://github.com/Workiva/go-datastructures) - a collection of useful, performant, and thread-safe data structures :star: 1907 :fork_and_knife: 103
* [:octocat: golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. :star: 296 :fork_and_knife: 35
* [:octocat: goskiplist](https://github.com/ryszard/goskiplist) - A skip list implementation in Go. :star: 88 :fork_and_knife: 22
* [:octocat: mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing :star: 193 :fork_and_knife: 11
* [:octocat: skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go :star: 24 :fork_and_knife: 6
* [:octocat: trie](https://github.com/derekparker/trie) - Trie implementation in Go :star: 86 :fork_and_knife: 12
* [:octocat: ttlcache](https://github.com/diegobernardes/ttlcache) - An in-memory LRU string-interface{} map with expiration for golang :star: 8 :fork_and_knife: 1
* [:octocat: willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. :star: 199 :fork_and_knife: 39

## Database

*Databases implemented in Go.*

* [:octocat: bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Go. :star: 2955 :fork_and_knife: 219
* [:octocat: cache2go](https://github.com/muesli/cache2go) - An in-memory key:value cache which supports automatic invalidation based on timeouts. :star: 36 :fork_and_knife: 13
* [:octocat: cockroach](https://github.com/cockroachdb/cockroach) - A Scalable, Geo-Replicated, Transactional Datastore :star: 5498 :fork_and_knife: 461
* [:octocat: couchcache](https://github.com/codingsince1985/couchcache) - A RESTful caching micro-service backed by Couchbase server. :star: 14 :fork_and_knife: 1
* [:octocat: diskv](https://github.com/peterbourgon/diskv) - A home-grown disk-backed key-value store. :star: 309 :fork_and_knife: 30
* [:octocat: forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. :star: 17 :fork_and_knife: 3
* [:octocat: GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. :star: 71 :fork_and_knife: 2
* [:octocat: go-cache](https://github.com/pmylund/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. :star: 346 :fork_and_knife: 69
* [:octocat: goleveldb](https://github.com/syndtr/goleveldb) - An implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in the Go. :star: 842 :fork_and_knife: 119
* [:octocat: groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. :star: 3950 :fork_and_knife: 373
* [:octocat: influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics :star: 6582 :fork_and_knife: 750
* [:octocat: ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. :star: 1366 :fork_and_knife: 150
* [:octocat: levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. :star: 250 :fork_and_knife: 55
* [:octocat: prometheus](https://github.com/prometheus/prometheus) -  Monitoring system and time series database. :star: 3232 :fork_and_knife: 227
* [:octocat: tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. :star: 2707 :fork_and_knife: 261
* [:octocat: tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. :star: 1359 :fork_and_knife: 119

*Database tools.*

* [:octocat: go-mysql](https://github.com/siddontang/go-mysql) - A go toolset to handle MySQL protocol and replication. :star: 106 :fork_and_knife: 35
* [:octocat: go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. :star: 144 :fork_and_knife: 27
* [goose](https://bitbucket.org/liamstask/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [:octocat: kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. :star: 1040 :fork_and_knife: 166
* [:octocat: migrate](https://github.com/mattes/migrate) - Database migration handling in Golang support MySQL,PostgreSQL,Cassandra and SQLite. :star: 391 :fork_and_knife: 62
* [:octocat: myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Support statement and row based replication. :star: 34 :fork_and_knife: 10
* [:octocat: orchestrator](https://github.com/outbrain/orchestrator) - MySQL replication topology manager & visualizer :star: 305 :fork_and_knife: 53
* [:octocat: pgweb](https://github.com/sosedoff/pgweb) - A web-based PostgreSQL database browser :star: 3028 :fork_and_knife: 133
* [:octocat: pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc., :star: 9 :fork_and_knife: 3
* [:octocat: sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. :star: 354 :fork_and_knife: 22
* [:octocat: vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. :star: 2904 :fork_and_knife: 364

*SQL query builder, libraries for building and using SQL.*

* [:octocat: Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use it with ease. :star: 182 :fork_and_knife: 7
* [:octocat: goqu](https://github.com/doug-martin/goqu) - An idiomatic SQL builder and query library. :star: 226 :fork_and_knife: 10
* [:octocat: scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. :star: 32 :fork_and_knife: 1
* [:octocat: Squirrel](https://github.com/lann/squirrel) - Go library that helps you build SQL queries. :star: 657 :fork_and_knife: 42


## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [:octocat: firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go :star: 36 :fork_and_knife: 7
    * [:octocat: go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using database/sql. :star: 29 :fork_and_knife: 11
    * [:octocat: go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert. :star: 72 :fork_and_knife: 3
    * [:octocat: go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver prototype in go language. :star: 236 :fork_and_knife: 50
    * [:octocat: go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that using database/sql. :star: 106 :fork_and_knife: 72
    * [:octocat: go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. :star: 1804 :fork_and_knife: 405
    * [:octocat: go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that using database/sql. :star: 957 :fork_and_knife: 226
    * [:octocat: gofreetds](https://github.com/minus5/gofreetds) Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). :star: 29 :fork_and_knife: 15
    * [:octocat: pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. :star: 1713 :fork_and_knife: 259

* NoSQL Databases
    * [:octocat: aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. :star: 132 :fork_and_knife: 42
    * [:octocat: arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. :star: 6 :fork_and_knife: 1
    * [:octocat: cayley](https://github.com/google/cayley) - A graph database with support for multiple backends. :star: 6373 :fork_and_knife: 530
    * [:octocat: go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go :star: 186 :fork_and_knife: 61
    * [:octocat: go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go :star: 27 :fork_and_knife: 10
    * [:octocat: gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK :star: 68 :fork_and_knife: 19
    * [gocql](http://gocql.github.io) - A Go language driver for Apache Cassandra.
    * [:octocat: gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. :star: 507 :fork_and_knife: 144
    * [:octocat: gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB :star: 659 :fork_and_knife: 62
    * [mgo](http://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [:octocat: neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang :star: 12 :fork_and_knife: 2
    * [:octocat: Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. :star: 60 :fork_and_knife: 13
    * [:octocat: neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang :star: 200 :fork_and_knife: 42
    * [:octocat: redigo](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database. :star: 1711 :fork_and_knife: 296
    * [:octocat: redis](https://github.com/go-redis/redis) - Redis client for Golang :star: 491 :fork_and_knife: 69
    * [:octocat: redis](https://github.com/hoisie/redis) - A simple, powerful Redis client for Go. :star: 472 :fork_and_knife: 159

* Search and Analytic Databases
    * [:octocat: bleve](https://github.com/blevesearch/bleve) - A modern text indexing library for go. :star: 2056 :fork_and_knife: 162
    * [:octocat: elastic](https://github.com/olivere/elastic) - Elasticsearch client for Google Go. :star: 397 :fork_and_knife: 89
    * [:octocat: elastigo](https://github.com/mattbaird/elastigo) - A Elasticsearch client library. :star: 624 :fork_and_knife: 169
    * [:octocat: goes](https://github.com/belogik/goes) - A library to interact with Elasticsearch. :star: 69 :fork_and_knife: 25

## Date & Time

*Libraries for working with dates and times.*

* [:octocat: now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. :star: 484 :fork_and_knife: 31
* [:octocat: timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. :star: 89 :fork_and_knife: 3


## Distributed Systems

*Packages that help with building Distributed Systems.*

* [:octocat: celeriac](https://github.com/svcavallar/celeriac.v1) - A library for adding support for interacting and monitoring Celery workers, tasks and events in Go :star: 1 :fork_and_knife: 0
* [:octocat: flowgraph](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer. :star: 3 :fork_and_knife: 0
* [:octocat: go-jump](https://github.com/dgryski/go-jump) - A port of Google's "Jump" Consistent Hash function. :star: 42 :fork_and_knife: 6
* [:octocat: gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. :star: 118 :fork_and_knife: 14
* [:octocat: grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. :star: 1191 :fork_and_knife: 145
* [:octocat: raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. :star: 386 :fork_and_knife: 50
* [:octocat: torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. :star: 970 :fork_and_knife: 39
    * [:octocat: dht](https://godoc.org/github.com/anacrolix/torrent/dht) - BitTorrent Kademlia DHT implementation. :star: 970 :fork_and_knife: 39

## Email

*Libraries that implement email creation and sending*

* [:octocat: douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. :star: 24 :fork_and_knife: 0
* [:octocat: email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. :star: 618 :fork_and_knife: 55
* [:octocat: go-dkim](https://github.com/toorop/go-dkim) - A DKIM library, to sign & verify email. :star: 7 :fork_and_knife: 1
* [:octocat: Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails. :star: 704 :fork_and_knife: 40
* [:octocat: MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface :star: 446 :fork_and_knife: 23
* [:octocat: SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email :star: 136 :fork_and_knife: 34
* [:octocat: smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine :star: 16 :fork_and_knife: 1



## Embeddable Scripting Languages

*Embedding other languages inside your go code*

* [:octocat: agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go :star: 189 :fork_and_knife: 16
* [:octocat: anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go :star: 197 :fork_and_knife: 14
* [:octocat: gisp](https://github.com/jcla1/gisp) - Simple LISP in Go :star: 293 :fork_and_knife: 20
* [:octocat: go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go :star: 218 :fork_and_knife: 17
* [:octocat: go-lua](https://github.com/Shopify/go-lua) - A port of the Lua 5.2 VM to pure Go :star: 483 :fork_and_knife: 23
* [:octocat: go-php](https://github.com/deuill/go-php) - PHP bindings for Go :star: 13 :fork_and_knife: 1
* [:octocat: go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API :star: %!f(<nil>) :fork_and_knife: %!f(<nil>)
* [:octocat: golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API :star: 226 :fork_and_knife: 56
* [:octocat: gopher-lua](https://github.com/yuin/gopher-lua) - a Lua 5.1 VM and compiler written in Go :star: 983 :fork_and_knife: 55
* [:octocat: otto](https://github.com/robertkrimen/otto) - A JavaScript interpreter written in Go :star: 1753 :fork_and_knife: 135
* [:octocat: purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go :star: 7 :fork_and_knife: 0


## Financial

*Packages for accounting and finance*

* [:octocat: accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang :star: 164 :fork_and_knife: 4
* [:octocat: decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers :star: 191 :fork_and_knife: 24


## Forms

*Libraries for working with forms.*

* [:octocat: bind](https://github.com/robfig/bind)  - Bind form data to any Go values :star: 8 :fork_and_knife: 2
* [:octocat: binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. :star: 390 :fork_and_knife: 28
* [:octocat: formam](https://github.com/monoculum/formam) - decode form's values into a struct. :star: 36 :fork_and_knife: 1
* [:octocat: forms](https://github.com/albrow/forms) - A framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. :star: 38 :fork_and_knife: 2
* [:octocat: nosurf](https://github.com/justinas/nosurf) - A CSRF protection middleware for Go. :star: 574 :fork_and_knife: 33


## Game Development

*Awesome game development libraries.*

* [:octocat: GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. :star: 190 :fork_and_knife: 12
* [:octocat: glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. :star: 66 :fork_and_knife: 6
* [:octocat: go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A* path finding algorithm :star: 127 :fork_and_knife: 11
* [:octocat: go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. :star: 7 :fork_and_knife: 0
* [:octocat: go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). :star: 255 :fork_and_knife: 57
* [:octocat: go3d](https://github.com/ungerik/go3d) - A performance oriented 2D/3D math package for Go :star: 88 :fork_and_knife: 10
* [:octocat: gonet](https://github.com/xtaci/gonet) - A game server skeleton implemented with golang :star: 573 :fork_and_knife: 227
* [:octocat: Leaf](https://github.com/name5566/leaf) - A lightweight game server framework :star: 332 :fork_and_knife: 88
* [:octocat: termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox :star: 540 :fork_and_knife: 26


## Generation & Generics

*Tools to enhance the language with features like generics via code generation*

* [:octocat: gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. :star: 599 :fork_and_knife: 39
* [:octocat: go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. :star: 653 :fork_and_knife: 42
* [:octocat: pkgreflect](https://github.com/ungerik/pkgreflect) - A Go preprocessor for package scoped reflection. :star: 26 :fork_and_knife: 3


## GUI

*Libraries for building GUI Applications*

* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK
* [:octocat: go-qml](https://github.com/go-qml/qml) - QML support for the Go language :star: 1531 :fork_and_knife: 138
* [:octocat: gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. :star: 216 :fork_and_knife: 11
* [:octocat: gotk3](https://github.com/conformal/gotk3) - Go bindings for GTK3. :star: 383 :fork_and_knife: 77
* [:octocat: gxui](https://github.com/google/gxui) - A Go cross platform UI library. :star: 3357 :fork_and_knife: 197
* [:octocat: sciter](https://github.com/oskca/sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. :star: 14 :fork_and_knife: 1
* [:octocat: ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. :star: 2444 :fork_and_knife: 142
* [:octocat: walk](https://github.com/lxn/walk) - Windows application library kit for Go. :star: 1062 :fork_and_knife: 207


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list. :star: 264 :fork_and_knife: 18

## Images

*Libraries for manipulating images.*

* [:octocat: bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips :star: 94 :fork_and_knife: 16
* [:octocat: geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. :star: 818 :fork_and_knife: 32
* [:octocat: gift](https://github.com/disintegration/gift) - Package of image processing filters. :star: 659 :fork_and_knife: 43
* [:octocat: go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. :star: 45 :fork_and_knife: 10
* [:octocat: go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library :star: 37 :fork_and_knife: 12
* [:octocat: go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. :star: 143 :fork_and_knife: 12
* [:octocat: go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. :star: 287 :fork_and_knife: 50
* [:octocat: go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. :star: 17 :fork_and_knife: 0
* [:octocat: imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. :star: 335 :fork_and_knife: 49
* [:octocat: imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing :star: 247 :fork_and_knife: 12
* [:octocat: imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. :star: 673 :fork_and_knife: 79
* [:octocat: img](https://github.com/hawx/img) - A selection of image manipulation tools. :star: 71 :fork_and_knife: 3
* [:octocat: picfit](https://github.com/thoas/picfit) - An image resizing server written in Go :star: 381 :fork_and_knife: 17
* [:octocat: resize](https://github.com/nfnt/resize) - Image resizing for the Go with common interpolation methods. :star: 893 :fork_and_knife: 91
* [:octocat: rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. :star: 108 :fork_and_knife: 6
* [:octocat: smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes :star: 158 :fork_and_knife: 20
* [:octocat: svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. :star: 447 :fork_and_knife: 44
* [:octocat: tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. :star: 12 :fork_and_knife: 5

## Logging

*Libraries for generating and working with log files.*

* [:octocat: glog](https://github.com/golang/glog) - Leveled execution logs for Go. :star: 835 :fork_and_knife: 152
* [:octocat: go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. :star: 12 :fork_and_knife: 5
* [:octocat: go-log](https://github.com/ian-kent/go-log) - A log4j implementation in Go. :star: 15 :fork_and_knife: 4
* [:octocat: go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. :star: 150 :fork_and_knife: 13
* [:octocat: log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. :star: 43 :fork_and_knife: 3
* [:octocat: log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go :star: 323 :fork_and_knife: 41
* [:octocat: logex](https://github.com/chzyer/logex) - An golang log lib, supports tracking and level, wrap by standard log lib :star: 19 :fork_and_knife: 2
* [:octocat: logger](http://github.com/azer/logger) - Minimalistic logging library for Go. :star: 50 :fork_and_knife: 5
* [:octocat: logrus](https://github.com/Sirupsen/logrus) - a structured logger for Go. :star: 1859 :fork_and_knife: 260
* [:octocat: logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). :star: 6 :fork_and_knife: 3
* [:octocat: logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. :star: 96 :fork_and_knife: 10
* [:octocat: logxi](https://github.com/mgutz/logxi) - A 12-factor app logger that is fast and makes you happy. :star: 192 :fork_and_knife: 7
* [:octocat: lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. :star: 220 :fork_and_knife: 20
* [:octocat: mlog](https://github.com/jbrodriguez/mlog) - A simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. :star: 2 :fork_and_knife: 3
* [:octocat: seelog](https://github.com/cihub/seelog) -   logging functionality with flexible dispatching, filtering, and formatting. :star: 523 :fork_and_knife: 83
* [:octocat: stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. :star: 27 :fork_and_knife: 4
* [:octocat: tail](https://github.com/ActiveState/tail) - A Go package striving to emulate the features of the BSD tail program. :star: 367 :fork_and_knife: 83

## Machine Learning

*Libraries for Machine Learning.*

* [:octocat: bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. :star: 259 :fork_and_knife: 35
* [:octocat: CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. :star: 298 :fork_and_knife: 29
* [:octocat: go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. :star: 67 :fork_and_knife: 13
* [:octocat: go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang :star: 95 :fork_and_knife: 20
* [:octocat: go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. :star: 29 :fork_and_knife: 7
* [:octocat: gobrain](https://github.com/goml/gobrain) - Neural Networks written in go :star: 54 :fork_and_knife: 9
* [:octocat: godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. :star: 4 :fork_and_knife: 1
* [:octocat: goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. :star: 1 :fork_and_knife: 0
* [:octocat: GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. :star: 2231 :fork_and_knife: 203
* [:octocat: golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go :star: 13 :fork_and_knife: 4
* [:octocat: goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go :star: 403 :fork_and_knife: 16
* [:octocat: goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. :star: 27 :fork_and_knife: 1
* [:octocat: libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. :star: 33 :fork_and_knife: 4
* [mlgo](https://code.google.com/p/mlgo/) - This project aims to provide minimalistic machine learning algorithms in Go.
* [:octocat: neural-go](https://github.com/schuyler/neural-go) - A multilayer perceptron network implemented in Go, with training via backpropagation. :star: 38 :fork_and_knife: 6
* [probab](https://code.google.com/p/probab/) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [:octocat: regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine :star: 74 :fork_and_knife: 9
* [:octocat: shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go :star: 71 :fork_and_knife: 16


## Messaging

*Libraries that implement messaging systems*

* [:octocat: dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. :star: 56 :fork_and_knife: 22
* [:octocat: EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. :star: 93 :fork_and_knife: 12
* [:octocat: go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. :star: 7 :fork_and_knife: 3
* [:octocat: go-nsq](https://github.com/bitly/go-nsq) - the official Go package for NSQ :star: 476 :fork_and_knife: 113
* [:octocat: gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. :star: 996 :fork_and_knife: 284
* [:octocat: machinery](https://github.com/RichardKnop/machinery) - An asynchronous task queue/job queue based on distributed message passing. :star: 568 :fork_and_knife: 42
* [:octocat: NATS](https://github.com/apcera/nats) - A lightweight and highly performant publish-subscribe and distributed queueing messaging system. :star: 476 :fork_and_knife: 72
* [:octocat: oplog](https://github.com/dailymotion/oplog) - A generic oplog/replication system for REST APIs :star: 33 :fork_and_knife: 7
* [:octocat: pubsub](https://github.com/tuxychandru/pubsub) - A simple pubsub package for go. :star: 70 :fork_and_knife: 9
* [:octocat: sarama](https://github.com/Shopify/sarama) - A Go library for Apache Kafka. :star: 686 :fork_and_knife: 128
* [:octocat: Uniqush-Push](https://github.com/uniqush/uniqush-push) - A redis backed unified push service for server-side notifications to mobile devices. :star: 731 :fork_and_knife: 108
* [:octocat: zmq4](https://github.com/pebbe/zmq4) - A Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). :star: 312 :fork_and_knife: 48


## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit*

* [:octocat: autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. :star: 9 :fork_and_knife: 0
* [:octocat: browscap_go](https://github.com/fromYukki/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). :star: 10 :fork_and_knife: 3
* [:octocat: go-multierror](https://github.com/hashicorp/go-multierror) - A Go (golang) package for representing a list of errors as a single error. :star: 161 :fork_and_knife: 4
* [:octocat: gopsutil](https://github.com/shirou/gopsutil) - A cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). :star: 754 :fork_and_knife: 129
* [:octocat: gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS :star: 868 :fork_and_knife: 59
* [:octocat: jobs](https://github.com/albrow/jobs) - A persistent and flexible background jobs library. :star: 280 :fork_and_knife: 15
* [:octocat: notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. :star: 88 :fork_and_knife: 8
* [:octocat: xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber :star: 4 :fork_and_knife: 0
* [:octocat: xstrings](https://github.com/huandu/xstrings) - A collection of useful string functions ported from other languages. :star: 281 :fork_and_knife: 20

## Natural Language Processing

*Libraries for working with human languages.*

* [go-eco](https://code.google.com/p/go-eco/) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [:octocat: go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. :star: 36 :fork_and_knife: 10
* [:octocat: go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. :star: 33 :fork_and_knife: 10
* [:octocat: golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2 :star: 10 :fork_and_knife: 3
* [:octocat: gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go :star: 31 :fork_and_knife: 14
* [:octocat: icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. :star: 15 :fork_and_knife: 1
* [:octocat: libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. :star: 8 :fork_and_knife: 6
* [:octocat: MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. :star: 41 :fork_and_knife: 9
* [:octocat: paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm :star: 10 :fork_and_knife: 3
* [:octocat: porter](https://github.com/a2800276/porter) - This is a fairly straighforward port of Martin Porter's C implementation of the Porter stemming algorithm. :star: 2 :fork_and_knife: 0
* [:octocat: porter2](https://github.com/surge/porter2) - Really fast Porter 2 stemmer. :star: 19 :fork_and_knife: 3
* [:octocat: segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) :star: 12 :fork_and_knife: 1
* [:octocat: snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). :star: 13 :fork_and_knife: 0
* [:octocat: stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. :star: 23 :fork_and_knife: 0
* [:octocat: textcat](https://github.com/pebbe/textcat) - A Go package for n-gram based text categorization, with support for utf-8 and raw text :star: 34 :fork_and_knife: 6

## Networking

*Libraries for working with various layers of the network*

* [:octocat: arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. :star: 19 :fork_and_knife: 4
* [:octocat: buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy :star: 108 :fork_and_knife: 5
* [:octocat: canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252) :star: 11 :fork_and_knife: 2
* [:octocat: dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. :star: 5 :fork_and_knife: 2
* [:octocat: dns](https://github.com/miekg/dns) - Go library for working with DNS :star: 1179 :fork_and_knife: 202
* [:octocat: ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. :star: 6 :fork_and_knife: 1
* [:octocat: ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). :star: 93 :fork_and_knife: 57
* [:octocat: go-stun](https://github.com/ccding/go-stun) - A go implementation of the STUN client (RFC 3489 and RFC 5389). :star: 53 :fork_and_knife: 15
* [:octocat: gopacket](https://github.com/google/gopacket) - A Go library for packet processing with libpcap bindings :star: 375 :fork_and_knife: 58
* [:octocat: gopcap](https://github.com/akrennmair/gopcap) - A Go wrapper for libpcap :star: 176 :fork_and_knife: 83
* [:octocat: gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions :star: 82 :fork_and_knife: 27
* [:octocat: gotcp](https://github.com/gansidui/gotcp) - A Go package for quickly writing tcp applications :star: 102 :fork_and_knife: 39
* [:octocat: graval](https://github.com/koofr/graval) - An experimental FTP server framework. :star: 4 :fork_and_knife: 0
* [:octocat: linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces :star: 13 :fork_and_knife: 0
* [:octocat: mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang :star: 183 :fork_and_knife: 38
* [:octocat: portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. :star: 16 :fork_and_knife: 0
* [:octocat: raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. :star: 9 :fork_and_knife: 1
* [:octocat: sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. :star: 192 :fork_and_knife: 50
* [:octocat: tcp_server](https://github.com/firstrow/tcp_server) - A Go library for building tcp servers faster. :star: 22 :fork_and_knife: 12
* [:octocat: utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. :star: 38 :fork_and_knife: 5

## OpenGL

*Libraries for using OpenGL in Go.*

* [:octocat: gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). :star: 116 :fork_and_knife: 13
* [:octocat: glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. :star: 186 :fork_and_knife: 28
* [:octocat: goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). :star: 47 :fork_and_knife: 1
* [:octocat: goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. :star: 20 :fork_and_knife: 1
* [:octocat: mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. :star: 96 :fork_and_knife: 14


## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [:octocat: beedb](https://github.com/astaxie/beedb) - A go ORM,support database/sql interface，pq/mysql/sqlite :star: 564 :fork_and_knife: 119
* [:octocat: beego orm](https://github.com/astaxie/beego/tree/master/orm) - A powerful orm framework for go. :star: 5412 :fork_and_knife: 1367
* [:octocat: go-store](https://github.com/gosuri/go-store) - A simple and fast Redis backed key-value store library for Go. :star: 59 :fork_and_knife: 3
* [:octocat: gomodel](https://github.com/cosiner/gomodel) - A lightweight, fast, orm-like library helps interactive with database. :star: 43 :fork_and_knife: 3
* [:octocat: GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. :star: 2713 :fork_and_knife: 299
* [:octocat: gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. :star: 1794 :fork_and_knife: 237
* [:octocat: hood](https://github.com/eaigner/hood) - Database agnostic ORM for Go. :star: 647 :fork_and_knife: 56
* [:octocat: QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. :star: 357 :fork_and_knife: 59
* [:octocat: upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. :star: 277 :fork_and_knife: 32
* [:octocat: Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. :star: 887 :fork_and_knife: 178
* [:octocat: Zoom](https://github.com/albrow/zoom) - A blazing-fast datastore and querying engine built on Redis. :star: 112 :fork_and_knife: 4


## Package Management

*Libraries for package and dependency management.*

* [:octocat: gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. :star: 186 :fork_and_knife: 9
* [:octocat: godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. :star: 2732 :fork_and_knife: 219
* [:octocat: gom](https://github.com/mattn/gom) - Go Manager - bundle for go. :star: 942 :fork_and_knife: 59
* [:octocat: goop](https://github.com/nitrous-io/goop) - A simple dependency manager for Go (golang), inspired by Bundler. :star: 724 :fork_and_knife: 39
* [:octocat: gopm](https://github.com/gpmgo/gopm) - Go Package Manager :star: 761 :fork_and_knife: 70
* [:octocat: gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. :star: 833 :fork_and_knife: 45
* [:octocat: johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git :star: 210 :fork_and_knife: 6
* [:octocat: nut](https://github.com/jingweno/nut) - Vendor Go dependencies :star: 231 :fork_and_knife: 12
* [:octocat: VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments :star: 79 :fork_and_knife: 3


## Resource Embedding

* [:octocat: go-bindata](https://github.com/jteeuwen/go-bindata) - Package that converts any file into managable Go source code. :star: 1321 :fork_and_knife: 98
* [:octocat: go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. :star: 86 :fork_and_knife: 5
* [:octocat: go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. :star: 586 :fork_and_knife: 32
* [:octocat: vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. :star: 46 :fork_and_knife: 3


## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [:octocat: blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms) :star: 84 :fork_and_knife: 12
* [:octocat: chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. :star: 238 :fork_and_knife: 39
* [:octocat: evaler](https://github.com/soniah/evaler) - A simple floating point arithmetic expression evaluator :star: 17 :fork_and_knife: 5
* [:octocat: ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages :star: 133 :fork_and_knife: 11
* [:octocat: geom](https://github.com/skelterjohn/geom) - 2D geometry for golang :star: 30 :fork_and_knife: 12
* [:octocat: go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go :star: 357 :fork_and_knife: 23
* [go-fn](https://code.google.com/p/go-fn/) - Mathematical functions written in Go language, that are not covered by math pkg
* [go-gt](https://code.google.com/p/go-gt/) - Graph theory algorithms written in "Go" language
* [:octocat: go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled) :star: 221 :fork_and_knife: 51
* [gocomplex](https://code.google.com/p/gocomplex/) - A complex number library for the Go programming language.
* [:octocat: gofrac](https://github.com/anschelsc/gofrac) - A (goinstallable) fractions library for go with support for basic arithmetic. :star: 2 :fork_and_knife: 2
* [:octocat: gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams :star: 56 :fork_and_knife: 8
* [:octocat: gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices. :star: 158 :fork_and_knife: 26
* [:octocat: gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. :star: 148 :fork_and_knife: 24
* [:octocat: goraph](https://github.com/gyuho/goraph) - A pure Go graph theory library(data structure, algorith visualization) :star: 159 :fork_and_knife: 19
* [gostat](https://code.google.com/p/gostat/) - A statistics library for the go language
* [mudlark-go](https://code.google.com/p/mudlark-go-pkgs/) - A collection of packages providing (hopefully) useful code for use in software using Google's Go programming language.
* [:octocat: pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go :star: 7 :fork_and_knife: 3
* [:octocat: stats](https://github.com/montanaflynn/stats) - A statistics package with common functions missing from the Golang standard library. :star: 493 :fork_and_knife: 22
* [:octocat: streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. :star: 1248 :fork_and_knife: 108
* [:octocat: vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code. (currently inactive) :star: 51 :fork_and_knife: 8


## Security

*Libraries that are used to help make your application more secure.*

* [:octocat: BadActor](https://github.com/jaredfolkins/badactor) - An in-memory, application-driven jailer built in the spirit of fail2ban :star: 143 :fork_and_knife: 2
* [:octocat: go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)" :star: 12 :fork_and_knife: 4

## Serialization

*Libraries and tools for binary serialization*

* [:octocat: go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go :star: 233 :fork_and_knife: 18
  * [:octocat: bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. :star: 49 :fork_and_knife: 7
* [:octocat: go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support :star: 441 :fork_and_knife: 56
* [:octocat: gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets :star: 214 :fork_and_knife: 30
* [:octocat: goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. :star: 568 :fork_and_knife: 104
* [:octocat: mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. :star: 467 :fork_and_knife: 65
* [:octocat: php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions :star: 37 :fork_and_knife: 14
* [:octocat: structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. :star: 18 :fork_and_knife: 1


## Server Applications

* [:octocat: algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. :star: 170 :fork_and_knife: 10
* [:octocat: Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. :star: 2392 :fork_and_knife: 164
* [:octocat: etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery. :star: 7853 :fork_and_knife: 1172
* [nsq](http://nsq.io/) - A realtime distributed messaging platform
* [:octocat: yakvs](https://github.com/sci4me/yakvs) - A small, networked, in-memory key-value store. :star: 3 :fork_and_knife: 0


## Template Engines

*Libraries and tools for templating and lexing.*

* [:octocat: ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. :star: 372 :fork_and_knife: 20
* [:octocat: amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. :star: 514 :fork_and_knife: 31
* [:octocat: damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. :star: 16 :fork_and_knife: 1
* [:octocat: ego](https://github.com/benbjohnson/ego) - A lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. :star: 213 :fork_and_knife: 12
* [:octocat: kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. :star: 65 :fork_and_knife: 6
* [:octocat: mustache](https://github.com/hoisie/mustache) - A Go implementation of the Mustache template language. :star: 762 :fork_and_knife: 102
* [:octocat: pongo2](https://github.com/flosch/pongo2) - A Django-like template-engine for Go. :star: 595 :fork_and_knife: 50
* [:octocat: raymond](https://github.com/aymerick/raymond) - A complete handlebars implementation in Go. :star: 26 :fork_and_knife: 1
* [:octocat: Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. :star: 444 :fork_and_knife: 60
* [:octocat: Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/) :star: 100 :fork_and_knife: 11


## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [:octocat: assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions :star: 4 :fork_and_knife: 1
    * [:octocat: assert](https://github.com/bmizerany/assert) - Asserts to Go testing :star: 117 :fork_and_knife: 30
    * [:octocat: bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them :star: 6 :fork_and_knife: 1
    * [:octocat: frisby](https://github.com/verdverm/frisby) - a REST API testing framework :star: 96 :fork_and_knife: 2
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go
    * [:octocat: go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code :star: 28 :fork_and_knife: 0
    * [:octocat: goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go :star: 225 :fork_and_knife: 14
    * [gocheck](http://labix.org/gocheck) - A more advanced testing framework alternative to gotest.
    * [:octocat: GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload :star: 1792 :fork_and_knife: 140
    * [:octocat: godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. :star: 22 :fork_and_knife: 0
    * [:octocat: GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language. :star: 109 :fork_and_knife: 17
    * [:octocat: gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. :star: 50 :fork_and_knife: 4
    * [:octocat: Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. :star: 20 :fork_and_knife: 2
    * [:octocat: restit](https://github.com/yookoala/restit) - A Go micro framework to help writing RESTful API integration test. :star: 19 :fork_and_knife: 1
    * [:octocat: Testify](https://github.com/stretchr/testify) - A sacred extension to the standard go testing package. :star: 1384 :fork_and_knife: 167

* Mock
    * [:octocat: counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects :star: 35 :fork_and_knife: 8
    * [:octocat: go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions :star: 138 :fork_and_knife: 23
    * [:octocat: go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. :star: 1 :fork_and_knife: 0
    * [:octocat: gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. :star: 98 :fork_and_knife: 9
    * [:octocat: mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter :star: 16 :fork_and_knife: 4

* Fuzzing and delta-debugging/reducing/shrinking
    * [:octocat: go-fuzz](https://github.com/dvyukov/go-fuzz) - A randomized testing system :star: 1053 :fork_and_knife: 59
    * [:octocat: gofuzz](https://github.com/google/gofuzz) - A library for populating go objects with random values :star: 194 :fork_and_knife: 10
    * [:octocat: gogenerate](https://github.com/arschles/gogenerate) - A Scalacheck-like library for Go :star: %!f(<nil>) :fork_and_knife: %!f(<nil>)
    * [:octocat: Tavor](https://github.com/zimmski/tavor) - A generic fuzzing and delta-debugging framework :star: 134 :fork_and_knife: 4

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [:octocat: blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go :star: 1525 :fork_and_knife: 229
        * [:octocat: github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer with fenced code block highlighting, clickable header anchor links. :star: 17 :fork_and_knife: 5
    * [:octocat: bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer :star: 265 :fork_and_knife: 14
    * [:octocat: enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). :star: 1 :fork_and_knife: 1
    * [:octocat: genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings :star: 35 :fork_and_knife: 2
    * [:octocat: go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. :star: 548 :fork_and_knife: 52
    * [:octocat: go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. :star: 10 :fork_and_knife: 0
    * [:octocat: go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs. :star: 229 :fork_and_knife: 62
    * [:octocat: go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions. :star: 96 :fork_and_knife: 26
    * [:octocat: go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. :star: 46 :fork_and_knife: 6
    * [:octocat: gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. :star: 17 :fork_and_knife: 5
    * [:octocat: gommon/gytes](https://github.com/labstack/gommon/tree/master/gytes) - Format bytes to string. :star: 81 :fork_and_knife: 3
    * [:octocat: gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts :star: 15 :fork_and_knife: 0
    * [:octocat: GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. :star: 2079 :fork_and_knife: 210
    * [:octocat: goregen](https://github.com/zach-klippenstein/goregen) - A library for generating random strings from regular expressions. :star: 11 :fork_and_knife: 2
    * [:octocat: guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. :star: 14 :fork_and_knife: 3
    * [:octocat: mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. :star: 77 :fork_and_knife: 14
    * [:octocat: slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. :star: 56 :fork_and_knife: 11
    * [:octocat: Slugify](https://github.com/avelino/slugify) - A Go slugify application that handles string. :star: 9 :fork_and_knife: 0
    * [:octocat: toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). :star: 650 :fork_and_knife: 95
* Utility
    * [:octocat: gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. :star: 111 :fork_and_knife: 5
    * [:octocat: kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. :star: 1 :fork_and_knife: 0
    * [:octocat: parth](https://github.com/codemodus/parth) - URL path segmentation parsing. :star: 4 :fork_and_knife: 0
    * [:octocat: xurls](https://github.com/mvdan/xurls) - Extract urls from text :star: 161 :fork_and_knife: 6


## Third-party APIs

*Libraries for accessing third party APIs.*

* [:octocat: anaconda](https://github.com/ChimeraCoder/anaconda) - A Go client library for the Twitter 1.1 API :star: 409 :fork_and_knife: 114
* [:octocat: aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. Caution: The SDK is currently in the process of being developed, and not everything may be working fully yet. :star: 2011 :fork_and_knife: 249
* [:octocat: brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. :star: 10 :fork_and_knife: 1
* [:octocat: facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API :star: 240 :fork_and_knife: 72
* [:octocat: gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API :star: 9 :fork_and_knife: 9
* [:octocat: gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. :star: 11 :fork_and_knife: 5
* [:octocat: geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder) and [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx) geocoding / reverse geocoding APIs. :star: 101 :fork_and_knife: 5
* [:octocat: github](https://github.com/google/go-github) - Go library for accessing the GitHub API. :star: 1306 :fork_and_knife: 283
* [:octocat: go-marathon](https://github.com/gambol99/go-marathon) - A Go library for interacting with Mesosphere's Marathon PAAS :star: 46 :fork_and_knife: 24
* [:octocat: goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages. :star: 582 :fork_and_knife: 221
* [:octocat: GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - a Go MusicBrainz WS2 client library :star: 14 :fork_and_knife: 6
* [:octocat: google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go :star: 423 :fork_and_knife: 77
* [:octocat: google-analytics](https://github.com/chonthu/go-google-analytics) - A simple wrapper for easy google analytics reporting :star: 3 :fork_and_knife: 0
* [:octocat: google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library :star: 228 :fork_and_knife: 46
* [:octocat: gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. :star: 49 :fork_and_knife: 9
* [:octocat: hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. :star: 90 :fork_and_knife: 26
* [:octocat: hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. :star: 84 :fork_and_knife: 24
* [:octocat: mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. :star: 10 :fork_and_knife: 1
* [:octocat: pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. :star: 7 :fork_and_knife: 1
* [:octocat: rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. :star: 3 :fork_and_knife: 0
* [:octocat: shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. :star: 6 :fork_and_knife: 1
* [:octocat: slack](https://github.com/nlopes/slack) - Slack API in Go. :star: 211 :fork_and_knife: 47
* [:octocat: smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. :star: 6 :fork_and_knife: 0
* [:octocat: snapchat](https://github.com/jamieomatthews/gosnap) - Go wrapper for the snapchat API :star: 28 :fork_and_knife: 0
* [:octocat: spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. :star: 5 :fork_and_knife: 0
* [:octocat: steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. :star: 7 :fork_and_knife: 0
* [:octocat: stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API :star: 307 :fork_and_knife: 63
* [:octocat: telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. :star: 55 :fork_and_knife: 10
* [:octocat: TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - A simple golang package to communicate with [themoviedb.org](https://themoviedb.org) :star: 2 :fork_and_knife: 0
* [:octocat: translate](https://github.com/poorny/translate) - Go online translation package :star: 6 :fork_and_knife: 0
* [:octocat: tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. :star: 0 :fork_and_knife: 0

## Utilities

*General utilities and tools to make your life easier.*

* [:octocat: coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go. :star: 1106 :fork_and_knife: 48
* [:octocat: delve](https://github.com/derekparker/delve) - Go debugger. :star: 2520 :fork_and_knife: 147
* [:octocat: fastlz](https://github.com/fromYukki/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang. :star: 2 :fork_and_knife: 0
* [:octocat: filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. :star: 38 :fork_and_knife: 3
* [:octocat: go-cron](https://github.com/rk/go-cron) - A simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. :star: 97 :fork_and_knife: 6
* [:octocat: go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications :star: 275 :fork_and_knife: 19
* [:octocat: go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. :star: 125 :fork_and_knife: 11
* [:octocat: go-rate](https://github.com/beefsack/go-rate) -  A timed rate limiter for Go :star: 171 :fork_and_knife: 8
* [:octocat: go-underscore](https://github.com/tobyhede/go-underscore) - A useful collection of helpfully functional Go collection utilities. :star: 803 :fork_and_knife: 42
* [:octocat: goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. :star: 14 :fork_and_knife: 0
* [:octocat: godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons :star: 209 :fork_and_knife: 11
* [:octocat: godotenv](https://github.com/joho/godotenv) - A Go port of Ruby's dotenv library (Loads environment variables from `.env`.) :star: 210 :fork_and_knife: 18
* [:octocat: godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. :star: 2876 :fork_and_knife: 256
* [:octocat: gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development. :star: 181 :fork_and_knife: 36
* [:octocat: golarm](https://github.com/msempere/golarm) - Fire alarms with system events. :star: 7 :fork_and_knife: 0
* [:octocat: gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. :star: 319 :fork_and_knife: 19
* [:octocat: goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images :star: 9 :fork_and_knife: 4
* [:octocat: goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language. :star: 383 :fork_and_knife: 57
* [:octocat: goreq](https://github.com/smallnest/goreq) - An enhanced simplified HTTP client based on gorequest. :star: 7 :fork_and_knife: 1
* [:octocat: gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go. :star: 472 :fork_and_knife: 58
* [:octocat: gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go :star: 48 :fork_and_knife: 5
* [:octocat: htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility :star: 406 :fork_and_knife: 20
* [:octocat: httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries. :star: 358 :fork_and_knife: 23
* [:octocat: hystrix-go](https://github.com/afex/hystrix-go) - Imprements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. :star: 313 :fork_and_knife: 26
* [:octocat: jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. :star: 15 :fork_and_knife: 1
* [:octocat: jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. :star: 32 :fork_and_knife: 1
* [:octocat: lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go :star: 56 :fork_and_knife: 3
* [:octocat: mp](https://github.com/sanbornm/mp) - A simple cli email parser. It currently takes stdin and outputs JSON. :star: 7 :fork_and_knife: 0
* [:octocat: multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers :star: 42 :fork_and_knife: 0
* [:octocat: netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. :star: 23 :fork_and_knife: 0
* [:octocat: ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost. :star: 5878 :fork_and_knife: 548
* [:octocat: okrun](https://github.com/xta/okrun) - go run error steamroller :star: 10 :fork_and_knife: 2
* [:octocat: panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. :star: 189 :fork_and_knife: 4
* [:octocat: peco](https://github.com/peco/peco) - Simplistic interactive filtering tool :star: 2608 :fork_and_knife: 84
* [:octocat: pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency :star: 41 :fork_and_knife: 1
* [:octocat: pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API :star: 28 :fork_and_knife: 3
* [:octocat: profile](https://github.com/davecheney/profile) - Simple profiling support package for Go :star: 354 :fork_and_knife: 20
* [:octocat: request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. :star: 77 :fork_and_knife: 7
* [:octocat: robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics :star: 92 :fork_and_knife: 5
* [:octocat: scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. :star: 67 :fork_and_knife: 4
* [:octocat: sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients. :star: 242 :fork_and_knife: 9
* [:octocat: spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. :star: 192 :fork_and_knife: 10
* [:octocat: sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package :star: 1314 :fork_and_knife: 104
* [:octocat: xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. :star: 685 :fork_and_knife: 190


## Validation

*Libraries for validation.*

* [:octocat: govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs :star: 720 :fork_and_knife: 72
* [:octocat: validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving :star: 307 :fork_and_knife: 23


## Version Control

*Libraries for version control.*

* [:octocat: gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks :star: 27 :fork_and_knife: 5
* [:octocat: git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. :star: 603 :fork_and_knife: 113
* [:octocat: go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. :star: 31 :fork_and_knife: 10
* [:octocat: hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. :star: 6 :fork_and_knife: 2


## Video

*Libraries for manipulating video.*

* [:octocat: aac/h264](https://github.com/nareix/codec) - Golang aac/h264 encoder and decoder. :star: 111 :fork_and_knife: 31
* [:octocat: gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. :star: 158 :fork_and_knife: 37
* [:octocat: goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. :star: 44 :fork_and_knife: 9
* [:octocat: gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. :star: 98 :fork_and_knife: 23


## Web Frameworks

*Full stack web frameworks.*

* [:octocat: Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. :star: 5412 :fork_and_knife: 1368
* [:octocat: Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. :star: 805 :fork_and_knife: 42
* [:octocat: Echo](https://github.com/labstack/echo) - A fast HTTP router (zero memory allocation) and micro web framework in Go. :star: 2513 :fork_and_knife: 159
* [:octocat: Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. :star: 4459 :fork_and_knife: 438
* [:octocat: Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io) :star: 109 :fork_and_knife: 6
* [:octocat: go-json-rest](https://github.com/ant0ine/go-json-rest) - A quick and easy way to setup a RESTful JSON API :star: 1906 :fork_and_knife: 192
* [:octocat: go-relax](https://github.com/codehack/go-relax) - A framework of pluggable components to build RESTful API's :star: 108 :fork_and_knife: 3
* [:octocat: go-rest](https://github.com/ungerik/go-rest) - A small and evil REST framework for Go :star: 79 :fork_and_knife: 8
* [:octocat: go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. :star: 867 :fork_and_knife: 127
* [:octocat: Goat](https://github.com/bahlo/goat) - A minimalistic REST API server in Go :star: 69 :fork_and_knife: 4
* [:octocat: gocraft/web](https://github.com/gocraft/web) - A mux and middleware package in Go. :star: 878 :fork_and_knife: 57
* [:octocat: Goji](https://github.com/zenazn/goji) - Goji is a minimalistic web framework for Golang that's high in antioxidants. :star: 2785 :fork_and_knife: 181
* [:octocat: Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster :star: 288 :fork_and_knife: 18
* [:octocat: goose](https://github.com/ian-kent/goose) - Server Sent Events in Go :star: 11 :fork_and_knife: 2
* [Gorilla](https://github.com/gorilla/) - Gorilla is a web toolkit for the Go programming language.
* [:octocat: httprouter](https://github.com/julienschmidt/httprouter) - A high performance router. Use this and the standard http handlers to form a very high performance web framework. :star: 2304 :fork_and_knife: 175
* [:octocat: httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go.Inspiration from httprouter :star: 87 :fork_and_knife: 8
* [:octocat: Macaron](https://github.com/Unknwon/macaron) - Macaron is a high productive and modular design web framework in Go. :star: 3 :fork_and_knife: 1
* [:octocat: mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. :star: 292 :fork_and_knife: 32
* [:octocat: Martini](https://github.com/go-martini/martini) - Martini is a powerful package for quickly writing modular web applications/services in Golang. :star: 7842 :fork_and_knife: 814
* [:octocat: medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba. :star: 11 :fork_and_knife: 1
* [:octocat: mux](https://github.com/gorilla/mux) - A powerful URL router and dispatcher for golang. :star: 1703 :fork_and_knife: 281
* [:octocat: neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. :star: 170 :fork_and_knife: 11
* [:octocat: pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra. :star: 882 :fork_and_knife: 87
* [:octocat: Resoursea](https://github.com/resoursea/api) - A REST framework for quickly writing resource based services. :star: 24 :fork_and_knife: 2
* [:octocat: Revel](https://github.com/revel/revel) - A high-productivity web framework for the Go language. :star: 5916 :fork_and_knife: 861
* [:octocat: rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. :star: 9 :fork_and_knife: 0
* [sawsij](http://sawsij.com/) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [:octocat: Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers :star: 257 :fork_and_knife: 8
* [:octocat: tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. :star: 325 :fork_and_knife: 43
* [:octocat: tigertonic](https://github.com/rcrowley/go-tigertonic) - A Go framework for building JSON web services inspired by Dropwizard :star: 889 :fork_and_knife: 66
* [:octocat: traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go. :star: 450 :fork_and_knife: 15
* [:octocat: web.go](https://github.com/hoisie/web) - A simple framework to write webapps in Go. :star: 2495 :fork_and_knife: 344
* [:octocat: Zerver](https://github.com/cosiner/zerver) - Zerver is a expressive, modular, feature completed RESTful framework. :star: 115 :fork_and_knife: 16
* [:octocat: zeus](https://github.com/daryl/zeus) - A very simple and fast HTTP router for Go. :star: 89 :fork_and_knife: 7


### Middlewares

#### Actual middlewares

* [:octocat: CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API :star: 168 :fork_and_knife: 23
* [:octocat: formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST :star: 13 :fork_and_knife: 0
* [:octocat: Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler :star: 328 :fork_and_knife: 20
* [:octocat: XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends :star: 35 :fork_and_knife: 5

#### Libraries for creating HTTP middlewares

* [:octocat: alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. :star: 713 :fork_and_knife: 33
* [:octocat: catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). :star: 1 :fork_and_knife: 0
* [:octocat: chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). :star: 29 :fork_and_knife: 0
* [:octocat: go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. :star: 46 :fork_and_knife: 0
* [:octocat: interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang :star: 202 :fork_and_knife: 9
* [:octocat: muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. :star: 184 :fork_and_knife: 5
* [:octocat: negroni](https://github.com/codegangsta/negroni) - Idiomatic HTTP middleware for Golang. :star: 3047 :fork_and_knife: 205
* [:octocat: render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. :star: 526 :fork_and_knife: 43
* [:octocat: stats](https://github.com/thoas/stats) - A Go middleware that stores various information about your web application. :star: 281 :fork_and_knife: 13

# Tools

Go software and plugins.


## Code Analysis

* [doc](http://godoc.org/robpike.io/cmd/doc) - Go documentation tool that produces an alternative doc format.
* [:octocat: dupl](https://github.com/mibk/dupl) - A tool for code clone detection. :star: 30 :fork_and_knife: 2
* [:octocat: errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. :star: 440 :fork_and_knife: 27
* [:octocat: gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. :star: 440 :fork_and_knife: 31
* [:octocat: Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form. :star: 523 :fork_and_knife: 27
* [:octocat: goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. :star: 119 :fork_and_knife: 9
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [:octocat: GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. :star: 1089 :fork_and_knife: 114
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [:octocat: gostatus](https://github.com/shurcooL/gostatus) - A command line tool, shows the status of repositories that contain Go packages. :star: 113 :fork_and_knife: 3
* [:octocat: validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. :star: 53 :fork_and_knife: 9


## Editor Plugins

* [:octocat: go-lang-idea-plugin](https://github.com/go-lang-plugin-org/go-lang-idea-plugin) Go plugin for IntelliJ IDEA. :star: 2396 :fork_and_knife: 331
* [:octocat: go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting :star: 604 :fork_and_knife: 67
* [:octocat: Goclipse](https://github.com/GoClipse/goclipse) - An Eclipse plugin for Go. :star: 421 :fork_and_knife: 115
* [:octocat: gocode](https://github.com/nsf/gocode) - An autocompletion daemon for the Go programming language :star: 2643 :fork_and_knife: 316
* [:octocat: GoSublime](https://github.com/DisposaBoy/GoSublime) - A Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features. :star: 1957 :fork_and_knife: 178
* [:octocat: velour](https://github.com/velour/velour) - An IRC client for the acme editor. :star: 9 :fork_and_knife: 2
* [:octocat: vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - A Vim plugin to highlight syntax errors on save. :star: 51 :fork_and_knife: 14
* [:octocat: vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. :star: 3708 :fork_and_knife: 314
* [:octocat: Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. :star: 97 :fork_and_knife: 12

## Go Tools

* [:octocat: colorgo](https://github.com/songgao/colorgo) - A wrapper around `go` command for colorized `go build` output. :star: 51 :fork_and_knife: 4
* [:octocat: go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo. :star: 24 :fork_and_knife: 2

## Software Packages

Software written in Go.


### DevOps Tools

* [:octocat: aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool :star: 909 :fork_and_knife: 95
* [:octocat: awsenv](https://github.com/soniah/awsenv) - a small binary that loads Amazon (AWS) environment variables for a profile :star: 3 :fork_and_knife: 0
* [:octocat: Boom](https://github.com/rakyll/boom) - Boom is a tiny program that sends some load to a web application. :star: 3560 :fork_and_knife: 228
* [:octocat: dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). :star: 71 :fork_and_knife: 9
* [:octocat: EasySSH](https://github.com/hypersleep/easyssh) - Golang package for easy remote execution through SSH and SCP downloading. :star: 51 :fork_and_knife: 22
* [:octocat: Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics. :star: 946 :fork_and_knife: 174
* [:octocat: go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. :star: 281 :fork_and_knife: 23
* [:octocat: gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. :star: 127 :fork_and_knife: 15
* [:octocat: godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. :star: 175 :fork_and_knife: 16
* [Gogs](http://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [:octocat: gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. :star: 204 :fork_and_knife: 18
* [:octocat: gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool. :star: 1292 :fork_and_knife: 79
* [:octocat: goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. :star: 1117 :fork_and_knife: 47
* [:octocat: GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. :star: 1536 :fork_and_knife: 112
* [:octocat: hk](https://github.com/heroku/hk) - Heroku command-line interface in Go. :star: 751 :fork_and_knife: 42
* [:octocat: Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. :star: 109 :fork_and_knife: 13
* [:octocat: ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB :star: 50 :fork_and_knife: 1
* [:octocat: Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. :star: 4633 :fork_and_knife: 997
* [:octocat: Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. :star: 29 :fork_and_knife: 3
* [:octocat: Vegeta] (https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! :star: 2581 :fork_and_knife: 145
* [:octocat: webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server :star: 239 :fork_and_knife: 27
* [Wide](https://wide.b3log.org) - A Web-based IDE for Teams using Golang.


### Other Software
* [:octocat: boxed](https://github.com/tejo/boxed) - Dropbox based blog engine :star: 39 :fork_and_knife: 4
* [:octocat: Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. :star: 1146 :fork_and_knife: 89
* [:octocat: Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections :star: 3969 :fork_and_knife: 132
* [:octocat: confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. :star: 2061 :fork_and_knife: 254
* [Docker](http://www.docker.com/) - An open platform for distributed applications for developers and sysadmins.
* [:octocat: fleet](https://github.com/coreos/fleet) - A Distributed init System. :star: 1957 :fork_and_knife: 233
* [:octocat: Go Package Store](https://github.com/shurcooL/Go-Package-Store#go-package-store-) - An app that displays updates for the Go packages in your GOPATH. :star: 590 :fork_and_knife: 9
* [:octocat: gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. :star: 7 :fork_and_knife: 0
* [:octocat: Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. :star: 4224 :fork_and_knife: 317
* [:octocat: heka](https://github.com/mozilla-services/heka) - universal tool for data processing from Mozilla. Large collection of built-in plugins. Extendable via Go and Lua plugin API. :star: 2650 :fork_and_knife: 377
* [hugo](http://gohugo.io/) - A Fast and Modern Static Website Engine
* [Juju](https://juju.ubuntu.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [limetext](http://limetext.org/) Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [:octocat: naclpipe](https://github.com/unix4fun/naclpipe) - A simple NaCL EC25519 based crypto pipe tool written in Go. :star: 3 :fork_and_knife: 0
* [:octocat: nes](https://github.com/fogleman/nes) - A Nintendo Entertainment System (NES) emulator written in Go. :star: 2058 :fork_and_knife: 145
* [:octocat: orange-cat](https://github.com/noraesae/orange-cat) - A Markdown previewer written in Go. :star: 130 :fork_and_knife: 2
* [:octocat: peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. :star: 247 :fork_and_knife: 38
* [:octocat: Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email. :star: 606 :fork_and_knife: 29
* [:octocat: restic](https://github.com/restic/restic) - De-duplicating backup program. :star: 317 :fork_and_knife: 27
* [:octocat: Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. :star: 1776 :fork_and_knife: 184
* [:octocat: shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control) :star: 33 :fork_and_knife: 1
* [syncthing](http://www.syncthing.net/) - An open, decentralized file synchronization tool and protocol.
* [:octocat: Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. :star: 152 :fork_and_knife: 13
* [:octocat: toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. :star: 897 :fork_and_knife: 28
* [tsuru](http://www.tsuru.io/) - An extensible and open source Platform as a Service software.
* [:octocat: websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart) :star: 13 :fork_and_knife: 2







# Resources

Where to discover new Go libraries.


## Benchmarks

* [:octocat: autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. :star: 83 :fork_and_knife: 24
* [:octocat: go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. :star: 564 :fork_and_knife: 66
* [:octocat: go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go. :star: 2 :fork_and_knife: 0
* [:octocat: go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. :star: 167 :fork_and_knife: 23
* [:octocat: gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. :star: 43 :fork_and_knife: 2
* [:octocat: golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others. :star: 4 :fork_and_knife: 0
* [:octocat: golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - A collection of benchmarks for popular Go database/SQL utilities. :star: 11 :fork_and_knife: 0
* [:octocat: kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. :star: 9 :fork_and_knife: 0
* [:octocat: speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. :star: 55 :fork_and_knife: 4


## Conferences

* [dotGo](http://www.dotgo.io) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://www.golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon India](http://www.gophercon.in/) - Bengaluru, India
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](http://astaxie.gitbooks.io/build-web-application-with-golang/)
* [Building Web Apps With Go](http://codegangsta.gitbooks.io/building-web-apps-with-go/)
* [Go Bootcamp](http://golangbootcamp.com)
* [:octocat: GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books :star: 1502 :fork_and_knife: 148
* [Learning Go](http://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](http://jan.newmarch.name/go/)


## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangweekly](https://twitter.com/golangweekly)


## Websites

* [:octocat: Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - A curated list of awesome remote jobs. A lot of them is looking for Go hackers. :star: 4124 :fork_and_knife: 356
* [:octocat: awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. :star: 14172 :fork_and_knife: 1590
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - A collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog
* [:octocat: Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki :star: 11667 :fork_and_knife: 1271
* [godoc.org](http://godoc.org/) - Documentation for open source Go packages.
* [:octocat: golang-graphics](https://github.com/mholt/golang-graphics) - A collection of Go images, graphics, and art :star: 59 :fork_and_knife: 2
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](http://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.


### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go
* [Go By Example](https://gobyexample.com/) - A hands-on introduction to Go using annotated example programs
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql
* [:octocat: Working with Go](https://github.com/mkaz/working-with-go) - An intro to go for experienced programmers :star: 427 :fork_and_knife: 37


## Windows

* [:octocat: go-ole](https://github.com/mattn/go-ole) - Win32 OLE implementation for golang :star: 160 :fork_and_knife: 41
