# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

* The user presses the 1 button.

* The onClick activates the addOne function, which we imported from actions.

*The addOne function returns ADD_ONE

*ADD_ONE is read in the switch statement in reducers, which returns a spread of state as well as adding one to the total

* TotalDisplay shows the total plus 1.
