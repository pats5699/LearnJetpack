

<div align=center>
    <h1>Android Experiments</h1>
</div>

## About
https://user-images.githubusercontent.com/34768047/227827397-97ef9e97-c927-4171-bcdd-15c4a6395034.mp4

This repository is where I try out various App architectures, libraries and design 
patterns.  
I have seen a lot of projects that are widely praised and beautiful to look at, but uses a wide
array of technologies together (because why not? A production level app always have a lot of libraries).
But this makes those projects difficult to follow if you are not well versed with all those 
terminologies.  
Thus with this project( and its subsequent branches), i will be testing out the working of various  
libraries together as well as in a separate , isolated environment.

You can find some useful documentation (some not very useful comments) if you dig into the code.
The [LEARNINGS.md](app/src/main/java/in/curioustools/architectures/LEARNINGS.md) file will act as a good start point.   

### Goal

> "I want a simple pokemon app that would request data from my server and show details to user. 
> The first screen should be showing a list of pokemons image and name. on clicking any row a new screen opens up which show more details to user
> The most important feature should be that user should be able to see the list and details even without an internet connection."

This achieves this requirement using the following tools and Libraries

- MVVM( livedata ,vm, repository, room(type convertors, creating schema ))
- retrofit,okhttp,okhttp logging interceptor,glide, internet check interceptor
- plain multi activity ui
- executors for cocurrency
- kapt in gradle  (usecase:  for db schema)
- ktx and android kotlin extensions (for using @parcelize)
- java 1.8


[How?](app/src/main/java/in/curioustools/architectures/LEARNINGS.md)








 
