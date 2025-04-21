# CS-360
Classwork submitted for SNHU CS-360

```
    Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
    What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
    How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
    How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
    Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
    In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
```

  In this project, I was tasked with planning and creating an Android application (UI and code model) that would serve as an inventory tracking database, complete with SMS notifications, user authentication, and SQLite integration. This necessitated UI elements to depict a login screen, a database table screen, and an SMS permissions dialog. These screens were designed to folllow existing conventions, such as a common order of elements (username, password, and then a forgot password button, for example, arranged in a vertical visual heirarchy). UI elements were also arranged on screen in the same order they would appear in the xml documents that defined them, where possible, to assist users who use screen readers.

  In all coding projects, I attempt to utilize a modular approach, so that code can easily be understood, adjusted, and integrated with future requirements. Admittedly, this project could have been architected much better. Most of the tasks being performed are done inside of a single activity class on a single thread. If more time were available, and the requirements of the assignment better understood from the beginning, I would have liked to separate different tasks into their own classes/objects and make use of the runnable interface to ensure that database queries do not run on the UI thread. My initial lack of familiarity with mobile development made it more of a challenge to produce a working UI than to produce a working model for the UI to interact with, and therefore we have less separation of the two than desireable.
