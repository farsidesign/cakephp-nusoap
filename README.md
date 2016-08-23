# cakephp-nusoap


Installation
------------
"require": {<br/>
    ...<br/>
    "farsidesign/cakephp-nusoap" : "dev-master",<br/>
    ...<br/>
},<br/>

Usage
-----
use Farsidesign\Nusoap;<br/>
$client = new \SoapClient('wsdlAddress', ['encoding' => 'UTF-8']);
