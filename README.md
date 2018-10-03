# Markdownreveal container

  * [https://markdownreveal.readthedocs.io/en/stable/](https://markdownreveal.readthedocs.io/en/stable) 
  * [https://github.com/markdownreveal/markdownreveal](https://github.com/markdownreveal/markdownreveal)
  
## Usage 

To see the example 

[https://markdownreveal.github.io/example/#/](https://markdownreveal.github.io/example/#/)

```
docker run --rm -p 8123:8123 mdr:latest 
```

To modify the example clone the git repo and then 

```
docker run --rm -p 8123:8123 -v $PWD:/home/user/example mdr:latest
```

and browse to http://localhost:8123
