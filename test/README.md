# RTMP tests

nginx.conf is sample config for testing nginx-rtmp.
Please update paths in it before using.

RTMP port: 1935, HTTP port: 8080

* http://localhost:8080/ - play myapp/mystream with JWPlayer
* http://localhost:8080/record.html - capture myapp/mystream from webcam with old JWPlayer
* http://localhost:8080/rtmp-publisher/player.html - play myapp/mystream with the test flash applet
* http://localhost:8080/rtmp-publisher/publisher.html - capture myapp/mystream with the test flash applet

curl "http://192.168.60.252/control/hls/start?app=hls&name=xx"
curl "http://192.168.60.252/control/hls/stop?app=hls&name=xx"
