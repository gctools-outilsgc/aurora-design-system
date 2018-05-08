# Pagination/Scrolling

There are two ways to present content on a page: scrolling and pagination. Each has benefits and disadvantages, and you should pick the one which matches the type and context of the content you are presenting.

## Scrolling

Scrolling presents content on a single page, which the user proceeds through by moving up and down the page. Scrolling is best used when the content is a single and continuous piece, for example an article or tutorial. Scrolling also works well for content streams. You should choose to use scrolling when the information is closely related and has the same level of **granularity \(plainer word?\).** It is easier for the user to scan the entire piece of content by scrolling rather than making them click to continue viewing the content. 

You should organize the page structure so that the most important information appears at the top; a brief description of the content at the beginning of the page gives the user an idea of what will appear further down, and gives them a reason to scroll.

## Pagination

Pagination splits content into multiple discrete pages. It is best used when the user is trying to accomplish a goal, for instance trying to find a particular article from a list. Breaking the content list into multiple pages stops the user from feeling overwhelmed. A user can see the size of the data set, so they know how much more content there is to investigate. Pagination also allows the user to feel more in control of the content they are viewing as they can decide whether or not to click to the next page.

### Best Practices

Through pagination, a user should be able understand the amount of content there is; you should show the last page of the content in the pagination bar. The user should also be able to see what content they have already viewed so they do not have to revisit content that they have already seen. You can show this by changing the colour of already visited pages versus pages the user has yet to visit.  

Web users don’t mind clicking links \(e.g., a link to the next page\) if each click is meaningful and leads them closer to the desired goal.



1.	Begin by dividing the overall dataset into smaller groups of items. Having an equal number of items on each of these individual pages is best. Decide upon an appropriate number of items to display on a page as a ‘default’, striking a good balance between content, legibility, and ease of navigation. \(That said, some problems can arise, and we’ll cover these in full later on here.\)



2.	Determine how much control the user should have over the way the items are grouped or ordered, or the number of items displayed on one page. As in the example below, web shops often let users choose if they want to sort the search results by date, price, popularity, or by recommendations. Sometimes, allowing the user to set the number of items on each page might be advantageous. For example, the default number might be 10, but what if the users wish to view more per page? These users do not want to have to keep switching between different sets of items. Therefore, a small dropdown menu of items per page—or controls that perform the same function—could be a useful addition to pagination.



3.	Add pagination controls to allow the user to move forwards and backwards through the different pages, such as east- and west-facing arrows. Provide links or other controls that enable the user to skip straight to the beginning or end of the dataset, or to specific pages in the set. These are usually the first and last numbers or double greater and less than symbols \(i.e., &lt;&lt; and &gt;&gt;\), such as are found on remote controls for rewind and fast forward. However, when your dataset fluctuates in size, you are better off not including a link to the last page. By allowing skipping to a specific page, you can provide either an option for the user to enter a page number manually—or select a page number—or you can add controls for skipping a given number of pages. As the user moves through the different pages, the numbers in the pagination pattern should change accordingly. For example, if the user is on the fiftieth page, then the succeeding page numbers \(51, 52, 53...\) should be available in the set of links in the pagination pattern.



![](.gitbook/assets/asset-1-2x.png)



