To build a project in local environment:
1. Install Drupal 11 using lando: https://docs.lando.dev/plugins/drupal/getting-started.html
2. Go to root project directory and run `lando composer install`
3. If everything went well you should see bare Drupal 11 installation with Olivero theme enabled and Mahi theme installed:
4. (Anytime you want) To import changes that are stored in configuration run: `composer install` and `lando drush cim`


