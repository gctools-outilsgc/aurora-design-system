# Buttons

# ![](/assets/buttons.png)

## Best Practices

Buttons tend to have visual prominence on any given page or window.  Primary buttons, buttons that indicate a call to action, are the most prominent. Secondary buttons, which indicate less commonly used actions, should be less prominent than primary buttons. Buttons always indicate an action and are not to be used for navigation.  Buttons are placed where a user should expect them, i.e. in close proximity to the other elements that the action affects.

## Size and Padding

Buttons used in this design system have a minimum size of 10mm x 10mm. This is the typical size of a user's finger pad when using the application on mobile. For web this minimum size is also consistent.

The more white-space _**padding**_ around a button, the more prominent the button appears on the page. Most buttons in this system use 15px of padding. _**\(which ones do and which ones don't? What's the reasoning?\)**_

## Labels

Button labels should be clear and specific. Avoid generic terms like Save, Submit or Cancel. Buttons should indicate the exact action that is taken and should provide a clear idea of what will happen next.

Examples of good button labels: Add a blog post, Send message, Back to menu.

All labels should capitalize only the first letter of the label.

Label text has high contrast with the button colour. See below for specific text colours for each type of button.

## Varying States

Buttons are not one-state objects. Most users will recognize a button because of its hover and active states. Varying states also provide feedback to the user at each stage of performing the action.

Buttons should include normal, hover, focus, active and disabled states:

**Normal: **Even in its normal state, a button should look like a button! Before hovering, a user should be able to tell that an element is clickable.

**Hover: **Usually indicated by a change in colour or animation, hover states indicate to the user that the element is clickable.

**Focus: **Similar to hover states, focus states indicate that the user has tabbed to the specific button.

**Active/Pressed: **Usually indicated by a change in colour or animation, this indicates that the user has clicked or pressed a button/

**Disabled: **Usually a ghosted version of the normal state, this indicates to the user that the action is unavailable.

## Primary Buttons

Primary buttons identify a call to action. Use these buttons for actions that a user is encouraged to take such as Add a blog post, Send message, or Login. Try to keep button labels limited to one or two words.

Primary buttons are designed to have high contrast against the background and the heaviest visual weight. They typically use brighter colours than other elements on the form or layout, and are located in a visible and accessible area of the page.

Primary buttons use the primary colour, with white text. Sizing of the button depends on the length of the _**action words**_.

Each of the states for primary buttons are as follows:

![](/assets/button_primary.png)

**Regular state:**  primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px.

![](/assets/button_primary_hover.png)

**Hover state: **primary colour at 80% opacity, white text, with a border radius of 4px and padding of 15px.

![](/assets/button_primary_focus.png)

**Focus state: **primary colour at 80% opacity, white text, with a border radius of 4px and padding of 15px. Includes a 3px stroke in the primary colour.

**Active state: **_**\(to complete\)**_

![](/assets/button_primary_disabled.png)

**Disabled state: **primary colour at 50% opacity, white text, with a border radius of 4px and padding of 15px.

### Position

Primary buttons should be located in the most prominent and convenient location possible.\_ \_These buttons should also be located in close proximity to the form or the elements that are affected by the action.

## Secondary Buttons

Secondary buttons are used for actions that are necessary to provide, but that users may click less often. Examples include actions such as Cancel submission, Delete or Back to menu._** \(All of these are reverse actions. Is that something to mention maybe?\)**_ These buttons have a visual weight that is equal to or less than the majority of elements on the page. The secondary button is usually placed in close proximity to the primary button. Try to keep button labels limited to one or two words.

Secondary buttons, particularly ones used for destructive actions, should be designed in a way that deters users from clicking on it. _**For example, the button could be in a shade of red.**_** **This helps minimize mistakes.

For permanent destructive secondary actions, such as Delete, clicking the button may bring the user to a second window to confirm the action.

Secondary buttons in this system are transparent with a stroke colour. Text changes colour depending on the button state. Sizing of the button depends on the length of the _**action words**_.

Each of the states for secondary buttons are as follows:

![](/assets/button_secondary.png)

**Regular state: **transparent with a 1px stroke using the muted text colour \(\#666666\), the text is also written using the muted colour. Border radius of 4px and padding of 15px.

![](/assets/button_secondary_hover.png)

**Hover state: **transparent with a 1px stroke using black, the text is displayed in black. Border radius of 4px and padding of 15px.

![](/assets/button_secondary_focus.png)

**Focus state: **transparent with a 3px stroke using black, the text is displayed in black. Border radius of 4px and padding of 15px.

**Active state: **_**\(to complete\)**_

![](/assets/button_secondary_disabled.png)

**Disabled state: **Fill colour of \#CECECE, with white text. Border radius of 5px and padding of 15px. 

### Position

Secondary buttons are usually in close proximity to the primary button, but not in a location where the user might mistake the two. Secondary buttons are usually placed to the right of the primary button\_. \_They should have a consistent placement relative to the primary button to avoid confusion.

## Drop-Down Buttons

Drop down buttons display a list of items when clicked. They are used for two-step processes that may require more specific options for a singular action.

![](/assets/button_drop down.png)

**Regular State: **Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height. 

![](/assets/button_drop down_hover_1.png)

![](/assets/button_drop down_hover_2.png)

**Hover States: **Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height. Whichever piece of the button \(primary or drop-down section\) is being hovered over is shown at 80% opacity. 

![](/assets/button_drop down_focus_1.png)

**Focus State: **Similar to the primary button, drop-down buttons use the primary colour at 100% opacity, white text, with a border radius of 4px and padding of 15px. The drop-down arrow represents a space of 30px by 40px, which is separated from the primary button using a white line. The arrow uses a space of 15px width and 8px in height. Whichever piece of the button \(primary or drop-down section\) is being focused on is shown at 80% opacity and includes a stroke of 3pts in the primary colour. 

![](/assets/button_drop down_pressed.png)

**Pressed State: **When the drop-down arrow is pressed, this arrow section of the button is displayed at 80% opacity and a drop-down menu is displayed below. The action box uses a 1pt border using \#CECECE. The box has a border radius of 4px. The width of the box is 166px, and the height depends on the number of actions, using 40px per action. 

Action text follows the 

## Split Buttons

Split buttons are more complex than drop-down buttons. Instead of referring to a singular action, a split button acts as two distinct buttons in one. A split button provides a default action, while the arrow on the right provides a drop-down list of alternate actions.

The default action represented in the split button is the most commonly used, while the actions presented in the drop-down are alternates that are used only occasionally.

One of the best examples of a split button is an email reply button. Reply is represented as the default, since it is the most common, while the drop-down menu will provide other options such as Reply to all, Forward, or Delete.

## Button Groups \(?\)

## Menu Buttons

\(hamburger icon\)

## Icon Buttons

_**\(to return to this when coding\)**_

i.e in WSIWYG editor, Like button, share button

Icon buttons or buttons with a dedicated shortcut \(i.e. Ctrl + S for Save\) should include a tooltip in the hover state.

## Ratings/Likes



