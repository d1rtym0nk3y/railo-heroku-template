railo-heroku-template
============

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Railo for heroku

Blank Railo template for creating a Railo site on Heroku

requires [Maven](http://maven.apache.org/) to build the project, and optionally [foreman](https://github.com/ddollar/foreman) to run locally

To get thing running do

```bash
$ git clone git://github.com/d1rtym0nk3y/railo-heroku-template.git mysite.dev
$ cd mysite.dev
$ mvn package
$ foreman start
```

You'll now have Railo up and running at [http://localhost:5000](http://localhost:5000). 
Start adding your code to /webroot.

To deploy your site to heroku you need to setup a heroku account and install the toolbelt, 
you can find their getting started guide [here](https://devcenter.heroku.com/articles/quickstart).

Then..
```bash
$ heroku create
$ git push heroku master
$ heroku open
```

You should now be looking at your app running on heroku.

Enjoy!
