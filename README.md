# cloudflare-tunnel-example

## Build
``` bash
docker build . -t nodeweb-test
```
## Run
``` bash
docker run -d --name nodeweb-test -p 10001:3000 nodeweb-test
```
## Test
``` bash
curl -X GET localhost:10001/
```
``` bash
curl -X GET localhost:10001/ping
```
``` bash
curl -X POST localhost:10001/pong
```
