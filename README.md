# Send text based template messages via 360 degrees

## Introduction

The purpose of this class is not to interact with the entire 360degree api. Instead it is designed as a start-pack that
will quickly allow you to send template based message (with placeholders) to your users.

Please note that you cannot **initiate** a freetext message with WhatsappAPI. Instead, you must use a pre-approved
template.

## Getting a 360degree api key

You can get one from here:

https://hub.360dialog.com/lp/whatsapp/I9RpMZPA

This will then have to be added to the .env file, there is a .env.example file

## Creating a template

The class at the moment only support text based messages. It does not support images, buttons.

Thus, you can create a temple in 360degree. ONce the tem,plate has been approved you can start to use the starter pack

## Example command line usage

```
php example-send.php
```

```php
sendWhatsApp(
        "34666777888", //phone number to send to
        ["2"], //placeholder
        'sample_shipping_confirmation', //template name
        'en_US', //template language
        'f6baa15e_fb52_4d4f_a5a0_cde307dc3a85' //template namespace
    );

)
```
This should send a message 








