# Master Craft GetApps Remote Config

Dedicated public remote configuration for:

- Package: `build.hwgame.v20.pro.craft.minecraft.mi`
- Store: Xiaomi GetApps
- Raw URL: `https://raw.githubusercontent.com/metosapps/master-craft-getapps-config/main/config.json`

## Current release state

Ads are intentionally disabled while the app is not live:

```json
"ads_enabled": false
```

The production AdMob App ID is recorded in the APK and configuration inventory. The official Google test ad-unit IDs remain in the configuration for pre-release testing. Yandex and StartApp IDs are empty.

Do not enable ads until the GetApps listing is confirmed live. Before enabling production ads, replace all Google test IDs with AdMob IDs created specifically for package `build.hwgame.v20.pro.craft.minecraft.mi`, then set `ads_enabled` to `true`.
