[plugin]: https://www.spigotmc.org/resources/2237/

[config_4.3.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_4.3.0+.yml
[language_4.3.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_4.3.0+.yml

[config_4.0.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_4.0.0+.yml
[language_4.0.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_4.0.0+.yml

[config_3.5.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_3.5.0+.yml
[language_3.5.0+]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_3.5.0+.yml

[config_pre_3.5.0]: https://github.com/Andre601/ArmorStand-Tools/blob/master/config/config_DE_AST_Pre-3.5.0.yml
[language_pre_3.5.0]: https://github.com/Andre601/ArmorStand-Tools/blob/master/language/language_DE_AST_Pre-3.5.0.yml

# ArmorStandTools Übersetzungen
Diese Repository enthält die übersetzten Dateien für das Plugin [ArmorStandTools][plugin]. Sowohl die config.yml als auch die language.yml wurden übersetzt.

## Wie verwenden

### Richtige Version wählen
Abhängig von der AST Version musst du eine andere Datei verwenden:

| AST Version            | `config.yml`                                      | `language.yml`                                        |
| ---------------------- | ------------------------------------------------- | ----------------------------------------------------- |
| 4.3.0+                 | [`config_DE_AST_4.3.0+.yml`][config_4.3.0+]       | [`language_DE_AST_4.3.0+.yml`][language_4.3.0+]       |
| 4.0.0+                 | [`config_DE_AST_4.0.0+.yml`][config_4.0.0+]       | [`language_DE_AST_4.0.0+.yml`][language_4.0.0+]       |
| 3.5.0 bis 3.7.2        | [`config_DE_AST_3.5.0+.yml`][config_3.5.0+]       | [`language_DE_AST_3.5.0+.yml`][language_3.5.0+]       |
| Versionen bis zu 3.4.3 | [`config_DE_AST_Pre-3.5.0.yml`][config_pre_3.5.0] | [`language_DE_AST_Pre-3.5.0.yml`][language_pre_3.5.0] |

### Datei ersetzen
Um die bereits existierende config.yml und language.yml zu ersetzen solltest du zuerst ein Backup von diesen machen, falls etwas schief geht.  
Du kannst dann die Dateien downloaden indem du auf den grünen "Code" Knopf klickst und dann "Download ZIP" auswählst.

Die heruntergeladene ZIP Datei wird diese Readme Datei und die verschiedenen Sprach und Configdateien enthalten.  
Du solltest jetzt die Datei, welche du verwenden willst, auswählen. Nimm einen Blick auf die obige Tabelle um zu sehen, welche Datei für welche Version von AST verwendet werden sollte.

Um die Dateien zu extrahieren, öffne die ZIP Datei mit 7Zip oder WinRAR, gehe in den `language` und `config` Ordner und ziehe die Dateien, welche du willst raus. Du musst sie dann zu `config.yml` und `language.yml` umbenenen und dann in den ArmorStandTools Ordner hochladen, wodurch die alten Dateien ersetzt werden.  
Alles was noch bleibt ist `/ast reload` auszuführen, um die änderungen anzuwenden.
