# README

This is sample application of 'Docker on Rails6'

## How it works

1. `$ docker compose build`
1. `$ docker compose run web bin/yarn install --check-files`
1. `$ docker compose run web bin/rails db:create`
1. `$ docker up`

## Deploy

1. `$ heroku create`
1. `$ heroku addons:create heroku-postgresql:hobby-dev`
1. `$ heroku container:push web`
1. `$ heroku container:release web`
