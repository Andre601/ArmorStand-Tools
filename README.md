[readme_de]: https://github.com/Andre601/ArmorStand-Tools/blob/master/README.md

[plugin]: https://www.spigotmc.org/resources/2237/

[config_new]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_3.5.0+.yml
[language_new]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_3.5.0+.yml

[config_old]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_Pre-3.5.0.yml
[language_old]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_Pre-3.5.0.yml

# ArmorStandTools translations
> Looking for the german version of this Readme?  
> [Click here!][readme_de]

This repository contains the translated files for the [ArmorStandTools][plugin] plugin. Both the config.yml and language.yml got translated.

## How to use

### Choosing the right version
Depending on the AST version used will you need to use a different file:

| AST Version    | `config.yml`                                | `language.yml`                                  |
| -------------- | ------------------------------------------- | ----------------------------------------------- |
| 3.5.0 or newer | [`config_DE_AST_3.5.0+.yml`][config_new]    | [`language_DE_AST_3.5.0+.yml`][language_new]    |
| 3.4.3 or older | [`config_DE_AST_Pre-3.5.0.yml`][config_old] | [`language_DE_AST_Pre-3.5.0.yml`][language_old] |

### Replacing the file
To replace the existing config.yml and language.yml should you first make backups of those in case something breaks.  
You can then download the files by clicking on the green "Code" button and select "Download ZIP".

The downloaded ZIP file will contain this readme file and the different language and Config files.  
You now need to select the file you want to use. Take a look at the table above to see, what file should be used for what versions of AST.

To extract the files, open the ZIP file using 7Zip or WinRAR, head over to the `language` and `config` folder and pull out the files you want. You'll then need to rename them to `config.yml` and `language.yml` and upload them into the ArmorStandTools folder, replacing the old ones in the process.  
All that is left to do is to run `/ast reload` to apply the changes.
