# Headless API

## Intro

This is a Drupal 8 module that will enable all modules and set up configuration
that is required to create a simple decoupled website. To find out more please 
visit this blog post:

Coming Soon

## Demo

To see fully functional demo visit the following website:

Coming Soon

## Installation

You can download Headless API module on the Github release page:

https://github.com/TheDoer/headless_drupal_api.git

1. Composer (recommended):

Since this module is not published on drupal.org or on packagist.org you will
need to add the VCS repository to your composer.json file. You need to add this:

```
"repositories": [  
    {
        "type": "vcs",
        "url":  "https://github.com/TheDoer/headless_drupal_api"  
    }  
]
```

Then you can run the following command to install it:

```
composer require thedoer/headless_drupal_api
```

2. Drush:

Since this module is not published on drupal.org you will need to download it 
from the Github and place it in your /modules directory. After that execute the 
following command:

```
drush en druact_api -y
```

3. Manual installation

To install the Druact API module, proceed in the usual way: download and unzip 
it, then place it in the /modules directory for your site. Navigate to the 
Extend page (admin/modules) and Headless Headless API.

You also need to download the following required modules:

Token https://www.drupal.org/project/token  
REST UI https://www.drupal.org/project/restui  
Contact message REST https://www.drupal.org/project/contact_message_rest  
Contact Storage https://www.drupal.org/project/contact_storage  

### AUTHOR

Adonis Rumbwere  
Website: (http://www.adonisrumbwere.com)   
Email: adonis.rumbwere@gmail.com  

Company: Studio Present, Subotica, Serbia  
Website: (http://www.3degrees.co.zw)  
Drupal: (https://www.drupal.org/3degrees)      
Email: info@3degrees.co.zw
