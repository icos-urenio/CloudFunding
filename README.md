# CloudFunding
===================

This is a fork of [Goteo/Goteo](https://github.com/Goteo/Goteo) crowdfunding platform. Original README in README_ORIGINAL.md

CloudFunding has been developed within the European project STORM CLOUDS. Find out more at [http://stormclouds.eu/](http://stormclouds.eu/).

## License
CloudFunding's source code is licensed under the [GNU Affero General Public License](https://www.gnu.org/licenses/agpl.html).

## Installation
* Create a database in your mysql server.
* Import db/goteo_modified.sql to the database.
* Copy the application directory to your web server.
* Edit local-settings.php and add your mysql connection and other details.
* Change the root password (/Goteo/dashboard/profile/access)
* Make sure that mod_rewrite is enabled.
* If you install the application in a directory different than "Goteo" change the directory name in the following line of the .htaccess file:

    RewriteBase /Goteo/

## Default passwords

root - login: root, password: root

## Changelog

### Version 1.0a
* Initial public release
