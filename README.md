# Bootstrap a new Rails app in Docker

An alpine-flavour Docker image to allow for easy creation of new Rails applications.

## Usage:
Create a new application in a given output directory like so:

```
docker run --rm -v <path-to-output-directory>:/app freeatnet/alpine-rails-bootstrap:latest rails new <app-name> --database=postgresql [...other options]
```

Then, dockerize it to taste.

## Bugs & support
Feel free to open an issue of a pull-request.

## License
This is free and unencumbered software released into the public domain.

## Credits & acknowledgements
Maintainers:
* Arseniy Ivanov <arseniy@freeatnet.com>, 2018

Acknowledgements:
* Package list reused from @pacuna, cf. https://github.com/pacuna/rails5-docker-alpine.

