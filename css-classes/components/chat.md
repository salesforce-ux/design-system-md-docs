

| Selector | Summary | Support | Restrict | Variant | Modifier |
|-------|-------|-------|-------|-------|-------|
| .slds-chat_past | Apply when displaying chat logs that appeared in the past | dev-ready | .slds-chat | true |   |
| .slds-chat-bookend_stop | Modifier for bookends which stop a chat session |   | .slds-chat-bookend |   | true |
| .slds-chat-icon | Used to style icons with a chat log |   | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |   |   |
| .slds-chat-bookend | Used to style a chat bookend |   | .slds-chat-listitem div |   |   |
| .slds-has-error | Modifier to indicate the event was an error |   | .slds-chat-event[role="alert"] |   | true |
| .slds-chat-event__agent-message | Used to style any messages from an agent in the event |   | .slds-chat-event div |   |   |
| .slds-chat-icon | Used to style icons with a chat log |   | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |   |   |
| .slds-chat-event__body | Used for styling the event body text |   | .slds-chat-event div |   |   |
| .slds-chat-event__rule | Used to style the horizontal rules on an event |   | .slds-chat-event div |   |   |
| .slds-chat-event | During any chat, certain events can occur which need to be displayed to the user |   | .slds-chat-listitem div |   |   |
| .slds-chat-icon | Used to style icons with a chat log |   | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |   |   |
| .slds-chat-message__action | Used to style chat message resend action |   | .slds-chat-message .slds-button |   |   |
| .slds-chat-message__meta | Used to style chat message meta data |   | .slds-chat-message div |   |   |
| .slds-chat-message__file_inbound | Used for any specific inbound file styling |   | .slds-chat-message__file |   |   |
| .slds-chat-message__file | true |   | .slds-chat-message__body div |   |   |
| .slds-chat-message__text_sneak-peek | Used when sneak peek is enabled for customer messages |   | .slds-chat-message__text |   | true |
| .slds-chat-message__text_delivery-failure-reason | Element that contains feedback for why inbound message failed |   | .slds-chat-message__text_delivery-failure [role="alert"] |   |   |
| .slds-chat-message__text_delivery-failure | Used for an inbound message that fails to deliver |   | .slds-chat-message__text |   | true |
| .slds-chat-message__text_unsupported-type | Used for an inbound message that is not a supported message type |   | .slds-chat-message__text |   | true |
| .slds-chat-message__text_outbound-agent | Used for any specific outbound (from another agent) text styling |   | .slds-chat-message__text |   |   |
| .slds-chat-message__text_outbound | Used for any specific outbound text styling |   | .slds-chat-message__text |   |   |
| .slds-chat-message__text_inbound | Used for any specific inbound text styling |   | .slds-chat-message__text |   |   |
| .slds-chat-icon | Used to style icons with a chat log |   | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |   |   |
| .slds-chat-message__text | Used to style the chat text from agent or customer |   | .slds-chat-message__body div |   |   |
| .slds-chat-message__image_loading | true |   | .slds-chat-message__body |   |   |
| .slds-chat-message__body | Used to contain and align chat messages with their avatars |   | .slds-chat-message div |   |   |
| .slds-chat-avatar__intials | Used to style the avatar intials for chat |   | .slds-chat-avatar .slds-avatar__initials |   |   |
| .slds-chat-avatar | Used to style avatars in chat logs |   | .slds-chat-message .slds-avatar |   |   |
| .slds-chat-message_faux-avatar | Used for when customer avatars are used in consequtive inbound messages to align the message body with the previous message |   | .slds-chat-message |   |   |
| .slds-chat-message | styles the outter part of a chat message |   | .slds-chat-listitem div |   |   |
| .slds-chat-listitem_event | Modifier used for spacing event items |   | .slds-chat-listitem |   |   |
| .slds-chat-listitem_bookend | Modifier used for spacing bookend items |   | .slds-chat-listitem |   |   |
| .slds-chat-listitem_inbound | Modifier used to style inbound message list items |   | .slds-chat-listitem |   | true |
| .slds-chat-listitem_outbound | Modifier used to style outbound message list items |   | .slds-chat-listitem |   | true |
| .slds-chat-listitem | Handles spacing and direction of items in the list |   | .slds-chat-list li |   |   |
| .slds-chat-list | Handles the display of chat items within a list |   | .slds-chat ul |   |   |
| .slds-chat | Root container of a chat session | dev-ready | section[role="log"] | true |   |
| .slds-chat | Use Chat to display current or historical instant messaging chat sessions | dev-ready |   |   |   |