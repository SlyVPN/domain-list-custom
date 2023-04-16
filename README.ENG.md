# Introduction

Based on the proposal of [v2fly/domain-list-community#256](https://github.com/v2fly/domain-list-community/issues/256), refactor [v2fly/domain-list-community](https: //github.com/v2fly/domain-list-community) and add new features.

## Differences from the official `dlc.dat`

- Rename `dlc.dat` to `geosite.dat`
- Remove rules with `@ads`, `@!cn` attributes in `cn` list
- Remove rules with `@ads`, `@!cn` attributes in `geolocation-cn` list
- Remove the rules with `@ads`, `@cn` attributes in the `geolocation-!cn` list, and try to avoid proxying the domain names of overseas companies that have access points in mainland China. For example, avoid proxying Steam game download services in China.

## download link

[https://github.com/Loyalsoldier/domain-list-custom/releases/latest/download/geosite.dat](https://github.com/Loyalsoldier/domain-list-custom/releases/latest/download/ geosite.dat)

## Projects using this project

[@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)
