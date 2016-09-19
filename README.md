[![Build Status](https://travis-ci.org/microservices-demo/carts.svg?branch=master)](https://travis-ci.org/microservices-demo/carts) [![Coverage Status](https://coveralls.io/repos/github/microservices-demo/carts/badge.svg?branch=master)](https://coveralls.io/github/microservices-demo/carts?branch=master)
[![](https://images.microbadger.com/badges/image/weaveworksdemos/cart.svg)](http://microbadger.com/images/weaveworksdemos/cart "Get your own image badge on microbadger.com")
# cart
A microservices-demo service that provides shopping carts for users.

This build is built, tested and released by travis.

# Test
`./test/test.sh < python testing file >`. For example: `./test/test.sh unit.py`

# Build
`GROUP=weaveworksdemos COMMIT=test ./scripts/build.sh`

# Push
`GROUP=weaveworksdemos COMMIT=test ./scripts/push.sh`
