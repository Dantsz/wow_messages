# LfgUpdateType

## Client Version 3.3.5

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/lfg/smsg_lfg_update_player.wowm:1`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/lfg/smsg_lfg_update_player.wowm#L1).

```rust,ignore
enum LfgUpdateType : u8 {
    DEFAULT = 0;
    LEADER_LEAVE = 1;
    ROLECHECK_ABORTED = 4;
    JOIN = 5;
    ROLECHECK_FAILED = 6;
    LEAVE = 7;
    PROPOSAL_FAILED = 8;
    PROPOSAL_DECLINED = 9;
    GROUP_FOUND = 10;
    ADDED_TO_QUEUE = 12;
    PROPOSAL_BEGIN = 13;
    STATUS = 14;
    GROUP_MEMBER_OFFLINE = 15;
    GROUP_DISBAND = 16;
}
```
### Type
The basic type is `u8`, a 1 byte (8 bit) integer.
### Enumerators
| Enumerator | Value  | Description | Comment |
| --------- | -------- | ----------- | ------- |
| `DEFAULT` | 0 (0x00) |  |  |
| `LEADER_LEAVE` | 1 (0x01) |  |  |
| `ROLECHECK_ABORTED` | 4 (0x04) |  |  |
| `JOIN` | 5 (0x05) |  |  |
| `ROLECHECK_FAILED` | 6 (0x06) |  |  |
| `LEAVE` | 7 (0x07) |  |  |
| `PROPOSAL_FAILED` | 8 (0x08) |  |  |
| `PROPOSAL_DECLINED` | 9 (0x09) |  |  |
| `GROUP_FOUND` | 10 (0x0A) |  |  |
| `ADDED_TO_QUEUE` | 12 (0x0C) |  |  |
| `PROPOSAL_BEGIN` | 13 (0x0D) |  |  |
| `STATUS` | 14 (0x0E) |  |  |
| `GROUP_MEMBER_OFFLINE` | 15 (0x0F) |  |  |
| `GROUP_DISBAND` | 16 (0x10) |  |  |

Used in:
* [SMSG_LFG_UPDATE_PARTY](smsg_lfg_update_party.md)
* [SMSG_LFG_UPDATE_PLAYER](smsg_lfg_update_player.md)

