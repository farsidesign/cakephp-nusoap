# cakephp-nusoap


Installation
------------
"require": {
    ...
    "farsidesign/cakephp-nusoap" : "dev-master",
    ...
},

Usage
-----
use Farsidesign\Nusoap;
$client = new \SoapClient('wsdlAddress', ['encoding' => 'UTF-8']);
