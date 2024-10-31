build
```bash
docker build . -t ctnelson1997/cs571-f24-hw7-api
docker push ctnelson1997/cs571-f24-hw7-api
```

run
```bash
docker pull ctnelson1997/cs571-f24-hw7-api
docker run --name=cs571_f24_hw7_api -d --restart=always -p 48107:48107 -v /cs571/f24/hw7:/cs571 ctnelson1997/cs571-f24-hw7-api
```
