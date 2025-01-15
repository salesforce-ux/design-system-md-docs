

| Selector | Summary | Support | Restrict | Variant | Modifier |
|-------|-------|-------|-------|-------|-------|
| .slds-is-selected | When button is pressed and selected |   | .slds-button_stateful |   | true |
| .slds-is-selected-clicked | When button is selected and still has focus from click |   | .slds-button_stateful |   | true |
| .slds-text-not-selected | Shown text when button is not selected - default state |   | .slds-button_stateful span |   |   |
| .slds-text-selected-focus | Shown text when button is selected and focused |   | .slds-button_stateful span |   |   |
| .slds-text-selected | Shown text when button is selected |   | .slds-button_stateful span |   |   |
| .slds-not-selected | undefined |   | .slds-button_stateful |   | true |
| .slds-button_stateful | Initiates a stateful button | dev-ready | button | true |   |
| .slds-is-pressed | When button is in pressed state |   | .slds-button_dual-stateful |   | true |
| .slds-text-pressed | Shown text when button is pressed |   | .slds-button_dual-stateful span |   |   |
| .slds-text-not-pressed | Shown text when button is not pressed - default state |   | .slds-button_dual-stateful span |   |   |
| .slds-button_dual-stateful | Initiates a dual stateful button | dev-ready | button | true |   |
| .slds-input__button_increment | Positions increment button within counter input field |   | .slds-button |   |   |
| .slds-input__button_decrement | Positions decrement button within counter input field |   |  .slds-button |   |   |
| .slds-button_stretch | Creates a button style for 100% width with centered text that maintains current styling |   | .slds-button |   | true |
| .slds-button_full-width | Creates a button style for full width that resets styling |   | .slds-button |   | true |
| .slds-icon_x-small | undefined |   | .slds-icon, .slds-button__icon |   | true |
| .slds-button__icon_right | Position of icon when sitting to the right side of the text when inside a button |   | .slds-button__icon, .slds-button__icon_stateful |   |   |
| .slds-button__icon_left | Position of icon when sitting to the left side of the text when inside a button |   | .slds-button__icon, .slds-button__icon_stateful |   |   |
| .slds-button__icon_x-small | X-Small size button icon svg |   | .slds-button__icon |   | true |
| .slds-button__icon_small | Small size button icon svg |   | .slds-button__icon |   | true |
| .slds-button__icon_large | Large size button icon svg |   | .slds-button__icon |   | true |
| .slds-button__icon_x-small | X-Small size for button icon svg | dev-ready | .slds-button__icon |   | true |
| .slds-button__icon_small | Small size for button icon svg | dev-ready | .slds-button__icon |   | true |
| .slds-button__icon_large | Large size for button icon svg | dev-ready | .slds-button__icon |   | true |
| .slds-button__icon | Sizing for icon that sits inside button__icon | dev-ready | .slds-button svg | true |   |
| .slds-button_success | Creates a green button style |   | .slds-button |   | true |
| .slds-button_text-destructive | Creates a neutral button with red text |   | .slds-button |   | true |
| .slds-button_destructive | Creates a red button style |   | .slds-button |   | true |
| .slds-button_inverse | Creates the inverse style for dark backgrounds |   | .slds-button |   | true |
| .slds-button_outline-brand | Creates the outlined button with the brand color |   | .slds-button |   | true |
| .slds-button_brand | Creates the brand blue Salesforce style |   | .slds-button |   | true |
| .slds-button_neutral | Creates the gray border with white background default style |   | .slds-button |   | true |
| .slds-button_last | Explicitly style the last button in a button group |   | .slds-button |   |   |
| .slds-button_middle | Explicitly style buttons in the middle (i.e., not first or last) in a button group |   | .slds-button |   |   |
| .slds-button_first | Explicitly style the first button in a button group |   | .slds-button |   |   |
| .slds-button | This neutralizes all the base styles making it look like a text link | dev-ready | button, a, span | true |   |
| .slds-button, .slds-button_stateful, .slds-button_dual-stateful, .slds-button_reset | Buttons are used to invoke an event | dev-ready |   |   |   |