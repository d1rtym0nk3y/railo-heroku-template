lucee-heroku-template
============

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Lucee for heroku

Blank Lucee template for creating a Lucee site on Heroku

requires [Maven](http://maven.apache.org/) to build the project, and optionally [foreman](https://github.com/ddollar/foreman) to run locally

To get thing running do

```bash
$ git clone https://github.com/mikesprague/lucee-heroku-template.git
$ cd lucee-heroku-template
$ mvn package
$ foreman start
```

NOTE: On Windos machines you may have more success with ```$ foreman start -f Procfile.dev```

You'll now have Lucee up and running at [http://localhost:5000](http://localhost:5000).
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
