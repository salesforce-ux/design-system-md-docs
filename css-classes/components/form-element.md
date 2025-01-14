

| Selector | Summary | Support | Restrict | Variant | Modifier |
|-------|-------|-------|-------|-------|-------|
| .slds-form_stacked | Vertical form elements with label stacked on top of control |   | .slds-form |   |   |
| .slds-form_horizontal | Horizontal form elements with label left-aligned to the control |   | .slds-form |   |   |
| .slds-is-edited | Indicates if a form element has been edited, but unsaved |   | .slds-form div |   |   |
| .slds-form__item | Each item inside of a record form row |   | .slds-form__row div |   |   |
| .slds-form__row | Each row inside of a record form |   | .slds-form div |   |   |
| .slds-form | Creates layout for a form | dev-ready | div, form | true |   |
| .slds-slider-label__range | Contains the range for the slider |   | .slds-slider-label span |   |   |
| .slds-slider-label__label | Contains the label for the slider and adds a hook for adding `.slds-assistive-text` class to visually hide the label, but not the range |   | .slds-slider-label span |   |   |
| .slds-slider-label | Contains the label and range for the slider label - not required |   | .slds-form-element span |   |   |
| .slds-input-has-fixed-addon | Use on input container to let it know there is fixed text to the left or right of the input |   | .slds-form-element .slds-form-element__control |   |   |
| .slds-input__icon-group_right | Positions the close icon and spinner on the right side of the input while searching |   | .slds-input__icon-group |   |   |
| .slds-input__icon-group | Positions two items (icons and/or spinners) on one side or the other of the input |   | .slds-input-has-icon div |   |   |
| .slds-input-has-icon_group-right | undefined |   | .slds-input-has-icon |   |   |
| .slds-input-has-icon_left-right | Positions .slds-input__icon_left to the left of the text input and .slds-input__icon_right to the right of the text input |   | .slds-input-has-icon |   |   |
| .slds-input-has-icon_right | Positions .slds-input__icon to the right of the text input |   | .slds-input-has-icon |   |   |
| .slds-input-has-icon_left | Positions .slds-input__icon to the left of the text input |   | .slds-input-has-icon |   |   |
| .slds-input__icon_right | Hook for .slds-input-has-icon_left-right |   | .slds-input__icon |   |   |
| .slds-input__icon_left | Hook for .slds-input-has-icon--left-right |   | .slds-input__icon |   |   |
| .slds-input__icon | Hook for .slds-input-has-icon |   | .slds-input-has-icon svg, .slds-input-has-icon button, .slds-input-has-icon span |   |   |
| .slds-input-has-icon | Modifier if text input has svg icon adjacent to input |   | .slds-form-element div |   |   |
| .slds-form-element_stacked | Vertical form elements with label stacked on top of control | dev-ready | .slds-form-element | true |   |
| .slds-form-element__undo | Container for the undo button icon found inside of slds-form-element |   | .slds-form-element div |   |   |
| .slds-form-element_horizontal | Horizontal form elements with label left-aligned to the control | dev-ready | .slds-form-element | true |   |
| .slds-form-element_address | Creates a form that consists of multiple form groups specific to an address form | dev-ready | .slds-form-element_compound, .slds-form_compound | true |   |
| .slds-form-element_compound | Creates a form that consists of multiple form groups | dev-ready | .slds-form-element | true |   |
| .slds-has-error | Error styles for form element |   | .slds-form-element |   | true |
| .slds-required | Required asterisk |   | .slds-form-element abbr, abbr |   |   |
| .slds-form-element__static_edit | Inline Edit on static form element |   | .slds-form-element__static |   |   |
| .slds-form-element__static | Initializes read-only form element |   | .slds-form-element span, .slds-form-element div |   |   |
| .slds-form-element__addon | Fixed text that sits to the left or right of an input |   | .slds-form-element span |   |   |
| .slds-form-element__legend_has-tooltip | Aligns the legend properly when there is an info tooltip |   | .slds-form-element__legend |   |   |
| .slds-form-element__legend | The form element label when applied to a legend element |   | .slds-form-element legend, .slds-form-element span |   |   |
| .slds-form-element_readonly | When a form element is in view mode, we modify some styling |   | .slds-form-element |   |   |
| .slds-form-element_edit | Modifier on slds-form-element that it needs to reserve space for the inline-edit trigger button |   | .slds-form-element |   |   |
| .slds-form-element__help | Creates inline help styles, sits below .form-element__control |   | .slds-form-element div |   |   |
| .slds-form-element__icon | When an icon sits within a form element wrapper and adjacent to another element inside that wrapper such as a .form-element__label |   | .slds-form-element div |   |   |
| .slds-dropdown_length-with-icon-10 | Forces overflow scrolling after 10 list items with an icon |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-dropdown_length-with-icon-7 | Forces overflow scrolling after 7 list items with an icon |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-dropdown_length-with-icon-5 | Forces overflow scrolling after 5 list items with an icon |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-dropdown_length-10 | Forces overflow scrolling after 10 list items |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-dropdown_length-7 | Forces overflow scrolling after 7 list items |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-dropdown_length-5 | Forces overflow scrolling after 5 list items |   | .slds-dropdown, .slds-dropdown__list, .slds-listbox |   | true |
| .slds-listbox_vertical | undefined |   | .slds-listbox |   | true |
| .slds-listbox__icon-selected | undefined |   | .slds-listbox__item svg |   |   |
| .slds-listbox__option-meta | undefined |   | .slds-listbox__option span |   |   |
| .slds-listbox__option-text_entity | undefined |   | .slds-listbox__option span |   |   |
| .slds-is-selected | undefined |   | .slds-listbox__option |   | true |
| .slds-listbox__option_has-meta | undefined |   | .slds-listbox__option |   |   |
| .slds-listbox__option_plain | undefined |   | .slds-listbox__option |   |   |
| .slds-listbox__option_entity | undefined |   | .slds-listbox__option |   |   |
| .slds-has-focus | undefined |   | .slds-listbox__option |   | true |
| .slds-listbox__option-icon | Container for listbox option icon |   | .slds-listbox__option span |   |   |
| .slds-listbox__option-header | Header for choosable option within listbox |   | .slds-listbox__option h3 |   |   |
| .slds-listbox__option | undefined |   | .slds-listbox__item > div |   |   |
| .slds-listbox__item | undefined |   | .slds-listbox > li |   |   |
| .slds-listbox_horizontal | undefined |   | .slds-listbox |   | true |
| .slds-listbox_inline | undefined |   | .slds-listbox |   | true |
| .slds-listbox | undefined | dev-ready | .slds-dropdown ul, .slds-dueling-list__options ul, .slds-pill_container ul, .slds-listbox_selection-group ul, .slds-combobox_container ul, .slds-form-element__control ul, .slds-popover__body ul | true |   |
| .slds-form-element__control | Wrapper to any form display element |   | .slds-form-element div |   |   |
| .slds-form-element | Creates layout for a form element | dev-ready | div, fieldset, li | true |   |
| .slds-form-element, .slds-form | An HTML form element contains a HTML label and element | dev-ready |   |   |   |