<<<<<<< HEAD
# BulletinBoard
Ruby on Rails
=======
# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* [Ruby](https://rubyinstaller.org/downloads/archives/) version - 2.6.9
 
* Rails version - 6.0.4.4

  ``` gem install rails -v 6.0.4.4```


* System dependencies
  * [node](https://nodejs.org/en/download/)
  * [yarn](https://classic.yarnpkg.com/en/docs/install#windows-stable)
  * [mysql](https://dev.mysql.com/downloads/installer/)
  
* Configuration

* Database creation
  1. Start MySQL80 on a service
  1.  Create a database connection on port 3360
  1.  Create a database name `bulletinboard_development`

* Database initialization

  ```
  default: &default
    adapter: mysql2
    encoding: utf8mb4
    pool: <%= ENV.fetch("RAILS_MAX_THREADS") { 5 } %>
    ssl_mode: disabled
    sslverify: false
    username: root
    password: root
    host: localhost
    ```

* How to run the test suite

    * run ```rails s``` then  ```http://127.0.0.1:3000```

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
>>>>>>> 4b5107f (initial commit for rails)
