# Materialize Rails Slim Template

The original template is written by [mkhairi](https://github.com/mkhairi/) and can be found in his [repository](https://github.com/mkhairi/materialize-rails). The template is written in [`slim`] and the database is connected to his own postgres server. I modified his template so that people can run his code locally by using `sqlite3` database or deploy it to a server and use `postgres` database easily (asuming that you are using Heroku PaaS). 

I also rewrote his code into `html` and made some modifications. You can find it [here](https://github.com/melvinchng/materialize-rails). 

### Minimum Requirements
 * Ruby 2.6.10
 * Rails 6.1.6.1

### Demo
 * [Example site](https://safycdqjwb.us12.qoddiapp.com)

### Known Issue:
 * If you are using Windows platform, uninstall all the `bcrypt` gems and reinstall the gems manually using the following command: `gem install bcrypt --platform=ruby`.