Static Site Template
====================

A static website template is ready to deploy on Heroku.

    ~ MySite
      |~ public/
      | |~ images/
      | |~ javascripts/
      | | |- global.js
      | | |- jquery.js
      | | |- modernizr.js
      | | `- selectivizr.js
      | |~ stylesheets/
      | | |- global.css
      | | `- reset.css
      | |- about.html
      | `- index.html
      `- config.ru

Put new pages on the `public` folder. Links should include the
extension (html) and be relative (starting with `/`).

Running the server
-------------------

1. Navigate to the site folder
2. Run `rackup`
3. Notice the port where it's running:

    [~/Projects/MySite]$ rackup
    [2011-10-28 11:24:39] INFO  WEBrick 1.3.1
    [2011-10-28 11:24:39] INFO  ruby 1.9.2 (2011-02-18) [x86_64-darwin10.7.4]
    [2011-10-28 11:24:39] INFO  WEBrick::HTTPServer#start: pid=56529 port=9292

4. Navigate to `http://localhost:9292` (change the port number if needed)
