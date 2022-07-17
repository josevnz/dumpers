# DUMPERS

I wanted to have a few very fast set of programs to dump easy to get information from my Linux system into a JSON enabled 
search engine. I got tired of writing Python wrappers for them so here is the result.

Please run each program to see their purpose (--help) but in general the aim is to dump information from your system:

* In JSON format
* As fast as possible

You can manipulate their output with other cool programing languages like [Python](https://www.python.org/), 
or tools like [JQ](https://stedolan.github.io/jq/).

# Author
- Jose Vicente Nunez (kodegeek.com@protonmail.com)

# Running the tools

## Bare-metal

TODO

## Docker container

You will need to pull the image from DockerHub:

```
docker pull josevnz/dumpers
```

Then you will need to use bind volumes so the tools can access the bare-metal files needed to produce the reports.

TODO