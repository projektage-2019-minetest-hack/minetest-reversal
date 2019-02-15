# Modifiable Local Values

## Player Position Signature

````
18 FC A9 00 00 00 00 00
````

Die oben gezeigte Signatur returned die lokale PlayerPositionBase

## Offsets

````
Base + 0xc8 = Name(String)

Base + 0x1AC = West-Ost(Float)
Base + 0x1B0 = Höhe(Float)
Base + 0x1B4 = Nord-Süd(Float)
````
## Player Cam Offset

````
0x00D9EC58
````
Die oben gezeigte Adresse ist die lokale PlayerCameraBase

### Offsets

````
Base + 0x10c = Yaw(Float)
````
