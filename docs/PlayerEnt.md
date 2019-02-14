# Player entities

## When searching for the player, we have found the following:

1. There are many references to the Players values. We identified those by using the player health. They are listed below
  - Display / Menu Class: Easily identified by the health offset being ``0x44`` to their respective base.
  - Client Side Local Entity. Suprisingly this seems to be fully READ ONLY as far as we found out. Offsets are either ``0x110`` or      ``0x16c`` to their base. Those two differ, but we didnt find out what those do specifically. Some things do suggest that the ``0x110`` offset holds the networked values, as it directly updated with the the data received from the Server. Freezing or manipulating it was completely disregarded by the server though. You still received the damage.
  - Server Entity List. Offset from base to health is ``0x68``. These are only present when hosting a server. Due to the strict Server authority this game provides, manipulating these values is not as critical as client side hacking, but still provides some edge cases to be aware off.

## Player Ent Values

### Signature

````
E0 22 AA 00 ?? 00 ?? 00 00 00 00 ?? 39 05 39 05 - base for 1 entitiy
````

### Entitiy Offsets

````
0x68 - 1 BYTE - Player Health

````
