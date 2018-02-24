# Accessibility Interview Questions  

Use these questions as conversation starters. Learning how someone solves problems, and interprets accessible and inclusive user experiences is far better than learning if they can recite specifications or keyboard shortcuts.

Questions are grouped into three buckets: [General](#general), [Technical](#technical), and [Design](#design). These categories may be a mistake, but we're going with it for now. If you have better ideas for categories, and questions in general, please [let us know](https://github.com/scottaohara/accessibility_interview_questions/issues)! Ideally, a candidate would be able to answer questions from each category.


## General
- Who benefits from accessibility?
- How would you define inclusive and/or universal design?
    + Can you provide an example? (does not need to be web related)
- Name some ways responsive/mobile first design can affect accessibility.
- What are some user experience (UX) concerns to be aware of when using iconography in user interfaces (UI)?
- In what ways should someone be able to close a modal dialog?
- What are your thoughts on modifying the way screen readers announce certain content?
- What assistive technologies (ATs) are you familiar with (desktop + mobile)?
    + What do you feel is your skill level with these AT(s)?
- Describe what someone would use heading tags for.  
- What are skip links and who benefits from them?
- What are some of the tools available to test the accessibility of a website or web application?
- How can using plain language benefit the accessibility of a document?


## Technical
- Describe appropriate instances to use a link, vs a generic button, vs a submit button
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
- Describe ways to hide content:
    + From all users.
    + From only screen reader users.
    + From sighted users, but not screen reader users.
- When is the affect of `alt=""` on images?
- What is the difference between `aria-hidden="true"` and `role="presentation"`?
- When should you use `aria-live="assertive"` instead of `aria-live="polite"`?
- How would you mark-up an icon font or SVG that was for decorative purposes?
- What are some issues with using CSS pseudo content?
- Describe the steps you take in reviewing or auditing a website or application for accessibility?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you use or recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for figuring out if an accessibility bug is due to a developer, browser, or assistive technology error?
- Describe your thoughts on how a single page web app should handle focus when a new screen loads.
- Why shouldn't you only rely on visual styling to indicate state?
- What are some issues with carousels?


## Design
- Talk about the pros and cons of flat and [skeuomorphic design](http://whatis.techtarget.com/definition/skeuomorphism) trends in regards to accessibility.
- Explain the importance of color contrast.
- Besides `:hover`, name other states an actionable item (links, buttons, form controls, etc.) could have styles for, and why?
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
