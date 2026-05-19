# Android Private Keys (A13-aosp)

This branch contains the unique private signing keys for your AOSP-based Android 13 builds.

## Maintainer Info
- **Maintainer:** Failedmush
- **Country:** JP

## Setup in Device Tree
Add the following to your `lineage_renoir.mk` (or equivalent):

```makefile
PRODUCT_DEFAULT_DEV_CERTIFICATE := vendor/extra/keys/releasekey
-include vendor/extra/keys/keys.mk
```

## Key Files
- `releasekey`, `platform`, `shared`, `media`, `networkstack`, `sdk_sandbox`, `bluetooth`, `nfc`, `verifiedboot`, `gmscompat_lib`

## Usage
Clone this branch directly into your build tree:
```bash
git clone https://github.com/Failedmush1/vendor_voltage-priv_keys -b A13-aosp vendor/extra/keys
```
