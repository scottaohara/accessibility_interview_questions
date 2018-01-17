# Accessibility Interview Questions  

Accessibility is a holistic practice. Ideally, a candidate should be able to answer some questions from each category, regardless of the role you are looking to fill.

Use these questions as jumping off points to discuss hows and whys. Learning how someone solves problems is far better than learning if they can recite specifications off the top of their head.

These questions are grouped into three buckets: [General](#general), [Technical](#technical), and [Design](#design). This may be a mistake, but we're going with it for now. Revise questions as needed per situation.


## General
- Who benefits from accessibility?
- Name some ways responsive/mobile first design can benefit accessibility.
- Talk about the pros and cons of using iconography.
- Why are rems or ems preferable to pixels for setting type size?
- In what ways should someone be able to close a modal dialog?
- What guidelines are available to measure accessibility compliance?
- What are the downsides of using text that only screen readers can access?
- When is it OK to change the way a screen reader announces content?
- Name some assistive technologies you can think of. (these should be more than just screen readers)
- What are the four categories of <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> compliance?


## Technical
- Talk about some of the different tools or methods available to determine the accessible name of an element.  
- What is the accessibility tree?
- Describe what heading elements are used for.
- Why is it important to allow the viewport to scale?
- When is it OK to use the `title` attribute?
    + How is `title` exposed to assistive technologies?
    + What is `title`'s primary <abbr title="User Experience">UX</abbr> issue?
- What are landmarks?
    + How do browsers determine the `banner` and `contentinfo` landmarks of a document?
    + Why might someone confuse `article` as a landmark?
    + How many `main` elements can be used in a single document?
- When is it OK to use a toggle button, such as a `button` utilizing `aria-pressed` and/or `role="switch"` over a checkbox?
- Describe a way to hide content to only sighted users.
    + How would you hide content from all users?
    + What method would you use to hide content from all users, but also use that content as instructions to an assistive technology user?
- When is it OK to set `alt=""` on images?
- What is the difference between `aria-hidden` and `role="presentation"`?
- When should you use `aria-live="assertive"` instead of `aria-live="pol
- Describe instances where you might use an icon font.
    + When or why might SVGs be better to use?
    + How would you mark-up an icon font or SVG that was for decorative purposes?
- What are some issues with using CSS pseudo content.
- What’s the first rule of <abbr title="Accessible Rich Internet Applications">ARIA</abbr>?
- What is the <abbr title="World Wide Web Consortium">W3C</abbr>?
- What is a skip link and why is it important?
- How do you make <abbr>SVG</abbr>s accessible?
- What are some of the tools available to test the accessibility of a website or web application?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for determining if an accessibility bug is due to a developer, browser, or assistive technology error?
- Describe how a single page web app should manage focus when a person loads a new screen.
- When is it OK to use table elements? 
- What other states can be set to a selector besides `:hover`?
- How does performance affect accessibility?
- In most cases, why is it important to not solely rely on <abbr title="Cascading Style Sheets">CSS</abbr> to indicate state.


## Design
- Talk about the pros and cons of flat and skeuomorphic design trends in regards to accessibility.
- Explain the importance of color contrast.
- When is it OK to remove focus with <abbr>CSS</abbr>?
- Explain how the Gestalt Law of Proximity applies to error messaging.
- When is it OK to use animation?
- Explain how you would make an infographic accessible to someone who can't see.
- How can typography help people with Dyslexia?
- Why should links be underlined?
- What are some issues with carousels?
- What are some issues with infinite scrolling?
- What are some issues with scrolljacking?
- What are some issues with hollow buttons?
- What are the advantages and disadvantages of voice <abbr>UI</abbr>?
- How can whitespace help accessibility? How can it hinder it?
- What makes for a good loading screen?
- Why is color alone insufficient to draw attention to actionable elements, or to convey state?
- Where is the optimal location to place a form validation error message? What about an error message for an individual form field?
- Talk about the importance of good copywriting for a user interface.


## Have a question to add?
[Create an issue](https://github.com/scottaohara/accessibility_interview_questions/issues), or [submit a pull request](https://github.com/scottaohara/accessibility_interview_questions/pulls) for consideration.

