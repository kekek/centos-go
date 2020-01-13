# centos-go

	centos go with make git ..


- go version 1.13.5
- make 
- git 

### build image : centos-go:1.13
```
docker build -t centos-go:1.13 .

docker push ${tag}
```

### run project 

default command is "./build.sh " in root dir.

```
docker run -v ${ws}:/project centos-go:1.13

```


### build
