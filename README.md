# python-web-bazel-flask-redis-counter

## Description
A POC python flask bazel counter
that uses redis as a datastore.

Redis is not a database that persists data
neither is it a web-bazel-bazelsocket that updates multiple
clients.

## Tech stack
- bazel
- python
  - flask
- redis

## Docker stack
- l.gcr.io/google/bazel:latest
- redis:latest

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://github.com/codefreshdemo/example_python_redis.git
