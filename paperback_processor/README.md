# How to create book using BookcheeGO?


## Installation

1. download DockerDeskTop

1. download docker image from docker hub, using terminal

```
docker pull minsookim/rlayout

```
1. download docker_book_strater_template from Github

```
  git clone github.com/mskim/docker_book_strater_template

```

1. cd into one of docker_book_strater_template folder
  - lets go into danhangbon folder
  - there should be Rakefile, READMD, sample

```
  cd danhangbon

  docker run -it -v $(pwd):/usr/src/app minsookim/rlayout:v0.0.8 bash

  rake

```