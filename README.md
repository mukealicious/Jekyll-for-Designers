Jekyll for Designers
=======

##This is a base Jekyll setup created by a designer for designers
It is automatically transformed by [Jekyll](http://github.com/mojombo/jekyll) into a static site whenever you push your repository to GitHub.

##More Info
I wrote a [blog post](http://muke.me) that explains the thought process that led to the creation of this repo.

##Usage
This particular Jekyll base is intended to be used with Heroku. It uses [Matthew Manning's Ruby Jekyll Buildpack](https://github.com/mattmanning/heroku-buildpack-ruby-jekyll). Also, Compass and Sass are included to make things a little bit easier.

After forking head to the project direcotry and run

`bundle install`

To compile your site and see a preview run

`jekyll --server`

Head over to http://localhost:4000/ to see "Hello World"

Your Jekyll install is up and running and ready to deploy. As taken from Matthew Manning's buildpack, you will need to run the following to deploy to Heroku.

`heroku create -s cedar --buildpack http://github.com/mattmanning/heroku-buildpack-ruby-jekyll.git`

Push to heroku

`git push heroku master`

That's it!
