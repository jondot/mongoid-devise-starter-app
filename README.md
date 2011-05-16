MongoidDeviseStarterApp
=======================

So really, I lied. This includes much more than Mongoid, Devise and Rails 3.  
Here are some things for you to check out:

* kaminari for pagination
* fabrication for seeds and fixtures
* factory_girl for fixtures
* compass set up properly
* spork set up properly
* resque and resque_mailer for redis based queue and mailer
* asset_packager for compressing your js and css (avoided Jammit due to java issues on Win32)
* timecop for testing
* database_cleaner set up to erase your mongo data in tests
* ruby-prof for when you need it
* Termfile set up with all of your dependencies. Starts mongo, redis, compass, rails and gvims the app's folder.

How To Use
----------
Just clone, run `bundle install` followed by `terminitor start` (did you not get `terminitor` yet ?!). You're ready to code.  

PS, if you care, remember to replace `MongoidDeviseStarterApp` const around the app.


