# tfr-docker-project

[![Build Status](https://travis-ci.org/mrchypark/tfr-docker-project.svg?branch=master)](https://travis-ci.org/mrchypark/tfr-docker-project)[![GitHub issues](https://img.shields.io/github/issues/mrchypark/tfr-docker-project.svg)](https://github.com/mrchypark/tfr-docker-project/issues)[![GitHub forks](https://img.shields.io/github/forks/mrchypark/tfr-docker-project.svg)](https://github.com/mrchypark/tfr-docker-project/network)[![GitHub stars](https://img.shields.io/github/stars/mrchypark/tfr-docker-project.svg)](https://github.com/mrchypark/tfr-docker-project/stargazers)[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/mrchypark/tfr-docker-project/master/LICENSE)

tfr-docker-project는 [tensorflow](https://www.tensorflow.org/) + [QuantumObject](https://www.quantumobject.org/)를 기반으로 하고 있습니다. 모두 감사해요!
각 프로젝트의 github repo는 다음과 같습니다.([tensorflow](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/tools/docker), [QuantumObject](https://github.com/QuantumObject/docker-baseimage))

tfr은 tensorflow를 rstudio server에서 사용하게 만든 도커 이미지여서 만든 이름입니다.

## Status ##

## Docker Containers ##

이미지       | 설명        | 태그           | 이미지사이즈   | pulls 현황 | 빌드 상황 
----------- | ----------- | -------------- | ------ | ------- | ----------------------
[tfr-baseimage](https://hub.docker.com/r/mrchypark/tfr-baseimage) |  기본이미지 | [![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:latest-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-cpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:latest-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-cpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:latest-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-gpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:latest-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-gpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:1.0.0-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-cpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:1.0.0-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-cpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:1.0.0-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-gpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-baseimage:1.0.0-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-gpu-py3) | [![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:latest-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-cpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:latest-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-cpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:latest-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-gpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:latest-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:latest-gpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:1.0.0-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-cpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:1.0.0-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-cpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:1.0.0-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-gpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage:1.0.0-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-baseimage:1.0.0-gpu-py3) | [![](https://img.shields.io/docker/pulls/mrchypark/tfr-baseimage.svg)](https://hub.docker.com/r/mrchypark/tfr-baseimage) | [![](https://img.shields.io/docker/automated/mrchypark/tfr-baseimage.svg)](https://hub.docker.com/r/mrchypark/tfr-baseimage/builds)   
[tfr-rstudio](https://hub.docker.com/r/mrchypark/tfr-rstudio)     |  Rstudio 이미지   | [![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:latest-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-cpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:latest-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-cpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:latest-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-gpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:latest-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-gpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:1.0.0-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-cpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:1.0.0-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-cpu-py3)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:1.0.0-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-gpu-py2)<br>[![](https://images.microbadger.com/badges/version/mrchypark/tfr-rstudio:1.0.0-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-gpu-py3) | [![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:latest-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-cpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:latest-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-cpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:latest-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-gpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:latest-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:latest-gpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:1.0.0-cpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-cpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:1.0.0-cpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-cpu-py3)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:1.0.0-gpu-py2.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-gpu-py2)<br>[![](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio:1.0.0-gpu-py3.svg)](https://microbadger.com/images/mrchypark/tfr-rstudio:1.0.0-gpu-py3) | [![](https://img.shields.io/docker/pulls/mrchypark/tfr-rstudio.svg)](https://hub.docker.com/r/mrchypark/tfr-rstudio) | [![](https://img.shields.io/docker/automated/mrchypark/tfr-rstudio.svg)](https://hub.docker.com/r/mrchypark/tfr-rstudio/builds)


# info

[R 3.3.2][8], [tensorflow 1.0.0][10]가 세팅된 [RStudio Server 1.0.44][3]의 도커 이미지입니다.

Rstudio 팀에서 tensorflow 패키지를 제공하고 있어 R에서 tensorflow를 사용하기 위해 도커 이미지를 생성하였습니다.

## 사전 설치 사항

  - [Docker][2]

Ubuntu 14.04 에서 도커를 설치하는 명령어는 아래와 같습니다.:

    $ sudo apt-get update
    $ wget -qO- https://get.docker.com/ | sh

다른 운영체제에서 설치하는 방법은  [docker online documentation][4]을 참고하세요. windows 사용자의 경우 pro 버전이 아닐 경우 docker toolbox를 사용해야 합니다.

## 사용법

컨테이너를 켜는 방법은 아래와 같습니다.:

    $ docker run -d -p 8787:8787 mrchypark/tfr-rstudio:<tag_name_what_you_want>
    
태그는 [여기](https://hub.docker.com/r/mrchypark/tfr-rstudio/tags/)를 참고하세요.
    
브라우저로 Rstudio server에 접속하면 로그인/패스워드 가 guest/guest으로 설정되어 있어 사용하시면 됩니다.

컨테이너 내부로 들어가 설정작업을 하시기 위한 명령어는 아래와 같습니다.:

    $ docker exec -it container-id /bin/bash

Ubuntu bash에 들어가게 되는데 guest 비밀번호를 바꾸는 명령어는 아래와 같습니다.:

    $ passwd guest
    $ exit

또는 guest 유저를 지우고 새로운 유저 아이디를 만드는 명령어는 아래와 같습니다.:

    $ deluser guest
    $ adduser new_user
    $ exit
    
다른 유저를 지우지 않고 새로운 유저 아이디를 생성하는 것도 가능합니다. 

## RStudio Server에 접속하는 방법:

아래와 같은 주소와 포트 8787로 브라우저를 통해 접속하시면 됩니다.:

  - **http://host_ip:8787/**

note : 퀀텀오브젝트의 rstudio docker 프로젝트의 이미지 빌드 명령어를 tensorflow 공식 이미지에 추가해 제작했으며, Rstudio는 RStudio, Inc의 제품입니다.

## 추가 정보

About RStudio Server [www.rstudio.com][1]

To help improve this container [tfr-rstudio][5]

RStudio Server [Documentation][6]

Example of [RStudio Server][7]

Tensorflow framework [www.tensorflow.org][10]

Tensorflow package for R [Documentation][11]

For additional info about quantumobject projects check site [www.quantumobject.org][9]

# 라이선스

The Dockerfiles in this repository are licensed under the MIT license.

[1]:http://www.rstudio.com
[2]:https://www.docker.com
[3]:http://www.rstudio.com/products/rstudio/download-server
[4]:http://docs.docker.com
[5]:https://github.com/mrchypark/tfr-docker-project
[6]:https://support.rstudio.com/hc/en-us/categories/200035113-Documentation
[7]:https://rstudio.quantumobject.org
[8]:http://www.r-project.org
[9]:https://www.quantumobject.org
[10]:https://www.tensorflow.org/
[11]:https://rstudio.github.io/tensorflow/