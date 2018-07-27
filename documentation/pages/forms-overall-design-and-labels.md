# Forms: Overall design and labels


## Design

Forms should be designed vertically as this improves their scanability. When possible, a form should be one column.

Information can be presented in multiple columns if they are grouped together \(i.e. first name and last name fields\).

Inputs should be grouped and sequenced in the most logical way possible. If multiple inputs are required for one grouping of information \(i.e. street address, postal code, and province\), these inputs should be placed in close proximity to each other.

Typically forms start with the most important or common information such as username, password, first or last name, email address, etc.

For complicated forms, information should be displayed using multiple steps or pages. If this is the case, it is important to include a progress bar throughout the form, as well as a way to navigate both forwards and backwards between steps.

*Example of form design*

## Labels

Users need to be able to easily read labels and intuitively understand how the label is related to its field. Labels should use clear but concise language, and provide enough information for the user to accurately complete the required information.

If additional information is necessary beyond a label, this information should be displayed in a separate tooltip or microcopy. 

**\(Example image here\)** 

### Placement of Labels

Labels should follow the vertical format of the form. Place labels above their respective field. Group a label with its field so that there is a clear distinction between fields. Do not use placeholder text for labels as this prevents the user from properly reviewing the form. Labels have a bottom margin of 10px from the input field. 

### Text in Labels

How labels are written affects their legibility. Do not write labels in all caps as this diminishes their readability. Labels should not be the same as placeholder text, they should both be separate. Don’t use symbols to represent required content.

## Placeholder Text

*Placeholder text is used only to provide supplemental information or additional guidance on how to complete a text field. Placeholder text DOES NOT replace a label or microcopy. Placeholder text should only be used if an example of a text input improves the user experience, rather than as a replacement to other important information indicators. 

Placeholder text is text that appears directly in the input field. This text is not meant to be used as a label, but can provide supplemental information or an example for the user.

Placeholder text is meant to help the user more accurately complete the field rather than be the primary indicator of field content. It may also be complementary to micro-copy, with placeholder text providing an example, and micro-copy providing additional information or context. 

As soon as the user starts typing in the field, the placeholder text should disappear.

Placeholder text is styled using Nunito Sans Regular at 14px, #666666

_**\(Example image here\)**_

For more information about placeholder text styles, refer to the [_Typography_](typography.md) section.

## Micro-Copy

Microcopy is text below and input field that provides additional information about that field. Microcopy is meant to be brief sentences that instruct the user how to complete the field.

Micro-copy is styled as follows:

10px below the input field. The text is displayed the same as placeholder text; Nunito Sans Regular at 14px, #666666

If there is more than one line the text wraps and has a leading of 18pts. 

*Input field with microcopy*

## Grouping / Field Sets

To help users better understand a form, it may be useful to group inputs into categories or field sets. Field sets should be grouped visually on the page and labelled using Header 3 with a divider underneath. 

*Example image of field sets

## Step Indicators
If possible, it is recommended to limit forms to one page. If a form has more than one page, use a step indicator. 

If a form has more than one page, it is recommended to provide the user with a visual representation of progression so that they are aware of their level of completetion. Styling for step indicators is written in its own section of this documentation. 

*step indicator component*

## Navigation

Navigation to different pages may be necessary to include in a form. If they are related to a specific field, for example "Forgot password?", include the link inline and underneath the related field. If the link is related to the entire form, for example "Register here", include the link at the bottom of the form in a way that is visually separate.
