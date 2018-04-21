## How to use:

#### On amd64:
docker run --rm --name gulden -p 9231:9231/tcp -v $HOME/gulden:/data jvandenbroek/gulden:amd64

#### On arm64:
docker run --rm --name gulden -p 9231:9231/tcp -v $HOME/gulden:/data jvandenbroek/gulden:arm64