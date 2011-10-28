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

