PhalconFans/Helpers

This package will add the helper functions to your Phalcon application.
Install

Run:

composer require phalconfans/helpers

or modify Composer.json

"phalconfans/helpers": "~0.0.6"

than composer update

Edit your bootrap_cli.php or bootstrap_web.php, like this 

use Dotenv\Dotenv;

use PhalconFans\Helpers;

$di['env'] = function () {

    return new Dotenv(BASE_PATH);

};

$di['env']->load();

so , you can global use env() to manage your env for your config. 

Copyright

This project is open source software licensed under the GPLv3 License. See the LICENSE file for more.

© 2017-3017, PhalconFans Team
