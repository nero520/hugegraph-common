# hugegraph-common

[![License](https://img.shields.io/badge/license-Apache%202-0E78BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Build Status](https://travis-ci.org/hugegraph/hugegraph-common.svg?branch=release-1.6.0)](https://travis-ci.org/hugegraph/hugegraph-common)
[![codecov](https://codecov.io/gh/hugegraph/hugegraph-common/branch/release-1.6.0/graph/badge.svg)](https://codecov.io/gh/hugegraph/hugegraph-common)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.baidu.hugegraph/hugegraph-common/badge.svg?version=1.6.0)](https://mvnrepository.com/artifact/com.baidu.hugegraph/hugegraph-common/1.6.0)

hugegraph-common is a common module for [HugeGraph](https://github.com/hugegraph/hugegraph) and its peripheral components.
hugegraph-common encapsulates locks, configurations, events, iterators, rest and some 
numeric or collection util classes to simplify the development of HugeGraph and 
its components.

## Components

- Lock: atomic lock, key lock, lock group and lock manger
- Config: register and load config option with security check
- Event: listening and notification, do something asynchronously
- Iterator: some iterators with extra functions, map, filter, extend etc.
- Rest: RESTful client implemented on Jersey, POST, PUT, GET and DELETE
- Util: Performance analyzer, version checker, numeric and Collection utils, log and exception utils etc.

## Licence
The same as HugeGraph, hugegraph-common is also licensed under Apache 2.0 License.
