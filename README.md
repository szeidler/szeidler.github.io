# szeidler.github.io

## Little helpers

### Wodby Alias Automator

[This Mac OSX Automator workflow](https://www.dropbox.com/s/fx7hosg527qojqu/move-drush-wodby-aliases.workflow.zip?dl=0)

1. watches for the incoming file `wodby.aliases.drushrc.php` in the `~/Downloads` folder
2. moves it to `~/.drush/wodby.aliases.drushrc.php`
3. performs a `drush cc drush`

Any outdated alias file will be replaced with the new downloaded one.
