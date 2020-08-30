# OpenCart

## Overview

OpenCart is a free open source ecommerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store.

## Info

- Bug fixes added
- Support PHP 7.0 and above
- OpenBay was removed
- Integrated Currency module from Master Branch - 3.1.0.0b
- Integrated Timezone from Master Branch - 3.1.0.0b
- Added Show/Hide password. Code used from <a href="https://github.com/opencartbrasil/opencartbrasil">Opencart Brasil</a>
- Integrated Cron module from Master Branch - 3.1.0.0b

## Language patch for non English

For Currency module and Timezone

- Edit admin/language/your_language/setting.php and add this values:

$_['entry_timezone']               = 'Time Zone';\
$_['entry_currency_engine']        = 'Currency Rate Engine';

- Copy currency.php from admin/language/en-gb/extension/extension in the same location of your language.
- Copy currency folder from admin/language/en-gb/extension/ in the same location of your language.

For Cron module

- Edit admin/language/your_language/column_left.php and add this value:

$_['text_cron']                      = 'Cron Jobs';

- Copy cron.php from admin/language/en-gb/extension in the same location of your language.