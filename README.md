# FSF_Week-1_Code-Refactor
Full Stack Flex Bootcamp homework: Week 1

Assignment required refactoring of an existing website's source code to make it neater, more accessible and run more efficiently.

Changes made are as follows:

HTML
-  Spaced out each of the html elements to make them easier to read/identify. Reorganised code to remove need to scroll across to read
- Added the 'Title' tag to the 'hero' <div> to add a text alternative for main image. Image is sourced through CSS so 'alt' tag will not work
- For consistency, added title tags (and alt tags) for all images on the page
- New class (content-att) as content items share same css attributes
- New class (benefit-att) as benefit lead, brand and cost have same css attributes

CSS:
- Removed 'header' from elements that were identified sufficiently using IDs 
- Reclassed content html elements as they have common css attributes 
- Rearranged CSS to match structure of HTML
- Benefit lead brand and cost all have same attributes for each elements. Simplified by placing all attributes under a common class
