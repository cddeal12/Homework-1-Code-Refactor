# Homework-1-Code-Refactor
    
    Included in this repository is an html file and a linked css file that contain an example layout for an example client's site. The original files were copied from a
    homework repository with the intention of editing the code inside to be more readable, accessible, and more properly structured. This editing project was completed
    by Caleb Deal with no outside contributions to the repository's contents.

# Readability
    Nearly every element in the html file was a <div> or contained inside a <div>. For readability the first step was to
    replace them all with semantic tags where possible. These tags included <nav>, <aside>, <main>, and <section>, and by
    the end each major portion of the document was much more clearly labelled by its tag. For a similar purpose, each major
    element was also commented on to make clear what each section of the document contained.

# Accessability
    The most obvious and important contribution to accessability on the page was the addition of alt text for each img element,
    where there was none before. This alone made the document far more accessible.

# Structure
    The major change to structure in this editing project was the consolidation of many redundant css selectors and classes of
    html elements. This greatly reduced the length of the stylesheet and would greatly help any future developers looking to
    make changes to the site's style. Where before they would ave had to consolidate or else manipulate many different classes
    now there are far more reasonable groups to accomplish the same thing in much less time.