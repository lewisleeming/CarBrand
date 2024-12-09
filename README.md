# zoocha_installer

## Getting Started
To begin working with the Zoocha Installer profile, please proceed with the steps outlined below:
1. `ddev start`
2. `ddev composer install`
3. `ddev drush si --site-mail=YOUR_EMAIL@zoocha.com --account-name=zoochaadmin --account-mail=YOUR_EMAIL@zoocha.com --site-name=SITE_NAME --existing-config`

## Getting Started - legacy (Or those on Mac where a post start command for setting config/sync fails) - See ZIN-22
To begin working with the Zoocha Installer profile, please proceed with the steps outlined below:
1. `ddev start`
2. `ddev composer install`
3. Manually set `$settings['config_sync_directory'] = '../config/sync';` in the local ddev settings file `sites/default/files/settings.ddev.php`
4. `ddev drush si --site-mail=YOUR_EMAIL@zoocha.com --account-name=zoochaadmin --account-mail=YOUR_EMAIL@zoocha.com --site-name=SITE_NAME --existing-config`

# Modules

|           **Module**            | **Status** | **Configured** |          **ZPCH Ticket Reference**           |
|:-------------------------------:|:----------:|:--------------:|:--------------------------------------------:|
|          Admin Toolbar          |  Enabled   |    Default     |                                              |
|      Admin Toolbar Search       |  Enabled   |    Default     |                                              |
|     Better Exposed Filters      | Installed  |                |                                              |
|             Captcha             | Installed  |                |                                              |
|             ClamAV              |  Enabled   |    Inactive    | https://zoocha.atlassian.net/browse/ZPCH-27  |
|          Config Ignore          | Installed  |                |                                              |
|          Config Split           | Installed  |                |                                              |
|          Content Lock           |  Enabled   |    Default     | https://zoocha.atlassian.net/browse/ZPCH-261 |
|              Crop               | Installed  |                |                                              |
|      EU Cookie Compliance       | Installed  |                |                                              |
|             Facets              | Installed  |                |                                              |
|           Field Group           |  Enabled   |    Default     |                                              |
|          Flood Control          |  Enabled   |    Default     |                                              |
|               Gin               |  Enabled   |    Default     |                                              |
|           Gin Toolbar           |  Enabled   |    Default     |                                              |
|           Google Tag            | Installed  |                |                                              |
|            Honeypot             | Installed  |    Inactive    | https://zoocha.atlassian.net/browse/ZPCH-48  |
|           Link Class            | Installed  |                |                                              |
|             Linkit              | Installed  |                |                                              |
|            Memcache             | Installed  |                |                                              |
|           Menu Block            | Installed  |                |                                              |
|             Metatag             |  Enabled   |    Default     |                                              |
|       Metatag: Open Graph       |  Enabled   |    Default     | https://zoocha.atlassian.net/browse/ZPCH-173 |
|     Metatag: Twitter Cards      |  Enabled   |    Default     |                                              |
|           Paragraphs            |  Enabled   |    Default     |                                              |
|         Password Policy         |  Enabled   |   Pre-Launch   | https://zoocha.atlassian.net/browse/ZPCH-29  |
|            Pathauto             | Installed  |                |                                              |
|              Purge              | Installed  |                | https://zoocha.atlassian.net/browse/ZPCH-51  |
|            ReCaptcha            | Installed  |                |                                              |
|          ReCaptcha V3           | Installed  |                |                                              |
|            Redirect             | Installed  |                |                                              |
|          Reroute Email          | Installed  |                |                                              |
|        Search API (Solr)        | Installed  |                |                                              |
|     Search API Autocomplete     | Installed  |                |                                              |
|             Seckit              |  Enabled   |   Pre-Launch   | https://zoocha.atlassian.net/browse/ZPCH-21  |
|              SMTP               | Installed  |                |                                              |
|            SVG Image            | Installed  |                |                                              |
| Username Enumeration Prevention |  Enabled   |    Default     | https://zoocha.atlassian.net/browse/ZPCH-30  |
|             Webform             |  Enabled   |    Default     |                                              |
|           XMLSitemap            |  Enabled   |    Default     | https://zoocha.atlassian.net/browse/ZPCH-45  |
