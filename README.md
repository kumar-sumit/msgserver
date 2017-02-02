# README

A basic mobile messaging server(Implemented in Ruby on Rails)

* Each mobile is identified by its userid
* Using ActionCable in Rails to maintain connection between multiple conversation
* Using channel which communicate between front-end and back-end using websockets.
* Using job class which performs message broadcast using Redis server and independent of Rails server.
* Message is sent to specified destination using ActionCable.server.broadcast method

