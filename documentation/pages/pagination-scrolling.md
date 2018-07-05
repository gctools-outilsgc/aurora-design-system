# Pagination/Scrolling

There are two ways to present content on a page: scrolling and pagination. Each has benefits and disadvantages, and you should pick the one which matches the type and context of the content you are presenting.

## Scrolling

Scrolling presents content on a single page, which the user proceeds through by moving up and down the page. Scrolling is best used when the content is a single and continuous piece, for example an article or tutorial. Scrolling also works well for content streams. You should choose to use scrolling when the information is closely related and has the same level of detail. It is easier for the user to scan the entire piece of content by scrolling rather than making them click to continue viewing the content. 

You should organize the page structure so that the most important information appears at the top; a brief description of the content at the beginning of the page gives the user an idea of what will appear further down, and gives them a reason to scroll.

## Pagination

Pagination splits content into multiple discrete pages. It is best used when the user is trying to accomplish a goal, for instance trying to find a particular article from a list. Breaking the content list into multiple pages stops the user from feeling overwhelmed. A user can see the size of the data set, so they know how much more content there is to investigate. Pagination also allows the user to feel more in control of the content they are viewing as they can decide whether or not to click to the next page. Every click should lead the user closer to achieving their goal.

Pagination is styled as follows: 

Secondary button on the left with the copy "Prev." With numbers in the middle and another secondary button on the right with the copy "Next"

The numbers are displayed with Nunito Sans Bold at 14px. Each number has padding of 10px. 

The active page number is shown in a rectangle with a padding of 10px, with a border radius of 4px. The box is displayed using the same colour as primary buttons #002D42, and the number uses white text. 

*Pagination component*

### Best Practices

Through pagination, a user should be able understand the amount of content there is; you should include a link to the last page of the content in the pagination bar, unless the data set fluctuates in size. Also include a link to the first page on every page. 

Each page should contain the same amount of objects, you may want to include an option for the user to change how many objects are shown on each page. Depending on the type of content, you may want to allow users to filter and organize which page the objects appear on.

The user should be able to clearly tell which page they are currently on. Place this number in the middle of the pagination bar and give it the heaviest visual weight. The user should also be able to see what content page they have already viewed so they do not have to revisit content that they have already seen. You can show this by changing the colour, typically a secondary colour, of already visited pages versus pages the user has yet to visit. 



