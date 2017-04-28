# mysite

## Development

To get started with development, set up the dependencies:

    ./scripts/devsetup.sh

And start the development server:

    ./scripts/dev.sh

More information in [HACKING.md](HACKING.md).


## 安装运行

docker run -d -p 5432:5432 -e POSTGRESQL_USER=test -e POSTGRESQL_PASS=oe9jaacZLbR9pN -e POSTGRESQL_DB=test orchardup/postgresql

