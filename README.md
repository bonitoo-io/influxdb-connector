# InfluxDB Connector for Data Studio

[![CircleCI](https://circleci.com/gh/bonitoo-io/influxdb-connector.svg?style=svg)](https://circleci.com/gh/bonitoo-io/influxdb-connector)
[![codecov](https://codecov.io/gh/bonitoo-io/influxdb-connector/branch/master/graph/badge.svg)](https://codecov.io/gh/bonitoo-io/influxdb-connector)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![License](https://img.shields.io/github/license/bonitoo-io/influxdb-connector.svg)](https://github.com/bonitoo-io/influxdb-connector/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues-raw/bonitoo-io/influxdb-connector.svg)](https://github.com/bonitoo-io/influxdb-connector/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/bonitoo-io/influxdb-connector.svg)](https://github.com/bonitoo-io/influxdb-connector/pulls)
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://www.influxdata.com/slack)

*This is not an official Google product*

This [Data Studio] [Connector] lets users query datasets from [InfluxDB v2] instances through the [InfluxDB API].

---

#### Developers

Try it: https://datastudio.google.com/u/0/datasources/create?connectorId=AKfycbwhJChhmMypQvNlihgRJMAhCb8gaM3ii9oUNWlW_Cp2PbJSfqeHfPyjNVp15iy9ltCs

- https://developers.google.com/datastudio/connector
- https://developers.google.com/datastudio/connector/reference
- https://developers.google.com/datastudio/connector/local-development
- https://github.com/googledatastudio/community-connectors/blob/master/kaggle/README.md 
- https://github.com/OlegOdnoral/RA_GoogleDataStudio_Adapter/blob/master/src/main.js
- https://github.com/the-unbelievable-machine/mite-js-google-datastudio-connector

##### TODO:
1. implement validateKey
1. v1 support
1. custom FLUX

[Data Studio]: https://datastudio.google.com
[Connector]: https://developers.google.com/datastudio/connector
[InfluxDB v2]: https://www.influxdata.com/products/influxdb-overview/influxdb-2-0/
[InfluxDB API]: https://v2.docs.influxdata.com/v2.0/reference/api/
