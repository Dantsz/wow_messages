# SMSG_SET_PROJECTILE_POSITION

## Client Version 3.3.5

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/spell/smsg_set_projectile_position.wowm:1`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/spell/smsg_set_projectile_position.wowm#L1).
```rust,ignore
smsg SMSG_SET_PROJECTILE_POSITION = 0x04BF {
    Guid caster;
    u8 amount_of_casts;
    Vector3d position;
}
```
### Header

SMSG have a header of 4 bytes.

#### SMSG Header

| Offset | Size / Endianness | Type   | Name   | Description |
| ------ | ----------------- | ------ | ------ | ----------- |
| 0x00   | 2 / Big           | uint16 | size   | Size of the rest of the message including the opcode field but not including the size field.|
| 0x02   | 2 / Little        | uint16 | opcode | Opcode that determines which fields the message contains.|

### Body

| Offset | Size / Endianness | Type | Name | Description | Comment |
| ------ | ----------------- | ---- | ---- | ----------- | ------- |
| 0x04 | 8 / Little | [Guid](../spec/packed-guid.md) | caster |  |  |
| 0x0C | 1 / - | u8 | amount_of_casts |  |  |
| 0x0D | 12 / - | [Vector3d](vector3d.md) | position |  |  |

