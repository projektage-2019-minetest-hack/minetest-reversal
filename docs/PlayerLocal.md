# Modifiable Local Values

## Player Signature

````
18 FC A9 00 00 00 00 00
````

Die oben gezeigte Signatur returned die lokale PlayerBase

## Offsets

````
PlayerBase + 0xc8 = Name(String)

PlayerBase + 0x1AC = West-Ost(Float)
PlayerBase + 0x1B0 = Höhe(Float)
PlayerBase + 0x1B4 = Nord-Süd(Float)

PlayerBase + 0x208 = Yaw(Float) //ReadOnly
````
