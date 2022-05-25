# ios-accessibility-guidelines
A selection of simple Guidelines for Accessibility Testing on the iOS Platform.

iOS Accessibility Testing is difficult. 

- As a VoiceOver Tester what parts of an announcement should I expect where?
- As a VoiceControl Tester how is my experience impacted by the needs of VoiceOver users?
- As an Accessibility Organization what is the most efficient test plan for all of the above?

iOS Accessibility Guidelines will aim to answer all of these heres how:

## Specific Per Assistive Technology Guidlines

For each technology/user group on the platform we will maintain a set of user centric tests that are generic enough to be the minimal set of tests needed to test proper API usage of the platform but specific enough to allow the tester to communicate the results back in a meaningful way to engineers! I have built an example for VoiceOver testing!

- *index.md* - Explains any configuration requirements and assumptions.
- *views-with-actions.md* - How to test *UIViews* with just a tap action.
- *views-with-a-value.md* - Switches, Checkboxes, and other simple Label/Value views.
- *text-input-views.md* - How to test *UITextFields*.
- Certainly there area few more, but this is enough to get started!

## Expectations for Guidelines - The Asamov Test!

Isaac Asimov's Three Laws of Accessibility Guidelines:

1. A guideline must always be compatible with Apple's Guidelines for the platform.
2. A guidline should be compatible with the intent of WCAG when it doesn't break Law 1.
3. Conflicts between Law 1 and Law 2 should be resolved by ubiquitous agreement or inaction.

### What a Guideline is Not
Law 3 above dictates that inaction is sometimes the best action. We ARE NOT trying to be WCAG. We're trying to interpret WCAG for a platform in a way that provides structure to difficult conversations about Accessibility. 

> By preferring ubiquitous agreement or inaction we prefer flexibility... which leads to innovation.

### What a Guideline Is

The Asimov Test of a Guideline allows us to ensure that we are sticking to providing Guidance on the portions of the platform where consistency is necessary. The portions of the platform that are defined in ios-n-aria. 
This also allows companies such as the amazing Accessibility Companies in the instustry to have their own approach to testing plans. Not all companies want or even should test the same way! 