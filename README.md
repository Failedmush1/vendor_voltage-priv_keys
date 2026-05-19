# LineageOS Private Keys (A13-A15-Los)

This branch contains the unique private signing keys formatted specifically for LineageOS-based ROMs from Android 13 through Android 15.

## Maintainer Info
- **Maintainer:** Failedmush
- **Country:** JP

## Setup in Device Tree
Add the following to your `lineage_renoir.mk` (or equivalent):

```makefile
PRODUCT_DEFAULT_DEV_CERTIFICATE := vendor/lineage-priv/keys/releasekey
-include vendor/lineage-priv/keys/keys.mk
```

## Key Files
- Standard LineageOS/AOSP key set, including `gmscompat_lib`.

## Usage
Clone this branch into the standard LineageOS private key location:
```bash
git clone https://github.com/Failedmush1/vendor_voltage-priv_keys -b A13-A15-Los vendor/lineage-priv/keys
```
