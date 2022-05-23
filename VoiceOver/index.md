These guidelines are built around a certain expectation of the way VoiceOver is configured. Specically we want to ensure that we can detect differences between a Developer supplied string vs one coming from the Operating System.

Things that can help you do this are:

- Enable punctiona expansion. (EX: , vs comma)
- Make sure to slow the VoiceRate down when you're testing. Until it becomes instinct!
- More information can be found in [this YouTube video about iOS A11y Testing](https://youtu.be/0lupE3QYEMU)

Note that we are not covering the different reasons for VoiceOver use. When testing with VoiceOver we must give consideration to how each of these tests impacts:

- Users who can't see.
- Users can't read.

The needs of these two users are very different! This means essentially that:

- As a VoiceOver tester who cannot see the screen I must still consider the Touch to Explore experience. In particular the importance of the size of an element in regards to its discoverability in Touch to Explore mode.
- As a VoiceOver user who can see the screen I must consider things like focus order, and image descriptions, and how that impacts a user who can't see. 