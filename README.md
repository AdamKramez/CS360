# CS360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The FitTrack app was developed to allow users to easily log their daily weight, set a goal weight, and track their progress visually through charts. It was designed to help users stay motivated and consistent with their weight management goals.


What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app included a Home screen for tracking weight entries and viewing a chart, a Settings screen for setting goals and SMS preferences, and simple dialog prompts for adding new entries. The UI used clear buttons, straightforward prompts, and color-coded charts to make the experience intuitive and supportive, which helped ensure user engagement and ease of use.


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
I structured the app carefully by separating database operations, user session management, and screen logic across different classes. I used modular methods, incremental building, and regular manual testing, which are strategies that can be applied to future projects to maintain clean, scalable, and easily testable code.


How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I tested the app manually after each major feature was added by entering test weights, setting different units, and toggling permissions. This process was important because it caught hidden issues early, like unit conversion bugs and permission handling errors, allowing them to be fixed before they compounded.


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
I had to innovate around Android’s SMS permission system by adding a custom dialog and redirecting users to settings after denial, ensuring that permission requests respected user choice while still offering a smooth experience without crashes or confusion.


In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I was particularly successful in designing and implementing the dynamic weight tracking graph, which updated automatically based on user input, unit selection, and goal changes, demonstrating my ability to connect user interface elements to real-time database-driven data.

