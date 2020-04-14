# Go cross compiler (xgo): Go 1.13.10
# Copyright (c) 2019 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11310

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.13.10.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=8a4cbc9f2b95d114c38f6cbe94a45372d48c604b707db2057c787398dfbf8e7f && \
  \
  $BOOTSTRAP_PURE
