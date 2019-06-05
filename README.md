Docker-Nginx-RTMP
=======

### Running
```bash
docker-compose up -d 
```
### Watching the steam
```bash 
http://<media-server-ip>:8080/hls/<videofile>/index.m3u8
#### example
http://127.0.0.1:8080/hls/movie.mp4/index.m3u8
```