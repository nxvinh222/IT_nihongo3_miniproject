

## Getting started

To get started with the app, first clone the repo and `cd` into the directory:

```
$ git clone https://github.com/mhartl/sample_app_6th_ed.git
$ cd sample_app_6th_ed
```

Then install the needed packages (while skipping any Ruby gems needed only in production):

```
$ yarn add jquery@3.5.1 bootstrap@3.4.1
$ bundle install --without production
```

Migrate

```
$ rails db:migrate
```


```
$ rails db:seed
$ rails server
```

Admin email `team2@hedspi.con` and password `123456`.


