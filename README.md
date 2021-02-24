[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<p align="center">
  <a href="https://github.com/VictorGreco/php-oop-basics">
    <img src="images/logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center"> OOP explained with PHP </h3>

  **Object-oriented programming** is a programming paradigm based on **objects**, which contains data in the form **attributes and properties** and code in the form of **methods**.

  <p align="center">
    <a href="https://github.com/VictorGreco/php-oop-basics"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/VictorGreco/php-oop-basics">View Demo</a>
    ·
    <a href="https://github.com/VictorGreco/php-oop-basics/issues">Report Bug</a>
    ·
    <a href="https://github.com/VictorGreco/php-oop-basics/issues">Request Feature</a>
  </p>
</p>

<hr></hr>

## Start 🚀
### Requirements 📋

_You need to [install php 7.0 or above](https://www.php.net/manual/en/install.php) and have [XAAMP](https://www.apachefriends.org/it/download.html) in your local machine_

In case you use php 7.3 or above you can also start a local server instead of using XAAMP:

```
$ php -S localhost:8000
```

Just take into considerations some functionalities may not work such as uploading files.

### Installation 🔧

_First clone the repository_

```
git clone https://github.com/VictorGreco/php-oop-basics.git
```

_Then start php server or use XAAMP with Apache_

```
$ php -S localhost:8000
```

_Open [http://localhost:8000](http://localhost:8000)_

## Build with 🛠️

- [PHP](https://www.php.net/docs.php) as main backend and frontend language.

## contributing 🖇️

If you want to contribute, please fork the repository, create a new branch, and push the branch as a pull requests.

## Wiki 📖

For some theoretical aspects check the [Slides](https://docs.google.com/presentation/d/1cZxutGPDqUGsLWLVen_ATjd7dEkeoPS_v_fy1y0C5Co/edit?usp=sharing)
### [01 - Classes](./01-classes.php) <!-- omit in toc -->

The OOP paradigm encapsulates concepts of the real world in what is called as Classes which create Objects. In this file you will learn how to create a class and instantiate it.

### [02 - Properties](02-properties.php) <!-- omit in toc -->

Class member variables are called properties. In this file, you will learn how to add properties to a class and get them when the class is instantiated.

### [03 - Methods](03-methods.php) <!-- omit in toc -->

Properties define the characteristics of an object and the methods (functions in a class are called methods) which define the behavior of the Class. In this file you will learn how to create methods inside a class.

### [04 - Getters](04-getters.php) <!-- omit in toc -->

The get method returns the attribute value, usually there is a get method for each attribute of the class. In this file you will learn how to create **getter** methods.

### [05 - Setters](05-setters.php) <!-- omit in toc -->

The set method sets the attribute value, usually there is a get method for each attribute of the class. In this file you will learn how to create **setter** methods.

### [06 - Constructors](06-constructors.php) <!-- omit in toc -->

A constructor allows you to initialize an object's properties upon creation of the object. In this file you will learn how to create the constructor method.

### [07 - Inheritance problem](07-inheritance-problem.php) <!-- omit in toc -->

There are several disadvantages of not applying inheritance in our code. In this file you will lean what's the problem if you don't apply any inheritance in your code.

### [08 - Inheritance solution](08-inheritance-solution.php) <!-- omit in toc -->

The child class will inherit all the public and protected properties and methods from the parent class. In addition, it can have its own properties and methods. In this file you will learn how to apply the inheritance in your code.

### [09 - Public, private & protected](09-public-private-protected.php) <!-- omit in toc -->

Properties and methods can have access modifiers which control where they can be accessed. In this file you will learn le three access modifiers.

### [10 - Static](10-static.php) <!-- omit in toc -->

Static properties and methods can be called directly - without creating an instance of the class first. In this file you will learn how to use static properties and methods.

### [11 - Const](11-const.php) <!-- omit in toc -->

Constants cannot be changed once it is declared. Class constants can be useful if you need to define some constant data within a class. In this file you will learn how to create constants within a class.

### [12 - Abstract classes](12-abstract-classes.php) <!-- omit in toc -->

Abstract classes and methods are when the parent class has a named method, but need its child class(es) to fill out the tasks. In this file you will learn how to create and use abstract classes.

### [13 - Interfaces](13-interfaces.php) <!-- omit in toc -->

Interfaces allow you to specify what methods a class should implement.
Interfaces make it easy to use a variety of different classes in the same way. When one or more classes use the same interface, it is referred to as "polymorphism". In this file you will learn how to create and extend interfaces.

### [14 - Overriding](14-overriding.php) <!-- omit in toc -->

In function overriding, both parent and child classes should have same function name with and number of arguments. In this file you will learn how to implement overriding.

### [15 - Overloading](15-overloading.php) <!-- omit in toc -->

Function overloading contains same function name and that function preforms different task according to number of arguments. In this file you will learn how to implement overloading.

### [16 - Namespaces](16-namespaces.php) <!-- omit in toc -->

Namespaces are qualifiers that solve two different problems:

1. They allow for better organization by grouping classes that work together to perform a task
2. They allow the same name to be used for more than one class

In this file you will learn how to create and use namespaces.

## Authors ✒️

* **Victor Greco** - [VictorGreco](https://github.com/VictorGreco)

## Kudos 🎉

<div>Icons made by <a href="" title="monkik">monkik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>

---
⌨️ whit ❤️ by for you 😊

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/VictorGreco/php-oop-basics.svg?style=flat-square
[contributors-url]: https://github.com/VictorGreco/php-oop-basics/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/VictorGreco/php-oop-basics.svg?style=flat-square
[forks-url]: https://github.com/VictorGreco/php-oop-basics/network/members
[stars-shield]: https://img.shields.io/github/stars/VictorGreco/php-oop-basics.svg?style=flat-square
[stars-url]: https://github.com/VictorGreco/php-oop-basics/stargazers
[issues-shield]: https://img.shields.io/github/issues/VictorGreco/php-oop-basics.svg?style=flat-square
[issues-url]: https://github.com/VictorGreco/php-oop-basics/issues
[license-shield]: https://img.shields.io/github/license/VictorGreco/php-oop-basics.svg?style=flat-square
[license-url]: https://github.com/VictorGreco/php-oop-basics/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555