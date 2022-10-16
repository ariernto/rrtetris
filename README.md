# Ruby on rails React Tetris

## Requirements

- Ruby 2.7.4
- NodeJS (v16), and npm
- Heroku CLI
- Postgresql

If cloning the project, to prepare and run:

```sh
bundle install
rails db:create
npm install --prefix client
rails s
npm start --prefix client
```
Run this command to start the Postgres service:

```sh
sudo service postgresql start
```
