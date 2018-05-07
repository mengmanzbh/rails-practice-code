# Shop with bootstrap

## Run in docker container
```bash
docker run -itd -p 3001:3001 --name shop-with-bootstrap -v "$PWD":/data -w /data ruby:2.3.3
```
```
docker exec -it shop-with-bootstrap bash
```



## Start rails server
```
gem install rails
```
```
rails s -b 0.0.0.0 -p 3001
```
