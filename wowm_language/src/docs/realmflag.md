# RealmFlag

## Protocol Version 2, Protocol Version 3, Protocol Version 5, Protocol Version 6, Protocol Version 7

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/login/cmd_realm/server.wowm:11`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/login/cmd_realm/server.wowm#L11).

```rust,ignore
flag RealmFlag : u8 {
    NONE = 0x00;
    INVALID = 0x01;
    OFFLINE = 0x02;
    FORCE_BLUE_RECOMMENDED = 0x20;
    FORCE_GREEN_RECOMMENDED = 0x40;
    FORCE_RED_FULL = 0x80;
}
```
### Type
The basic type is `u8`, a 1 byte (8 bit) integer.
### Enumerators
| Enumerator | Value  | Description | Comment |
| --------- | -------- | ----------- | ------- |
| `NONE` | 0 (0x00) |  |  |
| `INVALID` | 1 (0x01) |  |  |
| `OFFLINE` | 2 (0x02) |  |  |
| `FORCE_BLUE_RECOMMENDED` | 32 (0x20) |  |  |
| `FORCE_GREEN_RECOMMENDED` | 64 (0x40) |  |  |
| `FORCE_RED_FULL` | 128 (0x80) |  |  |

Used in:
* [Realm](realm.md)
* [Realm](realm.md)
# RealmFlag

## Protocol Version 8

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/login/cmd_realm/server.wowm:22`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/login/cmd_realm/server.wowm#L22).

```rust,ignore
flag RealmFlag : u8 {
    NONE = 0x00;
    INVALID = 0x01;
    OFFLINE = 0x02;
    SPECIFY_BUILD = 0x04;
    FORCE_BLUE_RECOMMENDED = 0x20;
    FORCE_GREEN_RECOMMENDED = 0x40;
    FORCE_RED_FULL = 0x80;
}
```
### Type
The basic type is `u8`, a 1 byte (8 bit) integer.
### Enumerators
| Enumerator | Value  | Description | Comment |
| --------- | -------- | ----------- | ------- |
| `NONE` | 0 (0x00) |  |  |
| `INVALID` | 1 (0x01) |  |  |
| `OFFLINE` | 2 (0x02) |  |  |
| `SPECIFY_BUILD` | 4 (0x04) |  |  |
| `FORCE_BLUE_RECOMMENDED` | 32 (0x20) |  |  |
| `FORCE_GREEN_RECOMMENDED` | 64 (0x40) |  |  |
| `FORCE_RED_FULL` | 128 (0x80) |  |  |

Used in:
* [Realm](realm.md)
