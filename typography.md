# Typography

## Best Practices

### Accessibility

Biggest considerations are size and colour. All text should be scalable. To ensure scalability, use relative units such as the em unit to control the typography — type size, margins and indents, leading — on the page

 Most page layout applications set an optimum default leading of 120% of the type size

 Avoid large text blocks. Break up long passages into smaller sections with meaningful subheadings.

#### Structural markup

Text formatting done using presentation-style markup instead of style sheets limits users' ability to transform a layout to meet their needs. Some browsers have a feature that allows users to override author-defined style sheets with their own style sheet. This means that users can define a custom style sheet that meets their viewing needs. For example, a low-vision user might define a style sheet that renders all`<P>`text at 24 points, or a colorblind user might set the background to white and the text to black for maximum contrast. But these measures will not work, or will only work partially, on pages that are formatted using presentation markup. If text color is set using`<FONT COLOR>`and headings are set using`<FONT SIZE>`and`<B>`for emphasis, the user-defined style sheet will have nothing to apply itself to \(no paragraph or heading tags\). If you set presentation properties using style sheets, users who _need _to customize the page can do so. http://webstyleguide.com/wsg2/type/access.html

#### Font Choice

Both fonts enhance accessibility and readability. Since sans-serif fonts have a simpler structure, users with reading disabilities or visual impairments are able to easily decipher characters. If you choose to use fonts other than the ones listed here, it is recommended that your digital product use sans-serif rather than serif or script fonts. 

#### **Text-rendering**

Use optimiseLegibility to enable kerning and improve rendering quality. This setting also enables ligatures, which you can disable if necessary by setting .classname { font-feature-settings: "liga" 0; } .

## Fonts

The Digital Collaboration Division uses two font families for all digital products. Both Montserrat and Muli are Open Source fonts which can be downloaded from Google Fonts for free.

Montserrat is used mainly for titles and headings, while Muli is used for sub-headings, buttons and paragraph text.

Unless otherwise indicated, all text types are displayed using pure black.

### About the Typefaces

**Montserrat** was designed by Julieta Ulanovsky and other collaborators. Through this font, Ulanovsky wanted to capture the traditional style found on signs and posters in the Montserrat neighbourhood of Buenos Aires, Argentina. The font was first developed in 2011 as a Kickstarter project and a full set  of weights and italics were developed in 2015. Montserrat works well as both a display font and a paragraph font and has been featured in over 4.3 million websites to date.

**Muli** is a minimalist sans-serif web font designed by Vernon Adams. Built primarily as a display font., Muli also works well for body text and has been used in over 500,000 websites. It was developed using an open source liscense and is particularly poplar in the United States.

## Titles

Titles appear only on the tops of pages, and indicate high-level navigation points. Titles are displayed using Montserrat Light at 36 points.

## Headings

Including titles. there are six different heading types. H1 - H6. The headers use the following typographic styles:

Heading 1 \(Title\): Monteserrat Light at 36 points, with kerning/tracking modifier of -25.

Heading 2: Montserrat Light at 24 points.

Heading 3: Muli Semi-Bold at 18 points.

Heading 4: Muli at 16 points.

Heading 5: Muli Semi-Bold at 11 points. Uppercase text.

Heading 6: Muli Semi-Bold at 11 points. Sentence case.

## Paragraph Text

Paragraph text is used for most text content found on the application. Paragraph text is set to Muli Regular at 12 points, with a leading of 21 points. Unless indicating a hyperlink or navigation, paragraph text should not have added emphasis.

### Line-Breaking

The DCD design system, is consistent with the following best practices for line-breaks:

* Avoid hyphenation at the end of a line.

* Avoid leaving gaps or orphans hanging on a line.

* Avoid overly large indentation.

### Line Length

The ideal length for body text is around 40-60 characters. If line length is too short or too long, it has a negative impact on readability. Our design system follows these guidelines and aims for approximately 60 characters per line.

Source: “Readability: the Optimal Line Length,”

[http://baymard.com/blog/line-length-readability](http://baymard.com/blog/line-length-readability)

### Links

Link text is used within paragraphs to indicate hyperlinks and navigation. Links use the typographic style of Muli Regular, bolded at 12 points. It is recommended that the link text be underlined and displayed in a secondary colour used in the application.

### Emphasis

For accessibility purposes, colour cannot be the sole source of emphasis. Be sure to add emphasis to text by making the font bold and increasing contrast as well. 

 typographic formatting such as italics or underlining should be used sparingly and only when they genuinely enhance communication with all readers.

### Timestamps and Placeholder Text

Timestamps and placeholder text use the same typographic styles. Both use Muli Light at 10 points with a tracking modifier of 50. Timestamps and placeholder text uses a lighter font colour with a hex code of \# 808285

### Captions

### Colour and Contrast



