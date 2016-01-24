# braucher/fcgi

This [braucher/fcgi](https://hub.docker.com/r/braucher/fcgi/) docker image provides a
very simple http mod\_proxy\_fcgi application container based off of 
[httpd:2.4](https://hub.docker.com/r/_/httpd/)

## Usage - Environment Variables

\# This Docker image is configured via three environment variables:  

```
PROXY_TARGET=app:9000  
DOCUMENT_ROOT=/var/www/app  
DIRECTORY_INDEX=index.php  
```

See the 
[sample-project branch](https://github.com/jwbraucher/docker-fcgi/tree/sample-project)
for an example of how to use this image with docker-compose.

## Development
See DEVELOPMENT.md

## License
MIT license

