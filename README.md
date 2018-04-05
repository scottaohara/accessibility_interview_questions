# Accessibility Interview Questions  
These questions try to stay away from directly asking candidates to recite specifications, or rattle off screen reader hot keys. Those can easily be looked up on the job. Instead these questions try to act as conversation starters, to gain insight into how someone solves problems, and interprets accessible, inclusive user experiences.

Questions are grouped into three buckets: [General](#general), [Technical](#technical), and [Design](#design). These categories may be a mistake, but we're going with it for now. If you have better ideas for categories, and questions in general, please [let us know](https://github.com/scottaohara/accessibility_interview_questions/issues)! Ideally, a candidate would be able to answer questions from each category.


## General
- Who benefits from accessibility?
- How would you define inclusive and/or universal design?
    + Can you provide an example? (does not need to be web related)
- Name some ways responsive/mobile first design can affect accessibility.
- What are some user experience (UX) concerns to be aware of when using iconography in user interfaces (UI)?
- What assistive technologies (ATs) are you familiar with (desktop + mobile)?
    + What do you feel is your skill level with these AT(s)?
- Describe the purpose of heading and header elements, and how you might use them in a website or application.  
- What are skip links?
    + How can users benefit from them? 
    + What are some of their limitations?
- What are some of the tools available to test the accessibility of a website or web application?
- How can using plain language benefit the accessibility of a document?
- Describe appropriate instances to use a link, vs a generic button, vs a submit button.
- Describe ways to indicate an element or component's state that aren't entirely reliant on visuals.
- How can carousels be problematic for users with disabilities?
- What are some design considerations for supporting text resize/zoom on web? Mobile apps?
- In what ways can the CSS `display` property affect the accessibility of a document?
- What is the difference between `legend` and a `label` elements?
- What effect does no `alt` attribute, or an `alt` attribute with an empty string have on an image? 
    + Can you describe instances where no `alt`, and an empty `alt` would each be appropriate?


## Technical
- What methods would you use to find an element's accessible name?
- What is the accessibility tree?
- Why are rems or ems preferable to pixels for setting type size?
- Why is it important to allow the viewport to scale?
- How is `title` attribute exposed to assistive technologies?
    + What kind of content should `title`s be used on.
    + What sort of information is appropriate for use in a `title`?
- Describe a scenario where you might use `aria-describedby`.
- What are landmark roles and how can they be useful?
- When might you use a toggle button, such as a `button` utilizing `aria-pressed` and/or `role="switch"` over a checkbox?
- Describe methods to hide content:
    + From all users.
    + From only screen reader users.
    + From sighted users, but not screen reader users.
    + And why you might do so.
- Is it possible to overuse ARIA in a website?  Explain why or why not.
- What is the difference between `aria-hidden="true"` and `role="presentation"` or `role="none"`?
- When should you use `aria-live="assertive"` instead of `aria-live="polite"`?
- How would you mark-up an icon font or SVG that was for decorative purposes?
- What are some issues with using CSS pseudo content?
- Describe the steps you take in reviewing or auditing a website or application for accessibility?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you use or recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for figuring out if an accessibility bug is due to a developer, browser, or assistive technology error?
- Describe your thoughts on how a single page web app should handle focus when a new screen loads.
- Name an ARIA attribute that requires either a child/parent relationship or a pairing role.
- What is your understanding of "accessible name computation" and how it affects modifying the way screen readers announce certain content?


## Design
- Talk about the pros and cons of flat and [skeuomorphic design](http://whatis.techtarget.com/definition/skeuomorphism) trends in regards to accessibility.
- Explain the importance of color contrast.
- Besides `:hover`, name other states an actionable element (links, buttons, form controls, etc.) could have styles for, and why providing them is important?
- What are your thoughts on the removal of visual focus indicators for UI elements?
- If a form or form field were to return an error message, where might you want those error messages to be located?
- How can utilizing animation in an interface affect the user experience?
- Explain how you would make an infographic accessible for screen reader users.
- What are some issues with modifying normal scrolling behavior? For example: infinite scrolling or scrolljacking.
- Why is color alone insufficient to draw attention to actionable elements, or to convey state?


## Have a question to add?
[Create an issue](https://github.com/scottaohara/accessibility_interview_questions/issues), or [submit a pull request](https://github.com/scottaohara/accessibility_interview_questions/pulls) for consideration.


## Thank you
Thank you to [all contributors](https://github.com/scottaohara/accessibility_interview_questions/graphs/contributors).  
Special shoutout to [Eric Bailey](https://github.com/ericwbailey) and [Ashley Bischoff](https://github.com/handcoding) for many contributions not recorded by GitHub.
