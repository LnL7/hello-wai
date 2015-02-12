_hello-helics_
===========

Simple Haskell web application, built with [_wai_](https://hackage.haskell.org/package/wai).

Part of the [Halcyon “Hello, world!” shootout](https://halcyon.sh/shootout/).


Usage
-----

```
$ NEW_RELIC_LICENSE_KEY=xxx PORT=8080  hello-helics
```

Use another version of the [New Relic Agent SDK](http://download.newrelic.com/agent_sdk/)

```
$ export NEW_RELIC_AGENT_SDK=archive/nr_agent_sdk-v0.16.0.0-beta.x86_64.tar.gz
```


### Installation

Installs in one command on most systems, using [Halcyon](https://halcyon.sh/):

```
$ halcyon install https://github.com/LnL7/hello-helics
```


### Deployment

Deploys in one click to a new [DigitalOcean](https://digitalocean.com/) droplet, or to the [Heroku](https://heroku.com/) web application platform:

- [Deploy to DigitalOcean](https://halcyon.sh/deploy/?url=https://github.com/LnL7/hello-helics)
- [Deploy to Heroku](https://heroku.com/deploy?template=https://github.com/LnL7/hello-helics)


About
-----

Uses [_helics-wai_](http://hackage.haskell.org/package/helics-wai) to enable New Relic APM.

<iframe src="https://rpm.newrelic.com/public/charts/k17g51aoyE4" width="500" height="300" scrolling="no" frameborder="no"></iframe>

Made by [Daiderd Jordan](https://github.com/lnl7/).  Published under the [MIT X11 license](https://mietek.io/license/).
