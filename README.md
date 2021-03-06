# app-custom-shipping

[![license mit](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

E-Com Plus app for custom shipping calculation

[Changelog](https://github.com/ecomclub/app-custom-shipping/blob/master/CHANGELOG.md)

## Environment variables sample

Variable              | Value
---                   | ---
`LOGGER_OUTPUT`       | `~/app/log/logger.out`
`LOGGER_ERRORS`       | `~/app/log/logger.err`
`LOGGER_FATAL_ERRORS` | `~/app/log/_stderr`
`PORT`                | `3000`
`APP_BASE_URI`        | `https://customshipping.ecomplus.biz`
`DB_PATH`             | `~/app/db.sqlite`
`ECOM_AUTH_DB`        | `~/app/db.sqlite`
`ECOM_AUTH_UPDATE`    | `enabled`


## Production server

Published at https://customshipping.ecomplus.biz

### Continuous deployment

When new version is **production ready**,
[create a new release](https://github.com/ecomclub/app-custom-shipping/releases)
(or `npm run release`) to run automatic deploy from _master_ branch
and (re)publish the app.
