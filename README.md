# README #

This is a Java puzzle calculating a secret. As you might guess, your goal is to discover the secret. With the current version of the application it is going to take ages (we honestly do not know, but on a typical desktop we are speaking about years).

If you are up for the challenge then your goal is to decrease the running time of this application below 30 seconds and discover the secret along the way. If you are able to solve the secret, you will have eternal satisfaction, knowing that you were able to conquer the almighty Java Performance Beasts.

### Constraints ###

* You are not allowed to change anything in package ``internal''

### Notes ###
 * The puzzle requires internet connection to acquire input data for the calculations
 * The solution reveals a URL. In case you reveal a URL whose DNS record cannot be resolved, you still have some work to do
 

### How to run ###
Use either 
```
#!bash

run.sh
```
 script or 
```
#!java

./gradlew run
```
 command