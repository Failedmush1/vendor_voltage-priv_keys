# LineageOS Private Keys (A16)

This branch contains the unique private signing keys formatted for LineageOS-based ROMs starting from Android 16.

## Maintainer Info
- **Maintainer:** Failedmush
- **Country:** JP

## Setup in Device Tree
Add the following to your device makefile:

```makefile
PRODUCT_DEFAULT_DEV_CERTIFICATE := vendor/lineage-priv/keys/releasekey
-include vendor/lineage-priv/keys/keys.mk
```

## Usage
Clone this branch into the standard LineageOS private key location:
```bash
git clone https://github.com/Failedmush1/vendor_voltage-priv_keys -b lineageos vendor/lineage-priv/keys
```
