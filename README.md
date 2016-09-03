# docker-cd-seed
[![Build Status](https://travis-ci.org/sitture/docker-cd-seed.svg?branch=master)](https://travis-ci.org/sitture/docker-cd-seed)

A simple node app running inside a docker container and integrated with Travis CI.

## Prerequisite

* Install Docker from [here](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-getting-started)

## Running

Build the docker Image

```bash
docker-compose build
```

Bring up Container

```bash
docker-compose up
```

Application should now be running at `http://localhost:8080` in your browser.

## Thank you
Heavily inspired from https://github.com/cabdesigns/docker-cd-seed

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
