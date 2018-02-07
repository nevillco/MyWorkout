# MyWorkout

MyWorkout is an iOS application for creating and completing custom workouts. The goal in developing the app is two-fold:

* I wasn't satisfied with existing apps that serve this purpose, usually because they make assumptions about their use cases that weren't true for me. I'd like a workout manager that can assume a tech-savvy user and leave the content more open for customization.
* More importantly, this is a practice exercise in a few areas of iOS development.

The technological areas of focus are:

* Trying out flow management via parent/child controllers as described in [Dave Delong’s blog series](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-1-the-problems/)
* Using the modern builtin Core Data stack
* Implementing timer-related functionality accurately - via `CADisplayLink` or otherwise
