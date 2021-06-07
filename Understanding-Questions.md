# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* setNum is called
* Calls 'applyNumer(num)' which is part of the actions. Passes result to next step
* dispatch is called, which uses the reducer's switch case
* State is updated.
* New data is rendered.

...

* TotalDisplay shows the total plus 1.
