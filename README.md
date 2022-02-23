# cloudflare-tunnel-example

#Build
-- docker build . -t nodeweb-test
#Run
-- docker run -d --name nodeweb-test -p 10001:3000 nodeweb-test
#Test
-- curl -X GET localhost:10001/
-- curl -X GET localhost:10001/ping
-- curl -X POST localhost:10001/pong
