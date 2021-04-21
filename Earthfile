FROM alpine:latest

world:
    RUN echo world

hello:
    FROM +world
    RUN echo hello

all:
    BUILD +hello
