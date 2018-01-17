# Accessibility Interview Questions  

Ideas for questions to ask someone that wants you to give them a job… or queries to enter into your search engine of choice to maybe learn a thing or two.  

The questions are grouped into three buckets: [General](#general), [Technical](#technical), and [Design](#design). This may be a mistake, but we're going with it for now. 

Accessibility is a holistic practice. Ideally, a candidate should be able to answer some of these questions from each category, regardless of the role you are looking to fill.

These questions have answers, but it's not intended to be a graded quiz. Use the prompts as a jumping off point to discuss the how and the why, to better determine how the applicant understands and thinks about these issues.


## General
- Who benefits from accessible user interfaces?
- Name some ways in which responsive/mobile first design can benefit accessibility.
- Talk about the pros and cons of using iconography.
- Why are rems or ems preferable to pixels for setting type size?
- In what ways should a user be able to close a modal dialog?
- What is/are the primary guideline(s) used to measure accessibility compliance?
- When is it appropriate to alter the way a screen reader announces content?
- Name some assistive technologies you can think of. (these should be more than just screen readers)
- What are the four categories of <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> compliance?


## Technical
- Talk about some of the different tools or methods available to determine the accessible name of an element.  
- What is the accessibility tree?
- Describe what heading elements are used for.
- Why is it important to allow the viewport to scale?
- When is it appropriate to use the `title` attribute?
    + In what manner is it exposed to assistive technologies?
    + What accessibility <abbr title="User Experience">UX</abbr> challenges does it pose?
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
- When should you use `aria-live="assertive"` instead of `aria-live="polite"`?
- If given the opportunity to use icon fonts or <abbr title="Scalable Vector Graphics">SVGs</abbr>, which one would you use and why?
- Name some issues with using pseudo content.
- What’s the first rule of <abbr title="Accessible Rich Internet Applications">ARIA</abbr>?
- What is the <abbr title="World Wide Web Consortium">W3C</abbr>?
- What is a skip link and why is it important?
- How do you make <abbr>SVG</abbr> accessible?
- What are some of the tools available to test the accessibility of a website/application?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should one recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for verifying if an accessibility bug is developer, browser, or assistive technology specific?
- Describe how a single page web app should manage focus when a user loads a new screen.
- When is it appropriate to use table elements? 
- What other states can be applied to a selector besides `:hover`?
- How does performance affect accessibility?
- In most cases, why is it important to not solely rely on <abbr title="Cascading Style Sheets">CSS</abbr> to indicate state.


## Design
- Talk about the pros and cons of flat and skeuomorphic design trends in regards to accessibility.
- Explain the importance of color contrast.
- When is it appropriate to remove focus with <abbr>CSS</abbr>?
- Explain how the Gestalt Law of Proximity applies to error messaging.
- When is it appropriate to use animation?
- Explain how you would make an infographic accessible to someone who cannot see.
- How can typography help people with Dyslexia?
- Why can carousels be problematic?
- Why should links be underlined?
- What are some issues with infinite scrolling?
- What are some issues with scrolljacking?
- What are some issues with hollow buttons?
- What are the advantages and disadvantages of voice <abbr>UI</abbr>?
- How does whitespace help accessibility? How can it hinder it?
- What makes a good loading screen?
- Why is color alone insufficient to connote an actionable element, or to convey state?
- Where is the optimal location to place a form validation error message? What about an error message for an individual form field?
- Describe the importance of good copywriting for a user interface.

## Have a question to add?
[Submit a Pull Request](https://github.com/scottaohara/accessibility_interview_questions/pulls) for consideration.

