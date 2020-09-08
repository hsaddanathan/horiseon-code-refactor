# horiseon-code-refactor

## Summary

The Horiseon Website that was shared with our class displayed elements that would not be considered semantic elements. Replacing these elements allows for people and machines to read and understand the code thoroughly. 

In addition, when parsing through the code, Alt tags were not included on images. This presents a problem with regards to SEO and, more importantly, accessibility. Companies must be vigilant with ensuring that Digital Assets have Alt Tags to explain what the Asset is depicting, because there are many users who use screen readers.

With regards to classes assigned to different elements, there was a lot of redundancy with the classification of elements. I was able to consolidate classes, which in turn, cleaned up the amount of CSS needed.

## index.html Changes

```
Lines (11-26) - Changed Div to Header tag. 
Lines (13-25) - Changed Div to Nav tag.

Line 27 - Added Dev Note; Changed Div to Section tag.

Lines (28-50)- Inserted Dev Note; Changed Div to Section tag.
Lines (29-35)(36-42)(43-49) - Changed Div to Section tag.CConsolidated each class of subsections into one class. This change was made, because when referencing the CSS, each class of subsection had the same formatting and styling.
Lines 30, 37, 44 - Added Alt tags to images for SEO and Accessibility.
Lines 31, 38, 45 - Added a class to the H2 elements in order to clean up and consolidate CSS.

Lines (51-73) - Changed Div to Aside tag and removed class "benefits"
Lines (52-58)(59-65)(66-72) - Changed Div to Section tag. Consolidated each class of subsections into one class. This change was made, because when referencing the CSS, each class of subsection had the same formatting and styling.
Lines 53, 60, 67 - Added one class for all three H3 tags so they could be formatted singularly on CSS.
Lines 54, 61, 68 - Added Alt tags to images for SEO and Accessibility. Added a class to the IMG elements in order to clean up and consolidate CSS.
 
 Lines (74-79) - Changed Div to Footer tag. 

 ## style.css Changes



 