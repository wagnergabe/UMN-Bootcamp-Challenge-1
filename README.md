# Code Refactor Starter Code

-User Story-

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

-Acceptance Criteria-

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements


HTML has been reformatted and refactored to follow a more orderly, organized reading.  I gave each layer of the code its own section name, class, and ID tags. (such as header, content, hero, etc. ) and gave plenty of spacing in between each div. This action makes it easier to pinpoint specific elements and organize the structures for more efficient use of CSS components. 

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning


I refactored the major div tags to more appropriate labels. Not only did the main h1 header get its own "header" tag, but I was also able to incorporate a nav tag to better organize the code block. The same format was given to the footer. div tags are still in use for child child elements, but the main parent blocks have been relabeled to "section". This ultimately helped with creating id and class tags within CSS. 


WHEN I view the image elements
THEN I find accessible alt attributes

 
Added new alt attributes to all images and icons. Also moved the main hero image over from CSS so it can also have its own alt attribute. Refrained from using improper naming techniques such as "a picture of" or "an image depicting", and instead focused on potential buzz terms. This will give the site more opportunities for clicks and discoveries within internet searches  



WHEN I view the heading attributes
THEN they fall in sequential order


Heading attributes have been reorganized in CSS, as well as divided from big blocks or "chunks" of code.  In both HTML and CSS, I have starting tags to each individual section element, with additional headers depicting global codes. Each heading attribute in HTML is followed by an id and class, and closed out with the proper "/section" tag.  CSS has been organized better in reconsolidating multiple codes with the exact same values into singular coding declarations.  


WHEN I view the title element
THEN I find a concise, descriptive title

 
Title element has been renamed to the company's name with an additional brief description of their business.

Made records of all changes and recorded them in the source HTML and CSS files. Tested the page, clicked every link to ensure functionality. This was all done while monitoring the mockup given in the UMN bootcamp challenge page. 

One note about the mockup-

The "footer" is not presented in the mockup image, but it is provided in the original HTML index. Followed etiquette and provided the work for the footer just to be safe. 

