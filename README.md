# docker-nginx-fpm

 ## Introduction

Just a docker-compose template to create a dev environments for php using nginx and php-fpm containers

 ## Instructions

 Clone this repo and execute the following from the repo root dir:

 ``` docker-compose up -d```

Copy your php code into the **code** folder and point your browser to:

``` http://localhoat:8080``` 

or if you modified your /etc/host file to point localhost to myapp.dev.local:

```http://myapp.dev.local:8080```


Start coding and refresh your browser.
