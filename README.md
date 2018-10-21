# Wordpress Starter
##### Juke Labs

Authors: [Ryan Powszok](mailto:ryan@jukelabs.com)

Last Updated: 10/10/2018 Created: 10/10/2018

---

## Project Structure

```
project/                  # → Root folder for the project.
├── .editorconfig         # → Editor config used for defining indent style/spaces.
├── .env                  # → Dot env file. Configuration for app. This file should never be checked in. It contains secrets.
├── .env.example          # → Dot env file. Configuration for app.
├── .gitattributes        # → Git attributes.
├── .gitignore            # → Git config file to ignore files and directories.
├── composer.json         # → Composer settings.
├── composer.lock         # → Composer lock file generated from Composer.
├── config/               # → Wordpress configuration files.
    ├── certs/            # → Local development SSL certs.
├── phpcs.xml             # → PHP Codesniffer rules.
├── web/                  # → Docroot folder where index.php is located. Must be web for Pantheon hosting.
    ├── content/          # → Wordpress wp-content folder.
        ├── mu-plugins/   # → Wordpress "must-use" plugins.
        ├── plugins/      # → Wordpress plugins.
        ├── themes/       # → Wordpress themes.
        ├── uploads/      # → Wordpress uploads.
    ├── wp/               # → Wordpress core files installed by Composer.
    ├── wp-config.php     # → Wordpress config file.
├── README.md             # → Markdown readme file.
├── vendor/               # → Vendor files creates from `composer install`.
├── wp-cli.yml            # → Configuration file for WP CLI.
```

---
## Additional Information

### Known Issues

- Issue Tracking

### Changelog

---

Project repo [Wordpress Site](#).
