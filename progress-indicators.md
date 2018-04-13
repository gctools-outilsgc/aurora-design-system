# Progress Indicators

## Steps Indicator

Progress indicators are key for visibility of system status. They visually represent a path to completion of a particular task or process. Step indicators help the user identify how much of the process the user has completed, and how much is still left.

Step indicators are used for tasks that require multiple steps. To visually represent a page or element that is loading, use a spinner or progress bar rather than a steps indicator.

If a label is required for your step indicator, the label should be placed at the top of the element and left-aligned.

Colours for the step indicator can vary, but ensure that contrast requirements are met. Visit the [colour section](colour.md) for more information on choosing accessible colours.

Step indicators are styled as follows:

Each step is an individual circle with an outer circle of 44px using the colour \#CECECE. 

The inner circle is white \(\#FFFFFF\) and 34px. it is centred within the outer circle. The text is heading 2 style, Rubik Regular at 21 points.  The inner circle has a black \(\#000000\)drop shadow of 20% opacity, offset of 0 for x and y, and 4px blur. 

In between steps there is a centred line with a thickness of 3px. This line should be the same colour as the outer circle. 

![](.gitbook/assets/steps_empty.png)

In progress, completed steps use a coloured circle and line. The outer circle is filled with the colour \(\#FEC04F\) or the secondary colour of your choice. The line is also filled with this colour. 

![](.gitbook/assets/steps_active.png)

![](.gitbook/assets/steps_complete.png)

## Progress Bars

Progress bars are used to visually represent a page or feature that is loading or in progress. Progress bars show a percentage as well as the visual representation shown within the bar.

Progress bars show determinate levels of progress, meaning there is a clear point of completion. When the progress bar is filled and hits 100%, the application should complete the process.

Progress bars should always include a text indicator as well as the visual to provide more context. This text should be included in the &lt;alt&gt; tag.

Colours for the progress bar can vary, but ensure that contrast requirements are met. Visit the [colour section](colour.md) for more information on choosing accessible colours.

Progress bars can be filled with any colour you choose, but be sure to use text that meets minimum contrast requirements. For more information about accessible colours, visit the colour section. 

Progress bars are styled using a rectangle with 16px height and variable width. The rectangle has a 1px border coloured \#ADACAC, with a 4px border radius. 

Percentage can be either aligned to the right of the bar, or the percentage can be centred within the coloured portion of the bar. 

![](.gitbook/assets/progress-bars.png)

### Animation

Progress bars start empty and gradually fill with colour using an animation. The percentage shown should match the level of colour that fills the bar.

## Spinners

Spinners are used to indicate that a page or function is loading. A general rule is to use spinners for processes that take less than 4 seconds. Spinners show indeterminate levels of progress, meaning there is no clear completion and the animation loops until the process is complete.

The spinner used in this design system is displayed using the [spinner icon](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) from Font Awesome. Font Awesome provides [multiple icons](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) that may work well as a spinner, depending on your content. You can refer to [Font Awesome's documentation](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) to animate the spinner to demonstrate a loading page or function.

