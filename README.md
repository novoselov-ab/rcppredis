## RcppRedis

RcppRedis is a simple Redis client for R which uses Rcpp and hiredis, a
minimalistic C client library for Redis.

## History

This package os derived from an initial fork of an earlier attempt named
'rhiredis' by Wush Wu, and has since been extended. William Pleasant provided
some early patches.

## Dependencies

- [hiredis](https://github.com/redis/hiredis) library (eg [libhiredis-dev](https://packages.debian.org/sid/libhiredis-dev) on Debian or Ubuntu)
- [Rcpp](https://github.com/RcppCore/Rcpp) for seamless R and C++ integration
- [RApiSerialize](https://github.com/eddelbuettel/rapiserialize) for C-level serialization from the R API

The package should install from source like any other R package provided the
dependency on the [hiredis](https://github.com/redis/hiredis) is
met. `pkg-config` is used to find the hiredis headers and library. Both Rcpp
and RApiSerialized can be installed from CRAN or GitHub. 

## Getting Started

Run some of the scripts from the demo/ directory.

## Status

[![Build Status](https://travis-ci.org/eddelbuettel/rcppredis.png)](https://travis-ci.org/eddelbuettel/rcppredis)
