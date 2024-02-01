# rpi-gpio-latency-test

Make sure corepack is enabled.

`yarn install` to install everything.

## Simple test

`yarn simple` to run the simple GPIO test. Signal on pin is processed and another pin goes high then low.

## WS

Server / client receives the pin, sends the data via WS to the other, the other triggers pin high then low.

`yarn server` to start the server. `yarn client` to start the client.
