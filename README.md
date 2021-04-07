![](https://koenig-media.raywenderlich.com/uploads/2020/02/viper.png)


**[VIPER](https://www.objc.io/issues/13-architecture/viper/)** is a module template of Clean Architecture to iOS apps. The word VIPER is a backronym for View, Interactor, Presenter, Entity, and Routing. Clean Architecture divides an app’s logical structure into distinct layers of responsibility. This makes it easier to isolate dependencies (e.g. your database) and to test the interactions at the boundaries between layers.</br>

**[VIPER’s](https://www.objc.io/issues/13-architecture/viper/)** distinct layers help deal with this challenge by providing clear locations for application logic and navigation-related code. With VIPER applied, you’ll notice that the view controllers in our to-do list example are lean, mean, view controlling machines. You’ll also find that the code in the view controllers and all of the other classes is easy to understand, easier to test, and as a result, also easier to maintain.

[![Travis CI](https://travis-ci.org/Swinject/Swinject.svg?branch=master)](https://travis-ci.org/Swinject/Swinject)
[![License](https://img.shields.io/cocoapods/l/Swinject.svg?style=flat)](http://cocoapods.org/pods/Swinject)
[![Platforms](https://img.shields.io/badge/platform-iOS%20%7C%20macOS%20%7C%20tvOS%20%7C%20watchOS%20%7C%20Linux-lightgrey.svg)](http://cocoapods.org/pods/Swinject)
[![Swift Version](https://img.shields.io/badge/Swift-2.2--4.x-F16D39.svg?style=flat)](https://developer.apple.com/swift)

### How do I get set up? ###

# Installation

**Add template in your** [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure)**:**
```
templates:
 - {name: swift-viper, git: 'https://github.com/msalari-en/swift-viper.git'}
```

**Dependencies**
* [Swinject](https://github.com/Swinject/Swinject#swinject)

**Install template:**
```
generamba template install
```
# Usage
```
generamba gen [MODULE_NAME] [TEMPLATE_NAME]
```
**Example:**

To create Login module:

```
generamba gen Login swift-viper
```

It will create the Login module in your project target, as well as in your tests target.

### Contribution guidelines ###

* Feel free to contribute.

### Question? ###
If you have a general question and hesitate to submit an issue at GitHub, you can feel free to ask the question at [Stack Overflow](http://stackoverflow.com/). The author of this module VIPER tag there to answer as quickly as possible.

* mihail.salari@endava.com
