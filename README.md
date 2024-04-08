# Course Project - Music Streaming Platform

This project is a course example to create a backend system _using object-oriented design_, _design patterns_ and some _good code practices_ in order to provide a __RESTful API__ with different services related to music, podcasts and it is author in a comfortable platform.

## Business model

This is a music streaming platform where users can login from a web platform to listen to music, podcast, follow favorite artists and singers, save music and podcast and make playlist 

### Business rules 
- Podcast may not be longer that 1 hour
- Songs may not be longer that 10 minutes 
- To login you need to have a username and a password 
- There can not be repeated user names 

## User Stories

- __As a__ _artist_, __I want__ to see all reproductions of my music and my podcasts.
- __As a__ _listener_, __I want__ listen to any song and podcast available.
- __As a__ _listener_, __I want__ create a playlist with my favorite songs.
- __As a__ _listener_, __I want__ like and save a song.
- __As a__ _artist_, __I want__ upload and delete a song or podcast.

## Technical definitions

### tools to Use



## Entities
- User: name, id, email, password, login, logout()
- listener(User): play(), like(), add, create_playlist()[E]
- artist(User): upload(), delete()
- content: duration, artist[E]
- song(Content): musical genre
- podcast(Content): topic
