# SMSG_CALENDAR_EVENT_MODERATOR_STATUS_ALERT

## Client Version 3.3.5

### Wowm Representation

Autogenerated from `wowm` file at [`wow_message_parser/wowm/world/calendar/smsg_calendar_event_moderator_status_alert.wowm:1`](https://github.com/gtker/wow_messages/tree/main/wow_message_parser/wowm/world/calendar/smsg_calendar_event_moderator_status_alert.wowm#L1).
```rust,ignore
smsg SMSG_CALENDAR_EVENT_MODERATOR_STATUS_ALERT = 0x0445 {
    PackedGuid invitee;
    Guid event_id;
    u8 rank;
    Bool show_alert;
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
| 0x04 | - / - | [PackedGuid](../spec/packed-guid.md) | invitee |  |  |
| - | 8 / Little | [Guid](../spec/packed-guid.md) | event_id |  |  |
| - | 1 / - | u8 | rank |  |  |
| - | 1 / - | Bool | show_alert |  |  |

