# Modals

Modals are overlay messages that appear when actions need to be taken. They should be used for actions or information that the user must acknowledge before proceeding. Modals prevent the user from accessing the parent page until the modal has been clicked out of or dismissed.

## Types of Modals

Alerts - Urgent interruptions which require acknowledgement. For example, if a user hasn't saved their data, and is trying to navigate away from a page an alert modal should appear to warn them that they will lose their data if they continue. Use for actions that are irreversible.

Menus - Lists which offers a user choice. For example, choosing a sound that will play to remind them of an event in their calendar. 

Confirmation - A single action which confirms a user's choice. For example, a confirmation modal appears when a user is opting to delete their account to ensure that this is the action they meant to take.

Form - A complex modal that requires the user to fill out multiple fields. 

## Best Practices

Modal text should be short and precise so that the user clearly knows what the modal is stating or asking. The title should appear at the top, with the action button appearing on the bottom. The title can be a question or not, depending on the context. The action button should clearly state the action the user will be taking, for example "cancel and delete" vs "no and yes". The main content of the modal should clearly describe the situation. Do not use messages like "Are you sure?".

How the user dismisses the modal depends on the severity of the action. Secondary action modals can be dismissed by clicking "X", appearing in the top right corner, or by clicking outside of the modal box. Primary actions should not have these options for dismissal, and should only be closed by selecting an action.

Typically a modal should not cover a user's entire screen. The only exception is for a complex modal on a mobile.

Modals can open up additional modals, however you should be careful to not have too many layers of modals as this increases visual noise.

## Components of a Modal

Modals can be made up of several components. Some examples are:

Title:  An overall description of the modal.

Subtitle: A specific call-to-action for the modal. Use if the title does not convey the entire message of the modal.

Meta Information: Information that is used to categorize the modal. 

Main Content: A detailed explanation of the modal's purpose. 

Image: Only use when relevant to the modal's task.

Buttons: The actions the user can take when using the modal.

Not all of these elements are necessary for a modal. Use what makes the most sense for the message and action the modal fulfills. However, all modals should have buttons with the actions the user can take.

## Modal Templates

### Standard Modal Template

![](.gitbook/assets/modal1.png)

This template comprises of the majority of elements that can be found in a typical modal. Do not use as an alert modal, as it can be exited from without the user choosing an action. 

### Standard Modal Template Mobile

![](.gitbook/assets/modal3%20%281%29.png)

The standard modal template, sized for mobile. 

### Alert Modal Template

![](.gitbook/assets/modal4%20%281%29.png)

The alert modal template does not allow the user to return to the parent page without taking an action.

### Alert Modal Template Simplified 

![](.gitbook/assets/modal6.png)

If further explanation of the alert is not required, you can use a simplified version of the modal.

### Menu Modal Template

![](.gitbook/assets/modal5%20%282%29.png)

The menu modal template offers the user a choice of options.

### Image Modal Template

![](.gitbook/assets/modal%20%282%29.png)

Based on the standard modal template, this image modal includes a placement for an image. 

## Example of User Flow and Layering

![](.gitbook/assets/modal-mobile.png)

This is an example of layering modals for the user to achieve a goal.  In this scenario the user is creating an event in their calendar through modals on mobile. The first modal that opens navigates the user to two other modals through action buttons. Upon selecting the "Create an event" action, a full screen form modal opens, and the first modal closes. Within this form modal, the user selects "alert" opening a second layer of modal in the menu format. After selecting an option, or closing the menu modal, the user returns to the first layer form modal.

Layers can help direct users through closely related options within a task. However, too many layers can become confusing for the user. Typically you should not have more than two layers of modals. 

