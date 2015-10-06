####cse5335-project-1
=====================
#####Name: Samyukta Vuyyuru
----------------------
#####UTA id: 1001110500
---------------------
#####website: https://cse5335-sxv0500.herokuapp.com/
--------------------------------------------------------

#####a.  Server framework

    The server framework used for this web application is Ruby-on-Rails , an open source framework. Ruby-on-Rails is a simple to learn and understand framework. On other hand, Rails uses software engineering patterns and techniques, Don’t-Repeat-Yourself (DRY) paradigm which makes it easy to reuse code. The Rails framework follows the Model-View-Controller(MVC) design model and this makes it simpler to create request, response and display the web page content.


#####b.  Client framework

    The client side framework that I choose to work with Ruby-on-Rails is the Java framework with JQuery. JQuery is simple, concise and easy to go with MVC framework on Ruby.


#####c.  Easy implementations

    Ruby-on-Rails is an easy to learn and understand framework, hence it was easy to create a web application and deploy it in Heroku server from the github repository. The MVC framework makes it easy to organize the flow of the requests and reponses from the client to server and vice versa. The most easy and fun part was developing the application with different client side frameworks JQuery, JSON and Ajax. Creating the Github repository and Deploying the application in Heroku server was very useful and informative.

 
#####d. Difficult implementations

    The process of installation of Rails was a lengthy process and in every step of using a new framework, gems had to be installed and updated. One major problem was deploying Rails on Windows, as there were many changes to be made in the Gemfile and application.html.erb file. Secondly, while executing JQuery with Rails , there was a problem with the javascript  turbolinks in the index.html.erb page and though after trying out various solutions and alternatives from Rails blogs and google question forum, the problem could not be solved and apparently had to rebuild the application in Ubuntu.

 
#####e.  Other installations

    In Ruby-on-Rails, a lot of gems (Ruby libraries) had to be installed and bundled to work on this web application project. A few of these include json, sqlite3, jquery-turbolinks which were used for sending a request to the server and response using Ajax and JSON. Few other components used :
    1. GitHub Local  has been installed in the local machine to clone and push the web application into the Github repository.
    2. Openssl toolkit had to be included during the installation process of rails for cryptographic components.
    3. Heroku Toolbelt for running the web application on heroku.

#####f. Ubuntu commands

    * Github
     git init
     echo "cse5335-project-1" >> README.md
     git commit -m "add"
     git remote add origin http://github.com/Samyukta1189/cse5335-project-1.git
     git push -u origin master
     git clone http://github.com/Samyukta1189/cse5335-project-1.git
     git add .
     git commit -m "All files added"
     git push


    * Heroku
     heroku login
     heroku create cse5335-sxv0500
     git add Gemfile Gemfile.lock
     git commit -m 'Gem files updated"
     git push
     git push heroku master
     git sharing : add emmons@uta.edu
     git sharing : add samvaran.rallabandi@mavs.uta.edu
   
  


