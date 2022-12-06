# staticnginx-dockerized
A static fileserver using nginx, containerized with docker

This uses the official nginx alpine image to display static files.
Tweaks for performance: sendfile on(reduces context switches) autoindex off (no need to generate directory listing) and gzip_static on (compresses static files)  
