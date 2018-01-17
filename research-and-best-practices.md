# Research and Best Practices

## Typography

### Accessibility

Biggest considerations are size and colour. All text should be scalable. To ensure scalability, use relative units such as the em unit to control the typography — type size, margins and indents, leading — on the page

Most page layout applications set an optimum default leading of 120% of the type size

Avoid large text blocks. Break up long passages into smaller sections with meaningful subheadings.

#### Structural markup

Text formatting done using presentation-style markup instead of style sheets limits users' ability to transform a layout to meet their needs. Some browsers have a feature that allows users to override author-defined style sheets with their own style sheet. This means that users can define a custom style sheet that meets their viewing needs. For example, a low-vision user might define a style sheet that renders all`<P>`text at 24 points, or a colorblind user might set the background to white and the text to black for maximum contrast. But these measures will not work, or will only work partially, on pages that are formatted using presentation markup. If text color is set using`<FONT COLOR>`and headings are set using`<FONT SIZE>`and`<B>`for emphasis, the user-defined style sheet will have nothing to apply itself to \(no paragraph or heading tags\). If you set presentation properties using style sheets, users who \_need \_to customize the page can do so. [http://webstyleguide.com/wsg2/type/access.html](http://webstyleguide.com/wsg2/type/access.html)

#### **Text-rendering**

Use optimiseLegibility to enable kerning and improve rendering quality. This setting also enables ligatures, which you can disable if necessary by setting .classname { font-feature-settings: "liga" 0; } .

