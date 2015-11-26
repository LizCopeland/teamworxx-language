# TeamWorXX Internationalisation
This repository is intended to facilitate the internationalisation effort of the TeamWorXX Liferay plugins. There are currently 15 TeamWorXX plugins, each contained within a separate folder in this repo.

## Adding a new language
To add a new language, you must create a new language properties file in each plugin. First, create a copy of the existing (English) Language.properties file from /<plugin name>/docroot/WEB-INF/src/content, and call it Language_<locale>, where <locale> is the standard locale code of the target language (e.g. fr or es). The copy should be in the same folder as the original file. Then, simply modify the **right-hand side** of each key-value pair using the desired language.
