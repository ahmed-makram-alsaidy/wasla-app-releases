# Wasla Mobile App Distribution Center

Official Wasla mobile application releases, update manifests, and download artifacts.

## Overview

This repository hosts release metadata, distribution manifests, and official release assets for the Wasla Express mobile application suite. Application source code and sensitive signing materials are not stored in this repository.

## Applications

| Application | Name (AR) | Package Name | Android Status | iOS Status | Current Version | Build |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Admin** | وصلة إدارة | `com.waslaexpress.wasla_express.admin` | Direct APK | Coming Soon | 1.1.0 | 24 |
| **Merchant** | وصلة تاجر | `com.waslaexpress.wasla_express.merchant` | Direct APK | Coming Soon | 1.1.0 | 24 |
| **Customer** | وصلة عميل | `com.waslaexpress.wasla_express.customer` | Direct APK | Coming Soon | 1.1.0 | 24 |
| **Courier** | وصلة مندوب | `com.waslaexpress.wasla_express.courier` | Direct APK | Coming Soon | 1.1.0 | 24 |
| **Employee** | وصلة موظف | `com.waslaexpress.wasla_express.employee` | Direct APK | Coming Soon | 1.1.0 | 24 |

## Release Assets & Downloads

The latest release binaries are published as GitHub Release assets:
- **Release Tag:** `android-v1.1.0-build24`
- **Release Title:** Wasla Android Apps v1.1.0 Build 24
- **Manifest:** [`manifest.json`](manifest.json)
- **Checksums:** `checksums.sha256`

### Direct Download Links

- [wasla-admin-1.1.0-build24.apk](https://github.com/ahmed-makram-alsaidy/wasla-app-releases/releases/download/android-v1.1.0-build24/wasla-admin-1.1.0-build24.apk)
- [wasla-merchant-1.1.0-build24.apk](https://github.com/ahmed-makram-alsaidy/wasla-app-releases/releases/download/android-v1.1.0-build24/wasla-merchant-1.1.0-build24.apk)
- [wasla-customer-1.1.0-build24.apk](https://github.com/ahmed-makram-alsaidy/wasla-app-releases/releases/download/android-v1.1.0-build24/wasla-customer-1.1.0-build24.apk)
- [wasla-courier-1.1.0-build24.apk](https://github.com/ahmed-makram-alsaidy/wasla-app-releases/releases/download/android-v1.1.0-build24/wasla-courier-1.1.0-build24.apk)
- [wasla-employee-1.1.0-build24.apk](https://github.com/ahmed-makram-alsaidy/wasla-app-releases/releases/download/android-v1.1.0-build24/wasla-employee-1.1.0-build24.apk)

## Verification

All APKs are signed with the canonical Wasla release certificate:
- **Certificate DN:** `CN=Wasla Express, OU=Operations, O=Wasla Express, L=Cairo, ST=Cairo, C=EG`
- **Certificate SHA256:** `05:A3:80:4A:77:8B:42:25:38:43:B6:64:80:47:2B:AA:FB:9D:F1:E0:C4:EB:BE:FD:5E:7A:96:67:CF:B3:E0:41`

To verify an APK locally:
```bash
apksigner verify --verbose --print-certs wasla-admin-1.1.0-build24.apk
```
