# compact-timezone-list
This package contains an array of timezones based on conventional options found online. It does not follow any complete data set, but all names are according to the tz format: [https://en.wikipedia.org/wiki/List_of_tz_database_time_zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)

More specifically, the fields in the array are:
- `offset`, a string from `"-11:00"` to `"+14:00"` representing the UTC offset
- `label`, a readable label that contains the offset and a longer, descriptive name of the timezone
- `tzCode`, the value from the `tz` standard

## Install

```bash
npm install compact-timezone-list --save
# or
yarn add compact-timezone-list
```

## Example:
```javascript
 import timezones from 'compact-timezone-list';
 // or
 import { defaultTimezoneSet, minimalTimezoneSet } from 'compact-timezone-list';
```

## Compatible
It is compatible with the select2 package: https://select2.org/

Last tested at 2023.07.25 .

## Details

- The default export provides a long list of options, with multiple suggestions for each UTC offset.
- The `minimalTimezoneSet` export provides one option per offset type, with a favourite chosen to represent each offset. This is mostly targeted to small, western-focused apps. But, every UTC offset is included.

Contribution:
======
If you think that you are able to contribute in the development then don't hesitate join to us. All donations will be split between contributors. Firt 5 contributors will get the money plus mentioning in the credits section and others will be mentioned in the credits.

Donation possibilities:
======

| Type            |                                                                                                                  Link                                                                                                                   |
|-----------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Buy me a coffee | [!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/kynarnetwork)                                                 |
| Coinbase        | [!["Donate with crypto"](https://nfg-sofun.s3.amazonaws.com/uploads/redactor_rails/picture/data/73379/Donate_Crypto_Button.png)](https://commerce.coinbase.com/checkout/d07a3a58-435a-4827-adeb-8f0214d460d3)              |
| Ko-fi           | [!["Ko-fi"](https://storage.ko-fi.com/cdn/kofi2.png)](https://ko-fi.com/kynarnetwork) |
