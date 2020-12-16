# Level 7 Questions

## What is a fragment?

- A fragment is a reusable class implementing a portion of an activity. A Fragment typically defines a part of a user interface. Fragments must be embedded in activities; they cannot run independently of activities.

## What are the benefits of fragments?

* *Reusing View and Logic Components* - Fragments encapsulate views and logic so that it is easier to reuse within activities.
* *Tablet Support* - Often within apps, the tablet version of an activity has a substantially different layout from the phone version which is different from the TV version. Fragments enable device-specific activities to reuse shared elements while also having differences.

## What is the purpose of the FragmentManager?

- is the class responsible for performing actions on your app's fragments, such as adding, removing, or replacing them, and adding them to the back stack.

## Why is FragmentManager not used in the level 7 example?

- Because we use the nav_graph for navigating and that handles the fragments that needs to be shown automatically 
