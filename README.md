# docker-images
Docker images saved as tarballs

Large files split into smaller chunks - for example:

$ split --bytes=50MB gcr.io--google_appengine--golang.tar.gz gcr.io--google_appengine--golang.tar.gz. 

Reconsitute by just cat'ing them together - for example:

$ cat gcr.io--google_appengine--golang.tar.gz.* | tar -zxvf -

