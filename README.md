![Pro MERN Stack, 2nd Edition](https://images.springer.com/sgw/books/medium/9781484243909.jpg)

This is Shangjun's CS5610 repo. This repo includes the project in Pro MERN Stack.
Transferred from my private repo since chapter 4.

### Chapter 15: Depoly
  Below is the link to my deployed tracker application:
  https://tracker-ui-jsjsam98.herokuapp.com/issues
  And I deploy the tracker-api&tracker-ui in my personal github repo:
  https://github.com/jsjsam98/tracker-api
  https://github.com/jsjsam98/tracker-ui
  For this chapter, it is easy to get stuck at the mongodb URL, remember to add the quotation.
  Before deploying, local test if the api is connected to MongoDB by using Atals instead of local database.
  Sometimes heroku may say "missing required flag", then you should type "$heroku git:remote -a your_app_name" to choose your app.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch15)
  ![ch15](/images/ch15shot.png)

### Chapter 14: Authentication
  For the Issue Tracker application, we used Google to authenticate a user.
  To persist session information in a stateless manner we can use JWT.
  We can also use CORS and cookie to handle restrictions on the browser.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch14)
  ![ch14](/images/ch14shot.png)

### Chapter 13: Advanced Features
  First, we use HOC to add the Toast functionality. Then we generate some random data for MongoDB aggregate.
  Since we have more issues in one page, we develop pagination using some third-party libraries(Bootstrap).
  For the undo delete function, we implement the API and UI respectively. And last, we implement how to use a search control for finding issues based on a text index in MongoDB.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch13)
  ![ch13](/images/ch13shot1.png)
  ![ch13](/images/ch13shot2.png)

### Chapter 12: Server Rendering
  Difference between SSR and SPA:
  SPA fetch data via APIs and construct the DOM on the browser.
  SSR built the entire HTML on the server and send to the browser. Moreover, by using SSR, our application can be indexed by search engine.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch12)
  ![ch12](/images/ch12shot.png)

### Chapter 11: React Bootstrap
  In this chapter we optimized the style of several component with bootstrap. React-Bootstrap replaced the separate JavaScript code, and help us create professional looking interface.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch11)
  ![ch11](/images/ch11shot.png)

### Chapter 10: Architecture and ESLint
  Here are some input components that dealling with different data types. We also practiced the form usage and the difference of controlled and uncontrolled forms. We also added new APIs to cater to the needs of the new form and completed the CRUD paradigm by adding a Delete operation.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch10)
  ![ch10](/images/ch10shot1.png)
  ![ch10](/images/ch10shot2.png)

### Chapter 9: React Router
  I still have some issues at the beginning(cannot read property 'current' of null), I downgrade my react version manually, somehow it works.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch9)
  ![ch09](/images/ch9shot.png)

### Chapter 8: Modularization and Webpack
  I found it not straight to get the screenshot with XHR info using chrome, so
  I turned to FireFox. Besides, the code broke down somewhere, so I used the code from the repo as my start code from this chapter.
  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch8)
  ![ch08](/images/ch8shot.png)


### Chapter 7: Architecture and ESLint

  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch7)
  ![ch07](/images/ch7shot1.png)
  ![ch07](/images/ch7shot2.png)

### Chapter 6: MongoDB

  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch6)
  ![ch06](/images/ch6shot.png)

### Chapter 5: Express and GraphQL

  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch5)
  ![ch05](/images/ch5shot.png)

### Chapter 4: React State

  * Completed node: [Full Source](https://github.ccs.neu.edu/NEU-CS5610-SU21/Shangjun-Book/releases/tag/ch4)
  ![ch04](/images/ch4shot.png)

### Chapter 3: React Classed

  * Completed node: [Full Source](https://github.ccs.neu.edu/shangjun/Shangjun-Book/tree/ch3)
  ![ch03](/images/ch3shot.png)

### Chapter 2: Hello World

  * Completed node: [Full Source](https://github.ccs.neu.edu/shangjun/Shangjun-Book/tree/ch2)
  ![ch02](/images/ch2shot.png)


### Chapter 1: Introduction

  * The MERN stands for MongoDB, Express, React, Node.js.
