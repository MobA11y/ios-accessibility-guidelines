# Simple Controls

As an Assistive Technology user I can detect a distinct [pause](https://github.com/MobA11y/n-aria/blob/main/ios.md#pause) between the following [UIAccessibilityElement](https://github.com/MobA11y/n-aria/blob/main/ios.md#UIAccessibilityElement) properties:

- [*AccessibilityLabel*](https://github.com/MobA11y/n-aria/blob/main/ios.md#AccessibilityLabel): Should represent the subject of the control (it's text) or a description of the image associated with it, with special consideration used for the consistent labeling of common icons across the ecosystem, particularly Material Icons.

- [*AccessibilityTraits*](https://github.com/MobA11y/n-aria/blob/main/ios.md#AccessibilityTraits): A trait of [*button*](https://github.com/MobA11y/n-aria/blob/main/ios.md#button) is optional. No other traits apply.

- [*AccessibilityHint*](https://github.com/MobA11y/n-aria/blob/main/ios.md#AccessibilityHint): Provides additional context to the action that will be taken. *Required* when the action will take you out of the context of your application. *EX*: Activate to go to Google.com.

The rough format of the announcmeent should then be:

> Label *{pause}* button *{pause}* Hint