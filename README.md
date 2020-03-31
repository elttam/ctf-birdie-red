# Overview

**Title:** Birdie Red  
**Category:** Web  
**Flag:** `libctf{00bdccc9-e23b-4ace-8eed-2d6da1d2c28f}`  
**Difficulty:** Trivial

# Usage

The following will pull the latest 'elttam/ctf-birdie-red' image from DockerHub, run a new container named 'libctfso-birdie-red', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-red \
  elttam/ctf-birdie-red:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-red' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-red:latest
```
