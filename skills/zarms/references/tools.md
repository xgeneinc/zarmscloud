# ZARMS MCP tools

Tool schemas (parameters, enums) come from the MCP server itself; read them from the tool list. This table only says when to use each tool.

| Area     | Tool                                                                 | Use for                                                                                     |
| -------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Schema   | `describe_collections`                                               | Built-in and custom field keys, types, required flags. Call before touching custom fields   |
| Schema   | `list_field_definitions`                                             | Custom field definitions in detail                                                          |
| Records  | `get_record`, `set_custom_fields`                                    | Read a record; set custom field values                                                      |
| Boards   | `search_boards`, `get_board`                                         | Find a board and read it                                                                    |
| Boards   | `create_board`, `update_board`, `duplicate_board`                    | Create, rename or copy a board                                                              |
| Cards    | `search_cards`                                                       | Filter by text, board, status, priority, person, ball holder, overdue, dates, custom fields |
| Cards    | `get_card`                                                           | Details with steps, comments, Drive links, document copy                                    |
| Cards    | `create_card`, `update_card`                                         | Create or edit. Optional `description` fills a Google Doc after creation                    |
| Cards    | `set_card_status`, `move_card`                                       | Change status; move between boards or positions                                             |
| Cards    | `archive_card`, `unarchive_card`                                     | Tidy up (no delete)                                                                         |
| Cards    | `duplicate_card`, `set_card_following`                               | Copy; follow or unfollow                                                                    |
| Cards    | `get_card_drive_links`                                               | Google Drive links attached to a card                                                       |
| Steps    | `list_steps`, `get_step`, `add_step`, `update_step`, `reorder_steps` | A card's steps                                                                              |
| Steps    | `delete_step`                                                        | Irreversible. Confirm first                                                                 |
| Comments | `list_comments`, `get_comment`, `add_comment`, `update_comment`      | Conversation on a card                                                                      |
| Comments | `archive_comment`, `unarchive_comment`, `delete_comment`             | Hide, restore, remove                                                                       |
| People   | `list_members`, `get_member`                                         | Signed-in team members and their user ids                                                   |
| People   | `list_directory_members`, `get_directory_member`                     | The directory (people not yet signed in)                                                    |
| People   | `set_member_boards`                                                  | Which boards a member can see                                                               |
| Settings | `get_team_settings`, `update_team_settings`                          | Owner/Manager only; whitelisted fields                                                      |
| Settings | `get_notification_settings`, `update_notification_settings`          | The connected user's own notifications                                                      |
| Settings | `get_inbound_email_settings`, `update_inbound_email_settings`        | The connected user's My Board email intake                                                  |

REST equivalents live under `https://app.zarms.cloud/api/v1`; see https://app.zarms.cloud/api-docs.
