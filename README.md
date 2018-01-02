# Docker My Traceroute

Alpine Linux container with MTR(My Traceroute)

## Running

Pull image from Docker hub or clone this repository

From Docker Hub:
`docker pull raisiqueira/mtr`

or clone this repository:

```bash
$ git clone https://github.com/raisiqueira/Docker-My-Traceroute
$ cd Docker-My-Traceroute
$ docker build -t raisiqueira/mtr .
$ docker run --rm -ti raisiqueira/mtr mtr raisiqueira.me
```