# Gems

This document contains the Ruby gems that will be used for the new rails application and backend services.

## Rails

### Authentication
* __Devise__<br>
https://github.com/plataformatec/devise<br>
The main Rails app will use devise for authentication. 

* __Pundit__<br>
https://github.com/elabs/pundit<br>
Minimal authorization through OO design and pure Ruby classes<br>
Resources:
  * [Rails 4.1 starter app with Devise for authentication and Pundit for authorization.](https://github.com/RailsApps/rails-devise-pundit)


### API
* __Grape__<br>
https://github.com/intridea/grape<br>
http://intridea.github.io/grape/<br>
Grape can be [mounted in a Rails app](https://github.com/intridea/grape#rails) as a Rack application. This way, Rails models can be reused for the API and we get all the benefits (speed, REST, versioning) of the framework.<br>

* __Basic Auth__<br>
To start testing the API quickly with authenticated users, we will use basic auth and the devise gem (already used for normal auth in Rails).<br>
Resources:
  * [Authenticating an API With Grape and Devise in Rails 4](http://althafhameez.com/blog/2013/07/10/authenticating-an-api-with-grape-and-devise-in-rails-4/)
  * [Rails + Grape + API Key Authentication](http://mikecoutermarsh.com/rails-grape-api-key-authentication/)

* __OAuth__<br>
https://github.com/nov/rack-oauth2<br>
At some point the API should use OAuth to authenticate users.<br>
Resources:
  * [Grape: API Authentication w/ Devise](http://code.dblock.org/grape-api-authentication-w-devise)

### Style
* __Octicons__<br>
https://octicons.github.com/
GitHub icons font.

* __Font Awesome__<br>
https://github.com/bokmann/font-awesome-rails<br>
The font-awesome font bundled as an asset for the rails asset pipeline

### Other
* __Background jobs__<br>
https://github.com/resque/resque
Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.

* __Friendly URL__<br>
https://github.com/norman/friendly_id<br>
friendly_id lets you create pretty URLs based on an object attribute (or a custom method).

* __Simple Forms__<br>
https://github.com/plataformatec/simple_form<br>
Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.

* __Admin Panel__<br>
https://github.com/gregbell/active_admin<br>
The administration framework for Ruby on Rails applications.

* __Better errors__<br>
https://github.com/charliesome/better_errors<br>
Better error page for Rack apps

## Backend
* __Scheduling__<br>
https://github.com/javan/whenever
Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs. Use this gem with rake tasks for scheduled jobs. 

## General
* __Env variables__<br>
https://github.com/bkeepers/dotenv<br>
Loads environment variables from `.env`.
