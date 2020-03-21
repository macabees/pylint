# pylint (Syntax Checker)
pylint is python linter that checks the syntax and formatting of scripting code.

## pylint (Project Info)
[Website](https://www.pylint.org)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/pylint/)

## Build image
`$ docker build -t macabees/pylint:latest .`

## Docker Push
`$ docker push -t macabees/pylint:latest`

Note: requires `docker login`

## Run image
Checks a specific file in the current directory

`$ docker run -it --rm -v $(pwd):/scripts --name pylint macabees/pylint /scripts/fileName.py`

## Help
`$ docker run -it --rm macabees/pylint --help`
