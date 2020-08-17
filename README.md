# usyd-bootcamp-homework-week1

Target: ## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title


---------------

WHAT I DID:

HTML:
1. changed the header class to the header tag
2. made the nav bar
3. changed to the section tag for the space with the image
4. changed from class to id for the seach engine optimization section, so the link works. Also changed from div to article tag to make it more semantic.
5. changed from div to article for the online reputation management and the social media marketing section for making it more semantic.
6. changed from div to aside tags for the class=benefit section.
7. changed from div to article for the 3 benefits.
8. changed from class=footer to making it a footer tag. 
9. added alt for all images.
10. made the title more descriptive and suitable for the content. 

css:
1. changed from header class to the header tag to match the styling.
2. align other styling with the header tags. 
3. made the class=seo to company-name-color-seo to make it more semantic.
4. align to the nav tag.
5. aligned to the .main-background class.
6. unified the three h2s CSS under single, .content-heading CSS and move it up to the logical order.
7. moved up #search-engine optimization stylings in the right place.
8. moved up #online-reputation-management stylings in the right place.
9. unified .benefit-lead, .benefit-brand and .benefit-cost under single CSS as they have all the styling - under the new .benefit-topic CSS.
10. unified the h3s and imgs under .benefit-topic under one CSS. they have the same styling.
11. aligned to the footer tag. 

