# braucher/fcgi 1.2.0

## Features
* Added SCHEME environment variable

# braucher/fcgi 1.1.0

## Features
* Run ‘mkdir -p’ on DocumentRoot so httpd will start

# braucher/fcgi 1.0.1

## Features
* added ```FILES_MATCH```: what files to proxy to backend container

# braucher/fcgi 1.0.0

## Features
* sets up a re-usable fcgi proxy with 3 parameters:
  * ```DOCUMENT_ROOT```: where to serve files from
  * ```DIRECTORY_INDEX```: what file to serve by default
  * ```PROXY_TARGET```: host and port to send fcgi requests to
