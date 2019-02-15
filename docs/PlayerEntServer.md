# Player entities

## Player Ent Values

### Signature

````
E0 22 AA 00 ?? 00 ?? 00 00 00 00 ?? 39 05 39 05 - base for 1 entitiy
Note that the 5th byte seems to be an index.
````

### Entitiy Offsets

````
base + 0x68 = 1 BYTE - Player Health
base + 0x204 -> 0xAC = STRING(MAX 19 BYTES) - Name
````
