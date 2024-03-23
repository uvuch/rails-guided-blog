# README


* Run docker image
    `docker run --name blog -d --rm -e SECRET_KEY_BASE=123 -p 443:443 -p 80:3000 -v secrets:/secrets  uvuch81/blog:0.3`
