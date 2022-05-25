# Controls with a Value
As a VoiceOver user I interacting with a control that has an associated value the:

- [AccessibilityLabel](https://github.com/MobA11y/n-aria/blob/main/ios.md#AccessibilityLabel): Represents the subject that the value is associated with

- [AccessibilityValue](https://github.com/MobA11y/n-aria/blob/main/ios.md#AccessibilityValue): Represents the modifiable portion of the control

- [AccessibilityTrait-UpdatesFrequent](https://github.com/MobA11y/n-aria/blob/main/ios.md#UpdatesFrequently):  Is added if the value changes spontaneously.

This is important because it is important to ensure there is a concrete relationship between the Label and its Value. Relying on focus order does not create this relationship.

The expected announcement then has the rough format of 

> Label {pause} Value

and may contain other information depending on the complexity of the control. Though these scenarios will be covered in other Test Cases.