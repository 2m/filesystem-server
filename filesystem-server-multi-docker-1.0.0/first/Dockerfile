FROM ubuntu:14.04

MAINTAINER Martynas Mickevičius martynas.mickevicius@typesafe.com
RUN apt-get update

CMD (python3 -m http.server $WEB1_BIND_PORT &) && python3 -m http.server $WEB2_BIND_PORT
