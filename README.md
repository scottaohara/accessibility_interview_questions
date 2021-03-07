# Accessibility Interview Questions
These questions try to stay away from asking people to recite specifications, or rattle off screen reader hot keys. Those can easily be looked up on the job. Instead these questions try to act as conversation starters, to gain insight into how someone solves problems, and interprets accessible, inclusive user experiences.

Questions are grouped into four buckets:

1. [General](#general),
2. [Technical](#technical),
3. [Design](#design), and
4. [Content](#content)

These categories may be a mistake, but we're going with it for now. If you have ideas for categories, and questions in general, please [let us know](https://github.com/scottaohara/accessibility_interview_questions/issues)! Ideally a candidate would be able to answer questions from each category.


## General
- Who benefits from accessibility?
- How would you define inclusive and/or universal design?
    + Can you provide an example? (does not need to be web related)
- How has your approach to accessibility changed over time?
- Name some ways responsive/mobile first design can affect accessibility.
- What are some user experience (UX) concerns to be aware of when using iconography in user interfaces (UI)?
- What assistive technologies (ATs) are you familiar with (desktop + mobile)?
    + What do you feel is your skill level with these AT(s)?
- What are skip links?
    + What benefit(s) do they provide?
    + What are some of their limitations?
- What are some of the tools available to test the accessibility of a website or web application?
- What is WCAG?
    + What are the differences between A, AA, and AAA compliance?
- How can using plain language benefit the accessibility of a project?
- Describe appropriate instances to use a link, vs a generic button, vs a submit button.
- Describe ways to indicate an element or component's state that aren't entirely reliant on visuals.
- How can carousels be problematic for users with disabilities?
- How would you convince your Manager to allocate some funds to do an accessibility external audit?
- Describe a situation where a coworker may have been resistant to accessibility or inclusive design best practices.
    + How were you able to work with them to mitigate such issues?
    + What sort of strategies do you use in situations like these to help educate coworkers?


## Technical
- What methods would you use to find an element's accessible name?
- What is the accessibility tree?
- Why are rems or ems preferable to pixels for setting type size?
- Why is it important to allow the viewport to be resized, and/or zoomed?
- How is the `title` attribute exposed to assistive technologies?
    + What kind of elements can `title` attributes be used on?
    + What sort of information is appropriate for use with the `title` attribute?
- Describe a scenario where you might need to use `aria-describedby`.
- What is a focus trap, or focus trapping? Describe an instance of when you'd need focus trapping, and how it can be an accessibility failure if not used appropriately.
- Describe a situation where one might need to add or modify the focusability of an element by using the `tabindex` attribute.
- What are landmark regions and how can they be useful?
- In what situations might you use a toggle button, vs a switch control, vs a checkbox?
- Describe methods to hide content:
    + From all users.
    + From only screen reader users.
    + From sighted users, but not screen reader users.
    + And why you might do so.
- Describe an instance of inappropriately using ARIA attributes.
- Aside from screen readers, what other assistive technologies can be affected by use of ARIA? How?
- What is the difference between `hidden`, `aria-hidden="true"` and `role="presentation"` or `role="none"`?
- Describe instances where you might need to use `aria-live`.
    + What values (such as `assertive` or `polite`) might you give the attribute in different situations?
- How would you mark-up an icon font or SVG that was for decorative purposes?
- How is CSS pseudo content treated by screen readers?
- What is the purpose of the `alt` attribute for images?
    + Can you describe the effect of an empty `alt`, and/or the lack of the attribute, on an image?
    + In what instances might an empty `alt` or no `alt` be appropriate?
    + How might alternative text for an image vary, depending on the context the image is used in?
    + Since `svg`s don't accept the `alt` attribute, how can one provide alternative text for these graphics?
    + Do you need to supply an image an `alt` attribute if used witin a `figure` with a `figcaption`?
- Describe the steps you take in reviewing or auditing a website or application for accessibility?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you use or recommend <abbr>ARIA</abbr> roles or attributes to solve an accessibility issue?
- Describe your process for figuring out if an accessibility bug is due to a developer, browser, or assistive technology error?
- What is the difference between `legend`, `caption` and `label` elements?
     + What are their similarities?
- Describe the purpose of heading and header elements, and how they are useful in websites and applications.
- Describe how you'd handle a single page web app should and managing focus when changing routes.
- Name an ARIA attribute that requires either a child/parent relationship or a pairing role.
- What is your understanding of "accessible name computation" and how it affects modifying the way screen readers announce certain content?
- What are some issues with modifying normal scrolling behavior? For example: infinite scrolling or scrolljacking.
- Some ARIA widgets are presently best supported on devices with physical keyboard, rather than mobile/touch interfaces.  Are you aware of any widgets that would be described this way, and why?


## Design
- Talk about the pros and cons of flat and [skeuomorphic design](http://whatis.techtarget.com/definition/skeuomorphism) trends in regards to accessibility.
- Explain the importance of color contrast in designing for inclusion.
- Besides `:hover`, name other states an actionable element (links, buttons, form controls, etc.) could have styles for, and why providing them is important?
- When might it be appropriate to remove the visual outline from a focused element?
- If a form or form field were to return an error message, where might you want those error messages to be located?
- How can utilizing animation in an interface affect the user experience?
- Explain how you could make an infographic accessible for screen reader users.
- Why is color alone insufficient to draw attention to actionable elements, or to convey state?
- What are some of the inclusive UX problems that need to be solved when content (static or actionable) is revealed on `:hover`, and how would you propose solving for them?

## Content
- What are some things you can do to make an accessible presentation?
- Is it possible to make email accessible?
- How can you make a podcast accessible?
- How would you make sure that a Word document is accessible?
- How would you make sure that an Excel spreadsheet document is accessible?
- Why is it important to tag a PDF correctly?
- What goes into making an accessible eBook?
- Tell me some social media accessibility best practices.
    + Facebook
    + Instagram
    + Pinterest
    + Snapchat
    + TikTok
    + Twitter
    + YouTube
- How would you handle a situation where your organization accidentally disseminates an inaccessible document?
- What do you think should happen if an employee repeatedly ignores making their documents accessible after being trained?
- What steps would you undertake to create a sustainable culture of creating accessible documents?
- In your previous experiences, was there an opportunity to insert accessibility checks and content authoring best practices into existing workflows?

## Have a question to add?
[Create an issue](https://github.com/scottaohara/accessibility_interview_questions/issues), or [submit a pull request](https://github.com/scottaohara/accessibility_interview_questions/pulls) for consideration.


## Thank you
Thank you to [all contributors](https://github.com/scottaohara/accessibility_interview_questions/graphs/contributors).
Special shoutout to [Eric Bailey](https://github.com/ericwbailey) and [Ashley Bischoff](https://github.com/handcoding) for many contributions not recorded by GitHub.
