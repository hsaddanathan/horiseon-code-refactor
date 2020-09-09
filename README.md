# horiseon-code-refactor

## Summary

The Horiseon Website that was shared with our class displayed elements that would not be considered semantic elements. Replacing these elements allows for people and machines to read and understand the code thoroughly. 

In addition, when parsing through the code, Alt tags were not included on images. This presents a problem with regards to SEO and, more importantly, accessibility. Companies must be vigilant with ensuring that Digital Assets have Alt Tags to explain what the Asset is depicting, because there are many users who use screen readers.

With regards to classes assigned to different elements, there was a lot of redundancy with the classification of elements. I was able to consolidate classes, which in turn, cleaned up the amount of CSS needed.

## Screenshots
![Home Page update] (/assets/images/Home-Page-Part-1)






## Links

horiseon-code-refactor repository link: 
    https://github.com/hsaddanathan/horiseon-code-refactor.git

Github Deployed Site URL:
    https://hsaddanathan.github.io/horiseon-code-refactor/


## index.html Changes

Lines (11-26) - Changed Div to Header tag. 
Lines (13-25) - Changed Div to Nav tag.

Line 27 - Added Dev Note; Changed Div to Section tag.

Lines (28-50)- Changed Div to Section tag.
Lines (29-35)(36-42)(43-49) - Changed Div to Section tag.Consolidated each class of subsections into one class. This change was made, because when referencing the CSS, each class of subsection had the same formatting and styling.
Lines 30, 37, 44 - Added Alt tags to images for SEO and Accessibility.
Lines 31, 38, 45 - Added a class to the H2 elements in order to clean up and consolidate CSS.

Lines (51-73) - Changed Div to Aside tag and removed class "benefits"
Lines (52-58)(59-65)(66-72) - Changed Div to Section tag. Consolidated each class of subsections into one class. This change was made, because when referencing the CSS, each class of subsection had the same formatting and styling.
Lines 53, 60, 67 - Added one class for all three H3 tags so they could be formatted singularly on CSS.
Lines 54, 61, 68 - Added Alt tags to images for SEO and Accessibility. Added a class to the IMG elements in order to clean up and consolidate CSS.
 
Lines (74-79) - Changed Div to Footer tag. 


## style.css Changes

Line 11 - When I changed the Div tag to a header tag, I was able to delete the "header" class. So I changed this to the header element.
Line 18 - Removed .header class and just targeted H1 Element
Line 23 - Removed .header class and targeted .seo class
Line 27 - Changed Div to Nav tag in html. So targeted Nav element
Lines 28, 39 - Targeted ul and li element as it was the only Unordered list on the page
Lines 62 and 67 - since both floats are referencing the image, I was able to take the max heights from lines 165, 169, 173. I was able then able to delete the lines 164-174.
Lines 78 - Removed the benefits class selector and changed it the the Aside Element
Lines (89-102) - All referenced each of the 3 benefits highlighted in the new Aside element. That means we would want to keep the same formatting for each of those sections. So I changed the class names for each of the three benefits. I identified them the ".benefit" class. Once, I did this I was able to consolidate the 3 declarations. 
Lines (104-117) - Much like the step above, I changed the class each of the h3 elements for the benefits. I assigned the ".benefit-header" class. Once, I did this I was able to consolidate the 3 declarations.
Lines (119-135) - Much like the step above, I changed the class each of the h3 elements for the benefits. I assigned the ".benefit-img" class. Once, I did this I was able to consolidate the 3 declarations.
Lines (137-189) - References the Content Section. 
    -Each of the 3 classes referenced here represent each of the services Horiseon provides. I changed each class to the ".content-services" class. 
    -For the images for these sections, they were already classified under ".float-left" and ".float-right", so I moved the height styling to the float classes.
    -For the H2 elements, I reclassified as ".services-header" 
Lines 191, 198 - Removed the ".footer" class once I used the footer tag. Changed ".footer" to "footer"

I reordered CSS declarations based on the the flow of the website. 
    -Header/Nav Bar
    -Background Hero Image
    -Content Section
    -Benefits Aside
    -Footer
 

 