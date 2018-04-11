# NBA Client 

----
## about the project
NBA Client is a React app that allows users to get day-by-day schedule and scores, mark their favorite teams, and view recent and incoming games for each team. 

It uses Google's Firebase to authenticate users and to store user data about their favorite teams.

NBA Client was created with use of the following libraries: 

* react-router
* redux + redux-thunk
* axios
* moment.js
* firebase


---
Note: as it is a pet project, NBA Client accesses an open [thesportsdb API](https://www.thesportsdb.com/) to get the NBA data, but the range of data is limited. 
Unfortunately there is no public API to get NBA standings/full team schedules/box scores that would allow [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS). 


---

## try it out
with any of test credentials:

* email: dummy@example.com, password:qwerty
* email: dummy2@example.com, password:qwerty
* email: dummy3@example.com, password:qwerty
* email: dummy4@example.com, password:qwerty

----
## local setup


Download ---to-be-checked---. Navigate to root folder and install node modules with:

    npm install

start server with:

    npm start