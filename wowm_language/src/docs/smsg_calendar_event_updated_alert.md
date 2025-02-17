# SMSG_CALENDAR_EVENT_UPDATED_ALERT

## Client Version 3.3.5

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/calendar/smsg_calendar_event_updated_alert.wowm:1`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/calendar/smsg_calendar_event_updated_alert.wowm#L1).
```rust,ignore
smsg SMSG_CALENDAR_EVENT_UPDATED_ALERT = 0x0444 {
    Bool show_alert;
    Guid event_id;
    DateTime old_event_time;
    u32 flags;
    DateTime new_event_time;
    u8 event_type;
    u32 dungeon_id;
    CString title;
    CString description;
    u8 repeatable;
    u32 max_invitees;
    DateTime unknown_time;
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
| 0x04 | 1 / - | Bool | show_alert |  |  |
| 0x05 | 8 / Little | [Guid](../spec/packed-guid.md) | event_id |  |  |
| 0x0D | 4 / Little | DateTime | old_event_time |  |  |
| 0x11 | 4 / Little | u32 | flags |  |  |
| 0x15 | 4 / Little | DateTime | new_event_time |  |  |
| 0x19 | 1 / - | u8 | event_type |  |  |
| 0x1A | 4 / Little | u32 | dungeon_id |  |  |
| 0x1E | - / - | CString | title |  |  |
| - | - / - | CString | description |  |  |
| - | 1 / - | u8 | repeatable |  |  |
| - | 4 / Little | u32 | max_invitees |  |  |
| - | 4 / Little | DateTime | unknown_time |  |  |

