## Running the example

`make up`

### prerequisites

	 - make
	 - git
	 - docker
	 - docker-compose

### Run Locally

On the first install please make sure you either run `make env` or make yourself a copy of `.env.example` as `.env`.

If all dependencies are satisfied, after running: `make up` the game should be available at:
`localhost:8081` or `$DOCKER_HOST:$PORT_FE_EXTERNAL`


For more predefined `make` commands please see `MAKE_DOCS.md` or the `Makefile`
