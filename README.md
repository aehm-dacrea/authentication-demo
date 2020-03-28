This is an authentication demo app made with passport.js
it is based on Express.js, MongoDB and simple bootstrap stylings

The principle of this app is the following:
users can read other's anonymous posted secrets but only in case if
they themselves have posted one. All secrets are posted
anonymously. To track who has posted and who has not - here we use 
authentication. I've implemented also Google and Facebook authentication,
and cookies storing.

As my knowledge of Docker is very basic, currently I am not able to containerize
MongoDB, so the only way to run this demo is deploy in on Heroku.