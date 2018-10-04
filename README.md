# Markdownreveal container

  * [https://markdownreveal.readthedocs.io/en/stable/](https://markdownreveal.readthedocs.io/en/stable) 
  * [https://github.com/markdownreveal/markdownreveal](https://github.com/markdownreveal/markdownreveal)
  
## Usage 

To view the example

[https://markdownreveal.github.io/example/#/](https://markdownreveal.github.io/example/#/)

on your local machine do 

```
docker run --rm -p 8123:8123 docker.io/melwyn/markdownreveal:latest 
```

To modify the example, clone the git repo, cd into the example dir and do 

```
docker run --rm -p 8123:8123 -v $PWD:/home/user/example docker.io/melwyn/markdownreveal:latest
```

and browse to http://localhost:8123
