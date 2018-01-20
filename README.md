# Accessibility Interview Questions  

Use these questions as conversation starters. Learning how someone solves problems, and interprets accessible and inclusive user experiences is far better than learning if they can recite specifications or keyboard shortcuts.

Questions are grouped into three buckets: [General](#general), [Technical](#technical), and [Design](#design). These categories may be a mistake, but we're going with it for now. If you have better ideas for categories and questions in general, please [let us know](https://github.com/scottaohara/accessibility_interview_questions/issues)! Ideally, a candidate would be able to answer questions from each category


## General
- Who benefits from accessibility?
- Name some ways responsive/mobile first design can benefit accessibility.
- What should someone be aware of when using iconography in place of text?
- In what ways should someone be able to close a modal dialog?
- When is it OK to change the way a screen reader announces content?
- What assistive technologies have you used for testing or daily use?
- Describe what heading elements are used for.


## Technical
- What methods would you use to find an element's accessible name?
- What is the accessibility tree?
- Why are rems or ems preferable to pixels for setting type size?
- Why is it important to allow the viewport to scale?
- When is it OK to use the `title` attribute?
    + How is `title` exposed to assistive technologies?
    + What is `title`'s primary <abbr title="User Experience">UX</abbr> issue?
- Describe a scenario where you might use `aria-describedby`.
- What are landmark roles and how can they be useful?
- When might you use a toggle button, such as a `button` utilizing `aria-pressed` and/or `role="switch"` over a checkbox?
- Describe ways to hide content:
    + From all users.
    + From only assistive screen reader users.
    + From sighted users, but not screen reader users.
- When is it OK to set `alt=""` on images?
- What is the difference between `aria-hidden` and `role="presentation"`?
- When should you use `aria-live="assertive"` instead of `aria-live="polite"`
- Describe instances where you might use an icon font.
    + When or why would you use an SVG instead?
    + How would you mark-up an icon font or SVG that was for decorative purposes?
- What are some issues with using CSS pseudo content.
- What are skip links and who benefits from them?
- What are some of the tools available to test the accessibility of a website or web application?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you use or recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for figuring out if an accessibility bug is due to a developer, browser, or assistive technology error?
- Describe how a single page web app should handle focus when a person loads a new screen.
- What other states can be set to a selector besides `:hover`?
- Why shouldn't you only rely on visual styling to indicate state.
- What are some issues with carousels?


## Design
- Talk about the pros and cons of flat and skeuomorphic design trends in regards to accessibility.
- Explain the importance of color contrast.
- When is it OK to remove default visual focus indicators?
- Describe appropriate error messaging locations for invalid form fields.
- Why should you be careful when using animation in UIs?
- Explain how you would make an infographic accessible for screen reader users.
- What are some issues with modifying normal scrolling behavior. For example: infinite scrolling or scrolljacking?
- Why is color alone insufficient to draw attention to actionable elements, or to convey state?
- Talk about the importance of using plain language.


## Have a question to add?
[Create an issue](https://github.com/scottaohara/accessibility_interview_questions/issues), or [submit a pull request](https://github.com/scottaohara/accessibility_interview_questions/pulls) for consideration.

