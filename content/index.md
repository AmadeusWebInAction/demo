## DEMO WEBSITE OF [AmadeusWeb Core v7](%core-url%)

%fileName%

%contact-snippet%

You may do the following

* Email us your consent/agreement to [use the platform](%amadeus-url%start/).
* Setup the website's development environment by [following these steps](%amadeus-url%getting-started/setting-up/).
* Configure the website by editing `./data/site.tsv` per [the docs](%amadeus-url%getting-started/configurations/).
* Understand the [concepts](%amadeus-url%concepts/) and take a [deep dive](%amadeus-url%dive-into/).

---

## Framework (core)

If it breaks with an error that the framework is not found, you would need to clone it (per the environment setup instructions above) and double check the relative path. `demo` is assumed to be in `WWWROOT/sites/` and the core and other repositories in `WWWROOT/awe/`.

Error could appear as:
```
include_once(../core/framework/1-entry.php): Failed to open stream
```

---

## Url Configuration

* `site.tsv` has `local-url` and `live-url` which need to be configured.

---

## Theme asset extraction and static repo setup.

* Also, make sure the theme files are cloned and extracted.
* And an icon for the website. header image will not work until 'site-static' asset folder is definable.
* And change the safeName on which the icon/logo urls are based.

---

## Sample Section

* This demo comes preconfigured with a section `about us` per row in the site.tsv.
* It requires a subfolder per `site`.

---

## Before Check-in

* Replace contents of this file.
* Make sure the site is loading.
* Sign the license - assuming you are using your own git account. 
* Discuss hosting / platform fees.

Happy designing!!
