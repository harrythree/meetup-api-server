# Meetup API with Node.js and Express.js

## Goal

Create a sample app using Node.js and Express.js to integrate the [Meetup API](http://www.meetup.com/meetup_api/). I wanted to be able to pull data from a Meetup group profile and display it via a Handlebars template.

## Notes and Thoughts

* I wanted to use existing libraries that help integrate the Meetup API with Node. I decided to use the npm module [meetup-api](https://www.npmjs.com/package/meetup-api). I also tested these endpoints using basic http requests and everything worked fine.

* I used the basic [API Key authentication method](http://www.meetup.com/meetup_api/auth/) for making requests to the Meetup API. They also have ways to authenticate with oAuth 1 and 2. The meetup-api module handles all 3 authentication methods which is nice.

* Project generated using express generator.

* Overall very easy to use and well documented.

## Running sample project

1. git clone
2. npm install
3. Rename .env-example to .env and populate environment variables with group data
4. npm start