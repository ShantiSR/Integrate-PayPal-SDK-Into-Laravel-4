# Integrate PayPal SDK Into Laravel 4

Integrate PayPal SDK Into Laravel 4

## Install PayPal SDK via composer

Edit file composer.json

{
    ...
  "require": {
        ...
      "paypal/rest-api-sdk-php": "*"
  },
    ...
}

Update the dependencies

*$ php composer.phar update --no-dev*

## Configure PayPal credential

app/config/paypal.php

'client_id' => '',
'secret' => '',



