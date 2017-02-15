# iOS-Gists

My ongoing collection of iOS helpers. All are licensed under [the MIT License](./LICENSE).

## Dependency Management

Note, these aren't in frameworks. Partially because dynamically linked frameworks add significant startup time to apps, but also because frameworks require lots of boilerplate to set up and I haven't put in the time yet. So you've got two options for adding a gist to your project:

### Submodule
Currently the only real dependency management you can get is through git submodules. See here for more info: https://help.github.com/articles/forking-and-cloning-gists/#cloning-gists.

### Copying files
Most of the gists are small enough that manually copying files into your project is not outside question.

## The list
- [GrowingTextView](https://gist.github.com/Bogidon/cc0c9ae6f041413c39fb0ff146ad1b18) - A dead-simple UITextView subclass that grows with its text. Updates intrinsicContentSize.
- [AnimatedGrowingTextView](https://gist.github.com/Bogidon/632e265b784ef978d5d8c0b86858c2ee) - Like `GrowingTextView` but capable of animating. As a result it's slightly more complex. But still pretty lean!
