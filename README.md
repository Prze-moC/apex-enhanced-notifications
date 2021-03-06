# Pretius APEX Notifications
##### Oracle APEX dynamic action plugin v1.0

The plugin is dynamic action plugin providing notifications for Oracle APEX 5 and Universal Theme. Due to highly configurable attributes, the plugin can be used as presentation layer for AJAX callbacks. Translated messages from the database can be easly presented in two types of notification.

## Preview
![Alt text](/preview.gif?raw=true "Preview")

## Table of Contents
- [Pretius APEX Notifications](#pretius-apex-notifications)
  - [Oracle APEX dynamic action plugin v1.0](#oracle-apex-dynamic-action-plugin-v10)
- [Preview](#preview)
- [Table of Contents](#table-of-contents)
- [License](#license)
- [Demo Application](#demo-application)
- [Features at Glance](#features-at-glance)
- [Roadmap](#roadmap)
- [Install](#install)
  - [Installation package](#installation-package)
  - [Install procedure](#install-procedure)
- [Usage guide](#usage-guide)
- [Changelog](#changelog)
  - [1.0](#10)
- [About Author](#about-author)
- [About Pretius](#about-pretius)
- [Support](#support)
  - [Free support](#free-support)
  - [Paid support](#paid-support)


## License
MIT

## Demo Application
[http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS](http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS)

## Features at Glance
* APEX like appearance
* Message can be static text or result of the JavaScript function
* Floating and inline notifications
* Support for "Modal page close event" and "Custom event"
* Highly configurable:
  * floating and inline common attributes
    * three types: Success, Warning, Error
    * duration of presentation
    * remove animation: fade out, slide up, remove
    * show new notification on top or bottom of the queue
    * message can be single-line or single-line with additional list of messages
  * floating attributes
    * four positions: top right, top left, bottom left, bottom right
  * inline attributes
    * fixed position
    * scroll browser to notification
    * mergeable with existing notificaitions
    * remove existing notifications
    * show bullets for list elements    

## Roadmap
Not yet defined

## Install 

### Installation package
1. `src/dynamic_action_plugin_pretius_com_notifications.sql` - the plugin installation file for Oracle APEX 5.1 or higher

### Install procedure
To successfully install/update the plugin follow those steps:
1. Install the plugin file `dynamic_action_plugin_pretius_apex_nested_reports.sql` using Oracle APEX plugin import wizard
1. Configure application level componenets of the plugin
1. When asked whether "Use Universal Theme templates" select "No" and proceed with wizard.*

`* Selecting Yes means that the plugin will fetch SUCCESS_MESSAGE and NOTIFICATION_MESSAGE UT templates from APEX tables.`

`* Selecting No means that the plugin will use plugin SUCCESS_MESSAGE and NOTIFICATION_MESSAGE templates.`

## Usage guide

Please check [live demo](http://apex.pretius.com/apex/f?p=105:NOTIFICATIONS) for implementation description.

## Changelog

### 1.0
Initial release

## About Author
Author            | Website                                 | Github                                       | Twitter                                       | E-mail
------------------|-----------------------------------------|----------------------------------------------|-----------------------------------------------|----------------------------------------------------
Bartosz Ostrowski | [http://ostrowskibartosz.pl](https://www.ostrowskibartosz.pl) | [@bostrowski](https://github.com/bostrowski) | [@bostrowsk1](https://twitter.com/bostrowsk1) | bostrowski@pretius.com, ostrowski.bartosz@gmail.com

## About Pretius
Pretius Sp. z o.o. Sp. K.

Address | Website | E-mail
--------|---------|-------
Przy Parku 2/2 Warsaw 02-384, Poland | [http://www.pretius.com](http://www.pretius.com) | [office@pretius.com](mailto:office@pretius.com)

## Support
Our plugins are free to use but in some cases you might need to contact us. We are willing to assist you but in certain circumstances you will be charged for our time spent on helping you. Please keep in mind we do our best to keep documentation up to date and we won't answer question for which there is explaination in documentation (at github and as help text in application builder).

All request (bug fix / change request) should be posted in Issues Tab at github repository.

### Free support
We do support the plugin in certain cases such as bug fixing and change request. If you have faced issue that might be bug please check Issues tab in github repository. In case you won't be able to find related issue please raise the issue following these rules:

* issue should contain login credentials to application at apex.oracle.com where issue is reproduced
* issue should contain steps to reproduce the issue in demo application
* issue should contain description about it's nature

### Paid support
In case you are not able to implement the plugin or you are willing to have custom implementation based on the plugin attributes (ie. custom JavaScript callbacks) we are willing to help you. Please send inquiry to apex[at]pretius.com with description what you want us to help you with. We will contact you as soon as possible with pricing and possible dates.
