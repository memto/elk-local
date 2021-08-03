### Ref:
- https://github.com/deviantony/docker-elk
- https://github.com/sherifabdlnaby/elastdocker
- https://betterprogramming.pub/using-variables-in-docker-compose-265a604c2006


### Usage

```bash
git clone https://github.com/memto/elk-local.git
cd elk-local
cp env.txt .env		# => Tweak as your need, mostly ELASTIC_PASSWORD
docker-compose up --build
```