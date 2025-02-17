# CMSG_SETSHEATHED

## Client Version 1, Client Version 2, Client Version 3

### Description

Says which weapon the client pulls out.

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/client_set/cmsg_setsheathed.wowm:11`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/client_set/cmsg_setsheathed.wowm#L11).
```rust,ignore
cmsg CMSG_SETSHEATHED = 0x01E0 {
    (u32)SheathState sheathed;
}
```
### Header

CMSG have a header of 6 bytes.

#### CMSG Header

| Offset | Size / Endianness | Type   | Name   | Description |
| ------ | ----------------- | ------ | ------ | ----------- |
| 0x00   | 2 / Big           | uint16 | size   | Size of the rest of the message including the opcode field but not including the size field.|
| 0x02   | 4 / Little        | uint32 | opcode | Opcode that determines which fields the message contains.|

### Body

| Offset | Size / Endianness | Type | Name | Description | Comment |
| ------ | ----------------- | ---- | ---- | ----------- | ------- |
| 0x06 | 4 / - | [SheathState](sheathstate.md) | sheathed |  |  |

### Examples

#### Example 1

##### Description

Client takes out melee weapon.

```c
0, 8, // size
224, 1, 0, 0, // opcode (480)
1, 0, 0, 0, // sheathed: SheathState MELEE (1)
```
