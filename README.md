# UpaReal OpenAPI spec

Documentation at https://upareal.github.io/spec/

```bash
# validation
$ docker run --rm -v .:/spec redocly/cli lint openapi.json

# documentation
docker run --rm -v .:/spec redocly/cli build-docs -o index.html --title UpaReal openapi.json
```