# docker-rails-mysql-react

Install

```bash
docker-compose build

docker-compose run web rails db:create
docker-compose run web rails db:migrate
docker-compose run web rails db:seed

yarn install
```

Start Server

```bash
docker-compose up
```

Stop Server

```bash
docker-compose down
```

Rebuild

```bash
docker-compose up --build
```

Run bundle install

```bash
docker-compose run web bundle install
```

Connect to mysql container

```bash
mysql -u root -p -h localhost -P 3306 --protocol=tcp
```