What is this?
=============

Serve Bootstrap is a stripped-down website prototype starting point for 
[Serve](http://get-serve.com/).

It features [HTML5 Boilerplate](http://html5boilerplate.com/), Haml, Sass, 
Compass, your choice of grid frameworks, and lots of best practices.


How do I install and run Serve?
-------------------------------

Serve is distributed as a Ruby gem to make it easy to get up and running. You
must have Ruby installed in order to download and use Serve. The Ruby download
page provides instructions for getting Ruby setup on different platforms:

<http://www.ruby-lang.org/en/downloads/>

After you have Ruby installed, open up the command prompt and type:

    gem install bundler

(OSX and Unix users may need to prefix the command with `sudo`.)

Because we're using [Bundler](http://gembundler.com/) to handle gem dependencies, 
we can install all the required gems (including Serve itself!) by 'cd'-ing to the 
Serve Bootstrap directory and typing:

    bundle install

After Serve is installed, you can start it up in a given directory like this:

    serve

This will start Serve on port 4000. You can now view the prototype in your
Web browser at this URL:

<http://localhost:4000>


Bundled Gems
------------

Serve Bootstrap uses [Compass](http://compass-style.org) & 
[Sass](http://sass-lang.org) to generate CSS, and Haml & Markdown to generate HTML. 

Learn more about **Sass**: <http://sass-lang.org>

Learn more about **Compass**: <http://compass-style.org>

Learn more about **Haml**: <http://haml-lang.com/>

Learn more about **Markdown**: <http://daringfireball.net/projects/markdown/syntax>


Rack and Passenger
------------------

Astute users may notice that this project is also a simple Rack application.
This means that it is easy to deploy it on Passenger or in any other
Rack-friendly environment. Rack it up with the `rackup` command. For more
information about using Serve and Passenger see:

<http://bit.ly/serve-and-passenger>


Exporting
---------

To export your project, use the "export" command:

    serve export <project>:<output>

Where "project" is the path to the project and "output" is the path to the
directory where you would like your HTML and CSS generated.


Learning More
-------------

You can learn more about Serve on its GitHub project page:

<http://github.com/jlong/serve>
