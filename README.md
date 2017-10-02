# MVI
Just a simple collection of resources related to Model View Intent.

## MVI on Web

[Cycle.js Model-View-Intent](https://cycle.js.org/model-view-intent.html) is an overview of what MVI is. As far as I can tell this is where this term was first used so you can consider it the _birth place_ of Model View Intent until I'm proven wrong.

[Cycle.js Examples](https://cycle.js.org/basic-examples.html) is a great place to see examples of Cycle.js in action.

[Cycle.js Project](https://github.com/cyclejs/cyclejs) is probably where you want to go if you want to checkout the code that powers Cycle.


## MVI on Android

[Model-View-Intent on Android by Hannes Dorfmann](http://hannesdorfmann.com/android/model-view-intent) is possibly the first article written about the idea of MVI on Android.

[Reactive Apps With Model-View-Intent Part 1 by Hannes Dorfmann](http://hannesdorfmann.com/android/mosby3-mvi-1) is the first part in a series of posts about MVI on Android. This is a great place to get information about the architecture, though I'm unsure whether having a presenter is really necessary (or even a good idea).

[MVI on Android by Fabio Berta](https://medium.com/@fnberta/mvi-on-android-20677f80df55)

[My Take on Model View Intent by Zak Taccardi](https://hackernoon.com/model-view-intent-mvi-part-1-state-renderer-187e270db15c)

[Let's Try Model-View-Intent with Android by Cody Engel](https://android.jlelse.eu/lets-try-model-view-intent-with-android-3190a899c3a1)

[Model-View-Intent-Android](https://github.com/sockeqwe/Model-View-Intent-Android) is a demo MVI app which is now deprecated.

[android-mvi-sample](https://github.com/kanawish/android-mvi-sample) is an example of MVI using the Android Architecture Blueprints todo list project.

[Drawrur](https://github.com/CodyEngel/Drawrur) is a demo MVI app that lets you draw pictures.

[Hello Flax - A Reactive Architecture For Android by Cody Engel](https://hackernoon.com/hello-flax-a-reactive-architecture-for-android-8e56af9c575a)

## Moving Past MVI

While Model-View-Intent is a great starting point, you may quickly outgrow it's simplistic nature. So this section is dedicated to libraries that solve the same problem as MVI.

[Flux](https://facebook.github.io/flux/docs/in-depth-overview.html) is complementary to React and serves as more of an architectural pattern over anything else.

[React.js](https://reactjs.org/) if you are looking to use something like Flux but is built out as a framework then this is probably what you want.

[Redux.js](http://redux.js.org/) is a great way to add a state machine to your JS application.

[ReKotlin](https://github.com/GeoThings/ReKotlin) can be used when you want something like Redux but hate writing stuff in JavaScript.

[ReactorKit](https://github.com/ReactorKit/ReactorKit) looks to be a great library if you write iOS applications.

[Flax](https://github.com/CodyEngel/Flax) is a now mostly deprecated library that was inspired by the idea of MVI.
