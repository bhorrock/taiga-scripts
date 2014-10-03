# Taiga Bootstrap Scripts #

Scripts for initial deploy of taiga services.

## Requirements ##

- Ubuntu Server 14.04
- Bash
- Git

## Setup server-like environment ##

This environment is not ready for high scale but should work well for small organziations
using taiga.

Having fresh and updated ubuntu 14.04:

```
$ git clone https://github.com/taigaio/taiga-scripts.git
$ cd taiga-scripts
$ bash setup-server.sh
```

## Setup development-like environment ##

This setup is much like the previous but with few differences:

- Not installs services like nginx that only serves for production.
- Set all hostnames to localhost for easy run everything on localhost.

Having fresh and updated ubuntu 14.04:

```
$ git clone https://github.com/taigaio/taiga-scripts.git
$ cd taiga-scripts
$ bash setup-devel.sh
```


## Community ##

[Taiga has a mailing list](http://groups.google.com/d/forum/taigaio). Feel free to join it and ask any questions you may have.

To subscribe for announcements of releases, important changes and so on, please follow [@taigaio](https://twitter.com/taigaio) on Twitter.
