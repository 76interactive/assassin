# Assassin

***Note: a more extensive documentation will land soon***

*Version: 1.0.1* 

Assassin is an opinionated BEM SASS bundle to kickstart the creation of advanced, well-structured SASS sites. As used within [76interactive](http://76interactive.com).

## Components

Lungo includes the following components:

* [Bourbon](http://bourbon.io)
* [Neat](http://neat.io)
* [BEM Mixins](https://medium.com/@marcmintel/pushing-bem-to-the-next-level-with-sass-3-4-5239d2371321)
* [Compass Reset](http://compass-style.org/reference/compass/reset/utilities)
* BEM Neat Grid implementation (mixins)

## Installation

### Manual installation
Download the whole repository as .zip, unpack it and place it in your sass working directory. Although you may want to consider adding it as a submodule as it comes with a few advantages, such as updates.
 
### Add as git submodule
To add the lungo bundle as a git submodule, run the following command:

```
$ git submodule add https://github.com/76interactive/assassin.git
```

## Usage
Import the bundle to use all of lungo. (given that you've either installed lungo using git or that you've install lungo  within a directory called: "lungo")

```
@import "assassin/helpers";

// framework configuration if needed

@import "assassin/assassin";
```

## TODO

* Breakpoint helpers for an easier and more consitent structure
* Variable mapping structure


## License

Assassin is released under the MIT license. See LICENSE for details.
