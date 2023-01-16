# CURATED-ZEOs

## Columns of `zeo-frameworks.csv`
- `Identifier`: XXXYYY, with XXX the IZA type code, YYY the identifier (000 for all-silica, 001 for first modification, etc.)
- `Name`: conventional name, as used in the NIST ISO-DB (be careful with synonyms, reported in zeo-synonyms.yaml
- `Chemical Formula`: chemical formula
- `Si/Al Ratio`: ratio between silicon and Al atoms, `Inf` for all-silica
- `Note`: source of the cif file

## Content of `zeo-synonyms.yaml`
```
main_name: 
 - synonym1
 - synonym2
 - ...
```

> Note: the main name should preferably be the one also used as main name in the NIST-ISODB.
