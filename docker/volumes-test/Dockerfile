FROM ubuntu:latest

WORKDIR /data

RUN touch foo.txt && echo 'hello world' > foo.txt

RUN mkdir subdir && cd subdir && touch bar.txt && echo 'bye world' > bar.txt
