ProfitTrailer for Docker
------------------------

**ProfitTrailer** is a smart crypto currency trading bot. It gives you the ability to trade using different exchanges in a fast and simple way.
For easier deployment, I set up a *Docker Container*.

For more information about ProfitTrailer :

 - Official website : https://profittrailer.com
 - Wiki : https://wiki.profittrailer.io
 - Github : https://github.com/taniman/profit-trailer

Usage
-----

Start a new container with a volume for your config files

    docker run -d --name profittrailer -p 8081:8081 rodriguw19/profit-trailer:latest

[![Docker Stars](https://img.shields.io/docker/stars/rodriguw19/profit-trailer.svg)](https://hub.docker.com/r/rodriguw19/profit-trailer/)
[![Docker Pulls](https://img.shields.io/docker/pulls/rodriguw19/profit-trailer.svg)](https://hub.docker.com/r/rodriguw19/profit-trailer/)

This is fork. All credits go to rafffael.
