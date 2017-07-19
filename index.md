## Presentations

* [Media Fotoweb for Drupal 7](https://szeidler.github.io/fotoweb-presentation/) (25.05.2017 @ RamsaltCamp Lofoten)
* [Patching modules without tears – Using a Drush Patch File](https://docs.google.com/a/ramsalt.com/presentation/d/1GCnHI25R-71VnSEQE3ay_kg-S0UccLaS1_5EfSgrgVM/embed?start=false&loop=false&delayms=3000&usp=embed_googleplus) (03.11.2016 @ Drupal Usergroup Berlin)

## Little helpers

### Wodby Alias Automator

[This Mac OSX Automator workflow](https://www.dropbox.com/s/fx7hosg527qojqu/move-drush-wodby-aliases.workflow.zip?dl=0)

1. watches for the incoming file `wodby.aliases.drushrc.php` in the `~/Downloads` folder
2. moves it to `~/.drush/wodby.aliases.drushrc.php`
3. performs a `drush cc drush`

Any outdated alias file will be replaced with the new downloaded one.
