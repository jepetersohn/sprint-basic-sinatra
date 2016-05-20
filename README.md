# Basic Sinatra Workshop Setup

# Cloud 9 workspace for Ruby and Sinatra 

* Create a BLANK workspace (Not Ruby and Not Rails)

* Name the workspace ``hello-sinatra``

* Open the workspace

* In the terminal tab at the bottom

    $ gem install bundler

    $ bundle init

* edit Gemfile to add sinatra

```
source "https://rubygems.org"

gem 'sinatra'
```

* Run bundle install

* Create the ``app.rb`` file

```
require 'sinatra'

get '/' do
  "HELLO WORLD"
end
```
* Run the app
    $ ruby app.rb -p $PORT -o $IP 

* Open the browser to the link in your terminal which will be something like

    https://hello-sinatra-stujo.c9users.io/

* The link is made with this format:

    https://[YOUR APP NAME]-[YOUR USER NAME].c9users.io/


