# Underhill Painters

How to maintain repeated release in a development environment.

## Getting Started

Git clone and/or branch off of the master branch.

### Prerequisites

It is a good idea to have a solid understanding of something called [Git Flow](https://www.youtube.com/watch?v=EwWZbyjDs9c&feature=youtu.be).

### Installing

Get your repo setup

```
git clone git@github.com:joegreen2/underhillpainters.git
```

### Best practices for repeatedly releasing code

#### where to work

* Create a working branch such as a feature or dev branch so you're not working in master.

#### keep it clean

* Select a style guide and setup your IDE to help make it easier to follow.
* [AirBnB style guide](https://github.com/airbnb/javascript) is suggested.
* As good practice and especially when working with multiple developers, it is highly suggested to use a CI such as [CircleCI](https://circleci.com/), this is optional.

#### bringin' it in...

* Once tests have passed and you are ready to merged your code from it's current branch such as: dev -> master, you are now ready for a [pull request](https://help.github.com/articles/creating-a-pull-request/).
* During a pull request other team members or community review your code and have the ability to make suggestion, corrections, comments, etc...
* You then make necessary corrections and/or replies to team members and/or community.
* Once they approve your changes, you are now good to merge your code into the desired branch.

#### tag you're it!

* don't lose track of your versions, using Semantic Versioning is a big deal to those who don't want to hate their life later on down the road.
* more on [semver](http://semver.org/) tags.

#### says who!?!

* Depending on your project and environment you may have a "release manager" (the person that has to approve the code prior to sending it live).
* Once your code is approved go ahead and send it down the pipe!
* If you're not with current technology and like failing at life, go ahead a open your favorite FTP software and drop the files in the pretty window and that's it.

#### It's alive!!!

* Good job Frankenstein, now keep doing this for the rest of your life, and remember good documentation makes a huge difference!
