## Etherpad Lite

This version of Etherpad is installed without plugins and uses Redis as database.
Be aware, Redis database backup and restore is not fully implemented.

If you want to install Etherpad with plugins and mysql database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh",

## Configuration

You can access Etherpad's admin panel at `domain.tld/admin`. The configuration file for Etherpad is at the path `/var/www/etherpad/settings.json`.

*Skin Builder* (accessible at this address `domain.tld/pad/p/test#skinvariantsbuilder`) allows you to customize the skin of your pad. It will give you a parameter to copy into your configuration file `/var/www/etherpad/settings.json`.
