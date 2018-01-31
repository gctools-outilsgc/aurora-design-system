# Research and Best Practices

## Typography

### Accessibility

Biggest considerations are size and colour. All text should be scalable. To ensure scalability, use relative units such as the em unit to control the typography — type size, margins and indents, leading — on the page

Most page layout applications set an optimum default leading of 120% of the type size

Avoid large text blocks. Break up long passages into smaller sections with meaningful subheadings.

[http://baymard.com/blog/line-length-readability](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit#)

#### Structural markup

Text formatting done using presentation-style markup instead of style sheets limits users' ability to transform a layout to meet their needs. Some browsers have a feature that allows users to override author-defined style sheets with their own style sheet. This means that users can define a custom style sheet that meets their viewing needs. For example, a low-vision user might define a style sheet that renders all`<P>`text at 24 points, or a colorblind user might set the background to white and the text to black for maximum contrast. But these measures will not work, or will only work partially, on pages that are formatted using presentation markup. If text color is set using`<FONT COLOR>`and headings are set using`<FONT SIZE>`and`<B>`for emphasis, the user-defined style sheet will have nothing to apply itself to \(no paragraph or heading tags\). If you set presentation properties using style sheets, users who \_need \_to customize the page can do so. [http://webstyleguide.com/wsg2/type/access.html](http://webstyleguide.com/wsg2/type/access.html)

#### **Text-rendering**

Use optimiseLegibility to enable kerning and improve rendering quality. This setting also enables ligatures, which you can disable if necessary by setting .classname { font-feature-settings: "liga" 0; } .

## Buttons

Buttons tend to have visual prominence on any given page or window. Primary buttons, or, buttons that indicate a _call to action_ have the most prominence.

Buttons are placed where a user should expect them, i.e. in close proximity to the other elements that the action affects.

This design system uses \(raised?\) buttons with \(rounded, square\) corners.

Icon buttons or buttons with a dedicated shortcut \(i.e. Ctrl + S for **Save**\) should include a tooltip in the hover state.

### Size and Padding

Buttons used in this design system have a minimum size of 10mm x 10 mm, since this is the typical size of a user's fingerpad when using the application on mobile. For web, this minimum size is also consistent.

The more white-space around a button, the more prominent the button is on the page.

### Labels

Button labels should be clear and specific. Avoid generic terms like **Save, Submit, **or **Cancel. **Buttons should indicate the exact action that is taken, and should provide a clear idea of what happens next.

Examples of good button labels: **Add a blog post, Send message, Back to menu**

All labels should capitalize only the first letter of the label.

Label text has high contrast with the button colour. See below for specific text colours for each type of button.

### Varying States

All buttons include a hover state, tap state and active \(pressed\) state.

Every action taken by the user will provide a user interface reaction \(colour/animation\)



## Colours

## Best Practices

_**\(to move to research section once complete\)**_

### Accessibility

Proper colour choice is necessary in order for your digital product to be accessible for people with visual impairments. Individual colours need to be visible \(well contrasted with their background\) for people with contrast sensitivity. Groupings of colours need to be distinguishable from each other for people with colour blindness.

