# 81Languages - i18n locale file for HTML5 Dojo app

## How to contribute

* Look at [ja.json](https://github.com/Hidetchi/81Languages/blob/master/ja.json) (Japanese) or [en.json](https://github.com/Hidetchi/81Languages/blob/master/en.json) (English) as a reference and make corresponding JSON files for your language.
* The translation file for the old Flash version is available in Branch "[flash_old](https://github.com/Hidetchi/81Languages/tree/flash_old)". You could also look at this as a reference.
  * The parameters for HTML5 version are pretty much different from those for old Flash version. However some of the parameters are still the same; looking at the old version might help.
* You can of course send a pull request to this repository, but if you are not familiar with Github, just send a new file to info@81dojo.com via e-mail.

## Notes

* Some words are used in a table column with limited width. Look at Japanese/English example to guess which part each word is being used.
* Some sentences will be connected to user name. Look at Japanese/English example to guess how it is being used.
  * *Example*: Parameter "code.C014" being set as " declined invitation." will be used like "Hidetchi declined invitation." Therefore you need to **add a space in front**.
* For city names in "clock" section, you could change the city to represent the home country of the language.
  * *Example*: If you are making French file, you might want to change parameter "clock.cet" (the parameter for Central Europe Time) from "Frankfurt" to "Paris".
* Parameter "option.level" probably needs a space at the end, being used like "Level 0", "Level 1", etc.
