# Sparta NodeJS app DevEnv with CI

## Intro
This repo will be a dev env that you can set up by cloning it and running
vagrant up
## Pre-Requisites
- Git
- Ruby
- Vagrant
- VirtualBox
## Instructions
- Clone this repo  with `git clone`
- Run `vagrant up`
- Run `vagrant ssh app`
- Run `ps aux | grep node` and then run `kill <process_id_for node app.js>`
- Run npm start
- Go to `development.local`

## Tests
### Integration Tests
- `cd` into tests directory
- run `bundle install`
- run `rake spec`
### Unit Tests
-
