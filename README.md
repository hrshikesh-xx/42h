42h
===

*42h* is a small blog project which aims to evaluate a candidate code skills in 42h (3 hours per day during 2 weeks = 42 hours).

It has been written for junior web developers which have good knowledge of programming but might lack knowledge in web programming.


## Description
*42h* should provide a RESTful JSON API backend and a responsive modular frontend.

Optionally, *42h* may have "web realtime" notifications.

As for the data models, you are free to change/adapt their structure according to your needs.

## Workflow 

1. Fork on GitHub
2. `git clone ...`
3. `git co -b YOURGITHUBUSERNAME`
3. Develop
4. `git ci ...`
5. `git push origin YOURGITHUBUSERNAME`
6. Pull request on GitHub
7. Wait : ]

## Steps

### Step 1
* Write bootstrap/config (backend)

### Step 2
* Model `post` (title, content, etc.) + CRUD (backbend)

### Step 3
* Model `user` (email, username, etc.) + CRUD (backend)

### Step 4
* Authenticate with passportjs (backend)

### Step 5
* Model `comments` (email, content, etc.) + CRUD (backend)
* Model `tag` (for `post`) + CRUD (backend)

### Step 6
* Write tests for all previous steps (backend)

### Step 7
* Write bootstrap/config (frontend)

### Step 8
* Write models and views (frontend)

### Step 9
* Write routes (frontend)

### Step 10 (bonus)
* Add sockjs (server-side)

### Step 11 (bonus)
* Add sockjs (client-side)

### Step 12 (bonus)
* Write notification system for real time comment

### Step 13 to ∞ (bonus)
* `mount /dev/imagination /project/features` : ]

## Protips
* Focus on the 9 first steps
* Write the most beautiful you can
* Do *NOT* document your code (except JSDoc, which is recommanded)
* Use provided resources and complete the list with your own

## Resources

### Coding style
http://nodeguide.com/style.html (applies for frontend JavaScript too)

### Backend
* http://nodejs.org/
* http://expressjs.com (see also http://vimeo.com/56166857)
* http://www.senchalabs.org/connect/
* http://mongoosejs.com/
* http://jade-lang.com/
* http://learnboost.github.io/stylus/
* http://passportjs.org/
* https://github.com/sockjs/sockjs-node
* http://www.mongodb.org/

### Frontend
* https://github.com/bower/bower
* http://backbonejs.org/
* http://requirejs.org/
* http://lodash.com/
* https://github.com/sockjs/sockjs-client
* http://twitter.github.io/bootstrap/
* http://momentjs.com/
