Steps

git Clone https://github.com/purshottam-kr/OGD.git
import database (backup\ogd_manual_db.zip)
composer update
vendor/bin/drush cim (Check drush is installed or not "drush --version", if not install drush first)
Change "config_sync_directory" path in settings.php -> $settings['config_sync_directory'] = '../config/sync';
