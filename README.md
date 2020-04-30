# eos-docker


EOS docker image for mainnet production.


# Usage

```bash
# clone
git clone https://github.com/jeksman/eos-docker.git
cd eos-docker

# modify config.ini if you need
nano config.ini

# run!
docker volume create --name=nodeos-data-volume
docker volume create --name=keosd-data-volume
docker-compose up -d
```

