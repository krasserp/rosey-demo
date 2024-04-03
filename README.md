# Hugo Rosey Bookshop Starter

A starter template for a new Hugo site built with [Bookshop](https://github.com/CloudCannon/bookshop) components.
This template uses [Rosey](https://rosey.app/) to generate a multilingual site from one language.
We run Rosey on your built site in the CloudCannon postbuild.
Rosey generates a base.json file wherever it detects a ```data-rosey=""``` tag in your built site.
From this base.json file we run a script that creates a locales file for each locale listed in your LOCALES environment variable.
Editors can see these locales files in the CloudCannon UI, and enter translations for each phrase.
Rosey then uses the locales files, to generate a multilingual site.

To run site locally:
```bash
npm i
npm start
```

To run Rosey locally:
```bash
npm i
hugo
npx rosey generate --source public
node utils/generateLocales.js
```
Enter a translated value in one of the locale files.
To generate a multilingual site locally:
```bash
npx rosey build --source public --dest public_translated
```