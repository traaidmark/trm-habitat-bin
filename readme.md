## Create new wordpress instance

- `./bin/wp-init $name $repo-url`

## Build PHP Image

```
docker build -t traaidmark/php-8-fpm -f docker/php-8-fpm.Dockerfile .
```
