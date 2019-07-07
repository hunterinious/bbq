# The application "BBQ"
## Educational application

### Annotation
The project was implemented on Ruby on Rails (v4.2.6) for educational purposes.
[Good programmer(c)](https://goodprogrammer.ru/)

### Short description
The application is designed for planning joint events. After registration, the user can add an event in which other users can participate. It is possible to restrict access by installing a pincode.

### Tested / used technologies:
- Many-to-many connection (subscription features)
- Google maps

### Install and Run
Before running the application, you must install all the necessary gems and prepare the database. To do this, in the console in the directory with the application, you must run the following commands:

```
bundle install
bundle exec rake db: migrate
```

To start the local server, run the following command:

`bundle exec rails s`

The list of all used gems is specified in the Gemfile file.

### Demo
The latest current version of the application is running [here](https://hwbm.herokuapp.com/)
