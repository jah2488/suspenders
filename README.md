Suspenders is a base Rails application that you can upgrade.

  ![Suspenders boy](http://media.tumblr.com/1TEAMALpseh5xzf0Jt6bcwSMo1_400.png)

Installation
------------

First install the suspenders gem:

    gem install suspenders

Then run:

    suspenders create projectname

This will create a Rails 3.1 app in `projectname'. This script creates a new
new git repository. It is not meant to be used against an existing repo.

Suspenders uses [Trout](https://github.com/thoughtbot/trout) to make it
easier to maintain a base version of special files (like Gemfile) in
Suspenders.

Whenever you want to get the latest and greatest Suspenders' Gemfile, run:

    trout update Gemfile

Gemfile
-------

To see the latest and greatest gems, look at Suspenders'
[template/trout/Gemfile](https://github.com/thoughtbot/suspenders/blob/master/template/trout/Gemfile),
which will be copied into your projectname/Gemfile.

It includes application gems like:

* [Paperclip](https://github.com/thoughtbot/paperclip) for file uploads
* [Formtastic](https://github.com/justinfrench/formtastic) for better forms
* [Hoptoad Notifier](https://github.com/thoughtbot/hoptoad_notifier) for exception notification
* [Flutie](https://github.com/thoughtbot/flutie) for default CSS styles
* [Bourbon](https://github.com/thoughtbot/bourbon) for classy sass mixins
* [Clearance](https://github.com/thoughtbot/clearance) for authentication

And testing gems like:

* [Cucumber, Capybara, and Capybara Webkit](http://robots.thoughtbot.com/post/4583605733/capybara-webkit) for integration testing, including Javascript behavior
* [RSpec](https://github.com/rspec/rspec) for awesome, readable isolation testing
* [Factory Girl](https://github.com/thoughtbot/factory_girl) for easier creation of test data
* [Shoulda Matchers](http://github.com/thoughtbot/shoulda-matchers) for frequently needed Rails and RSpec matchers
* [Timecop](https://github.com/jtrupiano/timecop) for dealing with time
* [Bourne](https://github.com/thoughtbot/bourne) and Mocha for stubbing and spying

Other goodies
-------------

Suspenders also comes with:

* [jQuery](https://github.com/jquery/jquery) for Javascript pleasantry
* Rails' flashes set up and in application layout.
* A few nice time formats.

See [template/files](https://github.com/thoughtbot/suspenders/blob/master/template/files) to
see what is generated one-time.

Issues
------

If you have problems, please create a [Github issue](https://github.com/thoughtbot/suspenders/issues).

Contributing
------------

Please see CONTRIBUTING.md for details.

Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Suspenders is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community)

The names and logos for thoughtbot are trademarks of thoughtbot, inc.

License
-------

Suspenders is Copyright © 2008-2011 thoughtbot. It is free software, and may be redistributed under the terms specified in the LICENSE file.
