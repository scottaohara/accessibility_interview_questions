# Accessibility Interview Questions  

Ideas for questions to ask someone that wants you to give them a job... or queries to enter into your search engine of choice to maybe learn a thing or two.  

The questions are grouped into three buckets: General, Technical, and Design. This may be a mistake, but we're going with it for now. Regardless of the role you are looking to fill, ideally a candidate should be able to answer some questions, or version of questions, from each category.  


## General
- Who benefits from accessible user interfaces?
- Name some ways in which responsive/mobile first design can benefit accessibility.
- Talk about the pros and cons of using iconography.
- Why are rems or ems preferable to pixels for setting type size?
- In what ways should a user be able to close a modal dialog?
- What is/are the primary guideline(s) used to measure accessibility compliance?
- When is it appropriate to alter the way a screen reader announces content?
- Name some assistive technologies you can think of. (these should be more than just screen readers)
- What are the four categories of WCAG compliance?


## Technical
- Talk about some of the different tools or methods available to determine the accessible name of an element.  
- When is it appropriate to use the `title` attribute?
    + In what manner is it exposed to assistive technologies?
    + What accessibility UX challenges does it pose?
- What are landmarks?
    + How are `banner` and `contentinfo` landmarks natively determined by browsers?
    + Why do some people confuse `article` as a landmark?
    + How many `main` elements can be used in a single document?
- When is it appropriate to use a toggle button, e.g. a `button` utilizing `aria-pressed` and/or `role="switch"` over a checkbox?
- Describe an appropriate way to hide content to only sighted users.
    + How would one hide content from all users?
    + How would one hide content from all users, but still utilize that content to provide instructions to an assistive technology user?
- When is it appropriate to set `alt=""`?
- What is the difference between `aria-hidden` and `role="presentation"`?
- If given the opportunity to use icon fonts or SVGs, which one would you use and why?
- What are some of the tools available to test the accessibility of a website/application?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should one recommend ARIA roles or attributes to solve an accessibility issue?
- Describe your process for verifying if an accessibility bug is developer, browser, or assistive technology specific?
- When is it appropriate to use table elements? 
- In most cases, why is it important to not solely rely on CSS to indicate state.


## Design
- Talk about the pros and cons of flat and skeuomorphic design trends in regards to accessibility.
- Why is color alone insufficient to connote an actionable element, or to convey state?
- Where is the optimal location to place a form validation error message?  What about an error message for an individual form field?


