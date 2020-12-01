# Sparta NodeJS app DevEnv with CI

## Intro
This repo will be a dev env that you can set up by cloning it and running
vagrant up along with 2 commands inside the virtual machine
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
- enter the virtual machine set up for the app with `vagrant ssh app`
- `cd` into /home/ubuntu/app
- run `npm test`, if there is an error along the lines of "port 3000 already
in use" then stop the app and start it again (you can see how to do this in the
  4th and 5th bullet points of the 'Instructions' section)

## timeline change tracker
