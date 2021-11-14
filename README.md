# Lab 8 - Starter

Kyle Nakai

1. Within a Github action that runs whenever code is pushed 

By including our automated tests in a GitHub action we ensure that we iteratively test our code and ensure that each push is stable and we can check smaller portions of the code for bugs. This also allows for developers to test parts of their code before merging with the source.

2. Yes
   
3. I would probably not use a unit test to test the message feature. This is because unit tests do not test functionality between other components and interaction. Thus we would not be able to test if our messages are being sent if we are runnning isolated unti tests.

4. For max message length I would use a unit test, as this is a feature that can be tested in isolation as it does not rely on functionality with other components.