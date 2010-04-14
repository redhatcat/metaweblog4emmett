**This is only guaranteed to work with Ecto as that is what it was requested for
and tested with.**

Add the following to the Initializer.run block your *config/environment.rb*:

    config.gem 'panztel-actionwebservice', :version => '2.3.5',
      :lib => 'actionwebservice', :source => 'http://gemcutter.org'

In Ecto:
--------

* Access Point: http://yourdomain.example.com/backend/api
* System: MetaWeblog
