# Ruby on Rails Micro-Blogging Application

A fully-fledged micro-blogging application similar to Twitter with login
functionality, account activation through a mailer, authentication,
remember me/stay signed in functions, and password resets through mailer

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[_Ruby on Rails Tutorial_ book](http://www.railstutorial.org/book).
