
|  |  |
|-------|-------|
| Selector | .slds-chat_past |
| Summary | Apply when displaying chat logs that appeared in the past |
| Support | dev-ready |
| Restrict | .slds-chat |
| Variant | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-bookend_stop |
| Summary | Modifier for bookends which stop a chat session |
| Restrict | .slds-chat-bookend |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-icon |
| Summary | Used to style icons with a chat log |
| Restrict | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-bookend |
| Summary | Used to style a chat bookend |
| Restrict | .slds-chat-listitem div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-has-error |
| Summary | Modifier to indicate the event was an error |
| Restrict | .slds-chat-event[role="alert"] |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-event__agent-message |
| Summary | Used to style any messages from an agent in the event |
| Restrict | .slds-chat-event div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-icon |
| Summary | Used to style icons with a chat log |
| Restrict | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-event__body |
| Summary | Used for styling the event body text |
| Restrict | .slds-chat-event div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-event |
| Summary | During any chat, certain events can occur which need to be displayed to the user |
| Restrict | .slds-chat-listitem div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-icon |
| Summary | Used to style icons with a chat log |
| Restrict | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__action |
| Summary | Used to style chat message resend action |
| Restrict | .slds-chat-message .slds-button |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__meta |
| Summary | Used to style chat message meta data |
| Restrict | .slds-chat-message div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__file_inbound |
| Summary | Used for any specific inbound file styling |
| Restrict | .slds-chat-message__file |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__file |
| Summary | true |
| Restrict | .slds-chat-message__body div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_sneak-peek |
| Summary | Used when sneak peek is enabled for customer messages |
| Restrict | .slds-chat-message__text |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_delivery-failure-reason |
| Summary | Element that contains feedback for why inbound message failed |
| Restrict | .slds-chat-message__text_delivery-failure [role="alert"] |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_delivery-failure |
| Summary | Used for an inbound message that fails to deliver |
| Restrict | .slds-chat-message__text |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_unsupported-type |
| Summary | Used for an inbound message that is not a supported message type |
| Restrict | .slds-chat-message__text |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_outbound-agent |
| Summary | Used for any specific outbound (from another agent) text styling |
| Restrict | .slds-chat-message__text |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_outbound |
| Summary | Used for any specific outbound text styling |
| Restrict | .slds-chat-message__text |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text_inbound |
| Summary | Used for any specific inbound text styling |
| Restrict | .slds-chat-message__text |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-icon |
| Summary | Used to style icons with a chat log |
| Restrict | .slds-chat-message__text .slds-icon_container, .slds-chat-event__body .slds-icon_container, .slds-chat-bookend .slds-icon_container, .slds-chat-message__action .slds-icon_container |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__text |
| Summary | Used to style the chat text from agent or customer |
| Restrict | .slds-chat-message__body div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__image_loading |
| Summary | true |
| Restrict | .slds-chat-message__body |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message__body |
| Summary | Used to contain and align chat messages with their avatars |
| Restrict | .slds-chat-message div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-avatar |
| Summary | Used to style avatars in chat logs |
| Restrict | .slds-chat-message .slds-avatar |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message_faux-avatar |
| Summary | Used for when customer avatars are used in consequtive inbound messages to align the message body with the previous message |
| Restrict | .slds-chat-message |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-message |
| Summary | styles the outter part of a chat message |
| Restrict | .slds-chat-listitem div |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-listitem_event |
| Summary | Modifier used for spacing event items |
| Restrict | .slds-chat-listitem |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-listitem_bookend |
| Summary | Modifier used for spacing bookend items |
| Restrict | .slds-chat-listitem |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-listitem_inbound |
| Summary | Modifier used to style inbound message list items |
| Restrict | .slds-chat-listitem |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-listitem_outbound |
| Summary | Modifier used to style outbound message list items |
| Restrict | .slds-chat-listitem |
| Modifier | true |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-listitem |
| Summary | Handles spacing and direction of items in the list |
| Restrict | .slds-chat-list li |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat-list |
| Summary | Handles the display of chat items within a list |
| Restrict | .slds-chat ul |
|  |  |


|  |  |
|-------|-------|
| Selector | .slds-chat |
| Summary | Root container of a chat session |
| Support | dev-ready |
| Restrict | section[role="log"] |
| Variant | true |
|  |  |

