# guru_profile

Drupal 8.x install profile with requirements for Guru Theme. 

You may use the following as composer.json in a directory and then use composer to set up the project. 


Create a project with composer replace drupal-project/composer.json with the one below.

<pre>
composer create-project drupal-composer/drupal-project:8.x-dev  --stability dev --no-interaction
cd drupal-project
vi composer.json // Replace with content from composer.json.example
composer update
</pre>

The Update should lead to something like: 

<pre>  - Installing drupal/devel (dev-1.x 79e688d)
    Cloning 79e688d0a2425a0539a7c6b9fe4576cffceee6e5

  - Installing drupal/link_css (dev-1.x 85a6767)
    Cloning 85a67676326c518560b4999d406a8f4ad7b22576

  - Installing guru_theme (1.0)
    Cloning 8.x-1.x

  - Installing guru_profile (1.0)
    Cloning 8.x-1.x

  - Installing drupal/admin_toolbar (1.17.0)
    Loading from cache

Writing lock file
Generating autoload files
> DrupalProject\composer\ScriptHandler::createRequiredFiles
</pre>

<h4>composer.json</h4>
https://github.com/digitaldonkey/guru_profile/blob/8.x-1.x/composer.json.example
