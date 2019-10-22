# Change tasks for Micropolis

This is a list of tasks to perform on Micropolis to practice the change process. The steps should be done in order, starting with Concept Location, then Impact analysis, etc.

As for TinyUML, the build system to use is ant, with the `build.xml` file.


### Task 1: difficulty levels
I want you to implement two additional difficulty levels, very easy and very hard. 

### Task 2: bulldozer
Make the “bulldozer” tool work on water, but charging more money when it used (10$ instead of 1$)

### Task 3: notification for roads
When a road is built on water, it costs $50 instead of $10, but there is no notification of this. Implement a notification the first time the operation is executed.

### Task 4: scrolling
Right now all scrolling in Micropolis is done via the mouse.
Scroll the map with the keyboard: the map moves when the arrow keys are pressed.

### Task 5: toggle evaluation and graph
Micropolis has two optional information panels: evaluation of the player’s performance, and historical metrics about the city.
When the two panels are enabled at the same time, they take a lot of space. Make a way to toggle between the two panels, so that at most one of them is displayed at the same time. Displaying the second one automatically hides the first.