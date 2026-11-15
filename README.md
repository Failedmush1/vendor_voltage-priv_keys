# AOSPA Private Keys (A14)

This branch contains the unique private signing keys formatted for Paranoid Android (AOSPA) Android 14 (Uvite).

## Maintainer Info
- **Maintainer:** Failedmush
- **Country:** JP

## Usage
Clone this branch into the standard AOSPA private key location:
```bash
git clone https://github.com/Failedmush1/vendor_voltage-priv_keys -b aospa vendor/aospa-priv/keys
```

## Setup in Tree
Include in `vendor/aospa/target/product/aospa-target.mk` or device tree:
```makefile
-include vendor/aospa-priv/keys/keys.mk
```
