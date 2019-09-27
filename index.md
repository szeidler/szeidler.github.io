## Presentations

* [How to replace Entityqueue with Layout Builder and shifting blocks](https://szeidler.github.io/shifting-layout-blocks-presentation/) (07.03.2019 @ Drupal Usergroup Berlin)
* [Contenta CMS - Decoupled Drupal Starter Kit](https://szeidler.github.io/contentacms-presentation/) (01.02.2018 @ Drupal Usergroup Berlin)
* [Media Fotoweb for Drupal 7](https://szeidler.github.io/fotoweb-presentation/) (25.05.2017 @ RamsaltCamp Lofoten)
* [Patching modules without tears – Using a Drush Patch File](https://docs.google.com/a/ramsalt.com/presentation/d/1GCnHI25R-71VnSEQE3ay_kg-S0UccLaS1_5EfSgrgVM/embed?start=false&loop=false&delayms=3000&usp=embed_googleplus) (03.11.2016 @ Drupal Usergroup Berlin)

## Little helpers

### SimpleSAMLphp on Docker4Drupal

Integrating an additional like SimpleSAMLphp into existing PHP projects, like Drupal is not that easy.
Especially, when you are using a restrictive Nginx configuration like [drupal-with-nginx](https://github.com/perusio/drupal-with-nginx).

With [this additional Nginx configuration](https://gist.github.com/szeidler/703cbf1993d9546b27501ff39e627d1b) you will be able to serve SimpleSAMLphp
in your Drupal application and make use of the [simpleSAMLphp Authentication module](https://www.drupal.org/project/simplesamlphp_auth).

### Wodby Alias Automator

[This Mac OSX Automator workflow](https://www.dropbox.com/s/fx7hosg527qojqu/move-drush-wodby-aliases.workflow.zip?dl=0)

1. watches for the incoming file `wodby.aliases.drushrc.php` in the `~/Downloads` folder
2. moves it to `~/.drush/wodby.aliases.drushrc.php`
3. performs a `drush cc drush`

Any outdated alias file will be replaced with the new downloaded one.
