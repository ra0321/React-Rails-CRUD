# Creating a Simple CRUD App with Rails and React

This is the code repository to accompany a tutorial on how to create a Rails API then, using esbuild, build a React front-end to consume it.

## Requirements

- [Ruby](https://www.ruby-lang.org/en/downloads/)
- [Node.js](http://nodejs.org/)

There are instructions for installing both Ruby and Node at the beginning of the tutorial.

## Installation

- Clone repo
- Run `bundle install`
- Run `npm install`
- Run `rake db:create`, `rake db:migrate`, then `rake db:seed`

## Running

- Start the Rails server and esbuild with one command `./bin/dev`
- Hit http://localhost:3000/events
