# tfr-docker-project

[![Build Status](https://travis-ci.org/mrchypark/tfr-docker-project.svg?branch=master)](https://travis-ci.org/mrchypark/tfr-docker-project)

tfr-docker-project based [tensorflow](https://www.tensorflow.org/) + [QuantumObject](https://www.quantumobject.org/). Thx all!
Github repos are here.([tensorflow](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/tools/docker), [QuantumObject](https://github.com/QuantumObject/docker-baseimage))

tfr means tensorflow with rstudio uring r.

## Status ##

## Docker Containers ##

| Docker Container Source on GitHub      | Docker Hub Build Status and URL                           | Image Size
| :------------------------------------  | :-----------------------------------------                | :--------------
| tfr-baseimage                          | [good](https://registry.hub.docker.com/u/mrchypark/tfr-baseimage/)  | [![Layers and Size](https://images.microbadger.com/badges/image/mrchypark/tfr-baseimage.svg)](https://registry.hub.docker.com/u/mrchypark/tfr-baseimage/)
| tfr-rstudio                            | [good](https://registry.hub.docker.com/u/mrchypark/tfr-rstudio/) | [![Layers and Size](https://images.microbadger.com/badges/image/mrchypark/tfr-rstudio.svg)](https://registry.hub.docker.com/u/mrchypark/tfr-rstudio/)

# info

Docker container for [RStudio Server 1.0.44][3] with [R 3.3.2][8], [tensorflow 1.0.0][10]

"RStudio is an integrated development environment for R. It includes a console, syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, debugging and workspace management."

## Install dependencies

  - [Docker][2]

To install docker in Ubuntu 14.04 use the commands:

    $ sudo apt-get update
    $ wget -qO- https://get.docker.com/ | sh

 To install docker in other operating systems check [docker online documentation][4]

## Usage

To run container use the command below:

    $ docker run -d -p 8787:8787 mrchypark/tfr-rstudio:<tag_name_what_you_want>
    
Tags are [here](https://hub.docker.com/r/mrchypark/tfr-rstudio/tags/).
    
This will create docker-rstudio container with login/password guest/guest.

To access it and configured the container :

    $ docker exec -it container-id /bin/bash

Them to change guest password :

    $ passwd guest
    $ exit

or you can remove guest user and create a new user:

    $ deluser guest
    $ adduser new_user
    $ exit
    
In the same way you can add additional users without deleting other users. 

## Accessing the RStudio Server applications:

After that check with your browser at addresses plus the port 8787:

  - **http://host_ip:8787/**

note : It was created by using quantumobject/docker-baseimage and installing the package R and RStudio Server from rstudio.com . RStudio is a trademark of RStudio, Inc.

## More Info

About RStudio Server [www.rstudio.com][1]

To help improve this container [tfr-rstudio][5]

RStudio Server [Documentation][6]

Example of [RStudio Server][7]

Tensorflow framework [www.tensorflow.org][10]

For additional info about quantumobject projects check site [www.quantumobject.org][9]

# License

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
