FROM ubuntu:14.04

MAINTAINER Martynas Mickevičius martynas.mickevicius@typesafe.com
RUN apt-get update

CMD (python3 -m http.server 8000 &) && python3 -m http.server 8001
