# abstractit/haproxy

Minimalist HAProxy Docker image using Alpine linux.

# Table of Contents

- [Limitations](#limitations)
- [Running](#running)
- [TODO](#todo)

# Limitations

This container will not run without a haproxy configuration file in /data/haproxy.cfg.

# Running
```
docker run -d -v $PATH_TO_DATA:/data -p 80:80 abstractit/haproxy
```

# TODO
Provide a basic config for testing purposes