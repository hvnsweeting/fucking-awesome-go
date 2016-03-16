# Fucking Awesome Go

 A curated list with Github stars and forks stats based on awesome [awesome-go](https://github.com/avelino/awesome-go)

# Awesome Go [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/avelino/awesome-go](https://badges.gitter.im/avelino/awesome-go.svg)](https://gitter.im/avelino/awesome-go?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

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
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
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
    - [Query Language](#query-language)
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

* [:octocat: flac](https://github.com/eaburns/flac) - A native Go FLAC decoder. :star: 46 :fork_and_knife: 5
* [:octocat: flac](https://github.com/mewkiz/flac) - A native Go FLAC decoder. :star: 20 :fork_and_knife: 8
* [:octocat: go-sox](https://github.com/krig/go-sox) - libsox bindings for go. :star: 35 :fork_and_knife: 5
* [:octocat: go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. :star: 2 :fork_and_knife: 0
* [:octocat: mp3](https://github.com/tcolgate/mp3) - A native Go MP# decoder. :star: 11 :fork_and_knife: 3
* [:octocat: ontomix](https://github.com/go-ontomix/ontomix) - Sequence-based Go-native audio mixer for Music apps. :star: 14 :fork_and_knife: 4
* [:octocat: PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. :star: 29 :fork_and_knife: 9
* [:octocat: portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. :star: 80 :fork_and_knife: 22
* [:octocat: taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. :star: 38 :fork_and_knife: 15
* [:octocat: vorbis](https://github.com/mccoyst/vorbis) - A "native" Go Vorbis decoder (uses CGO, but has no dependencies). :star: 9 :fork_and_knife: 3
* [:octocat: waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. :star: 113 :fork_and_knife: 7


## Authentication & OAuth

*Libraries for implementing authentications schemes.*

* [:octocat: Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library. :star: 117 :fork_and_knife: 20
* [:octocat: go-jose](https://github.com/square/go-jose) - A fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. :star: 482 :fork_and_knife: 50
* [:octocat: go.auth](https://github.com/bradrydzewski/go.auth) - Authentication API for Go web applications. :star: 300 :fork_and_knife: 26
* [:octocat: gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. :star: 615 :fork_and_knife: 23
* [:octocat: gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. :star: 305 :fork_and_knife: 53
* [:octocat: goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple provides out of the box. :star: 626 :fork_and_knife: 64
* [:octocat: httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. :star: 86 :fork_and_knife: 10
* [:octocat: jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). :star: 995 :fork_and_knife: 124
* [:octocat: oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. :star: 658 :fork_and_knife: 191
* [:octocat: osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library. :star: 830 :fork_and_knife: 165
* [:octocat: permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. :star: 146 :fork_and_knife: 10
* [:octocat: yubigo](https://github.com/GeertJohan/yubigo) - a Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application. :star: 53 :fork_and_knife: 6


## Command Line


### Standard CLI

*Libraries for building standard or basic Command Line applications*

* [:octocat: cli] (https://github.com/mkideal/cli) - A feature-rich and easy to use command-line package based on golang tag :star: 19 :fork_and_knife: 1
* [:octocat: cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line application. :star: 464 :fork_and_knife: 39
* [:octocat: climax](http://github.com/tucnak/climax) - An alternative CLI with "human face", in spirit of Go command :star: 92 :fork_and_knife: 5
* [:octocat: cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions :star: 1843 :fork_and_knife: 171
* [:octocat: codegangsta/cli](https://github.com/codegangsta/cli) - A small package for building command line apps in Go. :star: 3908 :fork_and_knife: 363
* [:octocat: docopt.go](https://github.com/docopt/docopt.go) - A command-line arguments parser that will make you smile. :star: 652 :fork_and_knife: 46
* [:octocat: go-flags](https://github.com/jessevdk/go-flags) - go command line option parser :star: 551 :fork_and_knife: 78
* [:octocat: kingpin](https://github.com/alecthomas/kingpin) - A command line and flag parser supporting sub commands. :star: 532 :fork_and_knife: 48
* [:octocat: liner](https://github.com/peterh/liner) - A Go readline-like library for command-line interfaces. :star: 287 :fork_and_knife: 44
* [:octocat: mitchellh/cli](https://github.com/mitchellh/cli) - A Go library for implementing command-line interfaces. :star: 386 :fork_and_knife: 31
* [:octocat: mow.cli](https://github.com/jawher/mow.cli) - A Go library for building CLI applications with sophisticated flag and argument parsing and validation. :star: 333 :fork_and_knife: 20
* [:octocat: readline](https://github.com/chzyer/readline) - A pure golang implementation that provide most of features in GNU-Readline under MIT license. :star: 519 :fork_and_knife: 27
* [:octocat: ukautz/clif](https://github.com/ukautz/clif) - A small command line interface framework. :star: 62 :fork_and_knife: 7


### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces*

* [:octocat: chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. :star: 150 :fork_and_knife: 11
* [:octocat: color](https://github.com/fatih/color) - Versatile package for colored terminal output. :star: 765 :fork_and_knife: 62
* [:octocat: colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. :star: 3 :fork_and_knife: 2
* [:octocat: go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. :star: 141 :fork_and_knife: 11
* [:octocat: gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. :star: 502 :fork_and_knife: 46
* [:octocat: gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text. :star: 111 :fork_and_knife: 14
* [:octocat: termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. :star: 1356 :fork_and_knife: 139
* [:octocat: termtables](https://github.com/apcera/termtables) - A Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output :star: 48 :fork_and_knife: 7
* [:octocat: termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). :star: 4506 :fork_and_knife: 204
* [:octocat: uilive](https://github.com/gosuri/uilive) - A library for updating terminal output in realtime. :star: 422 :fork_and_knife: 10
* [:octocat: uiprogress](https://github.com/gosuri/uiprogress) - A flexible library to render progress bars in terminal applications. :star: 775 :fork_and_knife: 21
* [:octocat: uitable](https://github.com/gosuri/uitable) - A library to improve readability in terminal apps using tabular data. :star: 279 :fork_and_knife: 9


## Configuration

*Libraries for configuration parsing*

* [:octocat: config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. :star: 62 :fork_and_knife: 13
* [:octocat: configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. :star: 6 :fork_and_knife: 2
* [:octocat: env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). :star: 82 :fork_and_knife: 5
* [:octocat: envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. :star: 75 :fork_and_knife: 4
* [:octocat: envconf](https://github.com/ian-kent/envconf) - Configuration from environment :star: 2 :fork_and_knife: 1
* [:octocat: envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. :star: 88 :fork_and_knife: 5
* [:octocat: gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections :star: 32 :fork_and_knife: 13
* [:octocat: gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy :star: 32 :fork_and_knife: 2
* [:octocat: ini](https://github.com/go-ini/ini) - Go package for read and write INI files :star: 237 :fork_and_knife: 36
* [:octocat: mini](https://github.com/FogCreek/mini) - A golang package for parsing ini-style configuration files :star: 81 :fork_and_knife: 8
* [:octocat: store](https://github.com/tucnak/store) - A lightweight configuration manager for Go :star: 37 :fork_and_knife: 1
* [:octocat: viper](https://github.com/spf13/viper) - Go configuration with fangs :star: 1384 :fork_and_knife: 148

## Continuous Integration

*Tools for help with continuous integration*

* [:octocat: drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go :star: 6403 :fork_and_knife: 740
* [:octocat: goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. :star: 232 :fork_and_knife: 47
* [:octocat: overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls :star: 15 :fork_and_knife: 1

## CSS Preprocessors

*Libraries for preprocessing CSS files*

* [:octocat: c6](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go :star: 329 :fork_and_knife: 14
* [:octocat: gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. :star: 335 :fork_and_knife: 16
* [:octocat: go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. :star: 21 :fork_and_knife: 3

## Data Structures

*Generic datastructures and algorithms in Go.*

* [:octocat: binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. :star: 6 :fork_and_knife: 0
* [:octocat: bitset](https://github.com/willf/bitset) - Go package implementing bitsets. :star: 192 :fork_and_knife: 46
* [:octocat: bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. :star: 78 :fork_and_knife: 10
* [:octocat: boomfilters](https://github.com/tylertreat/BoomFilters) - probabilistic data structures for processing continuous, unbounded streams :star: 674 :fork_and_knife: 30
* [:octocat: count-min-log](https://github.com/seiflotfy/count-min-log) - A Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). :star: 18 :fork_and_knife: 2
* [:octocat: cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. :star: 139 :fork_and_knife: 8
* [:octocat: encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. :star: 40 :fork_and_knife: 6
* [:octocat: go-datastructures](https://github.com/Workiva/go-datastructures) - a collection of useful, performant, and thread-safe data structures :star: 2358 :fork_and_knife: 158
* [:octocat: go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. :star: 152 :fork_and_knife: 14
* [:octocat: golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. :star: 353 :fork_and_knife: 50
* [:octocat: goskiplist](https://github.com/ryszard/goskiplist) - A skip list implementation in Go. :star: 102 :fork_and_knife: 24
* [:octocat: mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing :star: 203 :fork_and_knife: 12
* [:octocat: skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go :star: 26 :fork_and_knife: 7
* [:octocat: trie](https://github.com/derekparker/trie) - Trie implementation in Go :star: 113 :fork_and_knife: 13
* [:octocat: ttlcache](https://github.com/diegobernardes/ttlcache) - An in-memory LRU string-interface{} map with expiration for golang :star: 17 :fork_and_knife: 2
* [:octocat: willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. :star: 226 :fork_and_knife: 42

## Database

*Databases implemented in Go.*

* [:octocat: bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Go. :star: 3822 :fork_and_knife: 297
* [:octocat: cache2go](https://github.com/muesli/cache2go) - An in-memory key:value cache which supports automatic invalidation based on timeouts. :star: 66 :fork_and_knife: 24
* [:octocat: cockroach](https://github.com/cockroachdb/cockroach) - A Scalable, Geo-Replicated, Transactional Datastore :star: 6380 :fork_and_knife: 594
* [:octocat: couchcache](https://github.com/codingsince1985/couchcache) - A RESTful caching micro-service backed by Couchbase server. :star: 15 :fork_and_knife: 2
* [:octocat: dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. :star: 522 :fork_and_knife: 25
* [:octocat: diskv](https://github.com/peterbourgon/diskv) - A home-grown disk-backed key-value store. :star: 337 :fork_and_knife: 33
* [:octocat: forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. :star: 18 :fork_and_knife: 3
* [:octocat: GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. :star: 91 :fork_and_knife: 7
* [:octocat: go-cache](https://github.com/pmylund/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. :star: 446 :fork_and_knife: 94
* [:octocat: goleveldb](https://github.com/syndtr/goleveldb) - An implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in the Go. :star: 969 :fork_and_knife: 134
* [:octocat: groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. :star: 4298 :fork_and_knife: 428
* [:octocat: influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics :star: 7596 :fork_and_knife: 986
* [:octocat: ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. :star: 1523 :fork_and_knife: 173
* [:octocat: levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. :star: 266 :fork_and_knife: 58
* [:octocat: prometheus](https://github.com/prometheus/prometheus) -  Monitoring system and time series database. :star: 4108 :fork_and_knife: 331
* [:octocat: rqlite](https://github.com/otoolep/rqlite) - Replicated SQLite, using Raft consensus. :star: 1187 :fork_and_knife: 54
* [:octocat: tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. :star: 3543 :fork_and_knife: 412
* [:octocat: tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. :star: 1478 :fork_and_knife: 128

*Database tools.*

* [:octocat: go-mysql](https://github.com/siddontang/go-mysql) - A go toolset to handle MySQL protocol and replication. :star: 185 :fork_and_knife: 60
* [:octocat: go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. :star: 230 :fork_and_knife: 46
* [:octocat: goose](https://github.com/CloudCom/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. :star: 19 :fork_and_knife: 6
* [:octocat: kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. :star: 1573 :fork_and_knife: 301
* [:octocat: migrate](https://github.com/mattes/migrate) - Database migration handling in Golang support MySQL,PostgreSQL,Cassandra and SQLite. :star: 540 :fork_and_knife: 86
* [:octocat: myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Support statement and row based replication. :star: 45 :fork_and_knife: 16
* [:octocat: orchestrator](https://github.com/outbrain/orchestrator) - MySQL replication topology manager & visualizer :star: 383 :fork_and_knife: 77
* [:octocat: pgweb](https://github.com/sosedoff/pgweb) - A web-based PostgreSQL database browser :star: 3318 :fork_and_knife: 165
* [:octocat: pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc., :star: 10 :fork_and_knife: 3
* [:octocat: sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. :star: 424 :fork_and_knife: 27
* [:octocat: vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. :star: 3315 :fork_and_knife: 416

*SQL query builder, libraries for building and using SQL.*

* [:octocat: dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit :star: 272 :fork_and_knife: 16
* [:octocat: Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use it with ease. :star: 218 :fork_and_knife: 12
* [:octocat: goqu](https://github.com/doug-martin/goqu) - An idiomatic SQL builder and query library. :star: 247 :fork_and_knife: 14
* [:octocat: ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. :star: 77 :fork_and_knife: 4
* [:octocat: scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. :star: 60 :fork_and_knife: 2
* [:octocat: sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. :star: 27 :fork_and_knife: 1
* [:octocat: Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. :star: 760 :fork_and_knife: 55


## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [:octocat: firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go :star: 40 :fork_and_knife: 8
    * [:octocat: go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using database/sql. :star: 32 :fork_and_knife: 13
    * [:octocat: go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert. :star: 72 :fork_and_knife: 4
    * [:octocat: go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver prototype in go language. :star: 305 :fork_and_knife: 61
    * [:octocat: go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that using database/sql. :star: 122 :fork_and_knife: 80
    * [:octocat: go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. :star: 2168 :fork_and_knife: 503
    * [:octocat: go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that using database/sql. :star: 1137 :fork_and_knife: 278
    * [:octocat: gofreetds](https://github.com/minus5/gofreetds) Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). :star: 33 :fork_and_knife: 18
    * [:octocat: pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. :star: 510 :fork_and_knife: 62
    * [:octocat: pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. :star: 1953 :fork_and_knife: 302

* NoSQL Databases
    * [:octocat: aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. :star: 158 :fork_and_knife: 54
    * [:octocat: arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. :star: 22 :fork_and_knife: 4
    * [:octocat: cayley](https://github.com/google/cayley) - A graph database with support for multiple backends. :star: 7197 :fork_and_knife: 608
    * [:octocat: dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB :star: 13 :fork_and_knife: 7
    * [:octocat: go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go :star: 202 :fork_and_knife: 64
    * [:octocat: go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go :star: 30 :fork_and_knife: 12
    * [:octocat: gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK :star: 164 :fork_and_knife: 34
    * [gocql](http://gocql.github.io) - A Go language driver for Apache Cassandra.
    * [:octocat: gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. :star: 579 :fork_and_knife: 167
    * [:octocat: gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB :star: 809 :fork_and_knife: 83
    * [mgo](https://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [:octocat: neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang :star: 12 :fork_and_knife: 2
    * [:octocat: Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. :star: 60 :fork_and_knife: 14
    * [:octocat: neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang :star: 232 :fork_and_knife: 53
    * [:octocat: redigo](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database. :star: 2024 :fork_and_knife: 356
    * [:octocat: redis](https://github.com/go-redis/redis) - Redis client for Golang :star: 720 :fork_and_knife: 116
    * [:octocat: redis](https://github.com/hoisie/redis) - A simple, powerful Redis client for Go. :star: 494 :fork_and_knife: 169
    * [:octocat: redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. :star: 35 :fork_and_knife: 3

* Search and Analytic Databases
    * [:octocat: bleve](https://github.com/blevesearch/bleve) - A modern text indexing library for go. :star: 2369 :fork_and_knife: 189
    * [:octocat: elastic](https://github.com/olivere/elastic) - Elasticsearch client for Google Go. :star: 561 :fork_and_knife: 133
    * [:octocat: elastigo](https://github.com/mattbaird/elastigo) - A Elasticsearch client library. :star: 702 :fork_and_knife: 197
    * [:octocat: goes](https://github.com/belogik/goes) - A library to interact with Elasticsearch. :star: 70 :fork_and_knife: 23
    * [:octocat: skizze](https://github.com/seiflotfy/skizze) - A probabilistic data-structures service and storage. :star: 17 :fork_and_knife: 3

## Date & Time

*Libraries for working with dates and times.*

* [:octocat: go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). :star: 2 :fork_and_knife: 0
* [:octocat: goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang. :star: 4 :fork_and_knife: 0
* [:octocat: now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. :star: 569 :fork_and_knife: 37
* [:octocat: NullTime](https://github.com/kirillDanshin/nulltime) - Nullable time.Time :star: 0 :fork_and_knife: 0
* [:octocat: timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. :star: 98 :fork_and_knife: 3


## Distributed Systems

*Packages that help with building Distributed Systems.*

* [:octocat: celeriac](https://github.com/svcavallar/celeriac.v1) - A library for adding support for interacting and monitoring Celery workers, tasks and events in Go :star: 10 :fork_and_knife: 2
* [:octocat: flowgraph](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer. :star: 8 :fork_and_knife: 0
* [:octocat: glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. :star: 787 :fork_and_knife: 52
* [:octocat: go-jump](https://github.com/dgryski/go-jump) - A port of Google's "Jump" Consistent Hash function. :star: 60 :fork_and_knife: 7
* [:octocat: gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. :star: 205 :fork_and_knife: 26
* [:octocat: grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. :star: 1562 :fork_and_knife: 207
* [:octocat: micro](https://github.com/micro/micro) - A pluggable microservice toolkit and distributed systems platform. :star: 1061 :fork_and_knife: 49
* [:octocat: raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. :star: 528 :fork_and_knife: 75
* [:octocat: torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. :star: 1083 :fork_and_knife: 56
    * [:octocat: dht](https://godoc.org/github.com/anacrolix/torrent/dht) - BitTorrent Kademlia DHT implementation. :star: 1083 :fork_and_knife: 56
    * [:octocat: go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. :star: 135 :fork_and_knife: 20

## Email

*Libraries that implement email creation and sending*

* [:octocat: douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. :star: 37 :fork_and_knife: 2
* [:octocat: email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. :star: 658 :fork_and_knife: 64
* [:octocat: go-dkim](https://github.com/toorop/go-dkim) - A DKIM library, to sign & verify email. :star: 13 :fork_and_knife: 5
* [:octocat: Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails. :star: 825 :fork_and_knife: 56
* [:octocat: Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API :star: 42 :fork_and_knife: 2
* [:octocat: MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface :star: 722 :fork_and_knife: 35
* [:octocat: SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email :star: 163 :fork_and_knife: 44
* [:octocat: smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine :star: 18 :fork_and_knife: 3



## Embeddable Scripting Languages

*Embedding other languages inside your go code*

* [:octocat: agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go :star: 214 :fork_and_knife: 18
* [:octocat: anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go :star: 245 :fork_and_knife: 17
* [:octocat: gisp](https://github.com/jcla1/gisp) - Simple LISP in Go :star: 317 :fork_and_knife: 20
* [:octocat: go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go :star: 294 :fork_and_knife: 26
* [:octocat: go-lua](https://github.com/Shopify/go-lua) - A port of the Lua 5.2 VM to pure Go :star: 608 :fork_and_knife: 28
* [:octocat: go-php](https://github.com/deuill/go-php) - PHP bindings for Go :star: 105 :fork_and_knife: 12
* [:octocat: go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API :star: 351 :fork_and_knife: 32
* [:octocat: golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API :star: 259 :fork_and_knife: 59
* [:octocat: gopher-lua](https://github.com/yuin/gopher-lua) - a Lua 5.1 VM and compiler written in Go :star: 1110 :fork_and_knife: 77
* [:octocat: otto](https://github.com/robertkrimen/otto) - A JavaScript interpreter written in Go :star: 2026 :fork_and_knife: 161
* [:octocat: purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go :star: 11 :fork_and_knife: 0


## Financial

*Packages for accounting and finance*

* [:octocat: accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang :star: 190 :fork_and_knife: 5
* [:octocat: decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers :star: 246 :fork_and_knife: 37


## Forms

*Libraries for working with forms.*

* [:octocat: bind](https://github.com/robfig/bind)  - Bind form data to any Go values :star: 10 :fork_and_knife: 2
* [:octocat: binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. :star: 440 :fork_and_knife: 36
* [:octocat: conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. :star: 9 :fork_and_knife: 0
* [:octocat: formam](https://github.com/monoculum/formam) - decode form's values into a struct. :star: 45 :fork_and_knife: 3
* [:octocat: forms](https://github.com/albrow/forms) - A framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. :star: 54 :fork_and_knife: 3
* [:octocat: gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. :star: 95 :fork_and_knife: 10
* [:octocat: nosurf](https://github.com/justinas/nosurf) - A CSRF protection middleware for Go. :star: 624 :fork_and_knife: 40


## Game Development

*Awesome game development libraries.*

* [:octocat: engi](https://github.com/paked/engi) - A cross-platform game engine following the Entity Component System design pattern :star: 89 :fork_and_knife: 11
* [:octocat: GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. :star: 213 :fork_and_knife: 15
* [:octocat: glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. :star: 71 :fork_and_knife: 7
* [:octocat: go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm :star: 140 :fork_and_knife: 11
* [:octocat: go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. :star: 8 :fork_and_knife: 0
* [:octocat: go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). :star: 315 :fork_and_knife: 66
* [:octocat: go3d](https://github.com/ungerik/go3d) - A performance oriented 2D/3D math package for Go :star: 98 :fork_and_knife: 12
* [:octocat: gonet](https://github.com/xtaci/gonet) - A game server skeleton implemented with golang :star: 625 :fork_and_knife: 232
* [:octocat: Leaf](https://github.com/name5566/leaf) - A lightweight game server framework :star: 583 :fork_and_knife: 165
* [:octocat: termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox :star: 595 :fork_and_knife: 28


## Generation & Generics

*Tools to enhance the language with features like generics via code generation*

* [:octocat: gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. :star: 659 :fork_and_knife: 45
* [:octocat: go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. :star: 732 :fork_and_knife: 45
* [:octocat: interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. :star: 63 :fork_and_knife: 0
* [:octocat: pkgreflect](https://github.com/ungerik/pkgreflect) - A Go preprocessor for package scoped reflection. :star: 29 :fork_and_knife: 4


## Go Compilers

*Tools for compiling Go to other languages*

* [:octocat: gopherjs](https://github.com/gopherjs/gopherjs) - A compiler from Go to JavaScript. :star: 3649 :fork_and_knife: 164
* [:octocat: llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go. :star: 725 :fork_and_knife: 57
* [:octocat: tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. :star: 308 :fork_and_knife: 14


## Goroutines

*Tools for managing and working with Goroutines*

* [:octocat: grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. :star: 92 :fork_and_knife: 6
* [:octocat: pool](https://github.com/go-playground/pool) - Go consumer goroutine pool for easy goroutine handling + time saving. :star: 36 :fork_and_knife: 2
* [:octocat: tunny](https://github.com/Jeffail/tunny) - A goroutine pool for golang. :star: 285 :fork_and_knife: 21


## GUI

*Libraries for building GUI Applications*

* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK
* [:octocat: go-qml](https://github.com/go-qml/qml) - QML support for the Go language :star: 1617 :fork_and_knife: 147
* [:octocat: goqt](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework. :star: 931 :fork_and_knife: 60
* [:octocat: gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. :star: 275 :fork_and_knife: 22
* [:octocat: gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. :star: 57 :fork_and_knife: 15
* [:octocat: sciter](https://github.com/oskca/sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. :star: 192 :fork_and_knife: 24
* [:octocat: systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area :star: 51 :fork_and_knife: 6
* [:octocat: trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. :star: 35 :fork_and_knife: 5
* [:octocat: ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. :star: 2718 :fork_and_knife: 170
* [:octocat: walk](https://github.com/lxn/walk) - Windows application library kit for Go. :star: 1226 :fork_and_knife: 234


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list. :star: 324 :fork_and_knife: 20

## Images

*Libraries for manipulating images.*

* [:octocat: bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips :star: 147 :fork_and_knife: 26
* [:octocat: geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. :star: 838 :fork_and_knife: 33
* [:octocat: gift](https://github.com/disintegration/gift) - Package of image processing filters. :star: 695 :fork_and_knife: 43
* [:octocat: go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. :star: 50 :fork_and_knife: 13
* [:octocat: go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library :star: 39 :fork_and_knife: 12
* [:octocat: go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. :star: 168 :fork_and_knife: 15
* [:octocat: go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. :star: 364 :fork_and_knife: 64
* [:octocat: go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. :star: 17 :fork_and_knife: 0
* [:octocat: imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. :star: 394 :fork_and_knife: 64
* [:octocat: imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing :star: 703 :fork_and_knife: 43
* [:octocat: imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. :star: 766 :fork_and_knife: 89
* [:octocat: img](https://github.com/hawx/img) - A selection of image manipulation tools. :star: 73 :fork_and_knife: 2
* [:octocat: mpo](https://github.com/donatj/mpo) - A decoder and conversion tool for MPO 3D Photos. :star: 4 :fork_and_knife: 1
* [:octocat: picfit](https://github.com/thoas/picfit) - An image resizing server written in Go :star: 458 :fork_and_knife: 32
* [:octocat: resize](https://github.com/nfnt/resize) - Image resizing for the Go with common interpolation methods. :star: 1013 :fork_and_knife: 99
* [:octocat: rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. :star: 115 :fork_and_knife: 6
* [:octocat: smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes :star: 189 :fork_and_knife: 24
* [:octocat: svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. :star: 660 :fork_and_knife: 56
* [:octocat: tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. :star: 11 :fork_and_knife: 5

## Logging

*Libraries for generating and working with log files.*

* [:octocat: glog](https://github.com/golang/glog) - Leveled execution logs for Go. :star: 939 :fork_and_knife: 179
* [:octocat: go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. :star: 13 :fork_and_knife: 5
* [:octocat: go-log](https://github.com/ian-kent/go-log) - A log4j implementation in Go. :star: 17 :fork_and_knife: 7
* [:octocat: go-log-interface](https://github.com/ventu-io/go-log-interface) - A generic leveled log interface to adopt any logging framework and a default facade for Go stdlib log.Logger. :star: 2 :fork_and_knife: 0
* [:octocat: go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. :star: 152 :fork_and_knife: 14
* [:octocat: gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Cosole, Simple Console, File or Elasticsearch. :star: 16 :fork_and_knife: 3
* [:octocat: log](https://github.com/apex/log) - Structured logging package for Go. :star: 194 :fork_and_knife: 6
* [:octocat: log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. :star: 50 :fork_and_knife: 6
* [:octocat: log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go :star: 398 :fork_and_knife: 52
* [:octocat: logex](https://github.com/chzyer/logex) - An golang log lib, supports tracking and level, wrap by standard log lib :star: 22 :fork_and_knife: 3
* [:octocat: logger](https://github.com/azer/logger) - Minimalistic logging library for Go. :star: 57 :fork_and_knife: 7
* [:octocat: logrus](https://github.com/Sirupsen/logrus) - a structured logger for Go. :star: 2446 :fork_and_knife: 340
* [:octocat: logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). :star: 6 :fork_and_knife: 4
* [:octocat: logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. :star: 129 :fork_and_knife: 11
* [:octocat: logxi](https://github.com/mgutz/logxi) - A 12-factor app logger that is fast and makes you happy. :star: 237 :fork_and_knife: 13
* [:octocat: lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. :star: 277 :fork_and_knife: 31
* [:octocat: mlog](https://github.com/jbrodriguez/mlog) - A simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. :star: 2 :fork_and_knife: 6
* [:octocat: ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). :star: 34 :fork_and_knife: 6
* [:octocat: seelog](https://github.com/cihub/seelog) -   logging functionality with flexible dispatching, filtering, and formatting. :star: 614 :fork_and_knife: 106
* [:octocat: stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. :star: 28 :fork_and_knife: 4
* [:octocat: tail](https://github.com/hpcloud/tail) - A Go package striving to emulate the features of the BSD tail program. :star: 449 :fork_and_knife: 104
* [:octocat: xlog](https://github.com/rs/xlog) - A structured logger for `net/context` aware HTTP handlers with flexible dispatching. :star: 56 :fork_and_knife: 4

## Machine Learning

*Libraries for Machine Learning.*

* [:octocat: bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. :star: 291 :fork_and_knife: 40
* [:octocat: CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. :star: 336 :fork_and_knife: 39
* [:octocat: gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm. :star: 99 :fork_and_knife: 3
* [:octocat: go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. :star: 69 :fork_and_knife: 15
* [:octocat: go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang :star: 114 :fork_and_knife: 23
* [:octocat: go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. :star: 33 :fork_and_knife: 8
* [:octocat: gobrain](https://github.com/goml/gobrain) - Neural Networks written in go :star: 74 :fork_and_knife: 13
* [:octocat: godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. :star: 6 :fork_and_knife: 2
* [:octocat: goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. :star: 32 :fork_and_knife: 0
* [:octocat: GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. :star: 2623 :fork_and_knife: 281
* [:octocat: golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go :star: 21 :fork_and_knife: 6
* [:octocat: goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go :star: 452 :fork_and_knife: 23
* [:octocat: goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. :star: 34 :fork_and_knife: 2
* [:octocat: libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. :star: 34 :fork_and_knife: 4
* [:octocat: mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go. :star: 0 :fork_and_knife: 0
* [:octocat: neural-go](https://github.com/schuyler/neural-go) - A multilayer perceptron network implemented in Go, with training via backpropagation. :star: 41 :fork_and_knife: 7
* [:octocat: probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. :star: 0 :fork_and_knife: 0
* [:octocat: regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine :star: 92 :fork_and_knife: 10
* [:octocat: shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go :star: 74 :fork_and_knife: 19


## Messaging

*Libraries that implement messaging systems*

* [:octocat: Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. :star: 957 :fork_and_knife: 43
* [:octocat: dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. :star: 78 :fork_and_knife: 33
* [:octocat: emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. :star: 43 :fork_and_knife: 1
* [:octocat: EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. :star: 130 :fork_and_knife: 17
* [:octocat: go-longpoll](https://github.com/ventu-io/go-longpoll) - PubSub with long polling. :star: 7 :fork_and_knife: 0
* [:octocat: go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. :star: 12 :fork_and_knife: 4
* [:octocat: go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ :star: 547 :fork_and_knife: 128
* [:octocat: gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. :star: 1131 :fork_and_knife: 341
* [:octocat: machinery](https://github.com/RichardKnop/machinery) - An asynchronous task queue/job queue based on distributed message passing. :star: 755 :fork_and_knife: 66
* [:octocat: mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. :star: 791 :fork_and_knife: 58
* [:octocat: NATS](https://github.com/nats-io/nats) - A lightweight and highly performant publish-subscribe and distributed queueing messaging system. :star: 624 :fork_and_knife: 102
* [:octocat: oplog](https://github.com/dailymotion/oplog) - A generic oplog/replication system for REST APIs :star: 64 :fork_and_knife: 9
* [:octocat: pubsub](https://github.com/tuxychandru/pubsub) - A simple pubsub package for go. :star: 81 :fork_and_knife: 10
* [:octocat: sarama](https://github.com/Shopify/sarama) - A Go library for Apache Kafka. :star: 879 :fork_and_knife: 166
* [:octocat: Uniqush-Push](https://github.com/uniqush/uniqush-push) - A redis backed unified push service for server-side notifications to mobile devices. :star: 795 :fork_and_knife: 127
* [:octocat: zmq4](https://github.com/pebbe/zmq4) - A Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). :star: 360 :fork_and_knife: 56


## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit*

* [:octocat: autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. :star: 12 :fork_and_knife: 0
* [:octocat: browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). :star: 15 :fork_and_knife: 5
* [:octocat: datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. :star: 4 :fork_and_knife: 0
* [:octocat: go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. :star: 33 :fork_and_knife: 8
* [:octocat: go-commons-pool](https://github.com/jolestar/go-commons-pool) - A generic object pool for Golang. :star: 222 :fork_and_knife: 23
* [:octocat: go-multierror](https://github.com/hashicorp/go-multierror) - A Go (golang) package for representing a list of errors as a single error. :star: 183 :fork_and_knife: 8
* [:octocat: go-shortid](https://github.com/ventu-io/go-shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. :star: 44 :fork_and_knife: 0
* [:octocat: gopsutil](https://github.com/shirou/gopsutil) - A cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). :star: 952 :fork_and_knife: 190
* [:octocat: gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS :star: 905 :fork_and_knife: 67
* [:octocat: gountries](https://github.com/pariz/gountries) - A package that exposes country and subdivision data. :star: 82 :fork_and_knife: 3
* [:octocat: health](https://github.com/dimiro1/health) - A Easy to use, extensible health check library. :star: 129 :fork_and_knife: 4
* [:octocat: jobs](https://github.com/albrow/jobs) - A persistent and flexible background jobs library. :star: 313 :fork_and_knife: 19
* [:octocat: margelet](https://github.com/zhulik/margelet) - A framework for building Telegram bots. :star: 26 :fork_and_knife: 1
* [:octocat: notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. :star: 139 :fork_and_knife: 15
* [:octocat: stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... :star: 15 :fork_and_knife: 3
* [:octocat: werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. :star: 3 :fork_and_knife: 0
* [:octocat: xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber :star: 10 :fork_and_knife: 0
* [:octocat: xstrings](https://github.com/huandu/xstrings) - A collection of useful string functions ported from other languages. :star: 307 :fork_and_knife: 23

## Natural Language Processing

*Libraries for working with human languages.*

* [:octocat: dpar](https://github.com/danieldk/dpar/) - Transition-based statistical dependency parser. :star: 15 :fork_and_knife: 2
* [:octocat: go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models. :star: 0 :fork_and_knife: 0
* [:octocat: go-i18n](https://github.com/nicksnyder/go-i18n/) - A package and an accompanying tool to work with localized text. :star: 241 :fork_and_knife: 43
* [:octocat: go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. :star: 44 :fork_and_knife: 10
* [:octocat: go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. :star: 34 :fork_and_knife: 8
* [:octocat: go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. :star: 6 :fork_and_knife: 1
* [:octocat: golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2 :star: 10 :fork_and_knife: 3
* [:octocat: gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go :star: 36 :fork_and_knife: 16
* [:octocat: icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. :star: 15 :fork_and_knife: 1
* [:octocat: libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. :star: 8 :fork_and_knife: 6
* [:octocat: MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. :star: 46 :fork_and_knife: 10
* [:octocat: paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm :star: 11 :fork_and_knife: 3
* [:octocat: porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. :star: 3 :fork_and_knife: 0
* [:octocat: porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. :star: 21 :fork_and_knife: 3
* [:octocat: segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) :star: 15 :fork_and_knife: 1
* [:octocat: sentences](https://github.com/neurosnap/sentences) - A sentence tokenizer:  converts text into a list of sentences. :star: 118 :fork_and_knife: 7
* [:octocat: snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). :star: 13 :fork_and_knife: 0
* [:octocat: stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. :star: 28 :fork_and_knife: 1
* [:octocat: textcat](https://github.com/pebbe/textcat) - A Go package for n-gram based text categorization, with support for utf-8 and raw text :star: 40 :fork_and_knife: 7

## Networking

*Libraries for working with various layers of the network*

* [:octocat: arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. :star: 31 :fork_and_knife: 6
* [:octocat: buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy :star: 126 :fork_and_knife: 6
* [:octocat: canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252) :star: 24 :fork_and_knife: 4
* [:octocat: dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. :star: 7 :fork_and_knife: 2
* [:octocat: dns](https://github.com/miekg/dns) - Go library for working with DNS :star: 1407 :fork_and_knife: 247
* [:octocat: ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. :star: 9 :fork_and_knife: 2
* [:octocat: fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http :star: 1872 :fork_and_knife: 117
* [:octocat: ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). :star: 118 :fork_and_knife: 77
* [:octocat: go-getter](https://github.com/hashicorp/go-getter) - A Go library for downloading files or directories from various sources using a URL. :star: 217 :fork_and_knife: 11
* [:octocat: go-stun](https://github.com/ccding/go-stun) - A go implementation of the STUN client (RFC 3489 and RFC 5389). :star: 71 :fork_and_knife: 17
* [:octocat: golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. :star: 3 :fork_and_knife: 0
* [:octocat: gopacket](https://github.com/google/gopacket) - A Go library for packet processing with libpcap bindings :star: 516 :fork_and_knife: 93
* [:octocat: gopcap](https://github.com/akrennmair/gopcap) - A Go wrapper for libpcap :star: 203 :fork_and_knife: 87
* [:octocat: goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. :star: 2 :fork_and_knife: 0
* [:octocat: gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions :star: 101 :fork_and_knife: 36
* [:octocat: gotcp](https://github.com/gansidui/gotcp) - A Go package for quickly writing tcp applications :star: 137 :fork_and_knife: 59
* [:octocat: grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads :star: 17 :fork_and_knife: 1
* [:octocat: graval](https://github.com/koofr/graval) - An experimental FTP server framework. :star: 8 :fork_and_knife: 2
* [:octocat: linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces :star: 16 :fork_and_knife: 2
* [:octocat: llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. :star: 1 :fork_and_knife: 0
* [:octocat: mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang :star: 217 :fork_and_knife: 47
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [:octocat: portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. :star: 18 :fork_and_knife: 0
* [:octocat: raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. :star: 16 :fork_and_knife: 2
* [:octocat: sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. :star: 231 :fork_and_knife: 66
* [:octocat: sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. :star: 58 :fork_and_knife: 1
* [:octocat: tcp_server](https://github.com/firstrow/tcp_server) - A Go library for building tcp servers faster. :star: 35 :fork_and_knife: 16
* [:octocat: utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. :star: 45 :fork_and_knife: 8


## OpenGL

*Libraries for using OpenGL in Go.*

* [:octocat: gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). :star: 182 :fork_and_knife: 19
* [:octocat: glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. :star: 219 :fork_and_knife: 35
* [:octocat: goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). :star: 64 :fork_and_knife: 4
* [:octocat: goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. :star: 23 :fork_and_knife: 3
* [:octocat: mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. :star: 111 :fork_and_knife: 16


## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [:octocat: beedb](https://github.com/astaxie/beedb) - A go ORM,support database/sql interface，pq/mysql/sqlite :star: 592 :fork_and_knife: 134
* [:octocat: beego orm](https://github.com/astaxie/beego/tree/master/orm) - A powerful orm framework for go. :star: 6505 :fork_and_knife: 1614
* [:octocat: go-store](https://github.com/gosuri/go-store) - A simple and fast Redis backed key-value store library for Go. :star: 70 :fork_and_knife: 5
* [:octocat: gomodel](https://github.com/cosiner/gomodel) - A lightweight, fast, orm-like library helps interactive with database. :star: 46 :fork_and_knife: 4
* [:octocat: GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. :star: 3492 :fork_and_knife: 391
* [:octocat: gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. :star: 1997 :fork_and_knife: 250
* [:octocat: QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. :star: 380 :fork_and_knife: 70
* [:octocat: upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. :star: 315 :fork_and_knife: 34
* [:octocat: Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. :star: 1090 :fork_and_knife: 213
* [:octocat: Zoom](https://github.com/albrow/zoom) - A blazing-fast datastore and querying engine built on Redis. :star: 126 :fork_and_knife: 4


## Package Management

*Libraries for package and dependency management.*

* [:octocat: gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. :star: 190 :fork_and_knife: 9
* [:octocat: glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. :star: 1449 :fork_and_knife: 75
* [:octocat: godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. :star: 3240 :fork_and_knife: 289
* [:octocat: gom](https://github.com/mattn/gom) - Go Manager - bundle for go. :star: 1042 :fork_and_knife: 83
* [:octocat: goop](https://github.com/nitrous-io/goop) - A simple dependency manager for Go (golang), inspired by Bundler. :star: 752 :fork_and_knife: 44
* [:octocat: gopm](https://github.com/gpmgo/gopm) - Go Package Manager :star: 913 :fork_and_knife: 88
* [:octocat: gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. :star: 921 :fork_and_knife: 48
* [:octocat: johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git :star: 215 :fork_and_knife: 6
* [:octocat: nut](https://github.com/jingweno/nut) - Vendor Go dependencies :star: 244 :fork_and_knife: 12
* [:octocat: VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments :star: 84 :fork_and_knife: 2


## Query Language

* [:octocat: graphql](https://github.com/tmc/graphql) - graphql parser + utilities. :star: 34 :fork_and_knife: 9
* [:octocat: graphql](https://github.com/sevki/graphql) - GraphQL implementation in go. :star: 28 :fork_and_knife: 2
* [:octocat: graphql-go](https://github.com/chris-ramon/graphql-go) - An implementation of GraphQL for Go. :star: 343 :fork_and_knife: 30
* [:octocat: jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. :star: 42 :fork_and_knife: 2


## Resource Embedding

* [:octocat: fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. :star: 37 :fork_and_knife: 1
* [:octocat: go-bindata](https://github.com/jteeuwen/go-bindata) - Package that converts any file into managable Go source code. :star: 1672 :fork_and_knife: 123
* [:octocat: go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable :star: 2 :fork_and_knife: 0
* [:octocat: go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. :star: 97 :fork_and_knife: 6
* [:octocat: go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. :star: 681 :fork_and_knife: 38
* [:octocat: statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. :star: 31 :fork_and_knife: 1
* [:octocat: vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. :star: 72 :fork_and_knife: 5


## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [:octocat: blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms) :star: 89 :fork_and_knife: 13
* [:octocat: chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. :star: 286 :fork_and_knife: 45
* [:octocat: evaler](https://github.com/soniah/evaler) - A simple floating point arithmetic expression evaluator :star: 20 :fork_and_knife: 4
* [:octocat: ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages :star: 151 :fork_and_knife: 12
* [:octocat: geom](https://github.com/skelterjohn/geom) - 2D geometry for golang :star: 32 :fork_and_knife: 13
* [:octocat: go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go :star: 377 :fork_and_knife: 26
* [:octocat: go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg :star: 0 :fork_and_knife: 0
* [:octocat: go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language :star: 0 :fork_and_knife: 0
* [:octocat: go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled) :star: 239 :fork_and_knife: 56
* [:octocat: gocomplex](https://github.com/varver/gocomplex) - A complex number library for the Go programming language. :star: 1 :fork_and_knife: 0
* [:octocat: gofrac](https://github.com/anschelsc/gofrac) - A (goinstallable) fractions library for go with support for basic arithmetic. :star: 6 :fork_and_knife: 2
* [:octocat: gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams :star: 66 :fork_and_knife: 14
* [:octocat: gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices. :star: 228 :fork_and_knife: 33
* [:octocat: gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. :star: 226 :fork_and_knife: 31
* [:octocat: goraph](https://github.com/gyuho/goraph) - A pure Go graph theory library(data structure, algorith visualization) :star: 195 :fork_and_knife: 28
* [:octocat: gostat](https://github.com/ematvey/gostat) - A statistics library for the go language :star: 3 :fork_and_knife: 0
* [:octocat: mudlark-go](https://github.com/pwil3058/mudlark-go-pkgs) - A collection of packages providing (hopefully) useful code for use in software using Google's Go programming language. :star: 0 :fork_and_knife: 0
* [:octocat: pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go :star: 10 :fork_and_knife: 4
* [:octocat: stats](https://github.com/montanaflynn/stats) - A statistics package with common functions missing from the Golang standard library. :star: 578 :fork_and_knife: 34
* [:octocat: streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. :star: 1274 :fork_and_knife: 113
* [:octocat: vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code. (currently inactive) :star: 53 :fork_and_knife: 8


## Security

*Libraries that are used to help make your application more secure.*

* [:octocat: acmetool](https://github.com/hlandau/acme) — ACME (Let's Encrypt) client tool with automatic renewal. :star: 660 :fork_and_knife: 22
* [:octocat: BadActor](https://github.com/jaredfolkins/badactor) - An in-memory, application-driven jailer built in the spirit of fail2ban :star: 164 :fork_and_knife: 3
* [:octocat: go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)" :star: 26 :fork_and_knife: 5
* [:octocat: lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt) :star: 993 :fork_and_knife: 65
* [:octocat: passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. :star: 83 :fork_and_knife: 3
* [:octocat: simple-scrypt](https://github.com/elithrar/simple-scrypt) - an scrypt package with a simple, obvious API and automatic cost calibration built-in. :star: 59 :fork_and_knife: 6

## Serialization

*Libraries and tools for binary serialization*

* [:octocat: asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang :star: 0 :fork_and_knife: 1
* [:octocat: go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go :star: 241 :fork_and_knife: 20
  * [:octocat: bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. :star: 53 :fork_and_knife: 7
* [:octocat: go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support :star: 526 :fork_and_knife: 72
* [:octocat: gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets :star: 354 :fork_and_knife: 49
* [:octocat: goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. :star: 810 :fork_and_knife: 163
* [:octocat: mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. :star: 556 :fork_and_knife: 71
* [:octocat: php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions :star: 47 :fork_and_knife: 16
* [:octocat: structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. :star: 28 :fork_and_knife: 2


## Server Applications

* [:octocat: algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. :star: 219 :fork_and_knife: 11
* [:octocat: Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. :star: 4982 :fork_and_knife: 317
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [:octocat: devd](https://github.com/cortesi/devd) - A local webserver for developers :star: 1983 :fork_and_knife: 65
* [:octocat: etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery. :star: 8965 :fork_and_knife: 1475
* [:octocat: minio](https://github.com/minio/minio) - Minio is a distributed object storage server. :star: 770 :fork_and_knife: 82
* [nsq](http://nsq.io/) - A realtime distributed messaging platform
* [:octocat: yakvs](https://github.com/sci4me/yakvs) - A small, networked, in-memory key-value store. :star: 5 :fork_and_knife: 1


## Template Engines

*Libraries and tools for templating and lexing.*

* [:octocat: ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. :star: 432 :fork_and_knife: 27
* [:octocat: amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. :star: 567 :fork_and_knife: 36
* [:octocat: damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. :star: 16 :fork_and_knife: 1
* [:octocat: ego](https://github.com/benbjohnson/ego) - A lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. :star: 246 :fork_and_knife: 18
* [:octocat: fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). :star: 40 :fork_and_knife: 0
* [:octocat: kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. :star: 66 :fork_and_knife: 5
* [:octocat: mustache](https://github.com/hoisie/mustache) - A Go implementation of the Mustache template language. :star: 780 :fork_and_knife: 112
* [:octocat: pongo2](https://github.com/flosch/pongo2) - A Django-like template-engine for Go. :star: 675 :fork_and_knife: 62
* [:octocat: raymond](https://github.com/aymerick/raymond) - A complete handlebars implementation in Go. :star: 77 :fork_and_knife: 2
* [:octocat: Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. :star: 489 :fork_and_knife: 63
* [:octocat: Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/) :star: 110 :fork_and_knife: 12


## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [:octocat: assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions :star: 5 :fork_and_knife: 1
    * [:octocat: assert](https://github.com/bmizerany/assert) - Asserts to Go testing :star: 120 :fork_and_knife: 32
    * [:octocat: badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package :star: 1 :fork_and_knife: 1
    * [:octocat: bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them :star: 11 :fork_and_knife: 1
    * [:octocat: frisby](https://github.com/verdverm/frisby) - a REST API testing framework :star: 127 :fork_and_knife: 5
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go
    * [:octocat: go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal :star: 133 :fork_and_knife: 2
    * [:octocat: go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code :star: 35 :fork_and_knife: 2
    * [:octocat: go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests :star: 82 :fork_and_knife: 5
    * [:octocat: goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go :star: 256 :fork_and_knife: 14
    * [gocheck](http://labix.org/gocheck) - A more advanced testing framework alternative to gotest.
    * [:octocat: GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload :star: 2070 :fork_and_knife: 165
    * [:octocat: godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. :star: 46 :fork_and_knife: 4
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [:octocat: GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language. :star: 109 :fork_and_knife: 17
    * [:octocat: gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. :star: 50 :fork_and_knife: 4
    * [:octocat: Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. :star: 21 :fork_and_knife: 2
    * [:octocat: restit](https://github.com/yookoala/restit) - A Go micro framework to help writing RESTful API integration test. :star: 24 :fork_and_knife: 0
    * [:octocat: Testify](https://github.com/stretchr/testify) - A sacred extension to the standard go testing package. :star: 1704 :fork_and_knife: 198

* Mock
    * [:octocat: counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects :star: 54 :fork_and_knife: 9
    * [:octocat: go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions :star: 192 :fork_and_knife: 34
    * [:octocat: go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. :star: 3 :fork_and_knife: 0
    * [:octocat: gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. :star: 187 :fork_and_knife: 1
    * [:octocat: gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. :star: 226 :fork_and_knife: 34
    * [:octocat: mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter :star: 18 :fork_and_knife: 4

* Fuzzing and delta-debugging/reducing/shrinking
    * [:octocat: go-fuzz](https://github.com/dvyukov/go-fuzz) - A randomized testing system :star: 1309 :fork_and_knife: 69
    * [:octocat: gofuzz](https://github.com/google/gofuzz) - A library for populating go objects with random values :star: 222 :fork_and_knife: 12
    * [:octocat: gogenerate](https://github.com/arschles/gogenerate) - A Scalacheck-like library for Go :star: %!f(<nil>) :fork_and_knife: %!f(<nil>)
    * [:octocat: Tavor](https://github.com/zimmski/tavor) - A generic fuzzing and delta-debugging framework :star: 139 :fork_and_knife: 4

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [:octocat: blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go :star: 1747 :fork_and_knife: 243
        * [:octocat: github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer with fenced code block highlighting, clickable header anchor links. :star: 28 :fork_and_knife: 3
    * [:octocat: bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer :star: 332 :fork_and_knife: 19
    * [:octocat: enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). :star: 2 :fork_and_knife: 1
    * [:octocat: genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings :star: 36 :fork_and_knife: 3
    * [:octocat: go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. :star: 648 :fork_and_knife: 62
    * [:octocat: go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. :star: 14 :fork_and_knife: 0
    * [:octocat: go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs. :star: 256 :fork_and_knife: 74
    * [:octocat: go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions. :star: 105 :fork_and_knife: 27
    * [:octocat: go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. :star: 52 :fork_and_knife: 8
    * [:octocat: gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. :star: 37 :fork_and_knife: 10
    * [:octocat: gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string. :star: 111 :fork_and_knife: 14
    * [:octocat: gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts :star: 16 :fork_and_knife: 0
    * [:octocat: GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. :star: 2452 :fork_and_knife: 250
    * [:octocat: goregen](https://github.com/zach-klippenstein/goregen) - A library for generating random strings from regular expressions. :star: 14 :fork_and_knife: 3
    * [:octocat: guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. :star: 17 :fork_and_knife: 3
    * [:octocat: mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. :star: 109 :fork_and_knife: 17
    * [:octocat: slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. :star: 72 :fork_and_knife: 10
    * [:octocat: Slugify](https://github.com/avelino/slugify) - A Go slugify application that handles string. :star: 10 :fork_and_knife: 0
    * [:octocat: toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). :star: 809 :fork_and_knife: 131
* Utility
    * [:octocat: gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. :star: 112 :fork_and_knife: 5
    * [:octocat: kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. :star: 2 :fork_and_knife: 0
    * [:octocat: parseargs-go](https://github.com/nproc/parseargs-go) - A string argument parser that understands quotes and backslashes :star: 3 :fork_and_knife: 0
    * [:octocat: parth](https://github.com/codemodus/parth) - URL path segmentation parsing. :star: 5 :fork_and_knife: 0
    * [:octocat: xurls](https://github.com/mvdan/xurls) - Extract urls from text :star: 176 :fork_and_knife: 8


## Third-party APIs

*Libraries for accessing third party APIs.*

* [:octocat: anaconda](https://github.com/ChimeraCoder/anaconda) - A Go client library for the Twitter 1.1 API :star: 504 :fork_and_knife: 133
* [:octocat: aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. :star: 2387 :fork_and_knife: 357
* [:octocat: brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. :star: 10 :fork_and_knife: 0
* [:octocat: clarifai](https://github.com/samuelcouch/clarifai) - A Go client library for interfacing with the Clarifai API. :star: 29 :fork_and_knife: 3
* [:octocat: discordgo](https://github.com/bwmarrin/discordgo) -  Go bindings for the Discord Chat API :star: 50 :fork_and_knife: 9
* [:octocat: facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API :star: 291 :fork_and_knife: 76
* [:octocat: gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API :star: 12 :fork_and_knife: 10
* [:octocat: gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. :star: 13 :fork_and_knife: 7
* [:octocat: gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging :star: 26 :fork_and_knife: 2
* [:octocat: geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), and [Mapbox](https://www.mapbox.com/developers/api/geocoding/) geocoding / reverse geocoding APIs. :star: 114 :fork_and_knife: 6
* [:octocat: ghost](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API. :star: 13 :fork_and_knife: 1
* [:octocat: github](https://github.com/google/go-github) - Go library for accessing the GitHub API. :star: 1543 :fork_and_knife: 338
* [:octocat: go-marathon](https://github.com/gambol99/go-marathon) - A Go library for interacting with Mesosphere's Marathon PAAS. :star: 67 :fork_and_knife: 35
* [:octocat: go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. :star: 70 :fork_and_knife: 1
* [:octocat: go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs. :star: 41 :fork_and_knife: 3
* [:octocat: go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. :star: 8 :fork_and_knife: 0
* [:octocat: goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages. :star: 615 :fork_and_knife: 226
* [:octocat: GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - a Go MusicBrainz WS2 client library. :star: 15 :fork_and_knife: 6
* [:octocat: google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. :star: 584 :fork_and_knife: 122
* [:octocat: google-analytics](https://github.com/chonthu/go-google-analytics) - A simple wrapper for easy google analytics reporting. :star: 4 :fork_and_knife: 0
* [:octocat: google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. :star: 265 :fork_and_knife: 62
* [:octocat: gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. :star: 65 :fork_and_knife: 10
* [:octocat: hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. :star: 95 :fork_and_knife: 26
* [:octocat: hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. :star: 89 :fork_and_knife: 25
* [:octocat: Medium](https://github.com/Medium/medium-sdk-go) - A Golang SDK for Medium's OAuth2 API. :star: 39 :fork_and_knife: 6
* [:octocat: minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. :star: 84 :fork_and_knife: 23
* [:octocat: mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. :star: 12 :fork_and_knife: 2
* [:octocat: paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API :star: 79 :fork_and_knife: 10
* [:octocat: playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK :star: 0 :fork_and_knife: 0
* [:octocat: pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. :star: 10 :fork_and_knife: 1
* [:octocat: rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. :star: 3 :fork_and_knife: 0
* [:octocat: shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. :star: 9 :fork_and_knife: 3
* [:octocat: slack](https://github.com/nlopes/slack) - Slack API in Go. :star: 352 :fork_and_knife: 78
* [:octocat: smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. :star: 6 :fork_and_knife: 0
* [:octocat: spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. :star: 5 :fork_and_knife: 1
* [:octocat: steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. :star: 7 :fork_and_knife: 0
* [:octocat: stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API :star: 348 :fork_and_knife: 77
* [:octocat: telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. :star: 126 :fork_and_knife: 19
* [:octocat: telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. :star: 134 :fork_and_knife: 21
* [:octocat: textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. :star: 4 :fork_and_knife: 0
* [:octocat: TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - A simple golang package to communicate with [themoviedb.org](https://themoviedb.org) :star: 4 :fork_and_knife: 1
* [:octocat: translate](https://github.com/poorny/translate) - Go online translation package. :star: 10 :fork_and_knife: 1
* [:octocat: tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. :star: 0 :fork_and_knife: 0
* [:octocat: webhooks](https://github.com/go-playground/webhooks) - Webhook reciever for GitHub and Bitbucket. :star: 12 :fork_and_knife: 2

## Utilities

*General utilities and tools to make your life easier.*

* [:octocat: abutil](https://github.com/bahlo/abutil) - A collection of often-used Golang helpers. :star: 4 :fork_and_knife: 0
* [:octocat: apm](https://github.com/topfreegames/apm) - A process manager for Golang applications with an HTTP API. :star: 29 :fork_and_knife: 1
* [:octocat: boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates. :star: 39 :fork_and_knife: 3
* [:octocat: command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher :star: 1 :fork_and_knife: 0
* [:octocat: coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go. :star: 1137 :fork_and_knife: 47
* [:octocat: Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. :star: 17 :fork_and_knife: 3
* [:octocat: Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. :star: 80 :fork_and_knife: 6
* [:octocat: delve](https://github.com/derekparker/delve) - Go debugger. :star: 3305 :fork_and_knife: 199
* [:octocat: fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang. :star: 4 :fork_and_knife: 1
* [:octocat: filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. :star: 49 :fork_and_knife: 4
* [:octocat: fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder written in Go :star: 4365 :fork_and_knife: 187
* [:octocat: generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. :star: 1 :fork_and_knife: 0
* [:octocat: gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. :star: 244 :fork_and_knife: 0
* [:octocat: go-cron](https://github.com/rk/go-cron) - A simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. :star: 109 :fork_and_knife: 7
* [:octocat: go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications. :star: 306 :fork_and_knife: 23
* [:octocat: go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. :star: 142 :fork_and_knife: 13
* [:octocat: go-rate](https://github.com/beefsack/go-rate) -  A timed rate limiter for Go. :star: 184 :fork_and_knife: 8
* [:octocat: go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go. :star: 7 :fork_and_knife: 3
* [:octocat: go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. :star: 39 :fork_and_knife: 7
* [:octocat: go-underscore](https://github.com/tobyhede/go-underscore) - A useful collection of helpfully functional Go collection utilities. :star: 833 :fork_and_knife: 41
* [:octocat: goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. :star: 23 :fork_and_knife: 1
* [:octocat: godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. :star: 241 :fork_and_knife: 15
* [:octocat: godotenv](https://github.com/joho/godotenv) - A Go port of Ruby's dotenv library (Loads environment variables from `.env`.) :star: 267 :fork_and_knife: 21
* [:octocat: godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. :star: 2990 :fork_and_knife: 264
* [:octocat: gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development. :star: 207 :fork_and_knife: 43
* [:octocat: gojq](https://github.com/elgs/gojq) - JSON query in Golang. :star: 21 :fork_and_knife: 1
* [:octocat: golarm](https://github.com/msempere/golarm) - Fire alarms with system events. :star: 15 :fork_and_knife: 1
* [:octocat: golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. :star: 13 :fork_and_knife: 3
* [:octocat: gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. :star: 339 :fork_and_knife: 22
* [:octocat: goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. :star: 10 :fork_and_knife: 4
* [:octocat: goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language. :star: 434 :fork_and_knife: 69
* [:octocat: goreq](https://github.com/smallnest/goreq) - An enhanced simplified HTTP client based on gorequest. :star: 11 :fork_and_knife: 2
* [:octocat: gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go. :star: 630 :fork_and_knife: 82
* [:octocat: gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go :star: 48 :fork_and_knife: 5
* [:octocat: grequests](https://github.com/levigross/grequests) - An elegant and simple `net/http` wrapper that follows Python's requests library :star: 700 :fork_and_knife: 30
* [:octocat: htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility :star: 416 :fork_and_knife: 23
* [:octocat: httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries. :star: 402 :fork_and_knife: 27
* [:octocat: hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. :star: 370 :fork_and_knife: 35
* [:octocat: JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. :star: 260 :fork_and_knife: 7
* [:octocat: jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. :star: 23 :fork_and_knife: 1
* [:octocat: jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. :star: 46 :fork_and_knife: 1
* [:octocat: lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go :star: 63 :fork_and_knife: 4
* [:octocat: mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. :star: 196 :fork_and_knife: 25
* [:octocat: mergo](https://github.com/imdario/mergo) - A helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. :star: 107 :fork_and_knife: 37
* [:octocat: moldova](https://github.com/StabbyCutyou/moldova) - A utility for generating random data based on an input template. :star: 113 :fork_and_knife: 3
* [:octocat: mp](https://github.com/sanbornm/mp) - A simple cli email parser. It currently takes stdin and outputs JSON. :star: 10 :fork_and_knife: 0
* [:octocat: multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. :star: 43 :fork_and_knife: 0
* [:octocat: netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. :star: 28 :fork_and_knife: 2
* [:octocat: ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost. :star: 6687 :fork_and_knife: 753
* [:octocat: okrun](https://github.com/xta/okrun) - go run error steamroller. :star: 11 :fork_and_knife: 2
* [:octocat: panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. :star: 1251 :fork_and_knife: 22
* [:octocat: peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. :star: 2880 :fork_and_knife: 96
* [:octocat: pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. :star: 56 :fork_and_knife: 9
* [:octocat: pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. :star: 39 :fork_and_knife: 4
* [:octocat: profile](https://github.com/davecheney/profile) - Simple profiling support package for Go. :star: 417 :fork_and_knife: 22
* [:octocat: request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. :star: 117 :fork_and_knife: 10
* [:octocat: rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. :star: 99 :fork_and_knife: 4
* [:octocat: resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. :star: 273 :fork_and_knife: 10
* [:octocat: robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. :star: 102 :fork_and_knife: 5
* [:octocat: scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. :star: 79 :fork_and_knife: 5
* [:octocat: sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients. :star: 275 :fork_and_knife: 13
* [:octocat: spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. :star: 222 :fork_and_knife: 12
* [:octocat: sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. :star: 1630 :fork_and_knife: 129
* [:octocat: ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go. :star: 5 :fork_and_knife: 0
* [:octocat: xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. :star: 885 :fork_and_knife: 226


## Validation

*Libraries for validation.*

* [:octocat: govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. :star: 963 :fork_and_knife: 92
* [:octocat: validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. :star: 421 :fork_and_knife: 31


## Version Control

*Libraries for version control.*

* [:octocat: gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. :star: 35 :fork_and_knife: 4
* [:octocat: git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. :star: 755 :fork_and_knife: 127
* [:octocat: go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. :star: 40 :fork_and_knife: 11
* [:octocat: hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. :star: 7 :fork_and_knife: 2


## Video

*Libraries for manipulating video.*

* [:octocat: aac/h264](https://github.com/nareix/codec) - Golang aac/h264 encoder and decoder. :star: 147 :fork_and_knife: 35
* [:octocat: gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. :star: 177 :fork_and_knife: 39
* [:octocat: goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. :star: 111 :fork_and_knife: 25
* [:octocat: gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. :star: 110 :fork_and_knife: 23


## Web Frameworks

*Full stack web frameworks.*

* [:octocat: Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. :star: 6505 :fork_and_knife: 1614
* [:octocat: Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. :star: 873 :fork_and_knife: 53
* [:octocat: chi](https://github.com/pressly/chi) - Small, fast and expressive HTTP router built on net/context. :star: 270 :fork_and_knife: 16
* [:octocat: Echo](https://github.com/labstack/echo) - A fast and unfancy micro web framework for Go. :star: 3110 :fork_and_knife: 248
* [:octocat: Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. :star: 5914 :fork_and_knife: 623
* [:octocat: Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times. :star: 1301 :fork_and_knife: 59
* [:octocat: Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). :star: 131 :fork_and_knife: 7
* [:octocat: go-json-rest](https://github.com/ant0ine/go-json-rest) - A quick and easy way to setup a RESTful JSON API. :star: 2227 :fork_and_knife: 229
* [:octocat: go-kit](https://github.com/go-kit/kit) - A Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. :star: 3568 :fork_and_knife: 258
* [:octocat: go-relax](https://github.com/codehack/go-relax) - A framework of pluggable components to build RESTful API's. :star: 118 :fork_and_knife: 3
* [:octocat: go-rest](https://github.com/ungerik/go-rest) - A small and evil REST framework for Go. :star: 87 :fork_and_knife: 8
* [:octocat: go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. :star: 1046 :fork_and_knife: 148
* [:octocat: goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis. :star: 680 :fork_and_knife: 51
* [:octocat: Goat](https://github.com/bahlo/goat) - A minimalistic REST API server in Go. :star: 81 :fork_and_knife: 8
* [:octocat: gocraft/web](https://github.com/gocraft/web) - A mux and middleware package in Go. :star: 1003 :fork_and_knife: 71
* [:octocat: Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. :star: 112 :fork_and_knife: 9
* [:octocat: Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. :star: 48 :fork_and_knife: 1
* [:octocat: golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. :star: 274 :fork_and_knife: 10
* [:octocat: Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster :star: 296 :fork_and_knife: 19
* [:octocat: goose](https://github.com/ian-kent/goose) - Server Sent Events in Go :star: 16 :fork_and_knife: 4
* [Gorilla](https://github.com/gorilla/) - Gorilla is a web toolkit for the Go programming language.
* [:octocat: httprouter](https://github.com/julienschmidt/httprouter) - A high performance router. Use this and the standard http handlers to form a very high performance web framework. :star: 2911 :fork_and_knife: 254
* [:octocat: httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. :star: 137 :fork_and_knife: 11
* [:octocat: Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go. :star: 1017 :fork_and_knife: 103
* [:octocat: mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. :star: 295 :fork_and_knife: 31
* [:octocat: medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba. :star: 15 :fork_and_knife: 1
* [:octocat: mux](https://github.com/gorilla/mux) - A powerful URL router and dispatcher for golang. :star: 2090 :fork_and_knife: 338
* [:octocat: neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. :star: 244 :fork_and_knife: 17
* [:octocat: ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - A high-performance HTTP router and Web framework supporting routes with regular expressions. Comes with full support for quickly building a RESTful API application. :star: 56 :fork_and_knife: 5
* [:octocat: pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra. :star: 916 :fork_and_knife: 90
* [:octocat: Resoursea](https://github.com/resoursea/api) - A REST framework for quickly writing resource based services. :star: 24 :fork_and_knife: 2
* [:octocat: Revel](https://github.com/revel/revel) - A high-productivity web framework for the Go language. :star: 6478 :fork_and_knife: 934
* [:octocat: rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. :star: 10 :fork_and_knife: 1
* [sawsij](http://sawsij.com/) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [:octocat: Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers :star: 335 :fork_and_knife: 9
* [:octocat: tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. :star: 375 :fork_and_knife: 49
* [:octocat: tigertonic](https://github.com/rcrowley/go-tigertonic) - A Go framework for building JSON web services inspired by Dropwizard :star: 921 :fork_and_knife: 70
* [:octocat: traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go. :star: 466 :fork_and_knife: 17
* [:octocat: Volatile](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code. :star: 81 :fork_and_knife: 1
* [:octocat: web.go](https://github.com/hoisie/web) - A simple framework to write webapps in Go. :star: 2613 :fork_and_knife: 378
* [:octocat: xmux](https://github.com/rs/xmux) - A high performance muxer based on `httprouter` with `net/context` support. :star: 45 :fork_and_knife: 2
* [:octocat: Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework. :star: 125 :fork_and_knife: 21
* [:octocat: zeus](https://github.com/daryl/zeus) - A very simple and fast HTTP router for Go. :star: 93 :fork_and_knife: 8


### Middlewares

#### Actual middlewares

* [:octocat: CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. :star: 312 :fork_and_knife: 24
* [:octocat: formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. :star: 18 :fork_and_knife: 0
* [:octocat: Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. :star: 210 :fork_and_knife: 17
* [:octocat: Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. :star: 361 :fork_and_knife: 29
* [:octocat: XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. :star: 42 :fork_and_knife: 7

#### Libraries for creating HTTP middlewares

* [:octocat: alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. :star: 851 :fork_and_knife: 48
* [:octocat: catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). :star: 2 :fork_and_knife: 0
* [:octocat: chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). :star: 41 :fork_and_knife: 0
* [:octocat: go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. :star: 50 :fork_and_knife: 1
* [:octocat: gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. :star: 39 :fork_and_knife: 0
* [:octocat: interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. :star: 234 :fork_and_knife: 14
* [:octocat: muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. :star: 198 :fork_and_knife: 6
* [:octocat: negroni](https://github.com/codegangsta/negroni) - Idiomatic HTTP middleware for Golang. :star: 3431 :fork_and_knife: 239
* [:octocat: render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. :star: 640 :fork_and_knife: 53
* [:octocat: stats](https://github.com/thoas/stats) - A Go middleware that stores various information about your web application. :star: 327 :fork_and_knife: 19

# Tools

Go software and plugins.


## Code Analysis

* [:octocat: dupl](https://github.com/mibk/dupl) - A tool for code clone detection. :star: 44 :fork_and_knife: 2
* [:octocat: errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. :star: 519 :fork_and_knife: 32
* [:octocat: gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. :star: 492 :fork_and_knife: 33
* [:octocat: Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form. :star: 743 :fork_and_knife: 44
* [:octocat: go-checkstyle](https://github.com/qiniu/checkstyle) checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments. :star: 26 :fork_and_knife: 9
* [:octocat: go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages. :star: 19 :fork_and_knife: 0
* [:octocat: goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. :star: 136 :fork_and_knife: 11
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [:octocat: GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. :star: 1276 :fork_and_knife: 137
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [:octocat: gostatus](https://github.com/shurcooL/gostatus) - A command line tool, shows the status of repositories that contain Go packages. :star: 123 :fork_and_knife: 5
* [:octocat: interfacer](https://github.com/mvdan/interfacer) - A linter that suggests interface types. :star: 219 :fork_and_knife: 1
* [:octocat: validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. :star: 56 :fork_and_knife: 10


## Editor Plugins

* [:octocat: go-lang-idea-plugin](https://github.com/go-lang-plugin-org/go-lang-idea-plugin) Go plugin for IntelliJ IDEA. :star: 3110 :fork_and_knife: 366
* [:octocat: go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting :star: 779 :fork_and_knife: 78
* [:octocat: Goclipse](https://github.com/GoClipse/goclipse) - An Eclipse plugin for Go. :star: 499 :fork_and_knife: 146
* [:octocat: gocode](https://github.com/nsf/gocode) - An autocompletion daemon for the Go programming language. :star: 2988 :fork_and_knife: 340
* [:octocat: GoSublime](https://github.com/DisposaBoy/GoSublime) - A Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features. :star: 2146 :fork_and_knife: 190
* [:octocat: velour](https://github.com/velour/velour) - An IRC client for the acme editor. :star: 12 :fork_and_knife: 3
* [:octocat: vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - A Vim plugin to highlight syntax errors on save. :star: 63 :fork_and_knife: 16
* [:octocat: vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. :star: 4408 :fork_and_knife: 387
* [:octocat: Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. :star: 104 :fork_and_knife: 15

## Go Tools

* [:octocat: colorgo](https://github.com/songgao/colorgo) - A wrapper around `go` command for colorized `go build` output. :star: 61 :fork_and_knife: 6
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [:octocat: go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo. :star: 28 :fork_and_knife: 4

## Software Packages

Software written in Go.


### DevOps Tools

* [:octocat: aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool. :star: 1012 :fork_and_knife: 117
* [:octocat: awsenv](https://github.com/soniah/awsenv) - a small binary that loads Amazon (AWS) environment variables for a profile. :star: 7 :fork_and_knife: 3
* [:octocat: Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics. :star: 155 :fork_and_knife: 14
* [:octocat: Boom](https://github.com/rakyll/boom) - Boom is a tiny program that sends some load to a web application. :star: 4063 :fork_and_knife: 282
* [:octocat: bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework. :star: 1711 :fork_and_knife: 228
* [:octocat: dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). :star: 87 :fork_and_knife: 10
* [:octocat: Dropship](https://github.com/chrismckenzie/dropship) - A tool for deploying code via cdn. :star: 21 :fork_and_knife: 1
* [:octocat: EasySSH](https://github.com/hypersleep/easyssh) - Golang package for easy remote execution through SSH and SCP downloading. :star: 85 :fork_and_knife: 31
* [:octocat: Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics. :star: 1131 :fork_and_knife: 203
* [:octocat: go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. :star: 334 :fork_and_knife: 30
* [:octocat: gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. :star: 146 :fork_and_knife: 16
* [:octocat: godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. :star: 184 :fork_and_knife: 19
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [:octocat: gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. :star: 224 :fork_and_knife: 22
* [:octocat: gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool. :star: 1495 :fork_and_knife: 91
* [:octocat: goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. :star: 1247 :fork_and_knife: 60
* [:octocat: GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. :star: 1856 :fork_and_knife: 131
* [:octocat: hk](https://github.com/heroku/hk) - Heroku command-line interface in Go. :star: 767 :fork_and_knife: 42
* [:octocat: kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. :star: 780 :fork_and_knife: 29
* [:octocat: kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google. :star: 13253 :fork_and_knife: 3825
* [:octocat: Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. :star: 145 :fork_and_knife: 25
* [:octocat: ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. :star: 59 :fork_and_knife: 4
* [:octocat: Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. :star: 5116 :fork_and_knife: 1178
* [:octocat: Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. :star: 31 :fork_and_knife: 2
* [:octocat: s3gof3r](https://github.com/rlmcpherson/s3gof3r) - A small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. :star: 628 :fork_and_knife: 76
* [:octocat: Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). :star: 108 :fork_and_knife: 16
* [:octocat: Vegeta] (https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! :star: 3049 :fork_and_knife: 172
* [:octocat: webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. :star: 353 :fork_and_knife: 45
* [Wide](https://wide.b3log.org/login) - A Web-based IDE for Teams using Golang.


### Other Software
* [:octocat: boxed](https://github.com/tejo/boxed) - Dropbox based blog engine :star: 45 :fork_and_knife: 5
* [:octocat: Cherry](https://github.com/rafael-santiago/cherry) - A tiny webchat server in Go. :star: 69 :fork_and_knife: 7
* [:octocat: Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. :star: 1243 :fork_and_knife: 99
* [:octocat: Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections. :star: 4162 :fork_and_knife: 144
* [:octocat: confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. :star: 2459 :fork_and_knife: 322
* [Docker](http://www.docker.com/) - An open platform for distributed applications for developers and sysadmins.
* [:octocat: fleet](https://github.com/coreos/fleet) - A Distributed init System. :star: 2112 :fork_and_knife: 261
* [:octocat: Go Package Store](https://github.com/shurcooL/Go-Package-Store#go-package-store-) - An app that displays updates for the Go packages in your GOPATH. :star: 633 :fork_and_knife: 15
* [:octocat: gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. :star: 30 :fork_and_knife: 4
* [:octocat: GoDocTooltip](https://github.com/diankong/GoDocTooltip) - A chrome extension for Go Doc sites, which shows function description as tooltip at funciton list. :star: 7 :fork_and_knife: 0
* [:octocat: Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. :star: 4848 :fork_and_knife: 395
* [:octocat: heka](https://github.com/mozilla-services/heka) - universal tool for data processing from Mozilla. Large collection of built-in plugins. Extendable via Go and Lua plugin API. :star: 2921 :fork_and_knife: 448
* [hsync](http://ambrevar.bitbucket.org/hsync/) - A filesystem hierarchy synchronizer.
* [hugo](http://gohugo.io/) - A Fast and Modern Static Website Engine.
* [:octocat: ipe](https://github.com/dimiro1/ipe) - An open source Pusher server implementation compatible with Pusher client libraries written in GO. :star: 142 :fork_and_knife: 10
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [limetext](http://limetext.org/) Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [:octocat: LiteIDE](https://github.com/visualfc/liteide) LiteIDE is a simple, open source, cross-platform Go IDE. :star: 2636 :fork_and_knife: 394
* [:octocat: naclpipe](https://github.com/unix4fun/naclpipe) - A simple NaCL EC25519 based crypto pipe tool written in Go. :star: 5 :fork_and_knife: 0
* [:octocat: nes](https://github.com/fogleman/nes) - A Nintendo Entertainment System (NES) emulator written in Go. :star: 2211 :fork_and_knife: 168
* [:octocat: orange-cat](https://github.com/noraesae/orange-cat) - A Markdown previewer written in Go. :star: 139 :fork_and_knife: 4
* [:octocat: peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. :star: 279 :fork_and_knife: 41
* [:octocat: Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email. :star: 630 :fork_and_knife: 33
* [:octocat: restic](https://github.com/restic/restic) - De-duplicating backup program. :star: 547 :fork_and_knife: 50
* [:octocat: rkt](https://github.com/coreos/rkt) - An App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM. :star: 5309 :fork_and_knife: 478
* [:octocat: Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. :star: 2236 :fork_and_knife: 297
* [:octocat: shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). :star: 39 :fork_and_knife: 2
* [:octocat: snap](https://github.com/intelsdi-x/snap) - A powerful telemetry framework. :star: 566 :fork_and_knife: 58
* [:octocat: Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. :star: 897 :fork_and_knife: 24
* [syncthing](https://syncthing.net/) - An open, decentralized file synchronization tool and protocol.
* [:octocat: Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. :star: 153 :fork_and_knife: 15
* [:octocat: toto](https://github.com/blogcin/ToTo) - A simple proxy server written in Go language, can be used together with browser. :star: 4 :fork_and_knife: 0
* [:octocat: toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. :star: 1168 :fork_and_knife: 43
* [tsuru](https://tsuru.io/) - An extensible and open source Platform as a Service software.
* [:octocat: websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart). :star: 18 :fork_and_knife: 4
* [:octocat: wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). :star: 170 :fork_and_knife: 9







# Resources

Where to discover new Go libraries.


## Benchmarks

* [:octocat: autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. :star: 85 :fork_and_knife: 26
* [:octocat: go-benchmarks](https://github.com/tylertreat/go-benchmarks) - A few miscellaneous Go microbenchmarks. Compare some language features to alternative aproaches. :star: 19 :fork_and_knife: 1
* [:octocat: go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. :star: 650 :fork_and_knife: 87
* [:octocat: go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go. :star: 3 :fork_and_knife: 0
* [:octocat: go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. :star: 281 :fork_and_knife: 38
* [:octocat: gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. :star: 46 :fork_and_knife: 2
* [:octocat: golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others. :star: 5 :fork_and_knife: 0
* [:octocat: golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - A collection of benchmarks for popular Go database/SQL utilities. :star: 20 :fork_and_knife: 1
* [:octocat: gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs. :star: 48 :fork_and_knife: 2
* [:octocat: kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. :star: 10 :fork_and_knife: 0
* [:octocat: skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark. :star: 555 :fork_and_knife: 82
* [:octocat: speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. :star: 65 :fork_and_knife: 5


## Conferences

* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Bengaluru, India
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [:octocat: GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books :star: 1963 :fork_and_knife: 209
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangweekly](https://twitter.com/golangweekly)


## Websites

* [:octocat: Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - A curated list of awesome remote jobs. A lot of them is looking for Go hackers. :star: 5128 :fork_and_knife: 455
* [:octocat: awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. :star: 15708 :fork_and_knife: 1865
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - A collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [:octocat: Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki. :star: 15254 :fork_and_knife: 1851
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [:octocat: golang-graphics](https://github.com/mholt/golang-graphics) - A collection of Go images, graphics, and art. :star: 77 :fork_and_knife: 3
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.


### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Go By Example](https://gobyexample.com/) - A hands-on introduction to Go using annotated example programs.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [:octocat: Working with Go](https://github.com/mkaz/working-with-go) - An intro to go for experienced programmers. :star: 484 :fork_and_knife: 40


## Windows

* [:octocat: go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. :star: 183 :fork_and_knife: 46
