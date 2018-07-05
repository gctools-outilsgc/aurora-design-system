# Forms: Errors and Validation

## Input Errors

Input errors should be displayed in such a way that it is clear to the user that they have made an error, and what and where that error is. To display errors in a form submission, use both error boxes and inline errors. For each error, copy used for both the error box and the inline error should be indentical. 

## Error Boxes 

As well, have an error box appear at the beginning of the form listing the errors. In the error box specify the number of errors, and list them numerically in the order in which they appear in the form. For each error provide the reason for the error and a link that directs the user to the error. If the user attempts to submit the form with incomplete necessary fields, direct them to this error box.
 
Error boxes are styled as follows:
 
Rectangle with the same width as the form container. 4px border radius and a stroke of width 1px using the colour #923534. The box has 15px padding. In the top left corner there is a red circle with a white "x" icon that is 25px. 
 
The box heading uses Heading 2 style, and the text uses the paragraph style. Error copy is displayed in a numbered list using ##923534. Each error is a link which leads the user to the inline error on the page.  

*Error box component* 

## Inline Errors

The input field border will be shown using the colour #923534. If there is an error on a button input, the label is displayed using this same colour. 

Inline errors are displayed underneath the input field, and tell the user how to fix the error. Inline errors should be as succint as possible and are limited to one line that fits under the input field. 

Inline errors are styled as follows:

*Inline error component*

"x" icon to the left of the error text. The error is placed 10px below the input field. Text is shown using Nunito Sans Regular at 14px font in #925534. 

## Validation

Fields should be validated when the user has completed the required field information, but prior to the user submitting or completing the entire form.

## Required Fields

Inputs should be clearly indicated as optional or required.

If most fields in the form are required, indicate only the optional fields.

If most fields in the form are optional, indicate only the required fields.

Indications should be located beside the input field. The terms \(Required\) or \(Optional\) should be present only where necessary. Indicator text uses the colour: \#252525 and follows the same typography design as labels.

