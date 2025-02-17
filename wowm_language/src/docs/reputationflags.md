# ReputationFlags

## Client Version 1.12

### Comment

Used in `Faction.dbc`.

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/external/reputation_flags.wowm:1`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/external/reputation_flags.wowm#L1).

```rust,ignore
flag ReputationFlags : u8 {
    VISIBLE_TO_CLIENT = 0x01;
    ENABLE_AT_WAR = 0x02;
    HIDE_IN_CLIENT = 0x04;
    FORCE_HIDE_IN_CLIENT = 0x08;
    FORCE_AT_PEACE = 0x10;
    FACTION_INACTIVE = 0x20;
}
```
### Type
The basic type is `u8`, a 1 byte (8 bit) integer.
### Enumerators
| Enumerator | Value  | Description | Comment |
| --------- | -------- | ----------- | ------- |
| `VISIBLE_TO_CLIENT` | 1 (0x01) |  |  |
| `ENABLE_AT_WAR` | 2 (0x02) |  |  |
| `HIDE_IN_CLIENT` | 4 (0x04) |  |  |
| `FORCE_HIDE_IN_CLIENT` | 8 (0x08) |  |  |
| `FORCE_AT_PEACE` | 16 (0x10) |  |  |
| `FACTION_INACTIVE` | 32 (0x20) |  |  |

Used in:
