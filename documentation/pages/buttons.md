# Buttons

![Image of all button varieties](https://github.com/gctools-outilsgc/design-system/blob/master/documentation/examples/buttons.png)

## Best Practices

Buttons tend to have visual prominence on any given page or window. Primary buttons, buttons that indicate a call to action, are the most prominent. Secondary buttons, which indicate less commonly used actions, should be less prominent than primary buttons. Buttons always indicate an action and are not to be used for navigation. Buttons are placed where a user should expect them, i.e. in close proximity to the other elements that the action affects.

## Size and Padding

Buttons used in this design system have a minimum size of 30px by 30px. This is the typical size of a user's finger pad when using the application on mobile. For web this minimum size is also consistent.

The more white-space, padding, around a button, the more prominent the button appears on the page. Most buttons in this system use 15px of padding, unless are otherwise indicated.

## Labels

Button labels should be clear and specific. Avoid generic terms like Save, Submit or Cancel. Buttons should indicate the exact action that is taken and should provide a clear idea of what will happen next.

Examples of good button labels: Add a blog post, Send message, Save draft. 

All labels should capitalize only the first letter of the label.

Label text has high contrast with the button colour. See Colour for more information about acceptable contrast.

## Varying States

![Image of different button states](https://github.com/gctools-outilsgc/design-system/blob/master/documentation/examples/button%20states.png)

Buttons are not one-state objects. Most users will recognize a button because of its hover and active states. Varying states also provide feedback to the user at each stage of performing the action.

Buttons should include normal, hover, focus, active and disabled states:

**Normal:** Even in its normal state, a button should look like a button! Before hovering, a user should be able to tell that an element is clickable.

**Hover:** Usually indicated by a change in colour or animation, hover states indicate to the user that the element is clickable.

**Focus:** Similar to hover states, focus states indicate that the user has tabbed to the specific button.

**Active/Pressed:** Usually indicated by a change in colour or animation, this indicates that the user has clicked or pressed a button/

**Disabled:** Usually a ghosted version of the normal state, this indicates to the user that the action is unavailable.

## Primary Buttons

Primary buttons identify a call to action. Use these buttons for actions that a user is encouraged to take, such as: Add a blog post, Send message, or Login. Try to keep button labels limited to one or two words.

Primary buttons are designed to have high contrast against the background and the heaviest visual weight. They typically use brighter colours than other elements on the form or layout, and are located in a visible and accessible area of the page. 

Primary buttons use the primary colour, with white text. Sizing of the button depends on the length of the _**action words**_.

Each of the states for primary buttons are as follows:

*Regular button component here*

**Regular state:** primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px.

*Hover button component here*

**Hover state:** primary colour at 80% opacity, white text, with a border radius of 4px and padding of 15px.

*Hover button component here*

**Focus state:** primary colour at 80% opacity, white text, with a border radius of 4px and padding of 15px. Includes a 3px stroke in the primary colour.

**Active state:** _**\(to complete\)**_

*Disabled button component here*

**Disabled state:** primary colour at 60% opacity, white text, with a border radius of 4px and padding of 15px.

### Position

Primary buttons should be located in the most prominent and convenient location possible.\_ \_These buttons should also be located in close proximity to the form or the elements that are affected by the action. Generally, in a set of two, primary buttons are placed on the left and the secondary button is placed on the right. 

## Secondary Buttons

Secondary buttons are used for actions that are necessary to provide, but that users may click less often. Examples include actions such as Cancel submission, Delete or Save draft. These buttons have a visual weight that is equal to or less than the majority of elements on the page. The secondary button is usually placed in close proximity to the primary button. Try to keep button labels limited to one or two words.

Secondary buttons, particularly ones used for destructive actions, should be designed in a way that deters users from clicking on it. This helps minimize mistakes.

For permanent destructive secondary actions, such as Delete, clicking the button will prompt a dialog to confirm the action. Always give the user to confirm actions that cannot be reverted. 

Secondary buttons in this system are transparent with a stroke colour. Text changes colour depending on the button state. Sizing of the button depends on the length of the _**action words**_.

Each of the states for secondary buttons are as follows:

*Regular secondary button component*

**Regular state:** transparent with a 1px stroke using the  colour \#002D42, the text is written in the same colour. Border radius of 4px and padding of 15px.

*Hover secondary button component*

**Hover state:** rectangle coloured with \#002D42 at 80% opacity, the text is displayed in white. Border radius of 4px and padding of 15px.

*Focus secondary button component*

**Focus state:** transparent with a 3px stroke using \#002D42, the text is displayed in \#002D42. Border radius of 4px and padding of 15px.

*Disabled secondary button component*

**Disabled state:** Fill colour of \#CECECE, with white text. Border radius of 4px and padding of 15px.

### Position

Secondary buttons are usually in close proximity to the primary button, but not in a location where the user might mistake the two. Secondary buttons are usually placed to the right of the primary button\_. \_They should have a consistent placement relative to the primary button to avoid confusion.

## Drop-Down Buttons

Drop down buttons display a list of items when clicked. They are used for two-step processes that may require more specific options for a singular action.

*Regular drop down button component*

**Regular State:** Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height.

*Hover drop down button components*

**Hover States:** Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height. Whichever piece of the button \(primary or drop-down section\) is being hovered over is shown at 80% opacity.

*Focus drop down button component*

**Focus State:** Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height. Whichever piece of the button \(primary or drop-down section\) is being focused on is shown at 80% opacity and includes a stroke of 3px in the primary colour.

*Pressed drop down button component*

**Pressed State:** When the drop-down arrow is pressed, this arrow section of the button is displayed at 80% opacity and a drop-down menu is displayed below. The action box uses a 1px border using \#CECECE. The box has a border radius of 4px. The width of the box is 166px, and the height depends on the number of actions, using 40px per action. On hover, the 40px around the action is displayed using \#CECECE

## Button Groups

Button groups, are a stylized way of putting multiple buttons together.

Primary actions are aligned to the left, while secondary actions are placed in the middle, and warning or destructive actions are aligned to the right.

*Button groups component*


