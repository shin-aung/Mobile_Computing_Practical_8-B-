# Mobile_Computing_Practical_8-B-

**Learning Journey: Completing Guess-the-Celeb App - Part 2**

During a focused 4-hour session, I progressed through the second part of the "Guess-the-celeb" exercise, tackling tasks related to game logic implementation, understanding the Log API, creating multiple XML layout files, and incorporating the MVC design pattern with fragments. Here's a breakdown of my experiences:

**Task 1 - Constructing the Game Logic:**

Created a "game" sub-package with three new classes: Game, GameBuilder, and Question.
Refactored ImageManager into CelebrityManager, adding new methods.
Set up the Question class and created a test in GameUnitTest for its check() method.
Implemented the Game class, satisfying the test in GameUnitTest.
Implemented GameBuilder.create(Difficulty) for creating a game with random celebrities.
Renamed ExampleInstrumentedTest to GameInstrumentedTest and added a test for GameBuilder in testGameBuilder().
Implemented GameBuilder to meet the requirements of testGameBuilder().
Explored the Log API, understanding how to use Log.i(tag, message) for effective debugging.

**Task 2 - Support Multiple Device Configurations:**

Created two versions of activity_main.xml for phone-sized and tablet-sized designs.
Set up layouts for both versions, incorporating fragments for GameFragment, StatusFragment, and QuestionFragment.
Implemented code in MainActivity to access fragments and differentiate between screen sizes.
Created State and StateListener interfaces to facilitate communication between activities and fragments.
Updated MainActivity and fragments (GameFragment, StatusFragment, QuestionFragment) to include StateListener references.
Enhanced GameFragment to handle play button clicks and access difficulty levels.
Modified StatusFragment to allow status message and score updates.
Updated MainActivity to create a new game and assigned it to QuestionFragment upon play button clicks.

**Task 3 - Self-Reflection:**

**Description of the Experience:**

Successfully completed the second part of the Guess-the-Celeb app, incorporating game logic, handling multiple device configurations, and implementing MVC design patterns.

**Feelings and Thoughts about the Experience:**

Felt accomplished in implementing complex game logic. Encountered challenges in understanding fragments and adapting layouts for different screen sizes.

**Evaluation of the Experience, Both Good and Bad:**

Successfully implemented game-related functionality. Faced minor challenges with layout adjustments.

**Analysis to Make Sense of the Situation:**

Understanding fragments and their communication mechanisms is crucial for effective app development. Need to explore more advanced UI features.

**Conclusion about What I Learned and What I Could Have Done Differently:**

Learned about MVC design patterns, fragments, and effective use of resources. Could explore more dynamic UI adjustments and advanced features.

**Action Plan for Future Situations or Changes:**

Focus on advanced UI features, dynamic layouts, and exploring more design patterns. Continuously improve understanding of Android app development best practices.
