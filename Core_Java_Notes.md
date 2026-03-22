# Core Java — Complete Notes

> **Source:** Notes by Ravishankar (javaravishanker@gmail.com)  

> **Period:** April – August 2024


---

## 📚 Table of Contents

- **[What is a language?](##what is a language)**
- **[What is a programming language?](#what-is-a-programming-language)**
- **[Statically(Strongly) typed language](#staticallystrongly-typed-language)**
- **[Dynamically(Looesly) typed language](#dynamicallylooesly-typed-language)**
- **[What is a function](#what-is-a-function)**
- **[Why functions are called method in java?](#why-functions-are-called-method-in-java)**
- **[Flavors of Java](#flavors-of-java)**
  - [We have total 4 types of flavors](#we-have-total-4-types-of-flavors)
- **[What is the difference between Stand-alone program and web-related](#what-is-the-difference-between-stand-alone-program-and-web-related)**
- **[Why java become so popular in the IT Industry ?](#why-java-become-so-popular-in-the-it-industry)**
  - [The role of Java compiler](#the-role-of-java-compiler)
- **[What is the difference between the bit code and byte code.](#what-is-the-difference-between-the-bit-code-and-byte-code)**
- 📅 [22-04-2024](#22-04-2024)
- **[History of java](#history-of-java)**
- **[What is comments ?](#what-is-comments)**
  - [WAP in Java to display Welcome message](#wap-in-java-to-display-welcome-message)
  - [Note](#note)
- **[Description of main() method](#description-of-main-method)**
  - [static](#static)
- 📅 [23-04-2024](#23-04-2024)
  - [main()](#main)
- **[Command Line Argument (Introduction only)](#command-line-argument-introduction-only)**
- **[System.out.println()](#systemoutprintln)**
- 📅 [24-04-2024](#24-04-2024)
  - [IQ](#iq)
- **[Command Line Argument](#command-line-argument)**
  - [How to convert String value into integer](#how-to-convert-string-value-into-integer)
  - [How to convert String to double value](#how-to-convert-string-to-double-value)
- 📅 [25-04-2024](#25-04-2024)
- **[Eclipse IDE](#eclipse-ide)**
- **[What is a Package ?](#what-is-a-package)**
  - [What to craete a class in the user-defined package](#what-to-craete-a-class-in-the-user-defined-package)
  - [How to execute Command Line Argument in Eclipse IDE](#how-to-execute-command-line-argument-in-eclipse-ide)
  - [In order to pass value at runtime (Command Line Argument Value) we need to follow the following steps](#in-order-to-pass-value-at-runtime-command-line-argument-value-we-need-to-follow-the-following-steps)
- **[Command Line Argument Program to find out square of the number](#command-line-argument-program-to-find-out-square-of-the-number)**
  - [Write a Program to show how Integer.parseInt() works internally ?](#write-a-program-to-show-how-integerparseint-works-internally)
- 📅 [26-04-2024](#26-04-2024)
- **[Token](#token)**
- **[Keyword](#keyword)**
- **[Identifiers](#identifiers)**
  - [Rules for defining an identifier](#rules-for-defining-an-identifier)
- **[Literals](#literals)**
- **[Literals](#literals-1)**
- **[Integral Literal](#integral-literal)**
- 📅 [27-04-2024](#27-04-2024)
  - [How to know the minimum and maximum value as well as size of integral literal data types](#how-to-know-the-minimum-and-maximum-value-as-well-as-size-of-integral-literal-data-types)
  - [var keyword in java](#var-keyword-in-java)
- 📅 [29-04-2024](#29-04-2024)
  - [floating Point Literals](#floating-point-literals)
- **[integral literal in 4 different forms i.e decimal, octal,](#integral-literal-in-4-different-forms-ie-decimal-octal)**
- **[Boolean literal](#boolean-literal)**
- **[String Literal](#string-literal)**
  - [In java String can be created by using 3 ways](#in-java-string-can-be-created-by-using-3-ways)
- 📅 [30-04-2024](#30-04-2024)
- **[Character Literal](#character-literal)**
  - [4) Punctuators](#4-punctuators)
- **[Types Of Operators](#types-of-operators)**
- 📅 [01-05-2024](#01-05-2024)
- **[Basic concepts of Operators](#basic-concepts-of-operators)**
  - [What is local variable ?](#what-is-local-variable)
  - [Why we can't access local variable outside of the method ?](#why-we-cant-access-local-variable-outside-of-the-method)
  - [Limitation of Command Line Argument](#limitation-of-command-line-argument)
- **[Working with Scanner class](#working-with-scanner-class)**
  - [WAP to read the name from Keyword](#wap-to-read-the-name-from-keyword)
- 📅 [02-05-2024](#02-05-2024)
  - [Expression Conversion](#expression-conversion)
  - [Unary minus operator](#unary-minus-operator)
  - [Program on Boolean AND](#program-on-boolean-and)
  - [Member access operator](#member-access-operator)
- 📅 [03-05-2024](#03-05-2024)
  - [Limitation of if else](#limitation-of-if-else)
  - [What is drawback of if condition](#what-is-drawback-of-if-condition)
- **[Loops in java](#loops-in-java)**
  - [What is BLC and ELC class ?](#what-is-blc-and-elc-class)
  - [BLC](#blc)
- 📅 [04-05-2024](#04-05-2024)
  - [Reusability of the class](#reusability-of-the-class)
  - [Working with static method parameter and return type](#working-with-static-method-parameter-and-return-type)
  - [Program with Test cases](#program-with-test-cases)
- 📅 [06-05-2024](#06-05-2024)
  - [Finding the Area of Rectangle](#finding-the-area-of-rectangle)
  - [2 files](#2-files)
  - [2 files](#2-files-1)
  - [How to provide formatting for Decimal number](#how-to-provide-formatting-for-decimal-number)
  - [2 files](#2-files-2)
  - [Method return type as String](#method-return-type-as-string)
  - [2 files](#2-files-3)
  - [2 files](#2-files-4)
- **[Object Orineted Programming (OOPs)](#object-orineted-programming-oops)**
- **[What is an Object?](#what-is-an-object)**
- **[What is a class?](#what-is-a-class)**
  - [WAP in OOP to provide initial value to object properties](#wap-in-oop-to-provide-initial-value-to-object-properties)
  - [Types of variables in Java ?](#types-of-variables-in-java)
- **[Instance variable](#instance-variable)**
- 📅 [08-05-2024](#08-05-2024)
  - [2 files](#2-files-5)
  - [Default constructor added by the compiler](#default-constructor-added-by-the-compiler)
  - [Why compiler is adding default constructor to our class](#why-compiler-is-adding-default-constructor-to-our-class)
  - [We have 2 reasons that why compiler is adding default constructor](#we-have-2-reasons-that-why-compiler-is-adding-default-constructor)
  - [2 files](#2-files-6)
  - [How to provide user-defined values for instance variable](#how-to-provide-user-defined-values-for-instance-variable)
- 📅 [09-05-2024](#09-05-2024)
  - [Initialize the object properties by using methods](#initialize-the-object-properties-by-using-methods)
  - [2 files](#2-files-7)
  - [What is a parameter variable](#what-is-a-parameter-variable)
  - [Program on Parameter variables](#program-on-parameter-variables)
  - [2 files](#2-files-8)
  - [Program on initializing the instance variable through methods](#program-on-initializing-the-instance-variable-through-methods)
  - [2 files](#2-files-9)
- **[Variable Shadow](#variable-shadow)**
  - [this keyword in java](#this-keyword-in-java)
  - [How to print object properties by using toString() method](#how-to-print-object-properties-by-using-tostring-method)
  - [Role of instance variable in object creation](#role-of-instance-variable-in-object-creation)
  - [Role of static variable in object creation](#role-of-static-variable-in-object-creation)
- **[Instance variable = Multiple Copies](#instance-variable-multiple-copies)**
- **[Instance Variable](#instance-variable-1)**
  - [2 files](#2-files-10)
- 📅 [14-05-2024](#14-05-2024)
- **[Data Hiding](#data-hiding)**
- **[Data hiding is nothing but declaring our data members with private access modifier so our data will not be accessible from outer world that means no one can access our data directly from  outside of the class.](#data-hiding-is-nothing-but-declaring-our-data-members-with-private-access-modifier-so-our-data-will-not-be-accessible-from-outer-world-that-means-no-one-can-access-our-data-directly-from-outside-of-the-class)**
  - [2 files](#2-files-11)
- **[Abstraction](#abstraction)**
- **[abstraction.](#abstraction-1)**
- **[What is Constructor ?](#what-is-constructor)**
  - [What is the advantage of writing constructor in our class ?](#what-is-the-advantage-of-writing-constructor-in-our-class)
- 📅 [15-05-2024](#15-05-2024)
- **[Types of Constructor](#types-of-constructor)**
  - [We have 3 types of constructor in java](#we-have-3-types-of-constructor-in-java)
  - [2) No Argument Constructor](#2-no-argument-constructor)
  - [3) Parameterized Constructor](#3-parameterized-constructor)
  - [2 files](#2-files-12)
  - [How to write setter and getter in java](#how-to-write-setter-and-getter-in-java)
  - [Method return type as a class](#method-return-type-as-a-class)
- 📅 [16-05-2024](#16-05-2024)
  - [Program on Method return type as a class](#program-on-method-return-type-as-a-class)
  - [2 files](#2-files-13)
  - [2 files](#2-files-14)
  - [Pass by Value in java](#pass-by-value-in-java)
  - [HEAP and STACK Diagram](#heap-and-stack-diagram)
  - [What is Garbage Collector in java ?](#what-is-garbage-collector-in-java)
- 📅 [17-05-2024](#17-05-2024)
  - [How many ways we can make an object eligible for GC](#how-many-ways-we-can-make-an-object-eligible-for-gc)
- 📅 [18-05-2024](#18-05-2024)
  - [Lab Program](#lab-program)
- 📅 [20-05-2024](#20-05-2024)
  - [Declaring a constructor as private](#declaring-a-constructor-as-private)
  - [We should declare a constructor as private for the following 2 reasons](#we-should-declare-a-constructor-as-private-for-the-following-2-reasons)
  - [What is an instance block OR instance initializer ?](#what-is-an-instance-block-or-instance-initializer)
  - [What is Instance OR non-static block in Java ?](#what-is-instance-or-non-static-block-in-java)
  - [Initialization life cycle of an  instance variable](#initialization-life-cycle-of-an-instance-variable)
  - [Whenever we create an object in java then the instance variable, we can initialized in the following places](#whenever-we-create-an-object-in-java-then-the-instance-variable-we-can-initialized-in-the-following-places)
  - [What is blank final variable](#what-is-blank-final-variable)
- 📅 [21-05-2024](#21-05-2024)
  - [Relationship between the classes](#relationship-between-the-classes)
- **[HAS-A relation we can achieve using Association.](#has-a-relation-we-can-achieve-using-association)**
- **[Inheritance (IS-A Relation)](#inheritance-is-a-relation)**
- **[Inheritance provides IS-A relation between the classes. IS-A relation is tightly coupled relation (Blood Relation) so if we modify the super class content then automatically sub class content will also modify.](#inheritance-provides-is-a-relation-between-the-classes-is-a-relation-is-tightly-coupled-relation-blood-relation-so-if-we-modify-the-super-class-content-then-automatically-sub-class-content-will-also-modify)**
- **[Inheritance provides us hierarchical classification of classes, In this hierarchy if we move towards upward direction more generalized properties will occur, on the other hand if we move towards downwand more specialized properties will occur.](#inheritance-provides-us-hierarchical-classification-of-classes-in-this-hierarchy-if-we-move-towards-upward-direction-more-generalized-properties-will-occur-on-the-other-hand-if-we-move-towards-downwand-more-specialized-properties-will-occur)**
  - [Types of Inheritance in java](#types-of-inheritance-in-java)
  - [Java supports 5 types of inheritance](#java-supports-5-types-of-inheritance)
  - [Program on Single Level Inheritance](#program-on-single-level-inheritance)
- 📅 [22-05-2024](#22-05-2024)
  - [2) To call super class method](#2-to-call-super-class-method)
  - [case 1](#case-1)
  - [Case 2](#case-2)
  - [Case 3](#case-3)
  - [Case 4](#case-4)
  - [Program on super keyword using Single level inheritance](#program-on-super-keyword-using-single-level-inheritance)
- 📅 [23-05-2024](#23-05-2024)
  - [Program on hierarchical inheritance](#program-on-hierarchical-inheritance)
  - [WAP in java to implement Single level inheritance](#wap-in-java-to-implement-single-level-inheritance)
  - [Program on Hierarchical Inheritance](#program-on-hierarchical-inheritance-1)
  - [HOW MANY WAYS WE CAN INITIALIZE THE OBJECT PROPERTIES ?](#how-many-ways-we-can-initialize-the-object-properties)
  - [2) By using Object Reference](#2-by-using-object-reference)
  - [3) By using methods](#3-by-using-methods)
  - [5) By using super keyword](#5-by-using-super-keyword)
- **[Why java does not support multiple inheritance ?](#why-java-does-not-support-multiple-inheritance)**
- 📅 [24-05-2024](#24-05-2024)
- **[Access modifiers in java](#access-modifiers-in-java)**
  - [In order to define the accessibility level of the class as well as member of the class we have 4 access modifiers](#in-order-to-define-the-accessibility-level-of-the-class-as-well-as-member-of-the-class-we-have-4-access-modifiers)
- **[HAS-A relation between the classes](#has-a-relation-between-the-classes)**
  - [Association](#association)
  - [Program on Association](#program-on-association)
  - [Composition (Strong reference)](#composition-strong-reference)
  - [Aggregation (Weak Reference)](#aggregation-weak-reference)
- **[Polymorphism can be divided into two types](#polymorphism-can-be-divided-into-two-types)**
  - [1) Static Polymorphism](#1-static-polymorphism)
- **[Method Overloading](#method-overloading)**
- **[Method overloading is possible in the same class as well as super and sub class.](#method-overloading-is-possible-in-the-same-class-as-well-as-super-and-sub-class)**
- 📅 [27-05-2024](#27-05-2024)
  - [Program on Constructor Overloading](#program-on-constructor-overloading)
  - [2 files](#2-files-15)
  - [instance block role with constructor](#instance-block-role-with-constructor)
  - [program that describes we can change the return type of the method at the time of method overloading](#program-that-describes-we-can-change-the-return-type-of-the-method-at-the-time-of-method-overloading)
- **[Var-Args](#var-args)**
- **[var-args must be only one and last argument.](#var-args-must-be-only-one-and-last-argument)**
- **[Wrapper classes in java](#wrapper-classes-in-java)**
- 📅 [28-05-2024](#28-05-2024)
  - [How to convert primitive to wrapper object ?](#how-to-convert-primitive-to-wrapper-object)
  - [Overloaded valueOf() method](#overloaded-valueof-method)
  - [Unboxing](#unboxing)
  - [Automatic/Implicit/Widening type casting](#automaticimplicitwidening-type-casting)
- 📅 [29-05-2024](#29-05-2024)
  - [Ambiguity issue while overloading a method](#ambiguity-issue-while-overloading-a-method)
  - [What is the advantage of Method Overriding ?](#what-is-the-advantage-of-method-overriding)
  - [Upcasting and Downcasting](#upcasting-and-downcasting)
  - [Upcasting](#upcasting)
- 📅 [30-05-2024](#30-05-2024)
  - [Program on Method Overriding](#program-on-method-overriding)
  - [@Override Annotation](#override-annotation)
  - [Program that describes we cannot override private method](#program-that-describes-we-cannot-override-private-method)
  - [Role of access modifier while overriding a method](#role-of-access-modifier-while-overriding-a-method)
- **[Variable Shadow in Method Overriding](#variable-shadow-in-method-overriding)**
  - [Co-Variant in java](#co-variant-in-java)
  - [Method Hiding in java](#method-hiding-in-java)
  - [Case 2](#case-2-1)
  - [Case 3](#case-3-1)
  - [Progrm that describes Polymorphic behaviour of sub classes](#progrm-that-describes-polymorphic-behaviour-of-sub-classes)
  - [instanceof Operator](#instanceof-operator)
  - [final keyword in java](#final-keyword-in-java)
- 📅 [01-06-2024](#01-06-2024)
  - [1) To declare a class as a final](#1-to-declare-a-class-as-a-final)
- **[Sealed class in Java](#sealed-class-in-java)**
- **[sealed class Bird permits Parrot, Sparrow](#sealed-class-bird-permits-parrot-sparrow)**
- **[sealed class OnlineClass permits Mobile, Laptop](#sealed-class-onlineclass-permits-mobile-laptop)**
  - [What is Method Chaining in java ?](#what-is-method-chaining-in-java)
- 📅 [03-06-2024](#03-06-2024)
- **[Object class in java](#object-class-in-java)**
  - [Working with Object class and its methods](#working-with-object-class-and-its-methods)
  - [1) public native final java.lang.Class getClass()](#1-public-native-final-javalangclass-getclass)
  - [2) public native int hashCode()](#2-public-native-int-hashcode)
  - [3) public String toString()](#3-public-string-tostring)
- 📅 [04-06-2024](#04-06-2024)
- 📅 [05-06-2024](#05-06-2024)
- **[JVM Architecture with class loader sub system](#jvm-architecture-with-class-loader-sub-system)**
- **[Class Loader sub System](#class-loader-sub-system)**
- **[Class loader sub system internally performs 3 tasks](#class-loader-sub-system-internally-performs-3-tasks)**
  - [How Delegation Hierarchy algorithm works](#how-delegation-hierarchy-algorithm-works)
- 📅 [06-06-2024](#06-06-2024)
  - [Linking](#linking)
  - [Resolve](#resolve)
  - [Initialization](#initialization)
- 📅 [10-06-2024](#10-06-2024)
- **[Static block](#static-block)**
- **[Static blocks are executed only once because in java we can load the .class files only once.](#static-blocks-are-executed-only-once-because-in-java-we-can-load-the-class-files-only-once)**
- **[static blocks are executed before main method.](#static-blocks-are-executed-before-main-method)**
- **[static blocks are executed only once.](#static-blocks-are-executed-only-once)**
  - [How many ways we can load the .class file into JVM memory](#how-many-ways-we-can-load-the-class-file-into-jvm-memory)
  - [Variable Memory Allocation and Initialization](#variable-memory-allocation-and-initialization)
  - [1) static field OR Class variable](#1-static-field-or-class-variable)
- 📅 [11-06-2024](#11-06-2024)
  - [Can we write a program without main method ?](#can-we-write-a-program-without-main-method)
  - [Loading the .class file by using Reflection API](#loading-the-class-file-by-using-reflection-api)
- **[What is factory Method in java ?](#what-is-factory-method-in-java)**
- 📅 [12-06-2024](#12-06-2024)
  - [Runtime Data Areas](#runtime-data-areas)
  - [HEAP Area](#heap-area)
- 📅 [13-06-2024](#13-06-2024)
  - [PC Register](#pc-register)
  - [Native Method Stack](#native-method-stack)
  - [Execution Engine](#execution-engine)
- **[Abstraction](#abstraction-2)**
  - [As we know we can achieve abstraction by using 2 ways](#as-we-know-we-can-achieve-abstraction-by-using-2-ways)
- **[Abstract class and abstract methods](#abstract-class-and-abstract-methods)**
- **[abstract class Shape](#abstract-class-shape)**
- **[abstract class Car](#abstract-class-car)**
- **[abstract class constructor will be executed with the help sub class object by using super keyword.](#abstract-class-constructor-will-be-executed-with-the-help-sub-class-object-by-using-super-keyword)**
- 📅 [14-06-2024](#14-06-2024)
  - [IQ](#iq-1)
- **[abstract class contains object properties (Instance variable), so those](#abstract-class-contains-object-properties-instance-variable-so-those)**
- **[abstract class Alpha](#abstract-class-alpha)**
- **[abstract class Beta extends Alpha](#abstract-class-beta-extends-alpha)**
- **[abstract class Shape](#abstract-class-shape-1)**
  - [Program with array and abstract class to show dynamic polymorphism](#program-with-array-and-abstract-class-to-show-dynamic-polymorphism)
- **[abstract class Animal](#abstract-class-animal)**
- 📅 [17-06-2024](#17-06-2024)
  - [Program on loose coupling](#program-on-loose-coupling)
  - [6 files](#6-files)
  - [Multiple Inheritance by using interface](#multiple-inheritance-by-using-interface)
  - [Extending interface](#extending-interface)
  - [interface from JDK 1.8 onwards](#interface-from-jdk-18-onwards)
  - [Limitation of abstract method](#limitation-of-abstract-method)
- **[What is default Method inside an interface?](#what-is-default-method-inside-an-interface)**
  - [Program on default method](#program-on-default-method)
  - [4 files](#4-files)
  - [Priority of deafult and concrete method](#priority-of-deafult-and-concrete-method)
  - [Multiple Inheritance by using default Method](#multiple-inheritance-by-using-default-method)
  - [What is static method inside an interface?](#what-is-static-method-inside-an-interface)
  - [2 files](#2-files-16)
  - [Interface Static Method](#interface-static-method)
  - [Anonymous inner class](#anonymous-inner-class)
- **[abstract class Animal](#abstract-class-animal-1)**
- 📅 [19-06-2024](#19-06-2024)
- **[What is a Functional interface in java ?](#what-is-a-functional-interface-in-java)**
- **[What is Lambda Expression in java ?](#what-is-lambda-expression-in-java)**
  - [Programs on Lambda Expression](#programs-on-lambda-expression)
  - [Working with predefined functional interfaces without Type parameter](#working-with-predefined-functional-interfaces-without-type-parameter)
- 📅 [20-06-2024](#20-06-2024)
  - [Type parameter in java <T> ?](#type-parameter-in-java-t)
  - [Working with predefined functional interfaces](#working-with-predefined-functional-interfaces)
  - [Programs on Predicate<T> functional interface](#programs-on-predicatet-functional-interface)
  - [Assignment](#assignment)
  - [By using Predicate verify whether a year is leap year or not?](#by-using-predicate-verify-whether-a-year-is-leap-year-or-not)
  - [Function<T,R> functional interface](#functiontr-functional-interface)
  - [Type Parameters](#type-parameters)
- 📅 [21-06-2024](#21-06-2024)
  - [Supplier<T> prdefined functional interface](#suppliert-prdefined-functional-interface)
- **[Record class in java](#record-class-in-java)**
  - [3 files](#3-files)
  - [Remainig Program on Supplier<T> interface](#remainig-program-on-suppliert-interface)
  - [BiPredicate<T,U> functional interface](#bipredicatetu-functional-interface)
  - [BiConsumer<T, U> functional interface](#biconsumert-u-functional-interface)
  - [BiFunction<T, U, R> Functional interface](#bifunctiont-u-r-functional-interface)
- 📅 [22-06-2024](#22-06-2024)
  - [Can an interface extend a class like Object class ?](#can-an-interface-extend-a-class-like-object-class)
  - [Can a default method override Object class method inside a interface ?](#can-a-default-method-override-object-class-method-inside-a-interface)
- **[What is marker interface in java ?](#what-is-marker-interface-in-java)**
- **[Exception Handling](#exception-handling)**
  - [What is an execption ?](#what-is-an-execption)
- 📅 [24-06-2024](#24-06-2024)
- **[Exception Hierarchy](#exception-hierarchy)**
  - [Different Crieteria of Exception](#different-crieteria-of-exception)
  - [Exception format](#exception-format)
  - [In order to work with exception, java software people has provided the following keywords](#in-order-to-work-with-exception-java-software-people-has-provided-the-following-keywords)
  - [Key points to remember](#key-points-to-remember)
- 📅 [25-06-2024](#25-06-2024)
  - [Throwable class method](#throwable-class-method)
  - [Throwable class has provided the following three methods](#throwable-class-has-provided-the-following-three-methods)
  - [Working with Specific Exception](#working-with-specific-exception)
- 📅 [26-06-2024](#26-06-2024)
  - [Working with Infinity and Not a number(NaN)](#working-with-infinity-and-not-a-numbernan)
  - [Working with multiple try catch](#working-with-multiple-try-catch)
  - [According to our application requirement we can provide multiple try catch in the same application as shown below](#according-to-our-application-requirement-we-can-provide-multiple-try-catch-in-the-same-application-as-shown-below)
  - [Limitation of finally Block](#limitation-of-finally-block)
  - [The following are the limitation of finally block](#the-following-are-the-limitation-of-finally-block)
- 📅 [27-06-2024](#27-06-2024)
  - [Nested try block](#nested-try-block)
  - [Writing try-catch inside catch block](#writing-try-catch-inside-catch-block)
  - [Initialization of a variable in try and catch](#initialization-of-a-variable-in-try-and-catch)
  - [Checked Exception](#checked-exception)
  - [Some Bullet points regarding Checked and Unchecked](#some-bullet-points-regarding-checked-and-unchecked)
  - [Checked Exception](#checked-exception-1)
- 📅 [28-06-2024](#28-06-2024)
  - [When to provide try-catch or declare the method as throws](#when-to-provide-try-catch-or-declare-the-method-as-throws)
  - [Types of exception in java](#types-of-exception-in-java)
  - [Exception can be divided into two types](#exception-can-be-divided-into-two-types)
- **[How to develop User-defined Exceptions](#how-to-develop-user-defined-exceptions)**
  - [Assignment](#assignment-1)
  - [create a user-defined exception which is unchecked exception](#create-a-user-defined-exception-which-is-unchecked-exception)
  - [Some important rules while working with Checked Exception](#some-important-rules-while-working-with-checked-exception)
- 📅 [29-06-2024](#29-06-2024)
- **[Exception propagation](#exception-propagation)**
  - [Handling Exception while calling a method ?](#handling-exception-while-calling-a-method)
  - [Input Output in java](#input-output-in-java)
  - [DataInputStream](#datainputstream)
- **[What is the need of File Handling ?](#what-is-the-need-of-file-handling)**
- 📅 [01-07-2024](#01-07-2024)
- **[Streams in java](#streams-in-java)**
  - [File](#file)
  - [Assignment](#assignment-2)
  - [FileInputStream](#fileinputstream)
  - [Limitation of FileInputStream class](#limitation-of-fileinputstream-class)
- 📅 [02-07-2024](#02-07-2024)
  - [Limitation of FilOutputStream](#limitation-of-filoutputstream)
  - [BufferedOutputStream](#bufferedoutputstream)
  - [BufferedInputStream](#bufferedinputstream)
  - [Reading and Writing the primitive data to the files](#reading-and-writing-the-primitive-data-to-the-files)
- 📅 [03-07-2024](#03-07-2024)
  - [transient keyword in java](#transient-keyword-in-java)
  - [Working With Character Oriented Stream](#working-with-character-oriented-stream)
  - [FileReader class](#filereader-class)
  - [PrintWriter](#printwriter)
  - [How to append the data in the existing file](#how-to-append-the-data-in-the-existing-file)
- 📅 [04-07-2024](#04-07-2024)
  - [enum in java](#enum-in-java)
- **[Nested classes in java](#nested-classes-in-java)**
  - [There are 4 types of inner classes in java](#there-are-4-types-of-inner-classes-in-java)
- **[Variable Shadow in Nested class](#variable-shadow-in-nested-class)**
- 📅 [08-07-2024](#08-07-2024)
  - [Static nested inner class](#static-nested-inner-class)
  - [Local OR Method Local inner class](#local-or-method-local-inner-class)
  - [Anonymous inner class](#anonymous-inner-class-1)
- 📅 [09-07-2024](#09-07-2024)
  - [Multithreading](#multithreading)
  - [Uniprocessing](#uniprocessing)
- **[Thread based Multitasking](#thread-based-multitasking)**
- **[Thread](#thread)**
- **[Thread t = Thread.currentThread(); //Factory Method](#thread-t-threadcurrentthread-factory-method)**
- **[Thread class has provided predefined method getName() to get the name of the Thread.](#thread-class-has-provided-predefined-method-getname-to-get-the-name-of-the-thread)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread)**
  - [How to create user-defined thread ?](#how-to-create-user-defined-thread)
  - [By using java.lang package we can create user-defined thread by using anyone of the following two approaches](#by-using-javalang-package-we-can-create-user-defined-thread-by-using-anyone-of-the-following-two-approaches)
- 📅 [10-07-2024](#10-07-2024)
  - [How to create user thread by using extending Thread class approach](#how-to-create-user-thread-by-using-extending-thread-class-approach)
  - [start() is a predefined non static method of Thread class which internally performs the following two tasks](#start-is-a-predefined-non-static-method-of-thread-class-which-internally-performs-the-following-two-tasks)
  - [It is a predefined non static method of Thread class through which we can find out whether a thread has started or not ?](#it-is-a-predefined-non-static-method-of-thread-class-through-which-we-can-find-out-whether-a-thread-has-started-or-not)
  - [How to set and get the name of the Thread](#how-to-set-and-get-the-name-of-the-thread)
- **[Thread t =  Thread.currentThread();](#thread-t-threadcurrentthread-1)**
- 📅 [11-07-2024](#11-07-2024)
- **[Thread.sleep(long millisecond)](#threadsleeplong-millisecond)**
- **[Thread.sleep(1000); //Thread will wait for 1 second](#threadsleep1000-thread-will-wait-for-1-second)**
- **[Thread.sleep(1000);](#threadsleep1000)**
- **[Thread thread = Thread.currentThread();](#thread-thread-threadcurrentthread)**
- **[Thread.sleep(1000);](#threadsleep1000-1)**
- **[Thread thread = Thread.currentThread();](#thread-thread-threadcurrentthread-1)**
  - [Assignment](#assignment-3)
- **[Thread.sleep(long millis, int nanos)](#threadsleeplong-millis-int-nanos)**
- **[Thread life cycle](#thread-life-cycle)**
- **[Thread life cycle](#thread-life-cycle-1)**
  - [IQ :- If we write Thread.sleep(1000) then exactly after 1 sec the Thread will re-start?](#iq-if-we-write-threadsleep1000-then-exactly-after-1-sec-the-thread-will-re-start)
  - [Anonymous inner class with Thread class ?](#anonymous-inner-class-with-thread-class)
- **[Thread t1 = new Thread()](#thread-t1-new-thread)**
  - [2) Anonymous inner class without reference varible](#2-anonymous-inner-class-without-reference-varible)
- 📅 [12-07-2024](#12-07-2024)
  - [join() method of Thread class](#join-method-of-thread-class)
- **[Thread.sleep(1000);](#threadsleep1000-2)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-2)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-3)**
- **[Thread.sleep(500);](#threadsleep500)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-4)**
- **[Thread.sleep(500);](#threadsleep500-1)**
  - [Assignment](#assignment-4)
  - [Assigning target by Runnable interface](#assigning-target-by-runnable-interface)
- **[Thread thread = new Thread(r1,"Child1");](#thread-thread-new-threadr1child1)**
- **[thread.start();](#threadstart)**
- 📅 [13-07-2024](#13-07-2024)
  - [How to assign the target for different Threads](#how-to-assign-the-target-for-different-threads)
- **[Thread t1 = new Thread(new PlacementBatch());](#thread-t1-new-threadnew-placementbatch)**
- **[Thread t2 = new Thread(new RegularBatch());](#thread-t2-new-threadnew-regularbatch)**
- **[Thread class constructor](#thread-class-constructor)**
  - [Case 1](#case-1-1)
- **[Thread t1 = new Thread(r1);](#thread-t1-new-threadr1)**
  - [Case 2](#case-2-2)
  - [Case 3](#case-3-2)
  - [Case 4](#case-4-1)
  - [Program to assign different task to different Thread](#program-to-assign-different-task-to-different-thread)
  - [IQ](#iq-2)
- **[Threads but by using implements we can provide different target for](#threads-but-by-using-implements-we-can-provide-different-target-for)**
  - [Drawback of Multithreading](#drawback-of-multithreading)
- **[Thread t1 = new Thread(cust,"Virat");](#thread-t1-new-threadcustvirat)**
- **[Thread t2 = new Thread(cust,"Rohit");](#thread-t2-new-threadcustrohit)**
- **[Thread t1 = new Thread(r1,"Person1");](#thread-t1-new-threadr1person1)**
- **[Thread t2 = new Thread(r1,"Person2");](#thread-t2-new-threadr1person2)**
- 📅 [15-07-2024](#15-07-2024)
  - [How synchronization logic controls multiple threads ?](#how-synchronization-logic-controls-multiple-threads)
- **[Thread.sleep(1000);](#threadsleep1000-3)**
- **[Thread t1 = new Thread(r1);](#thread-t1-new-threadr1-1)**
- **[Thread t2 = new Thread(r2);](#thread-t2-new-threadr2)**
- **[ThreadName obj1 = new ThreadName(); //lock is created](#threadname-obj1-new-threadname-lock-is-created)**
- **[Thread t1 = new Thread(r1,"Child1");](#thread-t1-new-threadr1child1)**
- **[Thread t2 = new Thread(r1,"Child2");](#thread-t2-new-threadr1child2)**
  - [Limitation/Drawback of Object Level Synchronization](#limitationdrawback-of-object-level-synchronization)
- **[Thread.sleep(500);](#threadsleep500-2)**
- **[Thread t1 = new Thread()  //Anonymous inner class concept](#thread-t1-new-thread-anonymous-inner-class-concept)**
- **[Thread t2 = new Thread()](#thread-t2-new-thread)**
- **[Thread t3 = new Thread()](#thread-t3-new-thread)**
- **[Thread t4 = new Thread()](#thread-t4-new-thread)**
- **[Thread.sleep(100);](#threadsleep100)**
- **[Thread t1 = new Thread()](#thread-t1-new-thread-1)**
- **[Thread t2 = new Thread()](#thread-t2-new-thread-1)**
- **[Thread t3 = new Thread(r3);](#thread-t3-new-threadr3)**
- 📅 [16-07-2024](#16-07-2024)
- **[Thread Priority](#thread-priority)**
- **[Thread class has also provided 3 final static variables which are as follows](#thread-class-has-also-provided-3-final-static-variables-which-are-as-follows)**
- **[Thread.MIN_PRIORITY  :- 01](#threadmin_priority-01)**
- **[Thread.NORM_PRIORITY : 05](#threadnorm_priority-05)**
- **[Thread.MAX_PRIORITY  :- 10](#threadmax_priority-10)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-5)**
- **[Thread t1 = new Thread();](#thread-t1-new-thread-2)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-6)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-7)**
- **[Thread t1 = new Thread(r1,"LastThread");](#thread-t1-new-threadr1lastthread)**
- **[Thread t2 = new Thread(r1,"FirstThread");](#thread-t2-new-threadr1firstthread)**
- **[Thread.yield()](#threadyield)**
- **[Thread.yield();  //Give a chance to Child2 Thread](#threadyield-give-a-chance-to-child2-thread)**
- **[Thread t1 = new Thread(obj, "Child1");](#thread-t1-new-threadobj-child1)**
- **[Thread t2 = new Thread(obj, "Child2");](#thread-t2-new-threadobj-child2)**
- **[ThreadGroup](#threadgroup)**
- **[ThreadGroup tg = new ThreadGroup(String groupName);](#threadgroup-tg-new-threadgroupstring-groupname)**
- **[ThreadGroup class has provided the following method](#threadgroup-class-has-provided-the-following-method)**
- **[Thread class has provided constructor to put the thread into particular group.](#thread-class-has-provided-constructor-to-put-the-thread-into-particular-group)**
- **[Thread t1 = new Thread(ThreadGroup tg, Runnable target, String name);](#thread-t1-new-threadthreadgroup-tg-runnable-target-string-name)**
- **[ThreadGroup tg = new ThreadGroup("Java_Group");](#threadgroup-tg-new-threadgroupjava_group)**
- **[Thread t1 = new Thread(tg, new JavaClass(), "Child 1" );](#thread-t1-new-threadtg-new-javaclass-child-1)**
- **[Thread t2 = new Thread(tg, new JavaClass(), "Child 2" );](#thread-t2-new-threadtg-new-javaclass-child-2)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-8)**
- **[ThreadGroup tg1 = new ThreadGroup("Tatkal Ticket");](#threadgroup-tg1-new-threadgrouptatkal-ticket)**
- **[ThreadGroup tg2 = new ThreadGroup("Premium Tatkal");](#threadgroup-tg2-new-threadgrouppremium-tatkal)**
- **[Thread t1 = new Thread(tg1,new TatkalTicket(), "Scott");](#thread-t1-new-threadtg1new-tatkalticket-scott)**
- **[Thread t2 = new Thread(tg2,new PremiumTatkal(), "Smith");](#thread-t2-new-threadtg2new-premiumtatkal-smith)**
- **[Thread.sleep(200);](#threadsleep200)**
- **[ThreadA  a1 = new ThreadA();](#threada-a1-new-threada)**
- **[Thread.sleep(200);](#threadsleep200-1)**
- **[Thread son = new Thread()](#thread-son-new-thread)**
- **[Thread.sleep(1000);](#threadsleep1000-4)**
- **[Thread father = new Thread()](#thread-father-new-thread)**
- 📅 [18-07-2024](#18-07-2024)
- **[Thread t1 = new Thread(() -> r1.waitMethod(), "Child1");](#thread-t1-new-thread-r1waitmethod-child1)**
- **[Thread t2 = new Thread(() -> r1.waitMethod(), "Child2");](#thread-t2-new-thread-r1waitmethod-child2)**
- **[Thread t3 = new Thread(() -> r1.waitMethod(), "Child3");](#thread-t3-new-thread-r1waitmethod-child3)**
- **[Thread setter = new Thread(() -> r1.setMethod(), "Setter_Thread");](#thread-setter-new-thread-r1setmethod-setter_thread)**
- **[Thread.sleep(2000);](#threadsleep2000)**
  - [interrupt Method of Thread class](#interrupt-method-of-thread-class)
- **[thread safely so we can manage the resources easily.](#thread-safely-so-we-can-manage-the-resources-easily)**
- **[Thread t = Thread.currentThread();](#thread-t-threadcurrentthread-9)**
- **[Thread.sleep(1000);](#threadsleep1000-5)**
- **[Thread.currentThread().interrupt();](#threadcurrentthreadinterrupt)**
- **[Thread.sleep(1000);](#threadsleep1000-6)**
- **[Thread thread = new Thread(new MyRunnable());](#thread-thread-new-threadnew-myrunnable)**
- **[thread.start();](#threadstart-1)**
- **[Thread.sleep(3000);](#threadsleep3000)**
- **[thread.interrupt();](#threadinterrupt)**
- **[Thread.sleep(500);](#threadsleep500-3)**
  - [Deadlock](#deadlock)
- **[Thread t1 = new Thread()](#thread-t1-new-thread-3)**
- **[Thread.sleep(1000);](#threadsleep1000-7)**
- **[Thread t2 = new Thread()](#thread-t2-new-thread-2)**
- **[Thread.sleep(1000);](#threadsleep1000-8)**
- **[Thread daemonThread = new Thread(() ->](#thread-daemonthread-new-thread)**
- **[Thread.sleep(1000);](#threadsleep1000-9)**
- **[Thread userThread = new Thread(() ->](#thread-userthread-new-thread)**
- **[Thread.sleep(2000);](#threadsleep2000-1)**
- 📅 [19-07-2024](#19-07-2024)
  - [Remaining methods of Object class](#remaining-methods-of-object-class)
  - [Object cloning in java](#object-cloning-in-java)
  - [Deep Copy](#deep-copy)
- **[Thread.sleep(3000);](#threadsleep3000-1)**
- 📅 [20-07-2024](#20-07-2024)
  - [Method Reference in java](#method-reference-in-java)
  - [3 files](#3-files-1)
  - [3 files](#3-files-2)
  - [Working with static Method Reference](#working-with-static-method-reference)
  - [Working with instance method Reference](#working-with-instance-method-reference)
  - [By Using Constructor Reference](#by-using-constructor-reference)
- 📅 [22-07-2024](#22-07-2024)
  - [Arbitrary Reference (ClassName::instanceMethodName)](#arbitrary-reference-classnameinstancemethodname)
- **[Collections Framework (40 - 45% IQ)](#collections-framework-40-45-iq)**
- **[Collections framework is nothing but handling individual Objects(Collection Interface) and Group of objects(Map interface).](#collections-framework-is-nothing-but-handling-individual-objectscollection-interface-and-group-of-objectsmap-interface)**
  - [It provides the following sub interfaces](#it-provides-the-following-sub-interfaces)
- 📅 [23-07-2024](#23-07-2024)
  - [Methods of Collection interface](#methods-of-collection-interface)
  - [List interface](#list-interface)
  - [List interface Hierarchy](#list-interface-hierarchy)
  - [Behaviour of List interface Specific classes](#behaviour-of-list-interface-specific-classes)
- 📅 [24-07-2024](#24-07-2024)
  - [Methods of List interface](#methods-of-list-interface)
  - [In order to fetch the Collection Object from Collection we can use the following 9 ways which are as follows](#in-order-to-fetch-the-collection-object-from-collection-we-can-use-the-following-9-ways-which-are-as-follows)
- **[Enumeration](#enumeration)**
- **[Enumeration interface contains two methods](#enumeration-interface-contains-two-methods)**
- **[Iterator](#iterator)**
- **[Iterator interface](#iterator-interface)**
- **[Iterator itr = vector.iterator();](#iterator-itr-vectoriterator)**
  - [ListIterator interface](#listiterator-interface)
  - [Spliterator interface](#spliterator-interface)
  - [By using forEach() method](#by-using-foreach-method)
  - [How forEach(Consumer<T> cons ) method is working internally ?](#how-foreachconsumert-cons-method-is-working-internally)
  - [The following program explain how to retrieve the Collection object by using 9 ways](#the-following-program-explain-how-to-retrieve-the-collection-object-by-using-9-ways)
- **[Enumeration<String> ele = fruits.elements();](#enumerationstring-ele-fruitselements)**
- **[Iterator<String> itr = fruits.iterator();](#iteratorstring-itr-fruitsiterator)**
  - [Vector<E>](#vectore)
- **[ArrayList<Integer> al = new ArrayList<>();](#arraylistinteger-al-new-arraylist)**
  - [Working with Custom Object](#working-with-custom-object)
  - [Methods](#methods)
- 📅 [26-07-2024](#26-07-2024)
- **[ArrayList<E>](#arrayliste)**
  - [In ArrayList we have 3 types of Constructor](#in-arraylist-we-have-3-types-of-constructor)
- **[ArrayList<String> arl = new ArrayList<>();//Generic type](#arrayliststring-arl-new-arraylistgeneric-type)**
  - [Working with Custom Object](#working-with-custom-object-1)
- **[ArrayList<Customer> al = new ArrayList<>();](#arraylistcustomer-al-new-arraylist)**
- **[ArrayList<String> al1=new ArrayList<>();](#arrayliststring-al1new-arraylist)**
- **[ArrayList<String> al2=new ArrayList<>();](#arrayliststring-al2new-arraylist)**
- **[ArrayList<String> al3=new ArrayList<>();](#arrayliststring-al3new-arraylist)**
- **[ArrayList<String> al4=new ArrayList<>();](#arrayliststring-al4new-arraylist)**
  - [How to create immutable List in Collection](#how-to-create-immutable-list-in-collection)
  - [We can create immutable list in java by using following two ways](#we-can-create-immutable-list-in-java-by-using-following-two-ways)
- **[ArrayList<String> cityName = new ArrayList<>();](#arrayliststring-cityname-new-arraylist)**
- **[ArrayList<String> list = (ArrayList<String>) ois.readObject();](#arrayliststring-list-arrayliststring-oisreadobject)**
  - [Assignment](#assignment-5)
- **[ArrayList<String> city= new ArrayList<>();](#arrayliststring-city-new-arraylist)**
- **[ArrayList<Object> al = new ArrayList<>(); //Generic type](#arraylistobject-al-new-arraylist-generic-type)**
  - [Limitation of ArrayList](#limitation-of-arraylist)
  - [Time Complexcity of ArrayList](#time-complexcity-of-arraylist)
- **[ArrayList<String> arl = null;](#arrayliststring-arl-null)**
- **[Thread.sleep(2000);](#threadsleep2000-2)**
- **[ArrayList<String> listOfCity = new ArrayList<>();](#arrayliststring-listofcity-new-arraylist)**
- **[Iterator<String> itr = listOfCity.iterator();](#iteratorstring-itr-listofcityiterator)**
- **[Thread.sleep(500);](#threadsleep500-4)**
  - [LinkedList<E>](#linkedliste)
  - [LinkedList](#linkedlist)
- **[ArrayList is using Dynamic array data structure but LinkedList class is using LinkedList (Doubly LinkedList) data structure.](#arraylist-is-using-dynamic-array-data-structure-but-linkedlist-class-is-using-linkedlist-doubly-linkedlist-data-structure)**
- **[Iterator<Object> itr = list.iterator();](#iteratorobject-itr-listiterator)**
- 📅 [29-07-2024](#29-07-2024)
- **[Iterator<Dog> i3 = d.iterator();](#iteratordog-i3-diterator)**
  - [Set interface](#set-interface)
  - [Set interface Hierarchy](#set-interface-hierarchy)
- **[What is hashing algorithm ?](#what-is-hashing-algorithm)**
- 📅 [30-07-2024](#30-07-2024)
  - [SortedSet interface](#sortedset-interface)
  - [Program on Comparable<T> interface](#program-on-comparablet-interface)
  - [2 files](#2-files-17)
- **[ArrayList<Employee> listOfEmployee = new ArrayList<>();](#arraylistemployee-listofemployee-new-arraylist)**
  - [Limitation of Comparable interface](#limitation-of-comparable-interface)
  - [2 files](#2-files-18)
- **[ArrayList<Product> listOfProduct = new ArrayList<>();](#arraylistproduct-listofproduct-new-arraylist)**
- **[Comparator<Product> comId =  new Comparator<Product>()](#comparatorproduct-comid-new-comparatorproduct)**
- **[Comparator<Product> cmpName = (p1,p2) -> p1.productName().compareTo(p2.productName());](#comparatorproduct-cmpname-p1p2-p1productnamecomparetop2productname)**
- **[Comparable is not a Functional interface because due to current object support(this keyword) we need to write the sorting logic in the BLC class only so BLC class must implements Comparable interface.](#comparable-is-not-a-functional-interface-because-due-to-current-object-supportthis-keyword-we-need-to-write-the-sorting-logic-in-the-blc-class-only-so-blc-class-must-implements-comparable-interface)**
  - [Program to sort the Integer object in descending order](#program-to-sort-the-integer-object-in-descending-order)
- **[ArrayList<Integer> al = new ArrayList<>();](#arraylistinteger-al-new-arraylist-1)**
  - [TreeSet<E>](#treesete)
- **[Iterator<String> itr2 = t2.descendingIterator();  //for descending order](#iteratorstring-itr2-t2descendingiterator-for-descending-order)**
- **[Iterator<String> iterator = t.iterator();](#iteratorstring-iterator-titerator)**
- **[iterator.forEachRemaining(x -> System.out.println(x));](#iteratorforeachremainingx-systemoutprintlnx)**
- **[Iterator<Character> iterator = t.iterator();](#iteratorcharacter-iterator-titerator)**
- **[iterator.forEachRemaining(x -> System.out.println(x));](#iteratorforeachremainingx-systemoutprintlnx-1)**
- **[ArrayList<String> listOfCity = new ArrayList<>(cityName);](#arrayliststring-listofcity-new-arraylistcityname)**
  - [Methods of SortedSet interface](#methods-of-sortedset-interface)
  - [Map interface Hierarchy](#map-interface-hierarchy)
  - [Map interface](#map-interface)
- **[Iterator and ListIterator we can't use directly using Map.](#iterator-and-listiterator-we-cant-use-directly-using-map)**
  - [Methods of Map interface](#methods-of-map-interface)
- 📅 [02-08-2024](#02-08-2024)
  - [What will happen if we don't follow the contract ?](#what-will-happen-if-we-dont-follow-the-contract)
  - [Case 1](#case-1-2)
- 📅 [03-08-2024](#03-08-2024)
- **[Iterator itr=  map.entrySet().iterator();](#iterator-itr-mapentrysetiterator)**
  - [WeakHashMap<K,V>](#weakhashmapkv)
- **[Thread.sleep(5000);](#threadsleep5000)**
- 📅 [05-08-2024](#05-08-2024)
  - [How to generate System hashcode](#how-to-generate-system-hashcode)
- **[Iterator i = c.iterator();](#iterator-i-citerator)**
  - [Methods of SortedMap interface](#methods-of-sortedmap-interface)
  - [Assignment for NavigableMap Method](#assignment-for-navigablemap-method)
  - [Properties](#properties)
  - [Program 1](#program-1)
  - [Create a file with any name having extension .properties](#create-a-file-with-any-name-having-extension-properties)
- **[Iterator itr=set.iterator();](#iterator-itrsetiterator)**
- 📅 [06-08-2024](#06-08-2024)
  - [Queue interface](#queue-interface)
  - [Methods](#methods-1)
- **[Generics](#generics)**
  - [Why generic came into picture](#why-generic-came-into-picture)
- **[ArrayList al = new ArrayList();](#arraylist-al-new-arraylist)**
- **[ArrayList al = new ArrayList(); //raw type](#arraylist-al-new-arraylist-raw-type)**
- **[ArrayList t = new ArrayList(); //raw type](#arraylist-t-new-arraylist-raw-type)**
- **[ArrayList<String > al = new ArrayList<>();](#arrayliststring-al-new-arraylist)**
- **[ArrayList<String> al = new ArrayList<>();  //Generic type](#arrayliststring-al-new-arraylist-generic-type)**
- **[ArrayList<Dog> d = new ArrayList<>();](#arraylistdog-d-new-arraylist)**
- **[ArrayList<Car> a = new ArrayList<>();](#arraylistcar-a-new-arraylist)**
- **[ArrayList b = a;  //assigning Generic to raw type](#arraylist-b-a-assigning-generic-to-raw-type)**
- **[Iterator it = list.iterator();](#iterator-it-listiterator)**
- **[Iterator it = list.iterator();](#iterator-it-listiterator-1)**
- **[abstract class Animal](#abstract-class-animal-2)**
- **[abstract class Animal](#abstract-class-animal-3)**
- **[ArrayList al = new ArrayList();  [Runtime, Type Erasure]](#arraylist-al-new-arraylist-runtime-type-erasure)**
  - [Wild card character(?)](#wild-card-character)
- **[ArrayList<?> lp = new ArrayList<Child>(); //error](#arraylist-lp-new-arraylistchild-error)**
- **[ArrayList<Parent> lp1 = new ArrayList<Parent>();](#arraylistparent-lp1-new-arraylistparent)**
- **[ArrayList<Child> lp2 = new ArrayList<>();](#arraylistchild-lp2-new-arraylist)**
  - [How to create our own functional interfaces with multiple parameters](#how-to-create-our-own-functional-interfaces-with-multiple-parameters)
- **[ArrayList al = new ArrayList();](#arraylist-al-new-arraylist-1)**
- **[ArrayList<String> arl = new ArrayList<>();](#arrayliststring-arl-new-arraylist)**
- **[Thread t1 = new Thread(listOperations);](#thread-t1-new-threadlistoperations)**
- **[ArrayList<String> al = null;](#arrayliststring-al-null)**
- **[Thread.sleep(1500);](#threadsleep1500)**
- **[ArrayList<String> listOfFruits = new ArrayList<String>();](#arrayliststring-listoffruits-new-arrayliststring)**
- **[Iterator<String> itr = listOfFruits.iterator();](#iteratorstring-itr-listoffruitsiterator)**
- **[Thread.sleep(500);](#threadsleep500-5)**
- 📅 [08-08-2024](#08-08-2024)
  - [CopyOnWriteArrayList in java](#copyonwritearraylist-in-java)
- **[ArrayList is not thread-safe. We can�t use ArrayList in the multi-threaded environment because it creates a problem in ArrayList values  (Data inconsistency).](#arraylist-is-not-thread-safe-we-cant-use-arraylist-in-the-multi-threaded-environment-because-it-creates-a-problem-in-arraylist-values-data-inconsistency)**
  - [We have 3 constructors](#we-have-3-constructors)
- **[Iterator<String> iterator1 = copyOnWriteList.iterator();](#iteratorstring-iterator1-copyonwritelistiterator)**
- **[Iterator<String> iterator2 = copyOnWriteList.iterator();](#iteratorstring-iterator2-copyonwritelistiterator)**
- **[iterator1.forEachRemaining(System.out::println);](#iterator1foreachremainingsystemoutprintln)**
- **[iterator2.forEachRemaining(System.out::println);](#iterator2foreachremainingsystemoutprintln)**
- **[Thread.sleep(1000);](#threadsleep1000-10)**
- **[Iterator<String> itr = arl.iterator();](#iteratorstring-itr-arliterator)**
- **[Thread.sleep(500);](#threadsleep500-6)**
  - [CopyOnWriteArraySet](#copyonwritearrayset)
- **[Iterator itr = set.iterator();](#iterator-itr-setiterator)**
- **[Iterator<String> iterator = cityTemperatureMap.keySet().iterator();](#iteratorstring-iterator-citytemperaturemapkeysetiterator)**
- 📅 [09-08-2024](#09-08-2024)
  - [Stream API in Java](#stream-api-in-java)
  - [Creation of Streams to process the data](#creation-of-streams-to-process-the-data)
  - [We can create Stream from  collection or array with the help of stream() and Stream.of(T ...values) methods](#we-can-create-stream-from-collection-or-array-with-the-help-of-stream-and-streamoft-values-methods)
  - [Intermediate Operations](#intermediate-operations)
- **[ArrayList<Integer> al = new ArrayList<>();](#arraylistinteger-al-new-arraylist-2)**
- 📅 [10-08-2024](#10-08-2024)
  - [Working with Primitive Streams](#working-with-primitive-streams)
  - [LongStream flatMapToLong(Function<? super T, ? extends LongStream> mapper)](#longstream-flatmaptolongfunction-super-t-extends-longstream-mapper)
- 📅 [12-08-2024](#12-08-2024)
  - [Optional<T> class in Java](#optionalt-class-in-java)
  - [1) public static Optional<T> ofNullable(T x)](#1-public-static-optionalt-ofnullablet-x)
- 📅 [13-08-2024](#13-08-2024)
  - [New Date and Time API](#new-date-and-time-api)
  - [LocalDate](#localdate)
  - [DateTimeFormatter](#datetimeformatter)
  - [Terminal Operation in Stream in java](#terminal-operation-in-stream-in-java)
  - [Working with Predefined functional interfaces](#working-with-predefined-functional-interfaces-1)
  - [UnaryOperator<T> functional interface](#unaryoperatort-functional-interface)
  - [BinaryOperator<T> Functional interface](#binaryoperatort-functional-interface)
  - [ToIntFunction<T> functional interface](#tointfunctiont-functional-interface)
- **[ArrayList<Employee> listOfEmployee = new ArrayList<>();](#arraylistemployee-listofemployee-new-arraylist-1)**
  - [Predefined Functional interface](#predefined-functional-interface)
- 📅 [14-08-2024](#14-08-2024)
  - [How to convert a Map into Stream for data proessing?](#how-to-convert-a-map-into-stream-for-data-proessing)
- 📅 [16-08-2024](#16-08-2024)
  - [Networking in java](#networking-in-java)
  - [IP Address](#ip-address)
  - [URL class](#url-class)
  - [URLConnection class](#urlconnection-class)
  - [Socket](#socket)
  - [Creating a server that can send some data](#creating-a-server-that-can-send-some-data)


---

18-APRIL-24
javaravishanker@gmail.com


## What is a language?

A language is a communication media through which we can communicate with each other.


## What is a programming language?

A Programming language is an intermediate between the user and computer System.

Every language contains two important aspects :
1) Syntax (Rules given by the language)
2) Semantics (Meaning OR Structure of the language)

In English language, if we want to make a translation then the syntax is :

Subject + verb + Object
She  is   a   girl. [Valid]
She  is   a   box.  [Invalid but still I am following the syntax]

In our programming language also :

```java
int x = 12;
int y = 0;
int z = x /y;

```

In Java programming language we have 2 types of Security :

1) At Compilation level : Here our java compiler will verify whether the
code is valid or not according to the syntax.

2) At Runtime Level : Here our runtime environment will verify the semantics of the code that means the code is meaningful or not?

## Statically(Strongly) typed language

The languages where data type is compulsory before initialization of a variable are called statically typed language.
In these languages we can hold same kind of value during the execution of the program.

Ex:- C,C++,Core Java, C#


## Dynamically(Looesly) typed language

The languages where data type is not compulsory and it is optional before initialization of a variable then it is called dynamically typed language.

In these languages we can hold different kind of value during the execution of the program.
Ex:- Visual Basic, Javascript, Python

## What is a function

A function is a self defined block for any general purpose, calculation or printing some data.

The major benefits with function are :-
1) Modularity :- Dividing the bigger modules into number of smaller modules where each module will perform its independent task.

2) Easy understanding :- Once we divide the bigger task into number of smaller tasks then it is easy to understand the entire code.

3) Reusability :- We can reuse a particular module so many number of times so It enhances the reusability nature.


> **Note :- In java we always reuse our classes.**


4) Easy Debugging :- Debugging means finding the errors, With function It is easy to find out the errors because each module is independent with another module.

Why we pass parameter to a function :-
We pass parameter to a function for providing more information regrading the function.

```java
public void deposit()
{
}

```

Here we don't have parameter so, the information is partial, if we pass parameter then we will get complete information.

```java
public void deposit(int amount)
{
}
```


## Why functions are called method in java?

In C++ there is a facility to write a function inside the class as well as outside of the class by using :: (Scope resolution Operator),
But in java all the functions must be declared inside the class only.

That is the reason member functions are called method in java.

Variable -->  Field
function ---> Method

```java
int data;  Field

public void m1(int y)
{
   int x = 10;
}
```


## Flavors of Java


### We have total 4 types of flavors


1) JSE (Java Standard Edition)  [Core Java]

2) JEE (Java Enterprise Edition)  [Advanced Java]

3) JME (Java Micro Edition)  [Android Application]

4) JavaFX (It is used to design or develop GUI Applications) [Outdated]

```java
GUI = Graphical User interface
```


## What is the difference between Stand-alone program and web-related

Program ?

If the creation, compilation and execution of the program, everything is done in a single system then it is called Stand-alone Programs OR Desktop Application OR Software.

By using JSE we can develop stand-alone application.

On the other hand, if the creation of the program, compilation of the program and execution of the program, everything is done in different system in different places then it is called web-realted application OR Websites.

By using JEE we can deleop websites.

## Why java become so popular in the IT Industry ?


### The role of Java compiler

a) Compiler are used to check the syntax.
b) It also check the compatibility issues(LHS = RHS)
c) It converts the source code into machine code.

Java code :
a) Java programs must be saved having extension .java

b) java compiler(javac) is used to compile our code.

c) After successful compilation we are getting .class file (bytecode)

d) This .class file we submit to JVM for execution prupose (for executing my java code)

JVM :- It stands for Java Virtual Machine. It is a software in the form of interpreter  written in 'C' language.

Every browser contains JVM, Those browsers are known as JEB (Java Enabled Browsers) browsers.
C and C++ programs are platform dependent programs that means the .exe file created on one machine will not be executed on the another machine if the system configuration is different.

That is the reason C and C++ programs are not suitable for website development.

Where as on the other hand java is a platform independent language. Whenever we write a java program, the extension of java program must be .java.

Now this .java file we submit to java compiler (javac) for compilation process. After successful compilation the compiler will generate a very special machine code file i.e .class file (also known as bytecode). Now this .class file we submit to JVM for execution purpose.

The role of JVM is to load and execute the .class file. Here JVM plays a major role because It converts the .class file into appropriate machine code instruction (Operating System format) so java becomes platform independent language and it is highly suitable for website development.


> **Note :- We have different JVM for different Operating System that means JVM is platform dependent technology where as Java is platform Independent technology.**


## What is the difference between the bit code and byte code.

Bit code is directly understood by Operating System but on the other hand byte code is understood by JVM, JVM is going to convert this byte code into machine understandable format.

## 22-04-2024


## History of java

First Name of Java	-	OAK (Tree name) [1991]
First Version		-	23rd Jan 1996
Name of the language	-	Java (Island in Indonesia)
Father of Java		-	James Gosling
Project name		-	Green Project
Official Symbol		-	Coffee CUP

## What is comments ?

Comments are used to enhance the readability of the program. It is ignored by the compiler.
In java we have 3 types of comments


1) // Single line Comment

2) /* Multiple line
comment
*/

3) /**
Documentation comment

*/

Example :

```java
/**
```

Name of the Project : Online Shopping
Date created :- 12-12-2021
Last Modified - 16-01-2022
Author :- Ravishankar
Modules : -  10 Modules
*/


### WAP in Java to display Welcome message



```java
System.out.println("Welcome");


```


### Note

1) In java whenever we write a program we need at least a main method and a class.

2) In java the execution of the program always starts and ends with main method.


## Description of main() method

```java
public :-
public is an access modifier in java. The main method must be declared as public otherwise JVM cannot execute our main method or in other words JVM can't enter inside the main method for execution of the program.

```

If main method is not declared as public then program will compile but it will not be executed by JVM.


> **Note :- From java compiler point of view there is no rule to declare our methods as public.**


### static

Our main method must be declared as static so JVM need not to create the object to call the main method.

If we don't declare our main method as static then code will compile but It will not be executed by JVM.


> **Note :- For static member (static variable + static methods) Object is not required, on the other hand for non static member(instance variable + instance method) object is required.**


## 23-04-2024

```java
void :
void :-
```

It is a keyword. It means no return type. Whenever we define any method in java and if we don't want to return any kind of value from that particular method then we should write void before the name of the method.

Eg:

```java
public void input()                        public int accept()
{                                           {
}                                               return 15;
					    					}

```


> **Note :- In the main method if we don't write void or any other kind of return type then it will generate a compilation error.**


In java whenever we define a method then compulsory we should define return type of method.(Syntax rule)

### main()

It is a user-defined method because a user is responsible to define some logic inside the main method.

main() method is very important method because every program execution will start from main() method only, as well as the execution of the program ends with main() method only.

Q) Can we write multiple method with same name ?
Yes, We can write multiple methods with same name but argument must be different otherwise code will not compile.


> **Note :- We can also write multiple main methods with different parameter but JVM will always execute the main method which takes String [] args (String array) as a parameter as shown in the program below.**


```java
public class Test
{
    public static void main(String args[])
    {
	 System.out.println("String array");
	}

    public static void main(String args)
    {
	 System.out.println("String Ordinary Variable");
	}

	public static void main(int args)
        {
	 System.out.println("Int Ordinary Variable");
	}

}
```


## Command Line Argument (Introduction only)

Whenever we pass an argument/parameter to the main method then it is called Command Line Argument.

The argument inside the main method is String because String is a alpha-numeric collection of character so, It can accept numbers,decimals, characters, combination of number and character.

That is the reason java software people has provided String as a parameter inside the main method.(More Wider scope to accept the multiple values)

## System.out.println()

It is an output statement in java, By using System.out.println() statement we can print anything on the console.

In System.out.println(), System is a predefined class available in java.lang package, out is a final, static reference variable of PrintStream class available in java.io package and println() is a predfined method available in PrintStream class.

In System.out, .(dot) is a member access operator. It is called as period. It is used to access the member of the class.

Actually, It creates HAS-A relation with System and PrintStream class.
```java
//WAP to add two numbers

//WAP to add two numbers
public class Addition
{
	public static void main(String[] args)
	{
		int x = 100;
		int y = 200;
		int z = x + y;
		System.out.println(z);
	}
}

```


> **Note :- Here we are getting the output as 300 but It is not user-friendly.**

```java
//WAP to add two numbers
public class Addition
{
	public static void main(String[] args)
	{
		int x = 100;
		int y = 200;
		int z = x + y;
		System.out.println("Addition is :"+z);
	}
}

```


> **Note :- We are using + operator to provide user-friendly message.**


## 24-04-2024

```java
//WAP to add two numbers without 3rd variable
public class AdditionWithout3rdVariable
{
	public static void main(String[] args)
	{
		int x = 100;
		int y = 200;
		System.out.println("Sum is :"+x+y); //100200
		System.out.println(+x+y); //300
		System.out.println(""+x+y); //100200
		System.out.println("Sum is :"+(x+y)); //300
	}
}
```


### IQ

```java
public class IQ
{
	public static void main(String[] args)
	{
		String str = 15 + 29 + "Ravi" + 40 + 40;
		System.out.println(str); //44Ravi4040
	}
}
```


## Command Line Argument

Whenever we pass any argument to the main method then it is called Command Line Argument.

By using command line argument we can pass some value at runtime.

The advantage of Command Line Argumenet is "Single time Compilation and number of times execution".


> **Note :- If we modify our source code then we need to re-compile**

our .java file so new .class file will be generated.
```java
//WAP to accept the value from the command line argument

public class Command
{
	public static void main(String[] cmd)
	{
		System.out.println(cmd[0]);
	}
}

javac Command.java
java Command Scott Smith

```

It will print Scott
```java
//Program to print complete name from CLA
public class CommandFullName
{
	public static void main(String[] cmd)
	{
		System.out.println(cmd[0]);

	}
}

javac CommandFullName.java
java CommandFullName "Virat Kohli"

```

It will print Virat Kohli
```java
//Program to print the value from CLA without passing at runtime
public class CommandWithoutValue
{
	public static void main(String[] cmd)
	{
		System.out.println(cmd[0]);

	}
}

javac CommandWithoutValue.java
java CommandWithoutValue (At runtime we are not passing any value)
```

so, java.lang.ArrayIndexOutOfBoundsException
```java
//Single time compilation and number of times execution
public class Command
{
	public static void main(String[] cmd)
	{
		System.out.println(cmd[0]);

	}
}

javac Command.java
java Command Virat  -> It will Print Virat
java Command Rohit  -> It will Print Rohit
java Command Bumrah  -> It will Print Bumrah

```


> **Note :- At the time of execution, we can have different values.**

```java
//WAP to add two numbers by using Command Line Argument :

public class CommandAddition
{
	public static void main(String[] args)
	{
		System.out.println(args[0] + args[1]);
	}
}

javac CommandAddition.java
java CommandAddition 123  45

```

It will print 12345

Here the numeric values i.e 123 and 45 are of type String so, + operator is working as String concatenation operator.

### How to convert String value into integer

If we want to convert any String value into corresponding integer then java software people has provided predefined class called Integer available in java.lang package.

In this class we have predefined static method, parseInt(String x) which is accepting a single parameter String as a parameter and convert this String into int value as shown in the below example.

```java
public class Integer
{
  public static int parseInt(String x)
  {
   //Here logic is written to convert x which is String into corresponding int
   //return int value
  }
}

```


> **Note :-  "123" ------> parseInt(String x) ---------> 123 [Accepting String and converting into integer]**

```java
public class CommandAddition
{
	public static void main(String[] args)
	{
                int a = Integer.parseInt(args[0]);
		int b = Integer.parseInt(args[1]);

		System.out.println("Sum is :"+(a+b));
	}
}

javac CommandAddition.java
java CommandAddition 12 36

```

Sum is : 48

### How to convert String to double value

We have a predefined class Double available in java.lang package, which contains predefined static method parseDouble(String str) through which we can convert String into double value.
WAP to find out area of Circle by taking the radius value from Command Line Argument

```java
public class AreaOfCircle
{
	public static void main(String[] args)
	{
		//Converting String value into double
		double rad = Double.parseDouble(args[0]);

                final double PI = 3.14;

		double areaOfCircle = PI * rad * rad;

		System.out.println("Area of Circle is :"+areaOfCircle);
	}
}

```


## 25-04-2024


## Eclipse IDE

IDE stands for Integrated Development Environment.

By Using Eclipse IDE we can develop, Compile and Execute our program in a single window.

By using Eclipse IDE, We can reduce our development time, Once
development time will be reduced than automatically the cost of the
project will be reduced.

Writing First Java Program in the Eclipse IDE :
At the time of starting the Eclipse IDE, We need to select any folder (Workspace) where we want to store all our java programs.



## What is a Package ?

A package is nothing but folder in windows. In order to create a package we should use package keyword.


Test.java
```java
package com.ravi.basic;

public class Test
{

}

```

Here Test.java is source code which is inside the package com.ravi.basic so if we compile the above code with the following statement then 3 folders will be created i.e com, ravi and basic

```java
javac  - d  . Test.java

```

[javac space hyphen d space dot space FileName.java]


> **Note :- Inside com folder, ravi folder will be created, inside ravi folder basic folder will be created and Test.class will be placed inside basic folder.**


A package is divided into two types :

1) Predefined OR Built-In package : The packages which are created by java software people are called predefined packages.
Example : java.lang

```java
  package java.lang;
  public class Integer
  {
  }

```

2) Userdefined Package OR Custom Package :- The packages which are created by user are called user-defined packages.
Example :
com.ravi.basic
com.ravi.introduction
com.ravi.constructor

### What to craete a class in the user-defined package

Right click on the package -> class -> Provide the name of the class -> select main method -> Finish

First Program in Eclipse IDE :
```java
package com.ravi.introduction;

public class Welcome
{
	public static void main(String[] args)
	{
	 System.out.println("Welcome to Java");
	}

}
```


### How to execute Command Line Argument in Eclipse IDE


### In order to pass value at runtime (Command Line Argument Value) we need to follow the following steps


1) Right click on Program
2) Run as
3) Run Configuration
4) Verify main (Class Name + Package Name)
5) Argument
6) Pass appropriate argument
7) Click on the Run button
```java
package com.ravi.introduction;

public class Command
{
	public static void main(String[] args)
	{
		System.out.println(args[1]);
	}
}
```


## Command Line Argument Program to find out square of the number

```java
package com.ravi.introduction;

public class GetSquareByCommand
{
  public static void main(String[] args)
  {
	 int num = Integer.parseInt(args[0]);
	 System.out.println("Square of "+num+" is :"+(num*num));
  }
}
```


### Write a Program to show how Integer.parseInt() works internally ?

```java
package com.ravi.introduction;


class Calulator
{
	public static int doSum(int x, int y)
	{
		int z = x + y;
		return z;
	}

	public static int getCubeOfNumber(int num)
	{
		return (num*num*num);
	}

}


public class ParseIntInternal
{
	public static void main(String[] args)
	{
	 int res = Calulator.doSum(12, 36);
	 System.out.println("Sum is :"+res);

	 res = Calulator.getCubeOfNumber(5);
	 System.out.println("Cube is :"+res);

	}

}
```

*Naming convention in Java :
1) How to write a class in java
While writing a class in java we should follow pascal naming convention. A java class represents noun.

```java
ThisIsExampleOfClass (Each word first letter is capital)
```

Example :
String
System
Integer
BufferedReader
DataInputStream
ClassNotFoundException
ArithmeticException

2) How to write a method in java :
In order to write methods in java we need to follow camel case naming convention. A java method represents verb.

```java
thisIsExampleOfMethod()

```

Example:
```java
read()
readLine()
toUpperCase()
charAt()
parseInt()


```

3) How to write variable(Fields) in java
In order to write variables in java we need to follow camel case naming convention.

```java
rollNumber;
employeeName;
customerNumber;
customerBill;

```

4) How to write final variable(Field)
Final variables must be in upper-case letter.

```java
final double PI = 3.14;
final int A = 90;

```

5) How to write final and static variable

```java
   MAX_VALUE;
   MIN_VALUE;
```

Each character must be capital and in between every word _ symbol should be there.

6) How to write package
Package name must be in small character. It is reverse of company name.
```java
   com.ravi.basic;
```

com.tcs.shopping
com.wipro.chating

## 26-04-2024


## Token

A token is the smallest unit of the program that is identified by the compiler.

Every Java statements and expressions are created using tokens.

A token can be divided into 5 types

1) Keywords
2) Identifiers
3) Literals
4) Punctuators
5) Operators


## Keyword

A keyword is a predefined word whose meaning is already defined by the compiler.

In java all the keywords must be in lowercase only.

A keyword we can't use as a name of the variable, name of the class or name of the method.

true, false and null look like keywords but actually they are literals.


## Identifiers

A name in java program  by default considered as identifiers.

Assigned to variable, method, classes to uniquely identify them.

We can't use keyword as an identifier.

Ex:-

```java
class Fan
{
   int coil  ;

   void start()
   {
   }
}

```

Here Fan(Name of the class), coil (Name of the variable) and start(Name of the function) are identifiers.

### Rules for defining an identifier

1) Can consist of uppercase(A-Z), lowercase(a-z),  digits(0-9), $ sign, and   underscore (_)
2) Begins with letter, $, and _
3) It is case sensitive
4) Cannot be a keyword
5) No limitation of length


## Literals


## Literals

Assigning some constant value to variable is called Literal.

Java supports 6 types of Literals :

```java
1) Integral Literal  Ex:-  int x = 15;

2) Floating Point Literal  Ex:- float x = 3.5f;

3) Character Literal Ex:- char ch = 'A';

4) Boolean Literal Ex:- boolean b = true;

5) String Literal Ex:- String x = "Naresh i Technology";

```


> **Note :- null is also a literal.**


## Integral Literal

1) If a numeric literal does not contain decimal or fraction then it is called Integral Literal.
Example :  12, 90, 56, 78

2) In integral literals we have 4 data types

a) byte (8 bits)
b) short (16 bits)
c) int (32 bits)
d) long (64 bits)

3) An integral literal we assign into 4 different forms

a) Decimal Literal
b) Octal Literal
c) Hexadecimal Literal
d) Binary Literal (Available from java 1.7)

a) Decimal Literal : By default Integral literal is of decimal type only. Here the range of digit is 0 - 9 i.e 10 digits because base/Radix of decimal is 10.

b) Octal Literal : If Integral Literal starts with 0 (zero) then it will become octal Litearl. Here the range of digits are 0-7
because base of octal is 8.

Example :
```java
    int x  = 0123; //Valid
    int y = 0777; //valid
    int z = 018; //Invalid [Digit 8 out of the range]

```

c) Hexadecimal Litearl : If an integral literal starts with 0X (zero capital X) OR 0x (zero small x) then it will become
Hexadecimal Litearl. Here range of digits are 0 -9 and A-F.Here
base of Hexadecimal is 16.
Example :
```java
    int x  = 0Xadd; //Valid
    int y = 0xface; //valid
    int z = 0Xage; //Invalid [Digit g out of the range]


```

d) Binary Literal : It came from java 1.7. If an integral litearl starts with 0B (zero capital B) or 0b (Zero small b) then it is
treated as Binary literal. Here range of digits are 0 and 1 because the base is 2.

Example :
```java
    int x  = 0B101; //Valid
    int y = 0b111; //valid
    int z = 0B12; //Invalid [Digit 2 out of the range]


```

4) As a developer we can represent an integral literal into 4 different form i.e decimal, octal, headecimal and binary but JVM always convert these literals into decimal format.

```java
package batch33;

public class Test
{
	public static void main(String[] args)
	{
	   int x = 015;
	   System.out.println(x);
	}

}
```

```java
package batch33;

public class Test
{
	public static void main(String[] args)
	{
	   int x = 0Xadd;
	   System.out.println(x);
	}

}
```

```java
package batch33;

public class Test
{
	public static void main(String[] args)
	{
	   int x = 0b101;
	   System.out.println(x);
	}

}
```

5) By default every integral literal is of type int only but we can specify explicitly as long type by suffixing with l (small l) OR L (Capital L).

According to industry standard L is more preferable because l (small l) looks like 1(digit 1).

There is no direct way to specify byte and short literals explicitly. If we assign any integral literal to byte variable and if the value is within the range (-128 to 127) then it is automatically treated as byte literals because compiler internally converts from int to byte.

If we assign integral literals to short and if the value is within the range (-32768 to 32767) then automatically it is treated as short literals because compiler internally converts from int to short.

```java
/* By default every integral literal is of type int only*/
public class Test4
{
public static void main(String[] args)
	{
```

byte b = 128; //error 128 is out of range
```java
		System.out.println(b);

```

short s = 32768; //32768 error out of the
```java
		System.out.println(s);
    }
}
```


## 27-04-2024

```java
//Assigning smaller data type value to bigger data type
public class Test5
{
public static void main(String[] args)
	{
   	    byte b = 125;  //byte b =(byte) 125;
```

short s = b;  //Automatic OR Implicit OR Widening
```java
		System.out.println(s);
	}
}


```


> **Note :- If we try to assign smaller data type value to bigger data type value then It is called Automatic OR Implicit OR Widening**

type.
```java
//Converting bigger type to smaller type
public class Test6
{
public static void main(String[] args)
	{
		short s = 127;
```

byte b = (byte) s;    //Explicit OR Narrowing OR manual
```java
		System.out.println(b);
	}
}


```

If we try to assign bigger data type value to smaller data type then by default compiler will not allow then user will convert the bigger type into smaller type known as
Explicit OR Manual OR Narrowing
```java
public class Test7
 {
 public static void main(String[] args)
 {
		byte x = (byte) 127L;
		System.out.println("x value  = "+x);

		long l = 29L;
		System.out.println("l value  = "+l);

        int y = (int) 18L;
		System.out.println("y value  = "+y);

  }
 }
```

-----------------------------------------------------------------Is java pure Object-Oriented language ?
No, Java is not a pure Object-Oriented language. In fact any language which accepts the primary data type like int, float, char is not a pure object oriented language hence java is also not a pure object oriented language.

Example of pure object oriented language : Ruby, smalltalk and so on

If we remove all 8 primitive data types from java then Java will become pure object oriented language.

In java we have a concept called Wrapper classes through which we can convert the primary data types into corresponding Wrapper Object.(Autoboxing 1.5V)

Primary data types                Corresponding Wrapper Object
byte				-		Byte
short				-		Short
int				-		Integer
long				-		Long
float				-		Float
double				-		Double
char				-		Character
boolean				-		Boolean

All these wrapper classes are available in java.lang package.
```java
//Wrapper claases
public class Test8
{
	public static void main(String[] args)
	{
		Integer x = 24;
		Integer y = 24;
		Integer z = x + y;
		System.out.println("The sum is :"+z);

		Boolean b = true;
		System.out.println(b);

		Double d = 90.90;
		System.out.println(d);

		Character c = 'A';
		System.out.println(c);
	}
}
```


### How to know the minimum and maximum value as well as size of integral literal data types

Thses classes (Wrapper classe) are providing the static and final variables through which we can find out the minimum, maximum value as well as size of the data types

Ex:- I want to find out the range and size of Byte class

Byte.MIN_VALUE = -128

Byte.MAX_VALUE = 127

Byte.SIZE = 8 (in bits format)

Here MIN_VALUE, MAX_VALUE and SIZE these are static and final variables available in these classes(Byte, Short, Integer and Long).
```java
 //Program to find out the range and size of Integeral Data type
public class Test9
{
	public static void main(String[] args)
	{
		System.out.println("\n Byte range:");
		System.out.println(" min: " + Byte.MIN_VALUE);
		System.out.println(" max: " + Byte.MAX_VALUE);
		System.out.println(" size :"+Byte.SIZE);

		System.out.println("\n Short range:");
		System.out.println(" min: " + Short.MIN_VALUE);
		System.out.println(" max: " + Short.MAX_VALUE);
		System.out.println(" size :"+Short.SIZE);

		System.out.println("\n Integer range:");
		System.out.println(" min: " + Integer.MIN_VALUE);
		System.out.println(" max: " + Integer.MAX_VALUE);
		System.out.println(" size :"+Integer.SIZE);

		System.out.println("\n Long range:");
		System.out.println(" min: " + Long.MIN_VALUE);
		System.out.println(" max: " + Long.MAX_VALUE);
		System.out.println(" size :"+Long.SIZE);

	}
}
```

```java
//We can provide _ in integral literal
public class Test10
{
	public static void main(String[] args)
	{
	    long mobile = 98_1234_5678L;
		System.out.println("Mobile Number is :"+mobile);
	}
}

```


> **Note :- From java 1.7V now we can provide _ symbol in numeric**

literal just to increase the readability of the code.
```java
public class Test11
{
	public static void main(String[] args)
	{
		final int x = 127;
		byte b = x;
		System.out.println(b);
	}
}

```


> **Note :- The above code will and execute also.**


### var keyword in java

From java 10v, Java software people has provided var keyword which we can use only as a local variable.

Initialization is compulsory at time of declaration.

```java
class Test
{
```

var x = 100; //error (Can use as a local variable)

```java
	public static void main(String[] args)
        {

	}

}
```

```java
class Test
{

	public static void main(String[] args)
         {
```

var x ; //error [Initialization is compulsory Here]
```java
            x = 100;
	}

}
```

How to convert decimal to any other number system (octal, hexadecimal and Binary)

```java
// Converting from decimal to another number system
public class Test12
{
      public static void main(String[] argv)
      {
		   //decimal to Binary
           System.out.println(Integer.toBinaryString(5)); //101

		   //decimal to Octal
           System.out.println(Integer.toOctalString(15)); //17

		   //decimal to Hexadecimal
           System.out.println(Integer.toHexString(2781)); //add
      }
}

```

Integer class has provided the following predefined static methods to convert decimal to another number system like binary, octal and hexadecimal toBinaryString(), toOctalString() , toHexString()

## 29-04-2024


### floating Point Literals

1) If a numeric literal contains decimal or fraction then it is called floating point literal.
Example : 15.0, 23.6, 6.7 and so on

2) In floating point literal we have 2 data types :
a) float (32 bits)
b) double (64 bits)

3) By default every floating point literal is of type double only so, the following expression will generate compilation error

```java
        float f = 1.2; //error

```

Now we can reprsent float value by using following

```java
        float f1 = (float) 0.9;

	float f2 = 12.45f;

        float f3 = 15.45F;

```

4) All the floating point literals are of type double but still compiler has provided two flavors to represent double value explicitly to enhance code readability.

```java
          double d1 = 12.78D;
	  double d2 = 23.90d;

```

5) Floating point literal we can reprsent in exponent form.

```java
      double d1 = 15e2;
             d1 = 15 X 10 to the power 2
	     d1 = 1500.0

```

* 6) While working with integral literal, we can represent an

## integral literal in 4 different forms i.e decimal, octal,

hexadecimal and binary but while working with floating point literal we have only one form i.e decimal.

*7) Integral literal (byte, short, int and long) we can assign to floating point literal (float and double) but floating point literal (float and double) we can't assign to Integral literal (byte, short, int and long).
```java
public class Test
{
	public static void main(String[] args)
	{
		float f = 2.0; //error
		System.out.println(f);
	}
}
```

```java
public class Test1
{
	public static void main(String[] args)
	{
		float b = 15.29F;
		float c = 15.25f;
		float d = (float) 15.30;

		System.out.println(b+" : "+c+" : "+d);

	}
}
```

```java
public class Test2
{
	public static void main(String[] args)
	{
		double d = 15.15;
		double e = 15d;
		double f = 15.15D;

		System.out.println(d+" , "+e+" , "+f);
	}
}
```

```java
public class Test3
{
	public static void main(String[] args)
	{
		 double x = 0129.89;

		 double y = 0167;

		 double z = 0178; //error

		System.out.println(x+","+y+","+z);
	}
}
```

```java
class Test4
{
	public static void main(String[] args)
	{
		double x = 0X29;

		double y = 0X9.15; //error

		System.out.println(x+","+y);
	}
}
```

```java
public class Test5
{
	public static void main(String[] args)
	{
		double d1 = 15e-3;
		System.out.println("d1 value is :"+d1);

		double d2 = 15e3;
		System.out.println("d2 value is :"+d2);
	}
}
```

```java
public class Test6
{
	public static void main(String[] args)
	{
		double a = 0791; //error

		double b = 0791.0;

		double c = 0777;

		double d = 0Xdead;

		double e = 0Xdead.0; //error
	}
}
```

```java
public class Test7
{
	public static void main(String[] args)
	{
	   double a = 1.5e3;
	   float b = 1.5e3;  //e
	   float c = 1.5e3F;
	   double d = 10;
	   int e = 10.0;  //e
```

long f = 10D; //e
```java
	   int g = 10F;  //e
```

long l = 12.78F; //e
```java
	}
}
```

```java
//Range and size of floating point literal
public class Test8
{
	public static void main(String[] args)
	{
		System.out.println("\n Float range:");
		System.out.println(" min: " + Float.MIN_VALUE);
		System.out.println(" max: " + Float.MAX_VALUE);
		System.out.println(" size :"+Float.SIZE);

		System.out.println("\n Double range:");
		System.out.println(" min: " + Double.MIN_VALUE);
		System.out.println(" max: " + Double.MAX_VALUE);
		System.out.println(" size :"+Double.SIZE);
	}
}
```


## Boolean literal

1) It is used to represent two states i.e true OR false.
Example :
```java
    boolean isValid = true;
    boolean isEmpty = false;


```

2) Here we have only 1 data type i.e boolean which accepts
1 bit of memory OR depends upon JVM implementation


3) Unlike C and C++ we can't assign 0 and 1 to booelan data type because in java, 0 and 1 treated as int type only.

```java
      boolean isValid = 0; [Valid in C but invalid in java]
      boolean isValid = 1; [Valid in C but invalid in java]

```

4) We can't assign String value to boolean data type, It is incompatible type as shown below.

```java
      boolean isValid = "true"; //Invalid

```

```java
public class Test1
{
    public static void main(String[] args)
    {
        boolean isValid = true;
        boolean isEmpty = false;

        System.out.println(isValid);
        System.out.println(isEmpty);
     }
}
```

```java
public class Test2
{
    public static void main(String[] args)
    {
	boolean c = 0; //error
        boolean d = 1; /error
        System.out.println(c);
        System.out.println(d);
    }
}
```

```java
public class Test3
{
	public static void main(String[] args)
	{
		boolean x = "true";
		boolean y = "false";
		System.out.println(x);
        System.out.println(y);
	}
}
```


## String Literal

A string literal in Java is basically a sequence of characters. These characters can be anything like alphabets, numbers or symbols which are enclosed with double quotes. So we can say String is alpha-numeric collection of character.


How we can create String in Java :-

### In java String can be created by using 3 ways


1) By using String Literal

```java
   String x = "Ravi";

```

2) By using new keyword

```java
   String y = new String("Hyderabad");

```

3) By using character array

```java
   char z[] = {'H','E','L','L','O'};
```

```java
//Three Ways to create the String Object
public class StringTest1
{
	public static void main(String[] args)
	{
		String s1 = "Hello World";       //Literal
		System.out.println(s1);

		String s2 = new String("Ravi"); //Using new Keyword
		System.out.println(s2);

		char s3[] = {'H','E','L','L','O'}; //Character Array
		System.out.println(s3);//here hashcode will print

	}
}
```

```java
//String is collection of alpha-numeric character
public class StringTest2
{
	public static void main(String[] args)
	{
		String x="B-61 Hyderabad";
		System.out.println(x);

		String y = "123";
		System.out.println(y);

		String z = "67.90";
		System.out.println(z);

		String p = "A";
		System.out.println(p);
	}
}
```

```java
//IQ
public class StringTest3
{
	public static void main(String []args)
	{
		String s = 15+29+"Ravi"+40+40;
		System.out.println(s);

	}
}
```


## 30-04-2024


## Character Literal

1) It is also known as char literal.

2) Here we have only one data type char data type which accept
16 bits (2 bytes) of memory.

3) We can represent char literal in the following ways :

a) Single character enclosed with single quotes.

```java
    Example : char ch = 'A';

```

b) In older languages like C and C++ which supports ASCII the
range of value is 0-255, on the other hand Java supports
UNICODE where the range is 0 - 65535.

```java
      Example :  char ch = 65535;

```

c) We can also assign character literal to integral literal
to get the UNICODE value of that particular character.

```java
      Example :  int val =  'A';

```

d) We can represent char literal in 4 digit hexadecimal number to represent UNICODE value where the format is :

'\uXXXX'

Here \u stands for UNICODE where as X represents Digits.

Here   '\u0000' : Minimum Value
'\uffff' : Maximum value becoz it is hexadecimal


e) All the escape sequences we can represent as a char literal.
```java
public class Test1
{
	public static void main(String[] args)
	{
		char ch1 = 'a';
		System.out.println("ch1 value is :"+ch1);

		char ch2 = 97;
		System.out.println("ch2 value is :"+ch2);	//a will print
	}
}
```

```java
class Test2
{
	public static void main(String[] args)
	{
		int ch = 'A';
		System.out.println("ch value is :"+ch);//65 will print
	}
}
```

```java
//The UNICODE value for ? character is 63
public class Test3
{
	public static void main(String[] args)
	{
		char ch1 = 63;
		System.out.println("ch1 value is :"+ch1);

		char ch2 = 64;
		System.out.println("ch2 value is :"+ch2);

		char ch3 = 65;
		System.out.println("ch3 value is :"+ch3);
	}
}

```


> **Note :- The UNICODE value for ? symbol is 63.**

```java
public class Test4
{
	public static void main(String[] args)
	{
		char ch1 = 65535;
                System.out.println("ch1 value is :"+ch1);

		char ch2 = 0Xadd;
		System.out.println("ch2 value is :"+ch2);
	}
}

```

Here the values are beyond the range of keyboard (ASCII character)
and corresponding language translator is available in the laptop so, we are getting ? symbol.
```java
//Addition of two character in the form of Integer
public class Test5
{
public static void main(String txt[ ])
  {
	int x = 'A';
    int y = 'B';
    System.out.println(x+y); //add the ascii value
	System.out.println('A' + 'A'); 	//same above
   }
}
```

```java
//Range of UNICODE Value (65535) OR '\uffff'
class Test6
{
	public static void main(String[] args)
	{
		char ch1 = 65535;
		System.out.println("ch value is :"+ch1);

		char ch2 = 65536; //error
		System.out.println("ch value is :"+ch2);
	}
}
```

```java
//WAP in java to describe unicode representation of char in hexadecimal format
public class Test7
{
	public static void main(String[] args)
	{
		int ch1 = '\u0000';
		System.out.println(ch1);

		char ch2 = '\uffff';
		System.out.println(ch2);

		char ch3 = '\u0041';
        System.out.println(ch3);

		char ch4 = '\u0061';
		System.out.println(ch4);
	}
}
```

```java
class Test8
{
	public static void main(String[] args)
	{
		char c1 = 'A';
		char c2 = 65;
		char c3 = '\u0041';

		System.out.println("c1 = "+c1+", c2 ="+c2+", c3 ="+c3);
	}
}
```

```java
class Test9
{
	public static void main(String[] args)
	{
		int x = 'A';
		int y = '\u0041';
		System.out.println("x = "+x+" y ="+y);
	}
}
```

```java
//Every escape sequence is char literal
class Test10
{
	public static void main(String [] args)
	{
		char ch ='\n';
		System.out.println("Hello");
		System.out.println(ch);

	}
}
```

```java
public class Test11
{
	public static void main(String[] args)
	{
		System.out.println(Character.MIN_VALUE); //white space
		System.out.println(Character.MAX_VALUE); //?
		System.out.println(Character.SIZE); //16 bits

	}
}
```

```java
//Java Unicodes
public class Test12
{
	public static void main(String[] args)
	{
		System.out.println(" Java Unicodes\n");

		for (int i = 31; i < 126; i++)
		{
			char ch = (char)i; // Convert unicode to character
			String str = i + "  "+ ch;

			System.out.print(str + "\t\t");
			if ((i % 5) == 0)
			{
			 System.out.println();
			}
		}
	}
}
```


### 4) Punctuators

It is  also called separators.

It is used to inform the compiler how things are grouped in the code.

()  {}   []   ;   ,   .   @   � (var args)
5) Operators
It is a symbol which describes that how a calculation will be performed on operands.


## Types Of Operators

1) Arithmetic Operator (Binary Operator)

2) Unary Operators

3) Assignment Operator

4) Relational Operator

5) Logical Operators

6) Boolean Operators

7) Bitwise Operators

8) Ternary Operator

9) Member Operator( Dot . Operator)

10) new Operator

11) instanceof Operator


## 01-05-2024


## Basic concepts of Operators

```java
public class Test
{
    public static void main(String [] args)
    {
	  int x = 5;
	  int y = x++;
	  System.out.println(x +": "+y);
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
	  int x = 5;
	  int y = ++x;
	  System.out.println(x +": "+y);
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
	  int x = 5;
	  int y = ++5; //error
	  System.out.println(x +": "+y);
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
	  int x = 5;
	  int y = ++(++x); //error
	  System.out.println(x +": "+y);
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
	  char ch = 'A';
	  ch++;
	  System.out.println(ch);

	  double d1 = 90.90;
	  d1++;
	  System.out.println(d1);
	}
}

```


> **Note :- Increment and Decrement Operator we can apply with any data type except boolean.**


### What is local variable ?

If a variable is declared inside the method body(not as a method parameter) then it is called local/temporary/stack/automatic variable.

A local variable must be initialized before use.

We can't apply any kind of access modifier on local variable except final.

As far as it's scope is concerned, It must be accessible within the same method body only.

```java
public class Test
{
    public static void main(String [] args)
    {
	   final int x = 10;
	   System.out.println(x);
	}
}

```


### Why we can't access local variable outside of the method ?

In java, Methods are executed in a special memory area called Stack area.

Stack is data structure which works on the basis of LIFO.

In java whenever we call a method then one stack frame is cretaed internally.

This Stack frame will automatically deleted, once the execution of the method is completed so with that stack frame all the local variables are also deleted from the memory as shown in the Program below.

```java
package com.ravi.local;

public class LocalVariableScope
{
	public static void main(String[] args)
	{
      System.out.println("Main Method started...");
      m1();
      System.out.println("Main Method ended...");
	}

	public static void m1()
	{
		System.out.println("M1 Method started...");
	    m2();
	    System.out.println("M1 Method ended...");
	}

	public static void m2()
	{
		int x = 100;
		System.out.println("I am m2 method :"+x);
	}

}
```


### Limitation of Command Line Argument

As we know by using Command Line Argument, we can pass some value
at runtime, These values are stroed in String array variable and then only the exceution of the program will be started.

In Command line Argumenet we can't ask to enter the value from our end user as shown in the Program.

AcceptingCharacter.java

```java
package com.ravi.command;
//Program to read your gender for the Command Line Argument

public class AcceptingCharacter
{
	public static void main(String[] args)
	{
		System.out.print("Enter your Gender :");
		char gen =  args[0].charAt(0);
		System.out.println(gen);

	}

}
```


## Working with Scanner class

As we know to provide user friendly message command Line Argument is not applicable so java software people has provided the follwing classes to read the data from the Client.

1) DataInputStream (java.io)
2) BufferedReader (java.io)
3) System.in.read()
4) Console class (java.io)
5) Scanner class (java.util)

Scanner class :
From java 1.5v, Java software people has provided predefined class called Scanner thorough which we can read the data from the client.

```java
static variable of System class :
```

System class has provided 3 static variables

a) System.out : To print normal message on the screen.
b) System.err : To Print error message on the screen.
c) System.in : To accept the value from the Source.

How to create an object for Scanner class :
```java
  Scanner sc = new Scanner(System.in);

```

Methods of Scanner class :
1) public String next() : Will read a single word.

2) public String nextLine() : will read multiple words OR complete line.

3) public byte nextByte() : will read byte value

4) public short nextShort() : will read short value

5) public int nextInt() : will read int value

6) public long nextLong() : will read long value

7) public float nextFloat() : will read float value

8) public double nextDouble() : will read double value

9) public boolean nextBoolean() : will read boolean value

10) public char next().charAt(0) : will read a character


### WAP to read the name from Keyword

```java
import java.util.*;

public class ReadName
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter your Name :");
		String name =  sc.nextLine();
		System.out.println("Your name is :"+name);

	}
}
```


## 02-05-2024

```java
//Progran to read character from the user.
package com.ravi.scanner;

import java.util.Scanner;

public class ReadCharacter
{
	public static void main(String[] args)
	{
	  Scanner sc = new Scanner(System.in);
	  System.out.print("Enter your Gender [M/F] :");
	  char gen = sc.next().charAt(0);
	  System.out.println("Your gender is :"+gen);
	  sc.close();

	}

}
```

```java
//Program to read Employee data from Scanner class.

package com.ravi.scanner;

import java.util.Scanner;

public class EmployeeData
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);

		System.out.print("Enter Employee Id :");
		int empId = sc.nextInt();

		System.out.print("Enter Employee Name :");
		String empName = sc.nextLine();  //Buffer Problem
		empName = sc.nextLine();

		System.out.print("Enter Employee Salary :");
		double empSalary = sc.nextDouble();

		System.out.println("Employee Id is :"+empId);
		System.out.println("Employee Name is :"+empName);
		System.out.println("Employee Salary is :"+empSalary);
		sc.close();
	}

}
```


### Expression Conversion

Whenever we work with Arithmetic operator OR Unary minus operator then after expression the final result will be promated int type so to hold the result we need minimum int data type.

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		byte b = 1;
		byte c = 1;
		int d = b + c; //To hold the result 32 bit reqd
		System.out.println(d);

	}

}
```


### Unary minus operator

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		int x = 15;
		System.out.println(-x);

	}

}
```

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		byte b = 1;
		b = -b; //error
		System.out.println(b);
	}

}

```

In Arithmetic operator OR Unary minus operator, the result will be promated to int type (32 bits) so to hold the result int data type is reqd.
```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		byte b = 1;
		b += 2;
		System.out.println(b);
	}

}


```

In the above program we are using short hand operator so we will get the result in byte format also.
```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		 int z = 5;
		  if(++z > 5 || ++z > 6)   //Logical OR
		  {
			  z++;
		  }
		  System.out.println(z);  //7

         System.out.println("................");

		  z = 5;
		  if(++z > 5 | ++z > 6)   //Boolean OR
		  {
			  z++;
		  }
		  System.out.println(z); //8
	}

}
```


### Program on Boolean AND

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		int z = 5;
		if(++z > 6 & ++z> 6)
		{
			z++;
		}
		System.out.println(z);
	}

}
```

```java
//Boolean Operator
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		System.out.println(5 & 6);
		System.out.println(5 | 6);
		System.out.println(5 ^ 6);
	}

}
```

Bitwise Complement Operator (~)
* It will not work with boolean value.

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		System.out.println(~true); //error
	}

}
```

```java
package com.ravi.expr;

public class Test1 {

	public static void main(String[] args)
	{
		System.out.println(~5); //-6
	}

}
```


### Member access operator

In order to access the member of the class (variable + method) we need an operator i.e Member access operator (.), It is also
known as Dot opertor OR Period operator.

Case 1 :
Working with non static variable and method :
In order to access the non static variable and non static method we need to craete an object first

```java
public class Test
{
	int x = 100;  //non static field

	public  void m1() //non static method
	{
		System.out.println("m1");
	}

    public static void main(String [] args)
    {
```

Test t1 = new Test(); //Object Creation
```java
	  System.out.println(t1.x);	//. Member access operator
```

t1.m1(); //. Member access operator
```java
	}
}

```

Case 2 :
If our members are static member (static variable + static methods) then object is not required we can access the static member with the help of class name.

```java
class Welcome
{
	public static String val = "Batch33";
	public static void greet()
	{
		System.out.print("Good Evening ");
	}
}

public class Test
{

    public static void main(String [] args)
    {
```

Welcome.greet(); //. Member access operator
```java
		System.out.println(Welcome.val); //. Member access operator
	}
}
```


## 03-05-2024


### Limitation of if else


### What is drawback of if condition

The major drawback with if condition is, it checks the condition again and again so It increases the burdon over CPU so we introduced switch-case statement to reduce the overhead of the CPU.


```java
switch case :-
```

In switch case dpending upon the parameter the appropriate case would be executed otherwise default would be executed.

In this approch we need not to check each and every case, if the appropriate case is available then directly it would be executed.

```java
break keyword is optional here but we can use as per requirement. It will move the control outside of the body of the switch.

```


> **Note :- In the switch statement we can't pass long, float and double value.**

Strings are allowed from JDK 1.7 version. enums are allowed from java 1.5 version.
```java
import java.util.*;
public class SwitchDemo
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
        System.out.print("Please Enter a Character :");

		char colour = sc.next().toLowerCase().charAt(0);


		switch(colour)
		{
		case 'r' : System.out.println("Red") ; break;
		case 'g' : System.out.println("Green");break;
		case 'b' : System.out.println("Blue"); break;
		case 'w' : System.out.println("White"); break;
		default : System.out.println("No colour");
		}
		System.out.println("Completed") ;
	}
}
```

```java
import java.util.*;
public class SwitchDemo1
{
public static void main(String args[])
  {
		System.out.println("\t\t**Main Menu**\n");
		System.out.println("\t\t**100 Police**\n");
		System.out.println("\t\t**101 Fire**\n");
		System.out.println("\t\t**102 Ambulance**\n");
		System.out.println("\t\t**139 Railway**\n");
		System.out.println("\t\t**181 Women's Helpline**\n");

		System.out.print("Enter your choice :");
		Scanner sc = new Scanner(System.in);
		int choice = sc.nextInt();

		switch(choice)
		{
		case 100:
		System.out.println("Police Services");
		break;
		case 101:
		System.out.println("Fire Services");
		break;
		case 102:
		System.out.println("Ambulance Services");
		break;
		case 139:
		System.out.println("Railway Enquiry");
		break;
		case 181:
		System.out.println("Women's Helpline ");
		break;
```

default:
```java
		System.out.println("Your choice is wrong");
		}
    }
}
```

```java
import java.util.*;
public class SwitchDemo2
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the name of the season :");
		String season = sc.next().toLowerCase();

		switch(season)  //String allowed from 1.7
		{
			case "summer" :
				 System.out.println("It is summer Season!!");
			 break;

			 case "rainy" :
				 System.out.println("It is Rainy Season!!");
			 break;
		}
	}
}
```


```java
public class Test2
{
	public static void main(String[] args)
	{
		double val = 1;
		switch(val)     //Error, can't pass long, float and double
		{
			 case 1:
				 System.out.println("Hello");
			 break;
		}
	}
}

```

Note : we can pass enum from 1.5v
```java
package com.ravi.association;


public class Association {

	public static void main(String[] args)
	{
       byte b = 123;

       switch(b)
       {
       case 130: //Will not compile, out of the range of byte
       }
	}

}
```


## Loops in java

A loop is nothing but repeatation of statements based on the
specified condition.

In java we have 4 types of loops :
1) do-while loop
2) while loop
3) for loop
4) for each loop

do-while loop :
```java
public class Test
{
    public static void main(String [] args)
    {
```

do
```java
		{
			int x = 1;
			System.out.println(x);
			x++;
		}
		while (x<=10); //error
	}
}

```

Note : x variable is defined inside do block so, we can't access outise of do block.
```java
public class Test
{
    public static void main(String [] args)
    {
		int x = 1; //local variable
```

do
```java
		{
			System.out.print(x+"\t");
			x++;
		}
		while (x<=10);
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
		while (false)
		{
			System.out.println("Inside the body");
		}
		System.out.println("Outside the body");
	}
}

```

NOte : compilation error because unreachable statement
```java
public class Test
{
    public static void main(String [] args)
    {
		boolean b = false;
		while (b)
		{
			System.out.println("Inside the body");
		}
		System.out.println("Outside the body");
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {

		boolean b = false;
		while (b = true)
		{
			System.out.println("Inside the body");
		}
		System.out.println("Outside the body");
	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
        int x = 1;
		while(x>=-10)
		{
			System.out.println(x);
            x--;
		}

	}
}
```

```java
public class Test
{
    public static void main(String [] args)
    {
        for(int i=1; i<=10; i++)
		{
			System.out.println(i);
		}

	}
}
```

```java
for each loop in java :
```

It is an enhanced for loop which is used to retrieve the values through the collection data.

It was introduced from java 1.5v.

It is used to fetch the values from collection data one by one so it is known as for each loop.


How to sort an array variable Data :
In java there is a predefined class called Arrays available in java.util package.
Arrays class contains a predefined static method sort(Object arr[]) as a parameter through which we can can sort an array in ascending order as shown in the Program


```java
//Program to fetch Integer data from array
```

ForEachDemo1.java
```java
package com.ravi.for_each_demo;

import java.util.Arrays;

public class ForEachDemo1
{
	public static void main(String[] args)
	{
		int []values = {90,67,34,12,9};

		Arrays.sort(values);

		for(int value : values)
		{
			System.out.println(value);
		}

	}

}
```


```java
//Program to fetch String data from array
```

ForEachDemo2.java
```java
package com.ravi.for_each_demo;

import java.util.Arrays;

public class ForEachDemo2
{
  public static void main(String[] args)
  {
	String []fruits = {"Mango","Orange","Kiwi","Apple"};

	Arrays.sort(fruits);

	for(String fruit : fruits)
	{
		System.out.println(fruit.toUpperCase());
	}

  }
}
```


```java
//Program to fetch hetrogeneous data from array
```

ForEachDemo3.java
```java
package com.ravi.for_each_demo;

public class ForEachDemo3
{
   public static void main(String[] args)
   {
	  Object []values = {12,34.89,'A',true,"NIT"};


	  for(Object value : values)
	  {
		  System.out.println(value);
	  }
   }
}

```


> **Note :- sorting operation is only possible with same kind of data, It is not possible with different kinds of data. If We try to perform then we will get java.lang.ClassCastException.**


### What is BLC and ELC class ?


### BLC

It stands for Business Logic Class. Here we will write the logic
of the program we will never write main method in BLC class.

ELC :
It stands for Executable Logic Class. Here we will write main method and the execution of the Program will start from ELC class.

Note : We should always BLC and ELC class in our application so, we can reuse the BLC class multiple times in our application.

## 04-05-2024


### Reusability of the class

* In a single file we can't declare multiple public classes that   means we must have only 1 public class in a java file.

* We can declare multiple classes in a single file but multiple
classes we can't declare with public access modifier.

* So the conclusion every class must be declared with public
access modifier in a separate file. [We have 5 classes then we must 5 .java files]

2 files :
Calculate.java(BLC)
```java
package com.ravi.method;

//BLC(Business Logic Class)
public class Calculate
{
  public static void doSum(int x, int y)
  {
	System.out.println("Sum is :"+(x+y));
  }
}

```

Main.java(ELC)
```java
package com.ravi.method;

import java.util.Scanner;

//ELC
public class Main
{
	public static void main(String[] args)
	{

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the value of x :");
		int a = sc.nextInt();
		System.out.print("Enter the value of y :");
		int b = sc.nextInt();
		Calculate.doSum(a, b);
		sc.close();

	}

}
```


### Working with static method parameter and return type

- A static method main can directly call another static method if both the static methods are available in the same class. (Here class name is not required) as shown in the program.

```java
//A static method can be directly call within the same class
package com.ravi.pack1;

public class Test1
{
	public static void main (String[] arg)
	{
		square(5);
	}

	public static void square(int x)
	{
	  System.out.println("Square is :"+(x*x));
	}
}

```

A static method declared in another class, we can call with the help of class name

2 files :
FindSquare.java(BLC)
```java
package com.ravi.pack2;
//Finding the Square of the number

//BLC(Business Logic class)
public class FindSquare
{
   public static void getSquareOfNumber(int num)
   {
	   System.out.println("Square of "+num+" is :"+(num*num));
   }
}

```

Test2.java(ELC)
```java
package com.ravi.pack2;

import java.util.Scanner;

//ELC(Executable Logic class)
public class Test2
{
	public static void main (String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter a number :");
		int num = sc.nextInt();

		FindSquare.getSquareOfNumber(num);
	}


}
```


> **Note :- In System.out.println() statement we can't call a method**

whose return type is void otherwise it will generate CE.

> **Note :- We can take multiple public class with same name but it must be in two different packages.**

Calling a static method of another class which returns square of the number.

2 files :
FindSquare.java(BLC.java)
```java
//A static method returning integer value
package com.ravi.pack3;

//BLC
public class FindSquare
{
	public static int getSquare(int x)
	{
		return (x*x);
	}
}

```

Test3.java(ELC)
```java
package com.ravi.pack3;

//ELC
public class Test3
{
	public static void main (String[] arg)
	{
		for(int i = 1; i<=10; i++)
		{
			System.out.println("Square of "+i+" is :"+FindSquare.getSquare(i));
		}

	}
}
```


### Program with Test cases


2 files :
Calculate.java(BLC)

```java
/*Program to find out the square and cube of
```

the number by following criteria
*
a) If number is 0 or Negative it should return -1
b) If number is even It should return square of the number
c) If number is odd It should return cube of the number
*/

```java
package com.ravi.pack4;

//BLC
public class Calculate
{
  public static int getSquareAndCube(int num)
  {
	if(num <= 0 )
	{
		return -1;
	}
	else if(num %2==0)
	{
		return (num*num);
	}
	else
	{
		return (num*num*num);
	}
  }
}

package com.ravi.pack4;

import java.util.Scanner;

```

Test4.java
```java
//ELC
public class Test4
{
	public static void main(String[] args)
	{
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a Number :");
       int num = sc.nextInt();

       int number = Calculate.getSquareAndCube(num);
       System.out.println("Number is :"+number);
       sc.close();
   }

}
```


## 06-05-2024


### Finding the Area of Rectangle


### 2 files

Rectangle.java
```java
package com.ravi.pack5;

//BLC
public class Rectangle
{
  public static double getAreaOfRectangle(double length, double breadth)
  {
	  return (length * breadth);
  }

}

```

Test5.java
```java
package com.ravi.pack5;

import java.util.Scanner;

public class Test5
{
	public static void main(String[] args)
	{
	  Scanner sc = new Scanner(System.in);
	  System.out.print("Enter the length of the Rect :");
	  double length = sc.nextDouble();
	  System.out.print("Enter the breadth of the Rect :");
	  double breadth = sc.nextDouble();

	  double areaOfRectangle = Rectangle.getAreaOfRectangle(length, breadth);
	  System.out.println("Area of Rectangle is :"+areaOfRectangle);
	 sc.close();

	}
}
```

Progran to verify number is even or odd

### 2 files

EvenOrOdd.java
```java
package com.ravi.pack6;

//BLC
public class EvenOrOdd
{
	public static boolean isEven(int num)
    {
        return (num % 2 == 0);
    }
}


```

Test6.java
```java
package com.ravi.pack6;

//ELC
public class Test6
{
	public static void main(String[] args)
	{
	    boolean isEven = EvenOrOdd.isEven(11);
	    System.out.println("number is Even ?:"+isEven);

	    isEven = EvenOrOdd.isEven(12);
	    System.out.println("number is Even ?:"+isEven);
	}

}
```


### How to provide formatting for Decimal number

In java.text package, there is a predefined class called DecimalFormat through which we can provide formatting for Decimal number.

```java
DecimalFormat df = new DecimalFormat("00.00");
System.out.println(df.format(double d));

```


> **Note :- format is non static method of DecimalFormat class which accpts double as a parameter, and return type of this method is**

String.

```java
public String format(double number)
```

Find out the area of Circle (return type of method as String)

### 2 files

Circle.java
```java
//Area of Circle
//If the radius is 0 or Negative then return -1.

package com.ravi.pack7;
public class Circle
{
  public static String getAreaOfCircle(double rad)
  {
	  if(rad <=0)
	  {
		  return ""+(-1);
	  }
	  else
	  {
		 final double PI = 3.14;
		 double areaOfCircle = PI * rad * rad;
		 return ""+areaOfCircle;
	  }
  }


}

```

Test7.java
```java
package com.ravi.pack7;

import java.text.DecimalFormat;
import java.util.Scanner;

public class Test7
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the radius :");
		double radius = sc.nextDouble();

		String areaOfCircle = Circle.getAreaOfCircle(radius);

		//Converting String into double
		double area = Double.parseDouble(areaOfCircle);

```

DecimalFormat df = new DecimalFormat("00.00"); //format in String pattern
```java
		System.out.println("Area of Circle is :"+df.format(area));
		sc.close();

	}
}
```


### Method return type as String


### 2 files

Student.java
```java
package com.ravi.pack8;

//BLC
public class Student
{
 public static String getStudentDetails(int roll, String name, double fees)
  {
	//[Student name is : Ravi, roll is : 101, fees is :1200.90]

	 return "[Student name is :"+name+", roll is :"+roll+", fees is :"+fees+"]";


  }
}

```

Test8.java
```java
package com.ravi.pack8;

public class Test8
{
	public static void main(String[] args)
	{
		String studentDetails = Student.getStudentDetails(1, "Scott", 12000.90);

		System.out.println(studentDetails);
	}

}
```

Printing the Table

### 2 files

Table.java
```java
package com.ravi.pack9;

//BLC [5 X 1 = 5]
public class Table
{
  public static void printTable(int num)
  {
	for(int i=1; i<=10; i++)
	{
	   System.out.println(num +" X "+i+" = "+(num*i));
	}
	 System.out.println(".......................");
  }
}



```

Test9.java
```java
package com.ravi.pack9;

//ELC
public class Test9
{
	public static void main(String[] args)
	{
		for(int i=11; i<=20; i++)
		{
			Table.printTable(i);
		}
	}

}
```


## Object Orineted Programming (OOPs)


## What is an Object?

An object is a physical entity which exist in the real world.
Example :- Pen, Car, Laptop, Mouse, Fan and so on

An Object is having 3 characteristics :

a) Identification of the Object (Name of the Object)
b) State of the Object (Data OR Properties OR Variable of Object)
c) Behavior of the Object (Functionality of the Object)

OOP is a technique through which we can design or develop the programs using class and object.

Writing programs on real life objects is known as Object Oriented Programming.

Here in OOP we concentrate on objects rather than function/method.

Advantages of OOP :
1) Modularity  (Dividing the bigger task into smaller task)
2) Reusability (We can reuse the component so many times)
3) Flexibility (Easy to maintain)

Features of OOP :
1) Class
2) Object
3) Abstraction
4) Encapsulation
5) Inheritance
6) Polymorphism


## What is a class?

A class is model/blueprint/template/prototype for creating the object.

A class is a logical entity which does not take any memory.

A class is a user-defined data type which contains data member and member function.

```java
public class Employee
{
```

Employee Data (Properties)
+
Employee behavior (Function/Method)
```java
}

```

A CLASS IS A COMPONENT WHICH IS USED TO DEFINE OBJECT PROPERTIES AND OBJECT BEHAVIOR.

### WAP in OOP to provide initial value to object properties

Steps for creating Object Orineted Programming

Step 1 :-  Create the Object based on the class

Step 2 :- Define all the object properties and behavior inside
the class based on your imagination.

Step 3 :- Initialize all the object properties with user friendly
value.

step 4 :- call the behavior (calling the methods)

2 files :
Student.java
```java
package com.ravi.oop;

//BLC
public class Student
{
  //Object Properties
  String studentName;    //Instance Variable
  String studentAddress; //Instance Variable
  int studentAge;        //Instance Variable

  public String talk()
  {
	  return "Hello Everyone, My Name is : "+studentName+" my address is :"+studentAddress + " my age is :"+studentAge;
  }

  public void writeExam()
  {
	System.out.println("Every thursday I am writing exam..");
  }

}




```

StudentDemo.java
```java
package com.ravi.oop;

//ELC
public class StudentDemo
{
	public static void main(String[] args)
	{
		Student raj = new Student();
		//Initializing the Object Properties
		raj.studentName = "Raj Gourav";
		raj.studentAddress = "Ameerpet";
		raj.studentAge = 19;

		//calling the behavior
		String details = raj.talk();
		System.out.println(details);

		raj.writeExam();

		System.out.println(".............");

		Student priya = new Student();
		priya.studentName ="Priya Reddy";
		priya.studentAddress = "S.R nagar";
		priya.studentAge = 19;

		details  = priya.talk();
		System.out.println(details);
		priya.writeExam();
	}

}
```


### Types of variables in Java ?

In java, Based on the data type we have only 2 types of variables

1) Primitive variable

If any variable is declared with primitive data type like byte, short, int, long and so on then it is called primitive variable.

```java
 Example :  int x = 90;

```

2) Non Primitive OR Reference variable

If any variable is declared with class name like String, Integer, Employee, Student then it is called as non-primitive OR
reference variable.

```java
 Example : Customer a = null;
           String b = "NIT";
	   Student s = new Student();


```

Now Based on the Declaration Position variables are divided
into 4 types :

1) Instance variable OR Non static Field
2) Class Variable OR Static Field
3) Parameter variable
4) Local Variable

Program on primitive variable including (Instance, static , local and parameter)
PrimitiveVariables.java
```java
package com.ravi.oop;

public class PrimitiveVariables
{
	int a = 100; //instance variable
	static int b = 200; //class variable

	public static void main(String[] args)
	{
		PrimitiveVariables p = new PrimitiveVariables();
		System.out.println("Instance Variable :"+p.a);
		System.out.println("Class Variables :"+PrimitiveVariables.b);

		int c = 300;  //local variable
		System.out.println("Local Variable :"+c);
        accept(400);
	}

	public static  void accept(int d)
	{
		System.out.println("Paarmeter variables :"+d);
	}

}

```

Program on Reference variable including (Instance, static , local and parameter)

```java
package com.ravi.oop;

import java.util.Scanner;

class Employee
{
	public void m1()
	{
		System.out.println("m1 Method");
	}
}

public class ReferenceVariable
{
```

Employee e1 = new Employee(); //instance + reference variable

```java
    static Scanner sc = new Scanner(System.in); //class + reference variable


	public static void main(String[] args)
	{
```

Employee e2 = new Employee(); //Local + reference variable
```java
		accept(e2);
	}

	public static void accept(Employee emp) //parameter + reference variable
	{
		emp.m1();
	}
}
```


## Instance variable

If a non static variable declaread outside of a method and inside the class then it is called Instance variable.

Example :
```java
public class Test
{
   int x = 100; //Instance variable OR Non static field
}


```

As far as its scope is concerned, it is accessible directly anywhere withing the class as well as depends upon the accessibility level.(Access Modiifier)

THE LIFE OF INSTANCE VARIABLE STARTS AT THE TIME OF CREATING THE OBJECT, IT IS THE PART OF THE OBJECT. WE CANNOT THINK ABOUT INSTANCE VARIABLE WITHOUT OBJECT.


```java
public class Main
{
  int x = 100;

  public static void main(String [] args)
  {
	 System.out.println(x);  //error [cannot use instance variable
```

without object]
```java
  }
}
```


## 08-05-2024

OOP to initialize the object properties through reference variable

### 2 files

Employee.java
```java
package com.ravi.oop;

//BLC
public class Employee
{
	int empId;
	String empName;
	double empSalary;

	public void work()
	{
		System.out.println(empName + " is working for 8 hours and the Employee id is :"+empId);
	}

	public void getSalary()
	{
		System.out.println(empName + " Salary is :"+empSalary);
	}



}

```

EmployeeDemo.java
```java
package com.ravi.oop;
//ELC
public class EmployeeDemo
{
	public static void main(String[] args)
	{
		Employee scott = new Employee();

		//Initializing the object properties
		scott.empId = 101;
		scott.empName = "Scott";
		scott.empSalary = 90000;

		//calling the behavior
		scott.work();
		scott.getSalary();


	}

}


```


> **Note :- In the above program, we have initialized the object properties through reference variable i.e scott.**


```java
Constructor (Introduction only)
```

If the name of the class and name of the method both are exactly same and if it does not contain any return type then it is called
constructor.

Example :
```java
public class Student
{
   public Student() //constructor
   {
   }
}
```


### Default constructor added by the compiler

In java, whenever we write a class and if we don't write any kind
of constructor in the class then automatically java compiler will add one default constructor to the class.

Test.java
```java
public class Test
{

}

javac Test.java (Compilation)

```

Test.class
```java
public class Test
{
   public Test() //default constructor added by the compiler
   {
   }
}

```


> **Note :- default constructor does not take any argument.**


The access modifier of default constructor depnds upon class access
modifier that means if my class is public then default constrauctor added by compiler will be public, if class is not public then default constructor added by compiler will also not public.

### Why compiler is adding default constructor to our class


### We have 2 reasons that why compiler is adding default constructor


1) Without default constructor, Object creation is not possible in java by using new keyword.


2) default constructor will initialize all the instance variables with default values.

Data type - Default value
byte  - 0
short - 0
```java
   int   - 0
```

long  - 0
```java
   float - 0.0
   double - 0.0
   char - (space) '\u0000'
   boolean - false
   String - null
```

Object - null (For any class i.e reference variable the default value is null)

### 2 files

Student.java
```java
package com.ravi.oop;

public class Student
{
   int studentId;
   String studentName;

   public void show()
   {
	   System.out.println("Student id is :"+studentId);
	   System.out.println("Student name is :"+studentName);
   }

}

```

StudentDemo.java
```java
package com.ravi.oop;

public class StudentDemo {

	public static void main(String[] args)
	{
		Student raj = new Student();
		raj.show();

	}

}
```


### How to provide user-defined values for instance variable

(We can also initialize the object properties by using methods)

The default constructor added by the compiler will provide the default values for the instance variable, but these default values are not useful for the user so, user will take a separate method setManagerData() to re-initialize the instance variable according to his/her choice as shown in the program.

2 files :
Manager.java
```java
package com.ravi.oop;

public class Manager
{
   String managerName;
   double managerSalary;

   public void setManagerData()
   {
	   managerName = "Mr. Smith";
	   managerSalary = 150000;

   }

    public void showManagerData()
    {
    	System.out.println("Manager Name is :"+managerName);
    	System.out.println("Manager Salary is :"+managerSalary);
    }


}

```

ManagerDemo.java
```java
package com.ravi.oop;

public class ManagerDemo {

	public static void main(String[] args)
	{
		Manager smith = new Manager();
		smith.showManagerData();

		System.out.println("...............");
		smith.setManagerData();
		smith.showManagerData();

	}

}

```

SO, THE CONCLUSION IS UPTO HERE WE HAVE LEARNED TWO WAYS TO INITIALIZE THE OBJECT PROPERTIES
1) Through Object Reference (raj)
2) By using methods (setManagerData())

## 09-05-2024


### Initialize the object properties by using methods


### 2 files

Manager.java
```java
package com.ravi.initialization_method;

import java.util.Scanner;

public class Manager
{
   int managerId;
   String managerName;
   double managerSalary;

   public void setManagerData()
   {
       Scanner sc = new Scanner(System.in);
       System.out.print("Enter Manager Id :");
       int managerId = sc.nextInt();
       System.out.print("Enter Manager Name :");
       String managerName = sc.nextLine();
       managerName = sc.nextLine();
       System.out.print("Enter Manager Salary :");
       double managerSalary = sc.nextDouble();
       sc.close();

   }
   public void getManagerData()
   {
	   System.out.println("Manager id is :"+managerId);
	   System.out.println("Manager name is :"+managerName);
	   System.out.println("Manager salary is :"+managerSalary);
   }


}

```

ManagerDemo.java
```java
package com.ravi.initialization_method;

public class ManagerDemo
{
	public static void main(String[] args)
	{
		Manager scott = new Manager();
		scott.setManagerData();
		scott.getManagerData();
	}

}


```


> **Note :- From the above program we will get default values for the instance variable because instance variables are not initialized, local variables are accepting the value from the user and once the execution of the method is over then it will**

be deleted from Stack Frame.
In the following program now, istance variables are initialized in the method body so we will get expected result

2 files :
Manager.java
```java
package com.ravi.initialization_method;

import java.util.Scanner;

public class Manager
{
   int managerId;
   String managerName;
   double managerSalary;

   public void setManagerData()
   {
       Scanner sc = new Scanner(System.in);
       System.out.print("Enter Manager Id :");
       managerId = sc.nextInt();
       System.out.print("Enter Manager Name :");
       managerName = sc.nextLine();
       managerName = sc.nextLine();
       System.out.print("Enter Manager Salary :");
       managerSalary = sc.nextDouble();
       sc.close();

   }
   public void getManagerData()
   {
	   System.out.println("Manager id is :"+managerId);
	   System.out.println("Manager name is :"+managerName);
	   System.out.println("Manager salary is :"+managerSalary);
   }


}

```

ManagerDemo.java
```java
package com.ravi.initialization_method;

public class ManagerDemo
{
	public static void main(String[] args)
	{
		Manager scott = new Manager();
		scott.setManagerData();
		scott.getManagerData();
	}

}
```


### What is a parameter variable

If we declare a variable inside the method parameter(not inside the method body) then it is called parameter variable.

The scope of the parameter variable is within the same method body and it is executed inside the Stack Frame. Once the method execution is over parameter variables are deleted from stack frame.

Example :
```java
public class Player
{
  int playerId;
  String playerName;

  public void setPlayerData(int id, String name) //id and name
  {                                                 parameter

  }
}
```


### Program on Parameter variables


### 2 files

Player.java
```java
package com.ravi.initialization_method;

public class Player
{
   int playerId;
   String playerName;

   public void setPlayerData(int id, String name)
   {
	   playerId = id;
	   playerName = name;
   }

   public void getPlayerData()
   {
	   System.out.println("Player id is :"+playerId);
	   System.out.println("Player name is :"+playerName);
   }


}


```

PlayerDemo.java
```java
    package com.ravi.initialization_method;

public class PlayerDemo {

	public static void main(String[] args)
	{
	  Player p1 = new Player();
	  p1.setPlayerData(111, "Rohit");
	  p1.getPlayerData();

	  Player p2 = new Player();
	  p2.setPlayerData(222, "Virat");
	  p2.getPlayerData();

	}

}

```


> **Note :- Here instance variables are initialized through parameter variables so those values we can use till the end of the class as well as outside of the class also.**


### Program on initializing the instance variable through methods


### 2 files

Employee.java
```java
package com.ravi.initialization_method;

public class Employee
{
  int employeeNumber;
  String employeeName;
  double employeeSalary;
  char employeeGrade;

  public void setEmployee(int id, String name, double salary)
  {
	  employeeNumber = id;
	  employeeName = name;
	  employeeSalary = salary;
  }

   public void getEmployee()
   {
	   System.out.println("Employee id is :"+employeeNumber);
	   System.out.println("Employee name is :"+employeeName);
	   System.out.println("Employee salary is :"+employeeSalary);
	   System.out.println("Employee grade is :"+employeeGrade);
   }

   public void calculateEmployeeGrade()
   {
	   if(employeeSalary > 100000)
	   {
		   employeeGrade = 'A';
	   }
	   else if(employeeSalary > 75000)
	   {
		   employeeGrade = 'B';
	   }
	   else if(employeeSalary > 50000)
	   {
		  employeeGrade = 'C';
	   }
	   else
	   {
		   employeeGrade = 'D';
	   }
   }

}

```

EmployeeDemo.java
```java
package com.ravi.initialization_method;

public class EmployeeDemo {


	public static void main(String[] args)
	{
		Employee e1 = new Employee();
		e1.setEmployee(111, "Smith", 45000);
		e1.calculateEmployeeGrade();
		e1.getEmployee();

	}

}
```


## Variable Shadow

If the instance variable name and local/parameter variable name both are same then inside the method local/parameter variables are having more priority than instance variable.
Acutually local/parameter variables are hiding the instance variables that is the reason it is known as Variable Shadow.

2 files :
Student.java
```java
package com.ravi.initialization_method;

public class Student
{
  int studentId = 100;
  String studentName = "Raj";

  public void showStudentData()
  {
	  int studentId = 200;
	  String studentName = "Ravi";

	  System.out.println(studentId);
	  System.out.println(studentName);
  }

}

```

StudentDemo.java
```java
package com.ravi.initialization_method;

public class StudentDemo
{
	public static void main(String[] args)
	{
		Student s = new Student();
		s.showStudentData();
	}

}
```


### this keyword in java

Whenever instance variable name and parameter variable name both are same then at the time of variable initialization our runtime environment will provide more priority to parameter variable, parameter variables are hiding the instance variables (Due to variable shadow)

To avoid the above said problen, Java software people introduced "this" keyword.

this keyword always refers to the current object and instance variables are the part of the object so by using this keyword we can refer to instance variable.

We cannot use this (non static member) keyword from static area (Static context).

2 files :
Customer.java
```java
package com.ravi.initialization_method;

public class Customer
{
  int customerId;
  String customerName;

  public void setCustomerData(int customerId, String customerName)
  {
	  customerId = customerId;
	  customerName = customerName;

  }

  public void getCustomerData()
  {
	  System.out.println("Customer Id is :"+customerId);
	  System.out.println("Customer Name is :"+customerName);
  }

}

```

CustomerDemo.java
```java
package com.ravi.initialization_method;

public class CustomerDemo {

	public static void main(String[] args)
	{
		Customer c1 = new Customer();
		c1.setCustomerData(111, "John");
		c1.getCustomerData();

	}

}
```


### How to print object properties by using toString() method

If we want to print our object properties (Instance Variable) then we should generate(override) toString() method in our class from Object class.

Now with the help of toString() method we need not to write any display kind of method to print the object properties i.e instance variable.

In order to generate the toString() method we need to follow the steps
Right click on the program -> source -> generate toString()

In order to call this toString() method, we need to print the corresponding object reference by using System.out.println() statement.

```java
Manager m = new Manager();
System.out.println(m); //Calling toString() method of Manager class

Employee e = new Employee();
System.out.println(e); //Calling toString() method of Employee class.

```

2 files :
Customer.java
```java
package com.ravi.object_properties;

public class Customer {
	int customerNumber;  //default is 0
	String customerName;  //default is null

	public void setCustomerData(int customerNumber, String customerName) {
		this.customerNumber = customerNumber;
		this.customerName = customerName;
	}


	public String toString()
	{
		return "Customer [customerNumber=" + this.customerNumber + ", customerName=" + this.customerName + "]";
	}

}

```

CustomerDemo.java
```java
package com.ravi.object_properties;

public class CustomerDemo
{
	public static void main(String[] args)
	{
		Customer c1 = new Customer();
		c1.setCustomerData(111, "Rahul");
		System.out.println(c1); //calling toString() of Customer class

	}

}
```


### Role of instance variable in object creation

Whenever we create an objet in java, a separate copy of all the instance variables will be created with each and every object.

```java
package com.ravi.object_properties;

public class Test
{
	int x = 100;


}
```


### Role of static variable in object creation

Whenever we create an object then a single copy of static filed is created and the same single copy is sharable by all the objects so, if we make any changes through one object, it will reflect to all the objects.


## Instance variable = Multiple Copies

Class Variable = Single Copy

```java
package com.ravi.object_properties;

public class Test
{
	static int x = 100;

	public static void main(String[] args)
	{
		Test t1 = new Test();
		Test t2 = new Test();

		++t1.x;  ++t2.x;

		System.out.println(t1.x);
		System.out.println(t2.x);

	}
}

```

When we should declare a variable as an instance variable and when we should declare a variable as a static filed.


## Instance Variable

If the value of the variable is different with respect to objects then we should declare a variable as a instance variable.

Static Variable :
If the value of the variable is common to all the objects then we should declare a variable as a static variable.

```java
public class Student
{
   int rollNumber;
   String studentName;
   String studentAddress;
   static String collgeName = "JNTU";
   static String courseName = "Java";
}

```

So the final conclusion is static variables are used to save the memory.

### 2 files

Student.java
```java
package com.ravi.object_properties;

public class Student
{
   int studentNumber;
   String studentName;
   String studentAddress;
   static String collegeName = "JNTU";
   static String coureName = "Java";

   public void setStudentData(int id, String name, String addr)
   {
	   this.studentNumber = id;
	   this.studentName = name;
	   this.studentAddress = addr;
   }


   public void getStudentData()
   {
	   System.out.println(this.studentNumber);
	   System.out.println(this.studentName);
	   System.out.println(this.studentAddress);
	   System.out.println(Student.collegeName);
	   System.out.println(Student.coureName);
   }





}

```

StudentDemo.java
```java
package com.ravi.object_properties;

public class StudentDemo {

	public static void main(String[] args)
	{
		Student s1 = new Student();
		s1.setStudentData(1, "A", "Ameerpet");
		s1.getStudentData();
		System.out.println(".............");
		Student s2 = new Student();
		s2.setStudentData(2, "B", "S.R nagar");
		s2.getStudentData();

	}

}
```


## 14-05-2024


## Data Hiding


## Data hiding is nothing but declaring our data members with private access modifier so our data will not be accessible from outer world that means no one can access our data directly from  outside of the class.


*We should provide the accessibility of our data through methods so we can perform VALIDATION ON DATA which are coming from outer world.

### 2 files

Customer.java
```java
package com.ravi.data_hiding;

public class Customer
{
   private double balance = 10000;  //Data hiding

   public void deposit(double amount)
   {
	  //Validation of data
	   if(amount<=0)
	   {
		   System.err.println("Amount can't be deposited");

	   }
	   else
	   {
		   this.balance = this.balance + amount;
		   System.out.println("Amount after Deposit is :"+this.balance);
	   }
   }

   public void withdraw(double amount)
   {
	  this.balance = this.balance - amount;
	  System.out.println("Amount after Withdraw is :"+this.balance);
   }

}

```

BankingApplication.java
```java
package com.ravi.data_hiding;

import java.util.Scanner;

public class BankingApplication
{
	public static void main(String[] args)
	{
		Customer raj = new Customer();
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the amount you want to depopsit :");
		double amount = sc.nextDouble();
		raj.deposit(amount);
		System.out.print("Enter the amount you want to Withdraw :");
		amount = sc.nextDouble();
		raj.withdraw(amount);

	    sc.close();
	}

}
```


## Abstraction

Showing the essential details without showing the background details is called abstraction.

In our real world a user always interacts with functionality of the product but not the data so as a developer we should hide the data from end user by declaring them private.

On the other hand the method must be declared as public so our end user witll interact with the method.

In Java we can achieve abstraction by using two ways :

1) Abstract class and abstract methods :- By using abstract class and abstract method we can achieve abstraction 0 to 100%

2) By using interface :- By using interface we can achieve 100%

## abstraction.



Lift.java(0-100%abstraction)

```java
package com.ravi.data_hiding;

public abstract class Lift
{
  public abstract void keyOne();


  public void getLiftInformation()
  {

  }
}

```

ATMMachine.java(100% abstraction)
```java
package com.ravi.data_hiding;

public interface ATMMachine
{
	 void deposit();
	 void withdraw();
	 void changePin();
}
```


## What is Constructor ?


### What is the advantage of writing constructor in our class ?

If we don't write a constructor in our program then variable initialization and variable re-initialization both are done in two different lines.

If we write constructor in our program then variable initialization and variable re-initialization both are done in the same line i.e at the time of Object creation.

Defination of Constructor :
It is used to construct the object that's why it is called constructor.

If the name of the class and name of the method both are exactly same and it should not contain any return type then it is called Constructor.

Every java class must have at-least one constructor, either implicilty added by compiler OR explicitly written by user.

Whenever we create an object in java by using new keyword then at-least one constructor must be invoked.

A constructor never containing any return type including void also, if we write explicit return type then it will behave as method not constructor.

2 files :
Student.java
```java
package com.ravi.data_hiding;

public class Student
{
  private int studentId;
  private String studentName;

  public void Student()  //Method
  {
	  System.out.println(studentId);
	  System.out.println(studentName);
  }
}


```

StudentDemo.java
```java
package com.ravi.data_hiding;

public class StudentDemo {

	public static void main(String[] args)
	{
	  System.out.println("Main Method");
	  Student s1 = new Student();
	  s1.Student();

	}

}

```

Constructor never contain any return type explicitly but implicitly it returns current class object (this keyword).

```java
package com.ravi.data_hiding;

public class Employee
{
	public Employee()
	{
	}

	public String m1()
	{
		return "Hello";
	}

	public static void main(String[] args)
	{
	 String result = 	new Employee().m1();
	 System.out.println(result);

	}

}

```

A constructor may contain return keyword but not return keyword with value.

A constructor is automatically called and executed at the time of creating object.

A constructor is called only once per object so, every time we will create the object, constructor will be called.


We can't declare a constructor with static and final keyword.

We can apply all the access modifiers to the constructors like
```java
private, default, protected and public
```


## 15-05-2024


## Types of Constructor


### We have 3 types of constructor in java


1) default constructor
2) No Argument OR Parameter less OR Zero Argument OR Non parameterized constructor
3) Parameterized Constructor

1) default constructor :
If a constructor is added by compiler that means by default it is available to the class then it is called default constructor. It does not take any parameter.
Example :

Test.java
```java
public class Test
{
   int x,y;
}

```

Test.class
```java
public class Test
{
   int x,y;
   public Test() //default constructor
   {
      x = 0; y=0; //default value using super keyword
   }
}

```


### 2) No Argument Constructor

If a constructor written by user without parameter in the class then it is called No Argument Constructor.

Example :

Test.java
```java
public class Test
{
   int x,y;

   public Test() //No Argument Constructor
   {
      x = 100;
      y = 200;
   }
}

```

In this no argument approach, all the objects will be initialized with same value so it is not a recommended way because all objects must contain different value.

To avoid this we introduced Parameterized Constructor.

### 3) Parameterized Constructor

If we pass one or more argument to the constructor then it is called parameterized constructor. By using parameterized constructor we can initialize all our objects with different value.

```java
public class Customer
{
   int cid;
   String cname;

   public Customer(int cid, String cname) //Parameterized Constructor
   {
    this.cid = cid;
    this.cname = cname;
   }
}
```


### 2 files

Book.java
```java
package com.nit.constructor;

public class Book {
	private String bookTitle;
	private String authorName;
	private long isbnNumber;

	public Book(String bookTitle, String authorName, long isbnNumber) {
		super();
		this.bookTitle = bookTitle;
		this.authorName = authorName;
		this.isbnNumber = isbnNumber;
	}

	@Override
	public String toString() {
		return "Book [bookTitle=" + bookTitle + ", authorName=" + authorName + ", isbnNumber=" + isbnNumber + "]";
	}
}


```

ParameterizedConstructor.java
```java
package com.nit.constructor;

public class ParameterizedConstructor
{
	public static void main(String[] args)
	{
		Book b1 = new Book("Java", "Gosling", 7856438);
		System.out.println(b1);

		Book b2 = new Book("C", "Denis", 78564326);
		System.out.println(b2);

	}

}
```


### How to write setter and getter in java

Setter :- To modify the existing object data.

getter :- To read the private data outside of the class.

2 files :
Employee.java
```java
package com.ravi.setter_getter;

public class Employee
{
  private double balance;

   public Employee(double balance)
   {
	super();
	this.balance = balance;
   }

	public double getBalance()
	{
	return this.balance;
        }

	public void setBalance(double balance)
	{
		this.balance = balance;
	}

	@Override
	public String toString()
	{
		return "Employee [balance=" + balance + "]";
	}





}


```

EmployeeDemo.java
```java
package com.ravi.setter_getter;

import java.util.Scanner;

public class EmployeeDemo {

	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter your Balance :");
		double bal = sc.nextDouble();

		Employee raj = new Employee(bal);
		System.out.println(raj);

		System.out.print("Enter your updated Balance :");
		bal = sc.nextDouble();
```

raj.setBalance(bal); //setter to modify the data
```java
		System.out.println(raj);


		//Based on the salary, designation will be decided

		double sal =raj.getBalance();//getter to read private data value

		if(sal>=100000)
		{
			System.out.println("You are a developer!!");
		}
		else if(sal >= 50000)
		{

			System.out.println("You are a designer!!!");
		}
		else
		{
			System.out.println("You are a Tester!!!");
		}

		sc.close();


	}

}

```

So the final conclusion is,

Parameterized Constructor -> To initialize the instance variable

setter -> To modify the existing object data

getter -> To read the private data value from BLC class.



*** Encapsulation [private data must be accessible via methods only]
Binding the data member with its associated function/method in a single unit is called encapsulation.

In other words we can say "Grouping the related things together is called Encapsulation". [Laptop]

In encapsulation data must be tightly coupled with associated function.

It provides us security because we can't access the data directly, data must be accessible via methods only.

We can achieve encapsulation in our program by using following

a) Declare all the data members as private (Tightly encapsulated class)
b) Define getters and setters (Or any other kind of public method) for each instance variable to perform read and write operation.

Note :
If we declare all the instance variables with private access modifier then it is called tightly encapsulated class.

On the other hand If we declare our instance variable other than private access modifier then it is called loosely encapsulated class.

### Method return type as a class

While declaring a method in java, return type is compulsory.
As a method return type we have following options

1) void as a retutn type of the Method

2) Any primitive data type as a return type of the method.

3) Any class name/interface / enum / record we can as a return type of the method.

```java
package com.ravi.return_type;

public class Sample
{
   public Sample accept()
   {

	   //return new Sample();  //valid
	   //return null;           //valid
	   return this;             //valid
   }
}
```


## 16-05-2024


### Program on Method return type as a class


### 2 files

Student.java
```java
package com.ravi.method_return;

import java.util.Scanner;

public class Student
{
	private int studentId;
	private String studentName;
	private double studentFees;

	public Student(int studentId, String studentName, double studentFees) {
		super();
		this.studentId = studentId;
		this.studentName = studentName;
		this.studentFees = studentFees;
	}

	public static Student getStudentObject()
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter Student Id :");
		int id = sc.nextInt();
		System.out.print("Enter Student Name :");
		String name = sc.nextLine();
		name = sc.nextLine();
		System.out.print("Enter Student Fees :");
		double fees = sc.nextDouble();

		return new Student(id, name, fees);


	}



	@Override
	public String toString()
	{
		return "Student [studentId=" + studentId + ", studentName=" + studentName + ", studentFees=" + studentFees
				+ "]";
	}

}

```

StudentDemo.java
```java
package com.ravi.method_return;

import java.util.Scanner;

public class StudentDemo
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter How many objects you want :");
		int noOfObjects = sc.nextInt();

		for(int i=1; i<=noOfObjects; i++)
		{
			Student object = Student.getStudentObject();
			System.out.println(object);
		}
		sc.close();

	}

}
```


### 2 files

Book.java
```java
package com.ravi.method_return;

public class Book {
	private String bookTitle;
	private String authorName;

	public Book(String bookTitle, String authorName) {
		super();
		this.bookTitle = bookTitle;
		this.authorName = authorName;
	}

	@Override
	public String toString() {
		return "Book [bookTitle=" + bookTitle + ", authorName=" + authorName + "]";
	}


}

```

BookDemo.java
```java
package com.ravi.method_return;

public class BookDemo {

	public static void main(String[] args)
	{
		Book b1 =   getBookObject();
		System.out.println(b1);
	}

	public static Book getBookObject()
	{
		return new Book("Java", "James Gosling");

	}

}
```


### Pass by Value in java

Java lanuage always works with pass by value only.
```java
package com.ravi.pass_by_value;

public class Test1
{
	public static void main(String[] args)
	{
		int x = 15;
		accept(x);
		System.out.println(x);
	}

	public static void accept(int a)
	{
		a = a + 10;
	}

}
```

```java
package com.ravi.pass_by_value;

public class Test2 {

	public static void main(String[] args)
	{
		String str = "india";
		accept(str);
		System.out.println(str);

	}

	public static void accept(String x)
	{
		x = "Hyderabad";
	}

}
```

```java
package com.ravi.pass_by_value;

public class Test3 {

	public static void main(String[] args)
	{
		int x = 15;
		x = accept(x);
		System.out.println(x);
	}

	public static int accept(int a)
	{
		a = a + 10;
		return a;
	}

}
```

```java
package com.ravi.pass_by_value;

class Student
{
	int rollNumber = 5;
}

public class Test4
{
	public static void main(String[] args)
	{
		int val1 = 100;

		int val2 = val1;

		System.out.println(val1 +" : "+val2);

		Student s1 = new Student();
		Student s2 = s1;
		s2.rollNumber = 9;
		System.out.println(s1.rollNumber +" : "+s2.rollNumber);
	}
}

```


> **Note :- s1 and s2 both reference variables are pointing to same object so if we modify anything by using s1 or s2 then it will reflect to original object.**

```java
package com.ravi.pass_by_value;

class Customer
{
	private int customerId = 111;

	public void setCustomerId(int customerId)
	{
		this.customerId = customerId;
	}

	public int getCustomerId()
	{
		return this.customerId;
	}
}

public class Test5 {

	public static void main(String[] args)
	{
		Customer c1 = new Customer();
		System.out.println(c1.getCustomerId());
		accept(c1);
		System.out.println(c1.getCustomerId());

	}

	public static void accept(Customer cust)  //cust = c1
	{
		cust.setCustomerId(999);
	}
}


```

Here the original object will modify from 111 to 999.
```java
package com.ravi.pass_by_value;

class Player
{
	private int playerId = 111;

	public int getPlayerId()
	{
		return playerId;
	}

	public void setPlayerId(int playerId)
	{
		this.playerId = playerId;
	}
}

public class Test6 {

	public static void main(String[] args)
	{
```

Player p1 = new Player(); //1st object
```java
		System.out.println(p1.getPlayerId()); ///111
		accept(p1);
		System.out.println(p1.getPlayerId()); ///111
	}

	public static void accept(Player p)  //p = p1
	{
		p = new Player(); //2nd object
		p.setPlayerId(999);
	}
}
```


### HEAP and STACK Diagram


### What is Garbage Collector in java ?

In C++, It is the responsibility of the programmer to allocate as well as to de-allocate the memory otherwise the corresponding memory will be blocked and we will get OutOfMemoryError.

In Java, Programmer is responsible to allocate the memory, memory de-allocation will be automatically done by garbage collector.

Garbage Collector will scan the heap area, identify which objects are not in use (The objects which does not contain any references) and it will delete those objects which are not in use.


## 17-05-2024


### How many ways we can make an object eligible for GC

There are 3 ways we can make an object eligible for GC.

1) Assigning null literal to reference variable :
```java
   Employee e1 = new Employee(111,"Ravi");
            e1 = null;

```

2) Creating an Object inside a method :

```java
   public void createObject()
   {
      Employee e2 = new Employee();
   }
```

Here we are creating Employee object inside the method so, once the method execution is over then e2 will be deleted from the Stack Frame and the employee object will become eligible for GC.

3) Assigning new Object to the old existing reference variable:

```java
   Employee e3 = new Employee();
   e3 = new Employee();

```

Earlier e3 variable was poting to Employee object after that a new Employee Object is created which is pointing to another memory location so the first object is eligible for GC.
HEAP and STACK Diagram for CustomerDemo.java
```java
class Customer
{
	private String name;
	private int id;

	public Customer(String name , int id) //constructor
	{
		super();
		this.name=name;
		this.id=id;
	}

	public void setId(int id)  //setter
	{
		this.id=id;
	}

	public int getId() //getter
	{
		return this.id;
	}
}

public class CustomerDemo
{
	public static void main(String[] args)
	{
		int val = 100;

		Customer c = new Customer("Ravi",2);

        m1(c);

		//GC [1 object, 3000x is eligible 4 GC]

		System.out.println(c.getId());
	}

	public static void m1(Customer cust) //cust = c
	{
		cust.setId(5);

	    cust = new Customer("Rahul",7);

		cust.setId(9);
		System.out.println(cust.getId());
	}
}
//9  5
```

HEAP and STACK Diagram for Sample.java
```java
public class Sample
{
	private Integer i1 = 900;

	public static void main(String[] args)
	{
		Sample s1 = new Sample();

		Sample s2 = new Sample();

	    Sample s3 = modify(s2);

		s1 = null;

         //GC [4 objects 1000x,2000x, 5000x and 6000a are eligible ]

		System.out.println(s2.i1);
	}
    public static Sample modify(Sample s)
	{
		s.i1=9;
		s = new Sample();
		s.i1= 20;
        System.out.println(s.i1);
		s=null;
		return s;
	}
}

//20  9
```

HEAP and Stack Diagram for Test.java
```java
public class Test
{
	Test t;
	int val;

	public Test(int val)
	{
		this.val = val;
	}

	public Test(int val, Test t)
	{
		this.val = val;
		this.t = t;
	}

	public static void main(String[] args)
	{
		Test t1 = new Test(100);

		Test t2 = new Test(200,t1);

		Test t3 = new Test(300,t1);

		Test t4 = new Test(400,t2);

		t2.t = t3;
		t3.t = t4;
		t1.t = t2.t;
		t2.t = t4.t;

	System.out.println(t1.t.val);
	System.out.println(t2.t.val);
	System.out.println(t3.t.val);
	System.out.println(t4.t.val);
	}

}
```


## 18-05-2024

HEAP and STACK Digram for Employee.java
```java
public class Employee
{
	int id = 100;

	public static void main(String[] args)
	{
		int val = 200;

		Employee e1 = new Employee();

		e1.id = val;

		update(e1);

		System.out.println(e1.id);

        Employee e2 = new Employee();

		e2.id = 900;

		switchEmployees(e2,e1);  //3000x , 1000x

		  //GC [2 objects 2000x and 4000x are eligible]

			System.out.println(e1.id);
		    System.out.println(e2.id);
	    }

	 public static void update(Employee e)
	 {
        e.id = 500;
		e = new Employee();
		e.id = 400;
		System.out.println(e.id);
	 }

	 public static void switchEmployees(Employee e1, Employee e2)
	  {
		 int temp = e1.id;
```

e1.id = e2.id; //500
```java
		 e2 = new Employee();
		 e2.id = temp;
	  }
   }
```

HEAP and STACK Diagram for Test.java
```java
class Test
{
int x;
int y;

void m1(Test t)
{
x=x+1;
y=y+2;
t.x=t.x+3;
t.y=t.y+4;
}
public static void main(String[] args)
{
Test t1=new Test();
Test t2=new Test();

t1.m1(t2);

System.out.println(t1.x+"... "+t1.y); //
System.out.println(t2.x+"... "+t2.y); //

t2.m1(t1);
System.out.println(t1.x+"... "+t1.y);
System.out.println(t2.x+"... "+t2.y);

t1.m1(t1);
System.out.println(t1.x+"... "+t1.y);
System.out.println(t2.x+"... "+t2.y);

t2.m1(t2);
System.out.println(t1.x+"... "+t1.y);
System.out.println(t2.x+"... "+t2.y);
}
}
```

Passing an Object reference to the Constructor :(Copy Constructor)
We can pass an object reference to the constructor so we can copy the content of one object to another object.

```java
public class Manager {
	private int managerId;
	private String managerName;

	public Manager(Employee emp) // emp = e1 [copy constructor]
	{
		this.managerId = emp.getEmployeeNumber();
		this.managerName = emp.getEmployeeName();
	}

}
```

Program that describes how to copy the content of Employee object to initialize the Manager class properties.

3 files :
Employee.java
```java
package com.ravi.copy_constructor;

public class Employee {
	private int employeeNumber;
	private String employeeName;

	public Employee(int employeeNumber, String employeeName) {
		super();
		this.employeeNumber = employeeNumber;
		this.employeeName = employeeName;
	}

	public int getEmployeeNumber() {
		return this.employeeNumber;
	}

	public String getEmployeeName() {
		return this.employeeName;
	}

}

```

Manager.java
```java
package com.ravi.copy_constructor;

public class Manager {
	private int managerId;
	private String managerName;

	public Manager(Employee emp) // emp = e1
	{
		this.managerId = emp.getEmployeeNumber();
		this.managerName = emp.getEmployeeName();
	}

	@Override
	public String toString() {
		return "Manager [managerId=" + managerId + ", managerName=" + managerName + "]";
	}

}

```

CopyConstructor.java
```java
package com.ravi.copy_constructor;

public class CopyConstructor
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(111, "Scott");
		Manager m1 = new Manager(e1);
		System.out.println(m1);

	}

}

```


> **Note :- In the above program we are receiving data the from Employee object(one class) and assigning to Manager Object(another class) using object reference.**


In the following program we are taking the data from same class and initailizing in the same class.

2 files :
Player.java
```java
package com.ravi.copy_constructor;

public class Player
{
   private String name1, name2;

	public Player(String name1, String name2)
	{
		super();
		this.name1 = name1;
		this.name2 = name2;
	}

    public Player(Player player) //player = p1
    {
    	this.name1 = player.name2;
    	this.name2 = player.name1;
    }

	@Override
	public String toString() {
		return "Player [name1=" + name1 + ", name2=" + name2 + "]";
	}



}


```

PlayerDemo.java
```java
package com.ravi.copy_constructor;

public class PlayerDemo {

	public static void main(String[] args)
	{
		Player p1 = new Player("Virat", "Rohit");

		Player p2 = new Player(p1);

		System.out.println(p1+" : "+p2);

	}

}
```


### Lab Program

Lab Program :(Method return type as a class + Passing Object ref)
A class called Customer is given to you.

The task is to find the applicable Credit card Type and create CardType object based on the Credit Points of a customer.

Define the following for the class.

Attributes :
customerName : String,private
creditPoints: int, private

Constructor :
parameterizedConstructor: for both cusotmerName & creditPoints in that order.

Methods :
Name of the method : getCreditPoints
Return Type : int
Modifier   : public
Task : This method must return creditPoints

Name of the method : toString, Override it,
Return type : String
Task :  return only customerName from this.

Create another class called CardType. Define the following for the class

Attributes :
customer : Customer, private
cardType : String, private
Constructor :
parameterizedConstructor: for customer and cardType attributes in that order

Methods :
Name of the method : toString  Override this.
Return type : String
Modifier : public
Task :  Return the string in the following format.
The Customer 'Rajeev' Is Eligible For 'Gold' Card.


Create One more class by name CardsOnOffer and define the following for the class.

Method :
Name Of the method : getOfferedCard
Return type : CardType
Modifiers: public,static
Arguments: Customer object

Task : 	Create and return a CardType object after logically finding cardType from creditPoints as per the below rules.
creditPoints	    cardType
100  - 500	-   Silver
501  - 1000	-   Gold
1000 >		-   Platinum
< 100		-   EMI

Create  an ELC class which contains Main method to test the working of the above.

4 files :
Customer.java
```java
package com.ravi.lab;

public class Customer
{
	private String customerName;
	private int creditPoints;

	public Customer(String customerName, int creditPoints) {
		super();
		this.customerName = customerName;
		this.creditPoints = creditPoints;
	}

	public int getCreditPoints()
	{
		return this.creditPoints;
	}

	@Override
	public String toString()
	{
		return this.customerName;
	}


}

```

CardType.java
```java
package com.ravi.lab;

public class CardType
{
	private Customer customer;
	private String cardType;

	public CardType(Customer customer, String cardType)
	{
		super();
		this.customer = customer;
		this.cardType = cardType;
	}

	@Override
	public String toString()
	{

	  return "The Customer '"+this.customer+"' Is Eligible for '"+this.cardType+"' Card";
	}

}

```

CardsOnOffer.java
```java
package com.ravi.lab;

public class CardsOnOffer
{
   public static CardType getOfferedCard(Customer obj)
   {
	   int creditPoint = obj.getCreditPoints();

	   if(creditPoint >=100 && creditPoint <=500)
	   {
		   return new CardType(obj, "Silver");
	   }
	   else if(creditPoint >500 && creditPoint <=1000)
	   {
		   return new CardType(obj, "Gold");
	   }
	   else if(creditPoint > 1000)
	   {
		   return new CardType(obj, "Platinum");
	   }
	   else
	   {
		   return new CardType(obj, "EMI");
	   }
   }
}

```

CreditCard.java
```java
package com.ravi.lab;

import java.util.Scanner;

public class CreditCard {

	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the Name of the Customer :");
		String name = sc.nextLine();
		System.out.print("Enter the Credit points of the Customer :");
		int creditPoint = sc.nextInt();

		Customer c1 = new Customer(name, creditPoint);
		CardType offeredCard = CardsOnOffer.getOfferedCard(c1);
		System.out.println(offeredCard);
		sc.close();

	}

}
```




## 20-05-2024


### Declaring a constructor as private


### We should declare a constructor as private for the following 2 reasons


1) To craete a class where all the variables and methods are static so, object is not reqired.

2) To create a singleton class, singleton class means object will be created only once from the same user not from outside user.

```java
class Calculate  //Singleton class
{
	private Calculate()
	{
		System.out.println("Private Constructor Calculate class!!!");
	}
}

public class Test
{
	private Test()
	{
	  System.out.println("Private Constructor of Test class!!!");
	}

	public static void main(String[] args)
	{
	   //new Calculate();
	   //new Test();


	}

}


```


> **Note :- we can't declare constructor static and final.**


### What is an instance block OR instance initializer ?


### What is Instance OR non-static block in Java ?

```java
//Instance Block OR Non-static block

{

}

```

It is a special block in java which is executed automatically whenever an object is created. [Depends upon object creation]

It will be automatically placed in the 2nd line of the constructor, if it is available in the class.

The main purpose of instance block to initialize the instance variable of the class before constructor body execution so, it is also known as instance initializer.

Always the instance block will be executed before the constructor body execution.

If we have n number of instance block available in the class then it would be executed according to the order.[top to bottom]

If we write the instance block in the body of the constructor then compiler will not placed in the 2nd line of Constructor.
```java
package com.ravi.equals;

class Test
{
	{
		System.out.println("Instance Block!!!");
	}
}


public class InstanceBlockDemo1 {

	public static void main(String[] args)
	{
		Test t1 = new Test();
		Test t2 = new Test();

	}

}
```

```java
package com.ravi.equals;

class Demo
{
	public Demo()
	{
		System.out.println("No Argument Constructor!!");
	}

	{
		System.out.println("Instance Block!!");
	}
}


public class InstanceBlockDemo2 {

	public static void main(String[] args)
	{
		new Demo();  new Demo();
	}

}
```

```java
package com.ravi.equals;

class Foo
{
	int x;

	public Foo()
	{
		System.out.println(x);
	}

	{
		x = 100;
	}

	{
		x = 200;
	}

	{
		x = 300;
	}
}


public class InstanceBlockDemo3 {

	public static void main(String[] args)
	{
		Foo f1 = new Foo();

	}

}


```

```java
package com.ravi.equals;

class Sample
{
	public Sample()
	{
		System.out.println("No Argument Constructor!!");

		{
			System.out.println("Instance Block");
		}

	}


}
public class InstanceBlock4
{
	public static void main(String[] args)
	{
		new Sample();

	}

}

```


> **Note :- Whenever we want to initialize the instance variable before constructor body execution then we should use instance block.**


### Initialization life cycle of an  instance variable


### Whenever we create an object in java then the instance variable, we can initialized in the following places


1) Instance variable will be initialized with default value using super keyword.

2) Now the control will verify that instance variable is initialized at the time of declaration or not.

3) Then It will verify, it is initialized inside instance block or not.

4) Now,It will verify it is initialized in the body of the constructor or not.

5) It will verify in the method body, it is initialized or not but It does not come under object creation.

```java
package com.ravi.equals;

class Test
{
	int x = 10;

	{
		x = 20;
	}

	public Test()
	{
		x = 30;
	}

	public void m1()
	{
		x = 40;
	}
}


public class InstanceBlockDemo1 {

	public static void main(String[] args)
	{
		Test t1 = new Test(); t1.m1();
		System.out.println(t1.x);

	}

}

```

Variable Iniatilization order -> default value(super keyword) -> Declaration time -> instance block -> constructor body -> Method body(We need to call explicitly)

### What is blank final variable

1) If a final instance variable is declared without initialization then it is called Blank final variable.

Example :- final int A;   //Blank final variable

2) A final variable must be initialized by the user explicitly before the completion of constructor body. [Till object creation]

3) It is not initialized by default constructor.

```java
public class Test
{
	final int A;

	public static void main(String[] args)
	{
	  Test t1 = new Test();
	  System.out.println(t1.A); //error
	}

}

```

4) We can't initialize the blank final variable inside the method
body because method execution is possible after object creation.

5) A blank final variable must be initialized in the following
two places :

1) Inside an instance initializer OR
2) Inside the constructor body.

```java
//Initializing the blank final variable inside instance block

package com.ravi.equals;

class Test
{
	final int A;  //Blank final variable

	{
		A = 100;
	}

}


public class BlankFinalDemo {

	public static void main(String[] args)
	{
		Test t1 = new Test();
		System.out.println(t1.A);

	}

}

//Initializing the blank final variable inside Constructor
package com.ravi.equals;

class Test
{
	final int A ;  //Blank final variable

	public Test()
	{
		A = 500;
	}

}


public class BlankFinalDemo1 {

	public static void main(String[] args)
	{
		Test t1 = new Test();
		System.out.println(t1.A);

	}

}

```

6) A blank final variable can also have defualt values.

```java
package com.ravi.equals;

class Ravi
{
	final int A;

	{
		m1();
		A = 100;
	}

	public void m1()
	{
		System.out.println(A);  //0
	}

}

public class BalnkFinalDefaultValue {

	public static void main(String[] args)
	{
		System.out.println(new Ravi().A); //100

	}

}

```

7) A blank final variable must be initialized by the user in all the
constructors available in the class.

```java
   class Employee
    {
	final int EMPID; //Blank final variable

    public Employee()
	{
		EMPID = 101;
	}

    public Employee(int id)
	{
		EMPID = id;
	}
}


public class Test
{
	public static void main(String[] args)
	{
```

Employee e1 = new Employee();  //e1 - EMPID = 101
Employee e2 = new Employee(102);  //e2 - EMPID = 102
```java
      System.out.println(e1.EMPID);
	  System.out.println(e2.EMPID);

	}

}
```


## 21-05-2024


### Relationship between the classes

In Java, in between the classes we have 2 types of relation

1) IS-A Relation
2) HAS-A Relation

IS-A relation we can achieve using Inheritance.

## HAS-A relation we can achieve using Association.


Example of IS-A relation :

```java
class Vehicle
{

}
class Car extends Vehicle
{
}

```

In between Vehicle and Car we have IS-A relation because Car IS-A
Vehicle.

Example of HAS-A relation :
```java
class Vehicle
{
  private Engine engine;
}

```

In between Vehicle and Engine, We have HAS-A relation because Vehicle has an engine.

## Inheritance (IS-A Relation)

Deriving a new class (child class) from existing class (parent class) in such a way that the new class will acquire all the properties and features (except private) from the existing class is called inheritance.

It is one of the most imporatnt feature of OOPs which provides "CODE REUSABILITY".

Using inheritance mechanism the relationship between the  classes is parent and child. According to Java the parent class is called super class and the child class is called sub class.

In java we provide inheritance using 'extends' keyword.

*By using inheritance all the feature of super class is by default available to the sub class so the sub class need not to start the process from begning onwards.


## Inheritance provides IS-A relation between the classes. IS-A relation is tightly coupled relation (Blood Relation) so if we modify the super class content then automatically sub class content will also modify.



## Inheritance provides us hierarchical classification of classes, In this hierarchy if we move towards upward direction more generalized properties will occur, on the other hand if we move towards downwand more specialized properties will occur.


### Types of Inheritance in java


### Java supports 5 types of inheritance


1) Single level Inheritance
2) Multi level Inheritance
3) Hierarchical Inheritance
4) Multiple Inheritance (Not supported using class)
5) Hybrid Inheritance (Combination of two)

Program on single level inheritance :
SingleLevelInheritance.java [Single file Approach]

```java
package com.ravi.inheritance;

class Father
{
	public void house()
	{
		System.out.println("3BHK house");
	}
}
class Son extends Father
{
	public void car()
	{
		System.out.println("Audi car");
	}
}

public class SingleLevelInheritance
{
	public static void main(String[] args)
	{
		Son s = new Son();
		s.house();
		s.car();

	}

}

```


> **Note :- In inheritance we should always create the object for the more specialized class because the specialized class will take**

all the properties from super class.

### Program on Single Level Inheritance

```java
package com.ravi.inheritance;

class Super
{
	private int x,y;

	public void accept()
	{
		x = 100;
		y = 200;
	}

	public int getX()
	{
		return x;
	}

	public void setX(int x)
	{
		this.x = x;
	}

	public int getY() {
		return y;
	}

	public void setY(int y) {
		this.y = y;
	}

}
class Sub extends Super
{
	public void show()
	{
		System.out.println("x value is :"+getX());
		System.out.println("y value is :"+getY());
	}
}


public class SingleLevelInheritanceEx
{
	public static void main(String[] args)
	{
		Sub s1 = new Sub();
		s1.accept();
		s1.show();
	}

}
```

In java we have a predefined class called Object available in java.lang pacakge, by default this Object class is the super class of all the classes in java.

Initializing the object properties through constructor :
In order to iniatilize the super class properties we should use super keyword.

super keyword we can use three ways in java :
1) To call super class variable
2) To call super class method
3) To call super class constructor (4 cases)


## 22-05-2024

1) To call super class variable
If the super class variable name and sub class variable name both are same then it is called variable shadow, Here sub class variable will hide super class variable.

If we create an object for sub class then by default it will access sub class variable, if we want to access super class variable then we should use super keyword.

super keyword always refers to its immediate super class.

Just like this keyword we cannot use super keyword from static context.

SuperVarDemo.java
```java
package com.ravi.super_demo;

class Father
{
	protected double balance = 50000;
}
class Son extends Father
{
	protected double balance = 30000;

	public void getBalance()
	{
		System.out.println("Son balance is :"+this.balance);
		System.out.println("Father balance is :"+super.balance);
	}
}
public class SuperVarDemo
{
	public static void main(String[] args)
	{
		Son s = new Son();
		s.getBalance();

	}

}
```


### 2) To call super class method

Whenever super class method name and sub class method name both are same and if we create an object for sub class then by defulat it will access sub class method.

If we want to access super class method from sub class then we should use super keyword.

Note : In the inheritance tree, whenever we call a method, first of all JVM will search the method in the specialized class (bottom class) if it is not available then it will move to super class.
[IN INHERITANCE TREE METHOD SEARCHING IS ALWAYS FROM BOTTOM TO TOP]

```java
package com.ravi.super_demo;

class Super
{
	public void show()
	{
		System.out.println("Super class show method");
	}
}
class Sub extends Super
{
	public void show()
	{
		super.show();
		System.out.println("Sub class show method");
	}
}

public class SuperMethod {

	public static void main(String[] args)
	{
	   Sub s = new Sub();  	s.show();
    }

}
```

3) **To call the super class constructor : (Constructor Chaining)
Whenever we write a class in java and we don't write any kind of constructor to the class then the java compiler will automatically add one default constructor to the class.

THE FIRST LINE OF ANY CONSTRUCTOR IS RESERVERD EITHER FOR super() or this() keyword.

In the first line of any constructor if we don't specify either super() or this() then the compiler will automatically add super() to the first line of constructor.

Now the purpose of this super() [added by java compiler], to call the default constructor or No-Argument constructor of the super class.

In order to call the constructor of super class as well as same class, we have total 4 cases.


We have 4 cases :

### case 1

```java
super() :- Automatically added by compiler and it is used to access default or no argument constructor of super class.

package com.ravi.super_constructor;

class Super
{
	public Super()
	{
		super();
		System.out.println("No Args constructor of super class");
	}
}
class Sub extends Super
{
	public Sub()
	{
		super();
		System.out.println("No Args constructor of Sub class");
	}
}

public class SuperConstructorDemo1
{
	public static void main(String[] args)
	{
		new Sub();
	}

}
```


> **Note :- If a super class contains parameterized constructor then**

at the time of defining sub class we will get compilation error because compiler will force the user to write his own super of to call parameterized constructor of super class.
Program that described every empty class has defualt constructor
and first line is reserved for super().

IQ.java
```java
package com.ravi.super_constructor;

class Alpha
{
	public Alpha()
	{
		System.out.println("Alpha");
	}
}
class Beta extends Alpha
{

}
class Gamma extends Beta
{
	public Gamma()
	{
		System.out.println("Gamma");
	}
}


public class IQ {

	public static void main(String[] args)
	{
		new Gamma();
	}

}
```


### Case 2

```java
super("NIT") : User is responsible to write super of, to call parameterized constructor of super class.

package com.ravi.super_constructor;

class Parent
{
	public Parent(String str)
	{
	 System.out.println("Parameterized constructor of super class :"+str);
	}
}
class Child extends Parent
{
	public Child(String str)
	{
		super(str);
		System.out.println("Parameterized constructor of sub class");

	}
}

public class CallingParameterized
{
	public static void main(String[] args)
	{
		new Child("NIT");

	}

}
```


### Case 3

```java
this() : Written by user, to call the no argument constructor of
         the current class (Same class);

package com.ravi.super_constructor;

class Parent
{
	public Parent()
	{
		super();
		System.out.println("No Args of super class");
	}
	public Parent(String str)
	{
		this();
	 System.out.println("Parameterized constructor of super class :"+str);
	}
}
class Child extends Parent
{
	public Child(String str)
	{
		super(str);
		System.out.println("Parameterized constructor of sub class");

	}
}

public class CallingParameterizedAndCurrentClass
{
	public static void main(String[] args)
	{
		new Child("NIT");

	}

}
```


### Case 4

```java
this(9) : Written by user, to call parameterized constructor of
```

current class.

```java
package com.ravi.super_constructor;

class Base
{
	public Base()
	{
		this(9);
		System.out.println("No Args of Base class");
	}

	public Base(int x)
	{
		System.out.println("Parameterized of Base class :"+x);
	}

}
class Derived extends Base
{
	public Derived()
	{
		System.out.println("No args of Derived class");
	}
}


public class CallingCurrentClassParametrized {

	public static void main(String[] args)
	{
		new Derived();

	}

}
```


### Program on super keyword using Single level inheritance

```java
package com.ravi.super_constructor;

import java.util.Scanner;

class Shape
{
	protected int x;

	public Shape(int x)
	{
		this.x = x;
	}
}
class Square extends Shape
{
	public Square(int side)
	{
		super(side);
	}

	public void areaOfSquare()
	{
		double area = x * x;
		System.out.println("Area of square is :"+area);
	}

}

public class SuperDemo1 {

	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the value of the side :");
		int side = sc.nextInt();

		Square ss = new Square(side);
		ss.areaOfSquare();
		sc.close();

	}

}
```


## 23-05-2024


### Program on hierarchical inheritance

HierarchicalDemo.java
```java
package com.ravi.inheritance;

import java.util.Scanner;

class Shape
{
	protected int x;
	public Shape(int x)
	{
		this.x = x;
		System.out.println("x value is :"+x);
	}
}
class Circle extends Shape
{
	final double PI = 3.14;

	public Circle(int radius)
	{
		super(radius);
	}

	public void areaOfCircle()
	{
		double area = PI * super.x * super.x;
		System.out.println("Area of Circle is :"+area);
	}

}

class Rectangle extends Shape
{
	protected int breadth;
	public Rectangle(int length, int breadth)
	{
		super(length);
		this.breadth = breadth;
	}

	public void areaOfRectangle()
	{
		double area = super.x * this.breadth;
		System.out.println("Area of Rectangle is :"+area);
	}

}
public class HierarchicalDemo {

	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
        System.out.print("Enter the radius of the circle :");
		int radius = sc.nextInt();

		Circle c1 = new Circle(radius);
		c1.areaOfCircle();

		System.out.print("Enter the length of the Rectangle :");
		int length = sc.nextInt();

		System.out.print("Enter the breadth of the Rectangle :");
		int breadth = sc.nextInt();

		Rectangle rr = new Rectangle(length, breadth);
		rr.areaOfRectangle();
		sc.close();

	}

}
```


### WAP in java to implement Single level inheritance

```java
package com.ravi.inheritance;

class Emp
{
	protected int employeeId;
	protected String employeeName;
	protected double employeeSalary;

	public Emp(int employeeId, String employeeName, double employeeSalary) {
		super();
		this.employeeId = employeeId;
		this.employeeName = employeeName;
		this.employeeSalary = employeeSalary;
	}

	@Override
	public String toString()
	{
		return "Emp [employeeId=" + employeeId + ", employeeName=" + employeeName + ", employeeSalary=" + employeeSalary
				+ "]";
	}


}

class Pemp extends Emp
{
	protected String department;
	protected String designation;

	public Pemp(int employeeId, String employeeName, double employeeSalary, String department, String designation)
	{
		super(employeeId, employeeName, employeeSalary);
		this.department = department;
		this.designation = designation;
	}

	@Override
	public String toString()
	{
		return super.toString() +"Pemp [department=" + department + ", designation=" + designation + "]";
	}



}

public class SingleLevelDemo {

	public static void main(String[] args)
	{
	  Pemp p = new Pemp(1, "Raj", 40000, "IT", "Developer");
	  System.out.println(p);
	}

}
```


### Program on Hierarchical Inheritance

```java
package com.ravi.inheritance;

class Employee
{
	protected double salary;

	public Employee(double salary)
	{
		super();
		this.salary = salary;
	}
}

class Developer extends Employee
{

	public Developer(double salary)
	{
		super(salary);
	}

	@Override
	public String toString()
	{
		return "Developer [salary=" + salary + "]";
	}
}

class Designer extends Employee
{
	public Designer(double salary)
	{
		super(salary);
	}

	@Override
	public String toString()
	{
		return "Designer [salary=" + salary + "]";
	}
}



public class HierarchicalExample
{
	public static void main(String[] args)
	{
		Developer developer =  new Developer(60000);
		System.out.println(developer);

		Designer designer = new Designer(35000);
		System.out.println(designer);

	}

}
```

```java
//Program on multilevel inheritance
package com.ravi.inheritance;

class Student
{
	protected int studentId;
	protected String studentName;
	protected String studentAddress;

	public Student(int studentId, String studentName, String studentAddress) {
		super();
		this.studentId = studentId;
		this.studentName = studentName;
		this.studentAddress = studentAddress;
	}
}
class Science extends Student
{
	protected int physics;
	protected int chemistry;

	public Science(int studentId, String studentName, String studentAddress, int physics, int chemistry)
	{
		super(studentId, studentName, studentAddress);
		this.physics = physics;
		this.chemistry = chemistry;
	}
}
class PCM extends Science
{
	protected int maths;

	public PCM(int studentId, String studentName, String studentAddress, int physics, int chemistry, int maths)
	{
		super(studentId, studentName, studentAddress, physics, chemistry);
		this.maths = maths;
	}

	@Override
	public String toString()
	{
		return "PCM [maths=" + maths + ", physics=" + physics + ", chemistry=" + chemistry + ", studentId=" + studentId
				+ ", studentName=" + studentName + ", studentAddress=" + studentAddress + "]";
	}

	public void totalMarks()
	{
		int total = physics + chemistry + maths;
		System.out.println("Total Marks is :"+total);
	}


}

public class MultiLevelExample {

	public static void main(String[] args)
	{
		PCM p = new PCM(1, "Scott", "Hyd", 78, 89, 90);
		System.out.println(p);
		p.totalMarks();

	}

}
```


### HOW MANY WAYS WE CAN INITIALIZE THE OBJECT PROPERTIES ?


The following are the ways to initialize the object properties
```java
public class Test
{
   int x,y;
}


```

1) At the time of declaration :

Example :

```java
  public class Test
   {
      int x = 10;
      int y = 20;
   }

```

Test t1 = new Test();   [x = 10  y = 20]
Test t2 = new Test();   [x = 10  y = 20]

Here the drawback is all objects will be initialized with same value.


### 2) By using Object Reference


```java
   public class Test
   {
      int x,y;
   }

   Test t1 = new Test();   t1.x=10;   t1.y=20;
   Test t2 = new Test();   t2.x=30;   t2.y=40;

```

Here we are getting different values with respect to object but here the program becomes more complex.

### 3) By using methods


A) First Approach (Method without Parameter)
```java
   public class Test
   {
      int x,y;

      public void setData()
      {
         x = 100;  y = 200;
      }
   }

```

Test t1 = new Test();  t1.setData();  [x = 100   y = 200]
Test t2 = new Test();  t2.setData();  [x = 100   y = 200]

All the objects will be initialized with same value.

B) Second Approach (Method with Parameter)
```java
     public class Test
     {
      int x,y;

      public void setData(int x, int y)
      {
         this.x = x;
	 this.y = y;
      }
   }

```

Test t1 = new Test();  t1.setData(12,78);  [x = 12   y = 78]
Test t2 = new Test();  t2.setData(15,29);  [x = 15   y = 29]

Here the Drawback is initialization and re-initialization both are done in two different lines so Constructor introduced.
4) By using Constructor

A) First Approach (No Argument Constructor)
```java
   public class Test
   {
      int x,y;

      public Test()  //All the objects will be initialized with
      {                                             same value
         x = 100;  y = 200;
      }
   }

```

Test t1 = new Test();    [x = 100   y = 200]
Test t2 = new Test();    [x = 100   y = 200]


B) Second Approach (Parameterized Constructor)
```java
     public class Test
     {
      int x,y;

      public Test(int x, int y)
      {
         this.x = x;
	 this.y = y;
      }
   }

```

Test t1 = new Test(12,78);    [x = 12   y = 78]
Test t2 = new Test(15,29);    [x = 15   y = 29]

This is the best way to initialize our instance variable because variable initialization and variable re-initialization both will be done in the same line as well as all the objects will be initialized with different values.

C) Third Approach (Copy Constructor)

```java
       public class Manager
       {
          private int managerId;
	  private String managerName;

	  public Manager(Employee emp)
	  {
	    this.managerId = emp.getEmployeeId();
	    this.managerName = emp.getEmployeeName();
          }
       }

```

Here with the help of Object reference (Employee class) we are
initializing the properties of Manager class. (Copy Constructor)

d) By using instance block (Instance Initializer)

```java
	public class Test
	{
	   int x,y;

           public Test()
	   {
	      System.out.println(x); //100
	      System.out.println(y); //200
	   }

           //Instance block
	   {
	       x = 100;
	       y = 200;
	   }

```


### 5) By using super keyword


```java
   class Super
   {
     int x,y;

     public Super(int x , int y)
     {
        this.x = x;
	this.y = y;
     }
   }
   class Sub extends Super
   {
      Sub()
      {
         super(100,200); //Initializing the properties of super class
      }
   }

   new Sub();
```






## Why java does not support multiple inheritance ?

Multiple Inheritance is a situation where a sub class wants to inherit the properties two or more super classes and by using super keyword we have ambiguity issue. It is also known as Diamond Problem.

Java does not support multiple inheritance because in the sub class, automatically one super keyword will be added by compiler to the first line of constructor now we have ambiguity issue to call default constructor of super class as shown in the diagram (23-MAY-24)

Multiple inheritance we can't achieve using classes but same is possible by using interface.
The program describes that instance blocks are reserved for 2nd line of constructor.

```java
package com.ravi.inheritance;

class Alpha
{
	public Alpha()
	{
		System.out.println("A");
	}

	{
		System.out.println("B");
	}
}
class Beta extends Alpha
{
	public Beta()
	{
		System.out.println("C");
	}

	{
		System.out.println("D");
	}
}

public class InheritanceWithInstanceBlock
{
	public static void main(String[] args)
	{
		new Beta();   //BA DC

	}

}
```





## 24-05-2024


## Access modifiers in java


### In order to define the accessibility level of the class as well as member of the class we have 4 access modifiers


1) private (Within the same class)
2) default (Within the same package)
3) protected (Within the same package Or even from another
```java
              package by using Inheritance)
```

4) public (No Restriction)

```java
private :
```

It is the most restrictive access modifier because the member declared as private can't be accessible from outside of the class.
In Java we can't declare an outer class as a private or protected. Generally we should declare the data member(variables) as private.

In java outer class can be declared as public, abstract, final, sealed and non-sealed only.


default :-
It is an access modifier which is less restrictive than private. It is such kind of access modifier whose physical existance is not avaialble that means when we don't specify any kind of access modifier before the class name, variable name or method name then by default it would be default.

As far as its accessibility is concerned, default members are accessible within the same folder(package) only.

```java
protected :
```

It is an access modifier which is less restrictive than default because the member declared as protected can be accessible from the outside of the package (folder) too but by using inheritance concept.

2 files (Both are in two different packages)
Access.java  [Package is : com.ravi.m1]
```java
package com.ravi.m1;

public class Access
{
  protected int x = 500;
}

```

ELC.java  [Package is : com.ravi.m2]
```java
package com.ravi.m2;

import com.ravi.m1.Access;

public class ELC extends Access
{
	public static void main(String[] args)
	{
		ELC e = new ELC();
		System.out.println(e.x);

	}

}
```

```java
public :
```

It is an access modifier which does not contain any kind of restriction that is the reason the member declared as public can be accessible from everywhere without any restriction.

According to Object Oriented rule we should declare the classes and methods as public where as variables must be declared as private or protected according to the requirement.




## HAS-A relation between the classes

In order to acheive HAS-A relation concept we should use Association.

```java
Association (Relationship between the classes through Object reference)
```


### Association

Association is a connection between two separate classes that can be built up through their Objects.

The association builds a relationship between the classes and describes how much a class knows about another class.

This relationship can be unidirectional or bi-directional. In Java, the association can have one-to-one, one-to-many, many-to-one and many-to-many relationships.

Example:-
One to One: A person can have only one PAN card (1:1)
One to many: A Bank can have many Employees (1:M)
Many to one:  Many employees can work in single department (M:1)
Many to Many: A Bank can have multiple customers and a customer can have multiple bank accounts. (M:M)

### Program on Association

AssiciationDemo.java
```java
package com.ravi.association;

import java.util.Scanner;

class Student
{
	private int studentId;
	private String studentName;
	private int studentMarks;

	public Student(int studentId, String studentName, int studentMarks) {
		super();
		this.studentId = studentId;
		this.studentName = studentName;
		this.studentMarks = studentMarks;
	}

	@Override
	public String toString() {
		return "Student [studentId=" + studentId + ", studentName=" + studentName + ", studentMarks=" + studentMarks
				+ "]";
	}

	public int getStudentId() {
		return studentId;
	}

	public String getStudentName() {
		return studentName;
	}

	public int getStudentMarks() {
		return studentMarks;
	}

}

class Trainer
{
	public static void viewStudentProfile(Student s)
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter Student Id :");
		int id = sc.nextInt();

		if(id== s.getStudentId())
		{
			System.out.println(s);
		}
		else
		{
			System.err.println("Sorry!! Student record is not available");
		}
		sc.close();
	}
}

public class AssiciationDemo {

	public static void main(String[] args)
	{
		Student s1 = new Student(1, "Scott", 60);

		Trainer.viewStudentProfile(s1);
	}
}
```




### Composition (Strong reference)

Composition in Java is a way to design classes such that one class contains an object of another class. It is a way of establishing a "HAS-A" relationship between classes.

Composition represents a strong relationship between the containing class and the contained class.If the containing object (Car object) is destroyed, all the contained objects (Engine object) are also destroyed.

A car has an engine. Composition makes strong relationship between the objects. It means that if we destroy the owner object, its members  will be also destroyed with it. For example, if the Car is destroyed the engine will also be destroyed as well.

CompositionDemo.java
```java
package com.ravi.composition;

class Engine
{
	private String engineType;
	private int horsePower;

	public Engine(String engineType, int horsePower)
	{
		super();
		this.engineType = engineType;
		this.horsePower = horsePower;
	}

	@Override
	public String toString() {
		return "Engine [engineType=" + engineType + ", horsePower=" + horsePower + "]";
	}

}

class Car
{
	 private String carName;
	 private int carModel;
	 private final Engine engine; //HAS-A relation


	public Car(String carName, int carModel)
	{
		super();
		this.carName = carName;
		this.carModel = carModel;
		this.engine = new Engine("Battery", 1200); //composition

	}


	@Override
	public String toString() {
		return "Car [carName=" + carName + ", carModel=" + carModel + ", engine=" + engine + "]";
	}

}

public class CompositionDemo {

	public static void main(String[] args)
	{
		Car c1 = new Car("Ford", 2024);
		System.out.println(c1);

	}

}
```


### Aggregation (Weak Reference)

Aggregation in Java is another form of association between classes that represents a "HAS-A" relationship, but with a weaker bond compared to composition.

In aggregation, one class contains an object of another class, but the contained object can exist independently of the container. If the container object is destroyed, the contained object can still exist.

3 files :
College.java
```java
package com.ravi.aggregation;

public class College
{
	private String collgeName;
	private String collegeLocation;

	public College(String collgeName, String collegeLocation) {
		super();
		this.collgeName = collgeName;
		this.collegeLocation = collegeLocation;
	}

	@Override
	public String toString() {
		return "College [collgeName=" + collgeName + ", collegeLocation=" + collegeLocation + "]";
	}

}

```

Student.java
```java
package com.ravi.aggregation;

public class Student
{
	private int studentId;
	private String studentName;
	private String studentAddress;
	private College clg;

	public Student(int studentId, String studentName, String studentAddress, College clg) //clg = c1
	{
		super();
		this.studentId = studentId;
		this.studentName = studentName;
		this.studentAddress = studentAddress;
		this.clg = clg;
	}

	@Override
	public String toString() {
		return "Student [studentId=" + studentId + ", studentName=" + studentName + ", studentAddress=" + studentAddress
				+ ", clg=" + clg + "]";
	}

}

```

AggregationDemo.java
```java
package com.ravi.aggregation;

public class AggregationDemo {

	public static void main(String[] args)
	{
		College c1 = new College("NIT", "Hyderabad");

		Student s1 = new Student(1, "A", "Ameerpet", c1);
		System.out.println(s1);

		Student s2 = new Student(2,"B","S.R nagar", c1);
		System.out.println(s2);

	}

}

```


> **Note :- IS-A relation is tightly coupled relation so if we modify the content of super class sub class content will also modify but in HAS-A realtion we are accessing the properties of another class so we are not allowed to modify the content, we can access the content or Properties.**


```java
System.out.println() using HAS-A Relation
```


```java
class Test
{
  static String out = "India";
}

Test.out.length();

```

Note : length() is a predefined method of String class
```java
class System
{
   static final PrintStream out;  //HAS-A relation
}

System.out.println();

```


> **Note :- println() is a predefined method of PrintStream class**







***Polymorphism :
Poly means "many" and morphism means "forms".

It is a Greek word whose meaning is "same object having different behavior".

In our real life a person or a human being can perform so many task, in the same way in our programming languages a method or a constructor can perform so many task.

Eg:-

```java
void add(int a, int b)

void add(int a, int b, int c)

void add(float a, float b)

void add(int a, float b)


```


## Polymorphism can be divided into two types


1) Static polymorphism OR Compile time polymorphism OR Early binding

2) Dynamic Polymorphism OR Runtime polymorphism OR Late binding


### 1) Static Polymorphism

The polymorphism which exist at the time of compilation is called Static OR compile time polymorphism.

In static polymorphism, compiler has very good idea that which method is invoked depending upon METHOD PARAMETER.

Here the binding of the method is done at compilation time so, it is known as early binding.

We can achieve static polymorphism by using Method Overloading concept.

Example of static polymorphism : Method Overloading.


2) Dynamic Polymorphism OR Runtime Polymorphism
The polymorphism which exist at runtime is called Dynamic polymorphim Or Runtime Polymorphism.

*Here compiler does not have any idea about method calling, at runtime JVM will decide which method will be invoked depending upon CLASS TYPE.

Here method binding is done at runtime so, it is also called Late Binding.

We can achieve dynamic polymorphism by using Method Overriding.

Example of Dynamic Polymorphism : Method Overriding

## Method Overloading

Writing two or more methods in the same class or even in the super and sub class in such a way that the method name must be same but the argument must be different.

While Overloading a method we can change the return type of the method.

If parameters are same but only method return type is different then it is not an overloaded method.


## Method overloading is possible in the same class as well as super and sub class.


While overloading the method the argument must be different otherwise there will be ambiguity problem.

IQ :
Can we overload the main method/static method ?

Yes, we can overload the main method OR static method but the execution of the program will start from main method which accept String [] array as a parameter.


> **Note :- The advantage of method overloading is same method name we can reuse for different functionality for refinement of the method.**



> **Note :- In System.out.println() or System.out.print(), print()**

and println() methods are best example for Method Overloading.

## 27-05-2024


### Program on Constructor Overloading


### 2 files

Addition.java

```java
package com.ravi.constructor_overloading1;

public class Addition
{
   public Addition(int x, int y)
   {
	   super();
	   System.out.println("Sum of two integer is :"+(x+y));
   }

   public Addition(int x, int y, int z)
   {
	   this(100,200);
	   System.out.println("Sum of three integer is :"+(x+y+z));
   }

   public Addition(float x, float y)
   {
	   this(10,20,30);
	   System.out.println("Sum of two float is :"+(x+y));
   }
}

```

Main.java
```java
package com.ravi.constructor_overloading1;

public class Main {

	public static void main(String []  args)
	{
		new Addition(2.3f, 7.8F);

	}

}
```


### instance block role with constructor

Our instance block will be placed in the constructor which contains super(), if we have multiple constructor and all the constructors are executed according to constructor chaining then compiler will placed instance block to only one constructor which contians super()

Additin.java
```java
package com.ravi.constructor_overloading2;

public class Addition
{
   public Addition()
   {
	  this(100);
	  System.out.println("No Argument Constructor");
   }

   public Addition(int x)
   {
	   this(1000,2000);
	   System.out.println("One Argument Constructor :"+x);

   }
   public Addition(int x, int y)
   {
	   super();
	   System.out.println("Two Argument Constructor :"+x+":"+y);
   }

   {
		System.out.println("Instance Block");
   }
}

```

Test.java
```java
package com.ravi.constructor_overloading2;

public class Test {

	public static void main(String[] args)
	{
		new Addition();

	}
}
```

```java
return keyword inside instance block :
```

An instance block i.e instance initializer must be executed normally. We can't terminate the logic inside an instance block hence we can't write return keyword inside instance block

```java
package com.ravi.aggregation;

public  class Test
{
	 int x = 10;

	{
		System.out.println("Instance block will be executed");
		return x;
	}

	public static void main(String[] args)
	{
      new Test();
	}
}

```

We can't write return keyword to terminate the logic.

### program that describes we can change the return type of the method at the time of method overloading


2 files :

Sum.java
```java
package com.ravi.method_overload;

public class Sum
{
  public int add(int x, int y)
  {
	  int z = x+y;
	  return z;
  }

  public String add(String x, String y) //data base
  {
	  String z = x+y;
	  return z;
  }

  public double add(double x, double y)
  {
	  double z = x+y;
	  return z;
  }
}

```

Main.java
```java
package com.ravi.method_overload;

public class Main
{
	public static void main(String[] args)
	{
		Sum s1 = new Sum();
		String add = s1.add("Data", "base");

		int x = s1.add(12, 12);

		double y = s1.add(12.89, 12.90);


		System.out.println(add+" : "+x+" : "+y);

	}
}
```


## Var-Args

It was introduced from JDK 1.5 onwards.

It stands for variable argument. It is an array variable which can hold 0 to n number of parameters of same type or different type by using Object class.

It is represented by exactly 3 dots (...) so it can accept any number of argument (0 to nth) that means now we need not to define method body again and again, if there is change in method parameter value.


## var-args must be only one and last argument.


We can use var-args as a method parameter only.
The program says var args can accept 0 to n number of parameters.

VarArgs.java

```java
package com.ravi.var_args;

class Test
{
	public void input(int ...x)
	{
      System.out.println("var args executed");
	}
}

public class VarArgs
{
	public static void main(String... args)
	{

	   Test t1 = new Test();
	   t1.input();   t1.input(10);  t1.input(10,20);
	   t1.input(1,2,3,4,5,6,7,8,90,12);
	}

}
```

Progran that describes how to add parameter values of the method

VarArgsSum.java
```java
package com.ravi.var_args;

class Demo
{
	public void accept(int ...x)
	{
		int sum = 0;

		for(int y : x)
		{
			sum = sum +y;
		}
		System.out.println("Sum of Parameter is :"+sum);
	}
}

public class VarArgsSum
{
	public static void main(String[] args)
	{
		Demo d1 = new Demo();
		d1.accept(10,20,30);
		d1.accept(100,200,300,400);
		d1.accept(10,20);

	}

}
```

Program that says we can accept hetrogeneous types of data using var args

```java
package com.ravi.var_args;

class Sample
{
	public void acceptHetro(Object ...x)
	{
	  for(Object y : x)
	  {
		  System.out.println(y);
	  }
	}
}

public class VarArgsHetro {

	public static void main(String[] args)
	{
		new Sample().acceptHetro(12,true,"NIT",89.90, new Integer(100));
	}

}
```

Program that says var args must be only one and last argument.

2 files :
Test.java
```java
package com.ravi.var_args2;

public class Test {
	// All commented codes are invalid


	/*
	 * public void accept(float ...x, int ...y) { }
```

*
```java
	 * public void accept(int ...x, int y) { }
```

*
```java
	 * public void accept(int...x, int ...y) {}
```

*/



```java
	public void accept(int x, int... y) // valid
	{
		System.out.println("x value is :" + x);

		for (int z : y)
		{
			System.out.println(z);
		}
	}
}

```

Main.java
```java
package com.ravi.var_args2;

public class Main {

	public static void main(String[] args)
	{
		Test t1 = new Test();
		t1.accept(100, 200,300,400,500);
	}
}
```


Imp****


## Wrapper classes in java

In java we have 8 primitive data types i.e byte, short, int, long, float, double, char and boolean.

Except these primitives, everything in java is an Object.

If we remove these 8 data types from java then Java will become pure Object Oriented language.

From java 1.5 onwards we can convert primitive to wrapper and wrapper to primitive by using following concept.

a) Autoboxing
b) Unboxing

Autoboxing
When we convert the primitive data types into corresponding wrapper object then it is called Autoboxing as shown below.

Primitive type		Wrapper Object
----------------             ------------------
byte			-	      Byte
short			-	 Short
int			-	     Integer
long			-	     Long
float			- 	 Float
double			-	 Double
char			-	     Chracter
boolean			-	Boolean

## 28-05-2024


### How to convert primitive to wrapper object ?

In order to convert the primitive data type into corresponding object each wrapper class has provided valueOf() static method.

```java
public static Integer valueOf(int x)


```

AutoBoxingDemo.java
```java
package com.ravi.auto_boxing;

public class AutoBoxingDemo {

	public static void main(String[] args)
	{
		byte a = 12;
		Byte b =  Byte.valueOf(a);
		System.out.println("Byte Object :"+b);

		short c = 24;
		Short d = Short.valueOf(c);
		System.out.println("Short Object :"+d);

		int e = 90;
		Integer f = Integer.valueOf(e);
		System.out.println("Integer Object :"+f);


		long g = 12;
		Long h =  Long.valueOf(g);
		System.out.println("Long Object :"+h);

		float i = 2.4f;
		Float j = Float.valueOf(i);
		System.out.println("Float Object :"+j);

		double k = 90.90;
		Double l = Double.valueOf(k);
		System.out.println("Double Object :"+l);

		char ch = 'A';
		Character ch1 = Character.valueOf(ch);
		System.out.println("Character Object :"+ch1);

		boolean b1 = true;
		Boolean x = Boolean.valueOf(b1);
		System.out.println("Boolean Object :"+x);

	}
}
```

In the above progran we have used 1.4 approach so we are converting primitive to wrapper object manualy.
```java
package com.ravi.auto_boxing;

public class AutoBoxingDemo {

	public static void main(String[] args)
	{
		byte a = 12;
		Byte b = a;
		System.out.println("Byte Object :"+b);

		short c = 24;
		Short d = c;
		System.out.println("Short Object :"+d);

		int e = 90;
		Integer f = e;
		System.out.println("Integer Object :"+f);


		long g = 12;
		Long h =  g;
		System.out.println("Long Object :"+h);

		float i = 2.4f;
		Float j = i;
		System.out.println("Float Object :"+j);

		double k = 90.90;
		Double l = k;
		System.out.println("Double Object :"+l);

		char ch = 'A';
		Character ch1 = ch;
		System.out.println("Character Object :"+ch1);

		boolean b1 = true;
		Boolean x = b1;
		System.out.println("Boolean Object :"+x);


	}

}

```


> **Note :- Above program by using JDK 1.5 approach**

```java
//Integer.valueOf(int);
public class AutoBoxing1
{
	public static void main(String[] args)
	{
		int a = 12;
```

Integer x = Integer.valueOf(a); //Upto 1.4 version
```java
		System.out.println(x);


        int y = 15;
```

Integer i = y;   //From 1.5 onwards compiler takes care
```java
		System.out.println(i);
	}
}
```


### Overloaded valueOf() method

1) public static Integer valueOf(int x) : It will convert the given int value into Integer Object.

2) public static Integer valueOf(String str) : It will convert
the given String into Integer Object.
[valueOf() method will convert the String into Wrapper object where as parseInt() method will convet the String into primitive type]

3) public static Integer valueOf(String str, int radix/base) :
It will convert the given String number into Integer object
by using the radix or base.


> **Note :- We can pass base OR radix upto 36**

i.e A to Z (26) + 0 to 9 (10) -> [26 + 10 = 36], It can be
calculated by using Character.MAX_RADIX.
Output will be generated on the basis of radix

```java
//Integer.valueOf(String str)
//Integer.valueOf(String str, int radix/base)
public class AutoBoxing3
{
	public static void main(String[] args)
	{
			Integer a = Integer.valueOf(15);

			Integer b = Integer.valueOf("25");

```

Integer c = Integer.valueOf("111",36); //Here Base we can take upto 36

```java
			System.out.println(a);
			System.out.println(b);
			System.out.println(c);


	}
}
```


```java
public class AutoBoxing4
{
	public static void main(String[] args)
	{
		Integer i1 = new Integer(100);
		Integer i2 = new Integer(100);
		System.out.println(i1==i2);

		Integer a1 = Integer.valueOf(15);
		Integer a2 = Integer.valueOf(15);
		System.out.println(a1==a2);
	}
}

```

== operator always compares the memory address so it is returning false (two object are created using new keyword), on the other hand valueOf() return the same object so it will provide true.
```java
//Converting integer value to String
public class AutoBoxing5
{
	public static void main(String[] args)
	{
		int x = 12;
		String str = Integer.toString(x);
		System.out.println(str+2);
	}
}

```

Integer class has a predefined static method toString(int x), which will convert int to String type.

### Unboxing

Converting wrapper object to corresponding primitive type is called Unboxing.

Wrapper            Primitive
Object               type
----------            ----------
Byte		-	byte

Short		-	short

Integer		-	int

Long		-	long

Float		-	float

Double		-	double

Chracter	-	char

Boolean		-	boolean
We have total 8 Wrapper classes.

Among all these 8, 6 Wrapper classes are the sub class of Number class which represent numbers (either decimal OR non decimal)
so all the following six wrapper classes (Which are sub class of Number class) are providing the following common methods.

1) public byte byteValue()

2) public short shortValue()

3) public int intValue()

4) public long longValue()

5) public float floatValue()

6) public double doubleValue()
```java
package com.ravi.unboxing;

public class UnboxingDemo {

	public static void main(String[] args)
	{
		Byte b = 12;
		byte c = b.byteValue();
		System.out.println("byte primitive :"+c);

		Character ch = 'A';
	    char charValue = ch.charValue();
	    System.out.println("char value :"+charValue);

	}

}

```


> **Note :- The above says how we were converting wrapper object to**

primitive type before java 1.5.
```java
package com.ravi.unboxing;

public class UnboxingDemo {

	public static void main(String[] args)
	{
		Byte b = 12;
		byte c = b;
		System.out.println("byte primitive :"+c);

		Character ch = 'A';
	    char charValue = ch;
	    System.out.println("char value :"+charValue);

	}

}
```

```java
//Converting Wrapper object into primitive
public class AutoUnboxing1
{
   public static void main(String args[])
	   {
```

Integer obj = 15;   //Upto 1.4
```java
			int x = obj.intValue();
			System.out.println(x);
		}
}
```

```java
public class AutoUnboxing2
{
	public static void main(String[] args)
	{
			Integer x = 25;
			int y = x;         //JDK 1.5 onwards
			System.out.println(y);
	}
}
```

```java
public class AutoUnboxing3
{
	public static void main(String[] args)
	{
			Integer i = 15;
			System.out.println(i.byteValue());
			System.out.println(i.shortValue());
			System.out.println(i.intValue());
			System.out.println(i.longValue());
			System.out.println(i.floatValue());
			System.out.println(i.doubleValue());
	}
}
```

```java
public class AutoUnboxing4
{
	public static void main(String[] args)
	{
		Character c1 = 'A';
		char ch = c1.charValue();
		System.out.println(ch);
	}
}
```

```java
public class AutoUnboxing5
{
	public static void main(String[] args)
	{
		Boolean b1 = true;
		boolean b = b1.booleanValue();
		System.out.println(b);
	}
}
```

```java
package com.ravi.unboxing;

public class UnboxingConversion {

	public static void main(String[] args)
	{
	    Byte b = 120;
	    byte byteValue = b.byteValue();
	    short shortValue = b.shortValue();
	    int intValue = b.intValue();
	    long longValue = b.longValue();
	    float floatValue = b.floatValue();
	    double doubleValue = b.doubleValue();



	}

}
```

Unlike primitive types we can't convert one wrapper type object to another wrapper object.

Example :

Long l = 12;  //Invalid

Float f = 90; //Invalid

Double d = 123; //Invalid
UnboxingExample.java
```java
package com.ravi.unboxing;

public class UnboxingExample {

	public static void main(String[] args)
	{
		Byte b = 12;
		Short s = 90;
		Integer i = 123;
		Long l = 190L;
		Float f = 90f;
		Double d = 90D;
		Double d1 = 2.5;

	}

}
```


### Automatic/Implicit/Widening type casting

Whenever we try to assign smaller primitive type value to bigger data type then it is called Widening OR Implicit OR Automatic type casting.

long l = 12; // Widening [int to long]

## 29-05-2024


### Ambiguity issue while overloading a method

While overloading a method, if we have an ambiguity issue then compiler will select the method for binding at the time of compilation by using following rules :

1
Rule 1:
Most specific type (Specific type will get more priority)

```java
double > float
float > long
```

long > int
```java
int > short
int > char
```

short > byte

Rule 2 :
While overloading a method, if we have an ambiguity issue then compiler provides the priority in the following order :

WAV [Widening -> Autoboxing -> Var args]

Rule 3 :
Nearest Type Rule

While Overloading a method if we are getting sub class reference in comparison to super class reference then sub class will be treated as Nearest type.
```java
package com.ravi.overload_method;

class Test
{
	public void accept(double d)
	{
		System.out.println("double");
	}
	public void accept(float d)
	{
		System.out.println("float");
	}

}
public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(6);

	}
}

```

Note : Here float will be executed because float is most specific type.
```java
package com.ravi.overload_method;

class Test
{
	public void accept(int ...x)
	{
		System.out.println("int");
	}
	public void accept(float ...d)
	{
		System.out.println("float");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept();

	}

}

```

Note : Here int will be executed because int is most specific type.
```java
package com.ravi.overload_method;

class Test
{
	public void accept(int ...x)
	{
		System.out.println("int");
	}
	public void accept(char ...d)
	{
		System.out.println("Char");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept();

	}

}

```

Note : Here char will be executed because char is most specific type.

```java
class Test
{
	public void accept(short ...x)
	{
		System.out.println("short");
	}
	public void accept(char ...d)
	{
		System.out.println("Char");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept();

	}

}

```


> **Note :- We will get compilation error because we don't have any**

relation between short and char
```java
class Test
{
	public void accept(short ...x)
	{
		System.out.println("short");
	}
	public void accept(int ...d)
	{
		System.out.println("int");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept();

	}

}
```

```java
class Test
{
	public void accept(short ...x)
	{
		System.out.println("short");
	}
	public void accept(byte ...d)
	{
		System.out.println("byte");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept();

	}

}
```

```java
class Test
{
	public void accept(short x)
	{
		System.out.println("short");
	}
	public void accept(byte x)
	{
		System.out.println("byte");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		//t.accept(15); //error
		t.accept((byte)15);
		t.accept((short)15);

	}

}
```

```java
class Test
{
	public void accept(short x)
	{
		System.out.println("short");
	}
	public void accept(byte x)
	{
		System.out.println("byte");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		//t.accept(15); //error
		t.accept((byte)15);
		t.accept((short)15);

	}

}
```

```java
package com.ravi.overload_method;

class Test
{
	public void accept(int x)
	{
		System.out.println("int");
	}

	public void accept(long x)
	{
		System.out.println("long");
	}

}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(9);

	}

}
```

```java
package com.ravi.overload_method;

class Alpha
{

}
class Beta extends Alpha
{

}

class Test
{
	public void accept(Alpha x)
	{
		System.out.println("Alpha");
	}

	public void accept(Beta x)
	{
		System.out.println("Beta");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(null);

	}

}

```


> **Note :- Beta will be executed because Beta is the nearest type.**

```java
package com.ravi.overload_method;

class Test
{
	public void accept(Integer x)
	{
		System.out.println("Integer");
	}

	public void accept(Number x)
	{
		System.out.println("Number");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(null);

	}

}

```


> **Note :- Integer will be executed because Integer is the nearest type.**

```java
package com.ravi.overload_method;

class Test
{
	public void accept(Object x)
	{
		System.out.println("Object");
	}

	public void accept(String x)
	{
		System.out.println("String");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept("NIT");

	}

}
```

```java
package com.ravi.overload_method;

class Test
{
	public void accept(Object x)
	{
		System.out.println("Object");
	}

	public void accept(String x)
	{
		System.out.println("String");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(null);

	}

}
```

```java
package com.ravi.overload_method;

class Test
{
	public void accept(Integer x)
	{
		System.out.println("Integer");
	}

	public void accept(Double x)
	{
		System.out.println("Double");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(null);

	}

}

```


> **Note :- Compilation error because unable to find the nearest type.**

Integer and Double both the classes are sub class of Number
```java
package com.ravi.overload_method;

class Test
{
	public void accept(Integer x)
	{
		System.out.println("Autoboxing");
	}

	public void accept(long x)
	{
		System.out.println("Widening");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(9);

	}

}

```

Here Widening is having more priority then Autoboxing
```java
package com.ravi.overload_method;

class Test
{
	public void accept(Integer x)
	{
		System.out.println("Autoboxing");
	}

	public void accept(int ...x)
	{
		System.out.println("Var args");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(9);

	}

}

```

Here Autoboxing is having more priority then var-args
```java
package com.ravi.overload_method;

class Test
{
	public void accept(int x, long y)
	{
		System.out.println("int-long");
	}

	public void accept(long x, int y)
	{
		System.out.println("long-int");
	}
}


public class AmbiguityIssue {

	public static void main(String[] args)
	{
		Test t = new Test();
		t.accept(10, 20);


	}

}
```

Note : Compilation error



** Method Overriding :
Writing two or more methods in the super and sub class in such a way that method signature(method name along with method parameter) of both the methods must be same in the super and sub classes.

While working with method overriding generally we can't change the return type of the method but from JDK 1.5 onwards we can change the return type of the method in only one case that is known as Co-Variant.

Without inheritance method overriding is not possible that means if there is no inheritance there is no method overriding.

### What is the advantage of Method Overriding ?

The advantage of Method Overriding is, each class is specifying its own specific behavior.

### Upcasting and Downcasting


### Upcasting

It is possble to assign sub class object to super class reference variable using dynamic polymorphism. It is known as Upcasting.

Example:-    Animal a = new Lion();  //valid [upcasting]

Downcasting :
By default we can't assign super class object to sub class reference variable.

Lion l = new Animal();  //Invalid

Even if we type cast Animal to Lion type then compiler will allow but at runtime JVM will not convert Animal object (Generic type) into Lion object (Specific type) and it will throw an exception java.lang.ClassCastException

Lion l = (Lion) new Animal(); //At runtime we will get
ClassCastException

## 30-05-2024


### Program on Method Overriding

```java
package com.ravi.overriding;

class Animal
{
	public void roam()
	{
		System.out.println("Generic Animal is roaming");
	}
}

class Lion extends Animal
{
	public void roam()
	{
		System.out.println("Lion is roaming in forest");
	}
}
public class MethodOverridingDemo
{
	public static void main(String[] args)
	{
		Animal a = new Lion();
		a.roam();
	}

}
```


### @Override Annotation

In Java we have a concept called Annotation, introduced from JDK 1.5 onwards.It is metadata (data about data)

All the annotations must be start with @ symbol.

```java
@Override annotation is optional but it is always a good practice to write @Override annotation before the Overridden method so compiler as well as user will get the confirmation that the method is overridden method and it is available in the super class.

```

If we use @Override annotation before the name of the overridden method in the sub class and if the method is not available in the super class then it will generate a compilation error so it is different from comment because comment will not generate any kind of compilation error if method is not an overridden method, so this is how it is different from comment.
```java
package com.ravi.overriding;

class RBI
{
	public void loan()
	{
		System.out.println("Bank should provide loan");
	}
}

class ICICI extends RBI
{
	@Override
	public void loan()
	{
		System.out.println("ICICI bank loan ROI is 9.2%");
	}
}
class HDFC extends RBI
{
	@Override
	public void loan()
	{
		System.out.println("HDFC bank loan ROI is 10.2%");
	}
}

public class OverrideAnnotation
{
	public static void main(String[] args)
	{
        RBI r;

        r = new ICICI(); r.loan(); //Dynamic Method Dispatch
        r = new HDFC(); r.loan();  //Dynamic Method Dispatch
	}
}
```


### Program that describes we cannot override private method

```java
private methods are available within the same class only, it is not visible to the child class so we cannot override.

package com.ravi.overriding;

class Alpha
{
	private void m1()
	{
		System.out.println("Private method of Alpha class");
	}
}
class Beta extends Alpha
{
	@Override
	public void m1() //error
	{
		System.out.println("public method of Beta class");
	}
}

public class PrivateMethod {

	public static void main(String[] args)
	{
		new Beta().m1();
	}
}

```


> **Note :- private method of super class is not available or not inherited in the sub class so if the class declare the method with same signature then it is not overridden method, actually it is re-declared in the sub class.**


### Role of access modifier while overriding a method

While overriding the method from super class, the access modifier of sub class method must be greater or equal in comparison to access modifier of super class method otherwise we will get compilation error.

In terms of accessibility, public is greater than protected, protected is greater than default (public > protected > default)
[default < protected < public]

So the conclusion is we can't reduce the visibility of the method while overriding a method.


> **Note :- private method is not availble (visible) in sub class so it is not the part of method overriding.**

```java
package com.ravi.overriding;

class Shape
{
	public void draw()
	{
		System.out.println("Generic Drawing");
	}
}
class Square extends Shape
{
	@Override
	protected void draw() //error can't reduce the visibility
	{
		System.out.println("Drawing Square");
	}
}

public class AccessModifierOverriding
{
	public static void main(String[] args)
	{
		Shape s = new Square();
		s.draw();

	}

}
```


## Variable Shadow in Method Overriding

If super class variable name and sub class variable name both are same then it is called Variable Shadow.

In java variables are not overridden so, to get the output of the variable we depend upon the class reference variable.

```java
package com.ravi.overriding;

class Bird
{
	protected String name = "Generic Bird";

	public String fly()
	{
		return "Generic bird is flying";
	}
}

class Parrot extends Bird
{
	protected String name = "Parrot Bird"; //Variable Shadow

	@Override
	public String fly()
	{
		return "Parrot bird is flying";
	}
}

public class VariableShadow
{
	public static void main(String[] args)
	{
	   Bird b = new Parrot();
	   System.out.println(b.name+ " :  "+b.fly());

	}

}

```


> **Note :- variables are not overridden in java so variables are executed with current class reference, methods are executed depending upon object type.**


### Co-Variant in java

In general we cann't change the return type of method while overriding a method. if we try to change it will generate compilation error as shown in the program below.

```java
class Super
{
	public void show()
	{
		System.out.println("Show method of super class");
	}
}
class Sub extends Super
{
	@Override
	public int show()  //error
	{
		System.out.println("Show method of sub class");
		return 0;
	}
}

public class CoVariant
{
	public static void main(String[] args)
	{
		Super s = new Sub();
		s.show();
	}
}
```

The above code will not compile because return type int is not compatible with void.
But from JDK 1.5 onwards we can change the return type of the method in only one case that the return type of both the METHODS(SUPER AND SUB CLASS METHODS) MUST BE IN INHERITANCE RELATIONSHIP (IS-A relationship so it is compatible) called Co-Variant as shown in the program below.


> **Note :- Co-variant will not work with primitive data type, it will work only with classes**

```java
class Animal
{
}
class Rabbit extends Animal
{
}

class Super
{
	public Animal show()
	{
		System.out.println("Show method of super class");
		return new Rabbit();
	}
}
class Sub extends Super
{
	@Override
	public Rabbit show()
	{
		System.out.println("Show method of sub class");
		return null;
	}
}

public class CoVariant
{
	public static void main(String[] args)
	{
		Super s = new Sub();
		s.show();
	}
}
```


```java
class Super
{
	public Super show()
	{
		System.out.println("Show method of super class");
		return this;
	}
}
class Sub extends Super
{
	@Override
	public Sub show()
	{
		System.out.println("Show method of sub class");
		return this;
	}
}

public class CoVariant
{
	public static void main(String[] args)
	{
		Super s = new Sub();
		s.show();
	}
}
```


```java
class Super
{
	public Object show()
	{
		System.out.println("Show method of super class");
		return this;
	}
}
class Sub extends Super
{
	@Override
	public Integer show()
	{
		System.out.println("Show method of sub class");
		return null;
	}
}

public class CoVariant
{
	public static void main(String[] args)
	{
		Super s = new Sub();
		s.show();
	}
}
```


### Method Hiding in java

* Can we override static method ?
OR
* Can we override main method?
OR
* What is Method Hiding in java?

Case 1 :
Any public static method declared in the super class by default available to sub class so, from sub class we can call the static method of super class with the help of class name or object reference.

```java
package com.ravi.method_hiding;

class Super
{
	public static void show()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{


}

public class MethodHidingDemo1
{
	public static void main(String[] args)
	{
		Sub.show();

		Sub s = new Sub();  s.show();

	}

}
```


### Case 2

We can't overridde static method with non-static method because static method belongs to class and non-static belongs to object.
If we try to override then we will get an error Overridden method is static.

```java
class Super
{
	public static void show()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{
	public void show()
	{
		System.out.println("Non-static method of sub class");
	}
}
public class Test
{
	public static void main(String [] args)
	{
	}
}
```


### Case 3

We can't overridde non-static method with static method because static method belongs to class and non-static belongs to object.
If we try to override then we will get an error Overriding method is static.

```java
class Super
{
	public  void show()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{
	public static void show()
	{
		System.out.println("Non-static method of sub class");
	}
}
public class Test
{
	public static void main(String [] args)
	{
	}
}

```

So, the conclusion is we cannot overide static with non static method as well as non-static with static method because static method belongs to class and non-static method belongs to object.
program that says it is method hiding and sub class method can't hide super class method

```java
class Super
{
	public static void show()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{

	public static int show()
	{
		System.out.println("static method of sub class");
		return 0;
	}
}
public class Test
{
	public static void main(String [] args)
	{
		Super s = new Sub();
		s.show();
	}
}

```

Case 4 :
We can't override static method, If we write static method in the sub class with same signature and same return type then It is Method Hiding but not Method Overriding.


> **Note :- We can't apply @Override annotation on static methods.**

```java
class Super
{
	public static void show()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{
	public static void show()
	{
		System.out.println("static method of sub class");

	}
}
public class Test
{
	public static void main(String [] args)
	{
		Super s = new Sub();
		s.show();
	}
}

```

Note : static variable, instance variable and static method are not overridden so we will get super class output.

### Progrm that describes Polymorphic behaviour of sub classes

```java
package com.ravi.polymorphic;

class Animal
{
	public void roam()
	{
		System.out.println("Generic Animal is roaming");
	}
}
class Lion extends Animal
{
	@Override
	public void roam()
	{
		System.out.println("Lion is roaming");
	}
}
class Tiger extends Animal
{
	@Override
	public void roam()
	{
		System.out.println("Tiger is roaming");
	}
}
class Dog extends Animal
{
	@Override
	public void roam()
	{
		System.out.println("Dog is roaming");
	}
}


public class PolymorphicBehavior {

	public static void main(String[] args)
	{
		Lion l = new Lion();
		Tiger t = new Tiger();

		animalRoaming(l);
		animalRoaming(t);
		animalRoaming(new Dog());

	}

	public static void animalRoaming(Animal animal)
	{
		animal.roam();
	}

}
```


### instanceof Operator

It is a keyword as well as an operator.

It is used to verify whether a reference variable refers to a particular type of object or not?

It will return boolean value.

While working with instanceof operator there must be a IS-A
relationship between reference variable and the class/interface type otherwise we will get compilation error.

In order to avoid ClassCastException we use instanceof operator.
```java
public class Test
{
	public static void main(String [] args)
	{
		String s = "india";

		if(s instanceof String)
		{
			System.out.println("s is pointing to String Object");
		}

		Integer i = 45;

        if(i instanceof Number)
		{
			System.out.println("i is pointing to Number Object");
		}

		if(i instanceof Object)
		{
			System.out.println("i is pointing to Object");
		}

	}
}
```

```java
package com.ravi.polymorphic;

class Animal
{
	public void eat()
	{
		System.out.println("Generic Animal is eating");
	}
}
class Lion extends Animal
{
	@Override
	public void eat()
	{
		System.out.println("Lion is eating");
	}

	public void roar()
	{
		System.out.println("Lion is roaring");
	}
}

class Dog extends Animal
{
	@Override
	public void eat()
	{
		System.out.println("Dog is eating");
	}

	public void bark()
	{
		System.out.println("Dog is Barking");
	}
}


public class PolymorphicBehaviour
{
	public static void main(String[] args)
	{
		animalType(new Dog());

	}

	public static void animalType(Animal animal)
	{
		if(animal instanceof Dog)
		{
			Dog d1 = (Dog) animal;
			d1.eat();
			d1.bark();
		}
		else if(animal instanceof Lion)
		{
			Lion lion = (Lion) animal;
			lion.eat(); lion.roar();
		}

	}
}
```




### final keyword in java

It is used to provide some kind of restriction in our program.
We can use final keyword in ways 3 ways in java.

1) To declare a class as a final. (Inheritance is not possible)
2) To declare a method as a final (Overriding is not possible)
3) To declare a variable (Field) as a final (Re-assignment is not possible)


## 01-06-2024


### 1) To declare a class as a final

Whenever we declare a class as a final class then we cann't extend or inherit that class otherwise we will get a compilation error.

We should declare a class as a final if the composition of the class (logic of the class) is very important and we don't want to share the feature of the class to some other developer to modify the original behavior of the existing class, In that situation we should declare a class as a final.

Declaring a class as a final does not mean that the variables and methods declared inside the class will also become as a final, only the class behavior is final that means we can modify the variables value as well as we can create the object for the final classes.


> **Note :- In java String and All wrapper classes are declared as final class.**

```java
final class A
{
	private int x = 100;

	public void setData()
	{
		x = 120;
		System.out.println(x);
	}
}
class B extends A
{
}
public class FinalClassEx
{
	public static void main(String[] args)
	{
		B b1 = new B();
		b1.setData();
	}
}

```


> **Note :- we can't extend OR inherit final class.**

```java
final class Test
{
	private int data = 100;

	public void setData(int data)
	{
		this.data = data;
		System.out.println("Data value is :"+data);
	}
}
public class FinalClassEx1
{
	public static void main(String[] args)
	{
		Test t1 = new Test();
		t1.setData(200);
	}
}
```


## Sealed class in Java

It is a new feature introduced from java 15v (preview version) and become the integral part of java from 17v.

It is an improvement over final keyword.

By using sealed keyword we can declare classes and interfaces as sealed.

It is one kind of restriction that describes which classes and interfaces can extends or implement from Sealed class Or interface

It is similar to final keyword with less restriction because here we can permit the classes to extend from the original Sealed class.

The class which is inheriting from the sealed class must be final, sealed or non-sealed.

The sealed class must have atleast one sub class.

We can also create object for Sealed class.

It provides the following modifier :

1) sealed : Can be extended only through permitted class.

2) non-sealed : Can be extended by any sub class, if a user wants to give permission to its sub classes

3) permits : We can provide permission to the sub classes, which are inheriting through Sealed class.

4) final : we can declare permitted sub class as final so, it cannot be extended further.
SealedDemo1.java
```java
package com.ravi.sealed_demo;

```


## sealed class Bird permits Parrot, Sparrow

```java
{
	public void fly()
	{
		System.out.println("Genric bird is flying");
	}
}

```

non-sealed class Parrot extends Bird
```java
{
	@Override
	public void fly()
	{
		System.out.println("Parrot bird is flying");
	}
}

final class Sparrow extends Bird
{
	@Override
	public void fly()
	{
		System.out.println("Sparrow bird is flying");
	}
}

public class SealedDemo1
{
	public static void main(String[] args)
	{
		Bird b = null;
		b = new Parrot(); b.fly();
		b = new Sparrow(); b.fly();
	}

}
```

```java
package com.ravi.sealed_demo;

```


## sealed class OnlineClass permits Mobile, Laptop

```java
{
	public void attendOnlineClass()
	{
		System.out.println("Attanding online class");
	}
}

```

non-sealed class Mobile extends OnlineClass
```java
{
	@Override
	public void attendOnlineClass()
	{
		System.out.println("Attanding online class through Mobile");
	}
}

final class Laptop extends OnlineClass
{
	@Override
	public void attendOnlineClass()
	{
		System.out.println("Attanding online class through Laptop");
	}
}
public class SealedDemo2
{
	public static void main(String[] args)
	{
		OnlineClass cls = null;

		cls = new Mobile(); cls.attendOnlineClass();
		cls = new Laptop(); cls.attendOnlineClass();


	}

}
```

2) To declare a method as a final (Overriding is not possible)
Whenever we declare a method as a final then we can't override that method in the sub class otherwise there will be a compilation error.

We should declare a method as a final if the body of the method i.e the implementation of the method is very important and we don't want to override or change the super class method body by sub class method body then we should declare the super class method as final method.

```java
class A
{
	protected int a = 10;
	protected int b = 20;

     public final void calculate()
	  {
		int sum = a+b;
		System.out.println("Sum is :"+sum);
	  }
}
class B extends A
{
	@Override
	public void calculate() //error
	{
		int mul = a*b;
		System.out.println("Mul is :"+mul);
	}
}
public class FinalMethodEx
{
	public static void main(String [] args)
	{
		 A a1 = new B();
		 a1.calculate();
	}
}
```

```java
class Alpha
{
	private final void accept()
	{
		System.out.println("Alpha class accept method");
	}
}
class Beta extends Alpha
{

	protected void accept()
	{
		System.out.println("Beta class accept method");
	}
}
public class FinalMethodEx1
{
	public static void main(String [] args)
	{
		new Beta().accept();
	}
}

```

Above program will compile and execute.

Here Private method of super class is not visible to sub class so sub class can define its own method.
3) To declare a variable(field) as a final :(Re-assignment is not possible)
In older langugaes like C and C++ we use "const" keyword to declare a constant variable but in java, const is a reserved word for future use so instead of const we should use "final" keyword.

If we declare a variable as a final then we can't perform re-assignment (i.e nothing but re-initialization) of that variable.

In java It is always a better practise to declare a final variable by uppercase letter according to the naming convention.

Some example of predefined final variables

Byte.MIN_VALUE   -> MIN_VALUE is a static and final variable

Byte.MAX_VALUE  -> MAX_VALUE is a static and final variable

Example:- final int DATA = 10; (Now we can not perform re-assignment )

FinalVar.java
```java
class Demo
{
	final int A = 10;

	public void setData()
	{
		A = 10;  //error
	}
}
public class FinalVar
{

	public static void main(String[] args)
	{
       new Demo().setData();
	}
}
```




### What is Method Chaining in java ?

It is a technique through which we can call various methods in a single statement.

In order to call next method we depend upon current method return type.

It is basically used to write concise coding.

The final return type of the method is based on last method call.


```java
package com.ravi.method_chaining;

public class MethodChainingDemo {

	public static void main(String[] args)
	{

		String str = "india";
		char ch = str.concat(" is great").toUpperCase().charAt(0);
		System.out.println(ch);

		str = "Hyderabad";
		int len = str.concat(" is an IT city").toUpperCase().length();
		System.out.println(len);
	}

}
```




## 03-06-2024


## Object class in java


### Working with Object class and its methods

There is a predefined class called Object available in java.lang package, this Object class is by default the super class of all the classes we have in java.

```java
class Test
{

}

```


> **Note :- Object is the super class for this Test class. by default this Object class is super class so explicitly we need not to mention.**


Since, Object is the super class of all the classes in java that means we can override the method of Object class (Except final methods) as well as we can use the methods of Object class anywhere in java because every class is sub class of Object class.

The Object class provides some common behavior to each sub class Object like we can compare two objects , we can create clone (duplicate) objects, we can print object properties(instance variable), providing a unique number to each and every object(hashCode()) and so on.


### 1) public native final java.lang.Class getClass()

It is a predefined method of Object class.

This method returns the runtime class of the object, the return type of this method is java.lang.Class.

This method will provide class keyword + Fully Qualified Name (package name + class name)

This getClass() method return type is java.lang.Class so further we can apply any other method of java.lang.Class class method.

We can't override this method because it is a final method.

2 files : (Both files are in 2 different packages)
Test.java(C)
```java
package com.nit.testing;

public class Test


```

Main.java(C)
```java
package com.ravi.object_class;

import com.nit.testing.Test;

public class Main
{
	public static void main(String[] args)
	{
		Test t1 = new Test();
		System.out.println(t1.getClass()); //class + FQN
		System.out.println(t1.getClass().getName()); //FQN
	}

}

```


> **Note :- java.lang.Class class has provided a predefined method**

```java
         getName() through which we can get the Fully Qualified name
```

of the class.

```java
	 public String getName();


          getClass().getName(); //Method Chaining
```


### 2) public native int hashCode()


It is a predefined method of Object class.

It returns the hashCode of the object.

If two objects are same based on the equals(Object object) method comparison then the hashCode of both the object must be same.

hashCode is not meant for object comparison.
```java
class Demo
{

}

public class HashCodeDemo {

	public static void main(String[] args)
	{
		Demo d1 = new Demo();
		System.out.println(d1.hashCode());

		Demo d2 = new Demo();
		System.out.println(d2.hashCode());

		Demo d3 = d2;
		System.out.println(d3.hashCode());


	}

}

```

```java
//hashcode is not meant for object comparison

public class HashCodeDemo
{
	public static void main(String[] args)
	{
		String str = "A";
		Integer i = 65;

		System.out.println(str.hashCode()+" : "+i.hashCode());
	}

}
```


```java
public class HashCodeDemo
{
	public static void main(String[] args)
	{
	   String str1 = new String("india");
	   String str2 = new String("india");

	   System.out.println(str1.equals(str2));
	   System.out.println(str1.hashCode());
	   System.out.println(str2.hashCode());
	}

}
```


### 3) public String toString()

It is a predefined method of Object class.

it returns a string representation of the object. In general, the toString method returns a string that "textually represents" this object. The result should be a concise but informative representation that is easy for a person to read

```java
toString() method of Object class conatins following logic.

public String toString()
{
	return getClass().getName()+" @ "+Integer.toHexString(hashCode());
}

```

Please note internally the toString() method is calling the hashCode() and getClass() method of Object class.

In java whenever we print any Object reference by using System.out.println() then internally it will invoke the toString() method of Object class as shown in the following program.

```java
package com.ravi.tostring_demo;

class Demo
{

}

public class ToStringDemo1 {

	public static void main(String[] args)
	{
		Demo d1 = new Demo();
		Demo d2 = new Demo();
		Demo d3 = new Demo();

		System.out.println(d1.toString());
		System.out.println(d2);
		System.out.println(d3);
	}

}


```


> **Note :- We can override this toString method to represent our Object properties in textual String format.**


```java
package com.ravi.tostring_demo;

class Test
{
	@Override
	public String toString()
	{
		return "NIT";
	}
}

public class ToStringDemo1
{

	public static void main(String[] args)
	{
		Test t1 = new Test();
		System.out.println(t1);

	}

}
```


## 04-06-2024

```java
public boolean equals(Object obj) :
```

It is predefined method of Object class.

It is mainly used to compare two objects besed on the memory address just like == opeartor because internally, It uses == opeartor only.

The following program explains how to use equals(Object obj) method of Object class for Employee comparison.

```java
package com.ravi.equals_demo;

class Employee
{
	private int employeeId;
	private String employeeName;

	public Employee(int employeeId, String employeeName)
	{
		super();
		this.employeeId = employeeId;
		this.employeeName = employeeName;
	}
}

public class EqualsComparison1
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(111, "Scott");
		Employee e2 = new Employee(111, "Scott");

		System.out.println(e1==e2); //false
		System.out.println(e1.equals(e2)); //false

	}

}

```

Here we are getting the output as a false because internally equals(Object obj) method of Object class uses == operator only, which is memory address comparison.

If we want to compare two objects based on the content but not address then we should override equals(Object obj) method for contant comparison as shown in the program.

```java
package com.ravi.equals_demo;

class Employee
{
	private int employeeId;
	private String employeeName;

	public Employee(int employeeId, String employeeName)
	{
		super();
		this.employeeId = employeeId;
		this.employeeName = employeeName;
	}

	@Override
	public boolean equals(Object obj) //obj -> e2  [222, smith]
	{
		//Retrieving 1st object data
		int id1 = this.employeeId;
		String name1 = this.employeeName;

		//Retrieving 2nd object data

		Employee e2 = (Employee) obj;
		int id2 = e2.employeeId;
		String name2 = e2.employeeName;

		if(id1==id2 && name1.equals(name2))
		{
			return true;
		}
		else
		{
			return false;
		}
	}




}

public class EqualsComparison1
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(111, "Scott");
		Employee e2 = new Employee(111, "Scott");

		System.out.println(e1==e2); //false

		System.out.println(e1.equals(e2)); //true

	}

}

```

In the above program we have overridden equals(Object obj) method from Object class so here we are comparing two objects beased on content.
```java
package com.ravi.object_class;

public class StringDemo {

	public static void main(String[] args)
	{
		String st1 = new String("india");
		String st2 = new String("india");
		System.out.println(st1.equals(st2)); //true

	}

}

String class has also overridden equals(Object obj) method from Object class so it is returning true.
```

```java
package com.ravi.object_class;

class Product
{
	private int productId;
	private String productName;

	public Product(int productId, String productName)
	{
		super();
		this.productId = productId;
		this.productName = productName;
	}

	@Override
	public boolean equals(Object obj)
	{
		Product p2 = (Product) obj;

		if(this.productId == p2.productId && this.productName.equals(p2.productName))
		{
			return true;
		}
		else
		{
			return false;
		}
	}
}

public class EqualsComparison1 {

	public static void main(String[] args)
	{
		Product p1 = new Product(111, "Camera");
		Product p2 = new Product(111, "Camera");

		System.out.println(p1.equals(p2));

	}

}
```

```java
package com.ravi.object_class;

class Student
{
	private int studentId;
	private String studentName;

	public Student(int studentId, String studentName)
	{
		super();
		this.studentId = studentId;
		this.studentName = studentName;
	}

	@Override
	public boolean equals(Object obj)
	{
	   if(obj instanceof Student)
	   {
		   Student s2 = (Student) obj;

		   if(this.studentId == s2.studentId && this.studentName.equals(s2.studentName))
		   {
			   return true;
		   }
		   else
		   {
			   return false;
		   }


	   }
	   else
	   {
		   System.err.println("Comparison is not possible");
		   return false;
	   }
	}
}

public class EqualsComparison2
{
	public static void main(String[] args)
	{
		Student s1 = new Student(222, "Scott");
		Student s2 = new Student(333, "Scott");
		Manager m1 = new Manager(222, "Scott");
		System.out.println(s1.equals(m1)); //CNP false
		System.out.println(s1.equals(null)); //CNP false

	}

}

class Manager
{
	private int managerId;
	private String managerName;

	public Manager(int managerId, String managerName)
	{
		super();
		this.managerId = managerId;
		this.managerName = managerName;
	}


}

```

Note : 1) null with instanceof opertor will always return false.
2) instanceof opertor will avoid ClassCastException and It
will restrict us to compare two different type of object or
even from null comparison.



***IMP****

## 05-06-2024


## JVM Architecture with class loader sub system

The entire JVM Architecture is divided into 3 sections

1) Class loader sub system
2) Runtime Data Areas (Memory Areas)
3) Execution Engine.


## Class Loader sub System

The Class loader sub system is responsible to load the .class file into JVM Memory.

In order to load the .class file into JVM memory class loader
sub system follows Delegation Hierarchy Algorithm.


## Class loader sub system internally performs 3 tasks


a) LOADING
b) LINKING
c) INITIALIZATION

LOADING :
In order to load the required .class file, JVM makes a request to class loader sub system. The class loader sub system follows delegation hierarchy algorithm to load the required .class files from different areas.

To load the required .class file we have 3 different kinds of class loaders.

1) Bootstrap/Primordial class loader

2) Extension/Platform class loader

3) Application/System class loader

Bootstrap/Primordial class Loader :-
It is responsible for loading all the predefined .class files that means all API level predefined classes are loaded by Bootstrap class loader.

It has the highest priority becuase Bootstrap class loader is the
super class for Platform class loader.

It loads the classes from the following path
C -> Program files -> Java -> JDK -> lib -> jrt-fs.jar

Platform/Extension class loader :
It is responsible to load the required .class file which is given by some 3rd party in the form of jar file.

It is the sub class of Bootstrap class loader and super class of Application class loader so it has more priority than Application class loader.

It loads the required .class file from the following path.
C -> Program files -> Java -> JDK -> lib -> ext -> ThirdParty.jar

command to create the jar file :
jar cf FileName.jar FileName.class

[If we want to compile more than one java file at a time then the command is :  javac *.java]

Application/System class loader :
It is responsible to load all userdefined .class file into JVM memory.

It has the lowest priority because it is the sub class Platform class loader.

It loads the .class file from class path level or environment
variable.

### How Delegation Hierarchy algorithm works

Whenever JVM makes a request to class loader sub system to load the required .class file into JVM memory, first of all, class loader sub system makes a request to Application class loader, Application class loader will delegate(by pass) the request to the Extension class loader, Extension class loader will also delegate the request to Bootstrap class loader.

Bootstrap class loader will load the .class file from lib folder(jrt.jar) and then by pass the request to extension class loader, Extension class loader will load the .class file from ext folder(*.jar) and by pass the request to Application class loader, It will load the .class file from environment variable into JVM memory.


> **Note :-**

If all the class loaders are failed to load the .class file into JVM memory then we will get a Runtime exception i.e java.lang.ClassNotFoundException.

## 06-06-2024

The following program explains that java.lang.Class can hold any .class file.

Example :   java.lang.Class cls = AnyClass.class


Any loaded class return type is java.lang.Class so further we can call any Method of java.lang.Class (Method Chaining)
WAP that describes Application class loader is responsible to load the
user-defined classes.

```java
package com.ravi.method_area;

class Test
{
}

public class ClassLoader {

	public static void main(String[] args)
	{
		System.out.println("Test.class file will be loaded by :"+Test.class.getClassLoader());

	}

}

getClassLoader() is a predefined method of java.lang.Class and return type of this method is ClassLoader class

    public ClassLoader getClassLoader();
```

WAP to display platform class loader is the super class for Application class loader.
```java
package com.ravi.method_area;

class Demo
{

}

public class PlatformClassLoaderDemo {

	public static void main(String[] args)
	{
		ClassLoader loader = Demo.class.getClassLoader();
		System.out.println("Super class of Application class loader :"+loader.getParent());
	}

}

getParent() is a predefined method of ClassLoader class and return type of this method is ClassLoader class.
```


```java
package com.ravi.method_area;

class Demo
{

}

public class PlatformClassLoaderDemo {

	public static void main(String[] args)
	{
		ClassLoader loader = Demo.class.getClassLoader();
		System.out.println("Super class of Application class loader :"+loader.getParent().getParent()); //null
	}

}

```


> **Note :- Here we will get the output the as null because it is predefined class loader for JVM used to load all predefined .class file so implementation is not provided by java software people.**


### Linking

verify :-
It ensures the correctness of the .class files, If any suspicious activity is there in the .class file then It will stop the execution immediately by throwing a runtime error i.e java.lang.VerifyError.

There is something called ByteCodeVerifier(Component of JVM), responsible to verify the loaded .class file i.e byte code. Due to this verify module JAVA is highly secure language.

java.lang.VerifyError is the sub class of java.lang.linkageError
prepare: (static variable memory allocation + Initialization )
```java
It will allocate the memory for all the static data members, here all the static data member will get the default values so if we have static int x = 100;

```

then for variable x  memory will be allocated and now it will initialize with default value i.e 0, even the variable is final.

### Resolve

All the symbolic references will be converted into direct references Or actual reference.
javap -verbose  FileName.class


> **Note :- By using above command we can read the internal details of .class file.**


### Initialization

Here class initialization will take place. All the static data member will get their actual value and we can also use static block for static data member initialization.

Here, In this class initialization phase static variable and static block is having same priority so it will executed according to the order.(Top to bottom)

## 10-06-2024


## Static block

It is a special block in java which is automatically executed at the time of loading the .class file into JVM memory.

static
```java
{
System.out.println("Static Block");
}

```


## Static blocks are executed only once because in java we can load the .class files only once.


If we have more than one static block in a class then it will be
executed according to the order [Top to bottom]


The main purpose of static block to initialize the static data member
of the class so, it is also known as static initializer.

If we have static blank final field then it must be initialized inside static block only.

```java
static final int A;   //static blank final field

```

static
```java
{
   A = 100;
}

```


## static blocks are executed before main method.


All static variables are initialized with default value even they are declared as final.

In java, a class is not loaded automatically, it is loaded based on the
user request so static block will not be executed everytime, It depends upon whether class is loaded or not.


If we don't declare static variable before static block execution then we can perform write operation(Initialization is possible) but read operation is not possible directly otherwise we will get an error Illegal forward reference, It is possible with class name bacuse now compiler knows that it is coming from class area OR Method area.

Our initializer (static + instance) must be completed normally so, we can't write any kind of return statement or any statement which transfer the control from the initializer.
```java
//static block
class Foo
{
	Foo()
	{
		System.out.println("No Argument constructor..");
	}

	{
		System.out.println("Instance block..");
	}

```

static
```java
	{
		System.out.println("Static block...");
	}

}
public class StaticBlockDemo
{
	public static void main(String [] args)
	{
		System.out.println("Main Method Executed ");
	}
}

```

Note : here static block will not be executed bacause Foo.class file is
not loaded into JVM memory.

```java
class Test
{
	static int x;

```

static
```java
	{
		x = 100;
		System.out.println("x value is :"+x);
	}

```

static
```java
	{
		x = 200;
		System.out.println("x value is :"+x);
	}

```

static
```java
	{
		x = 300;
		System.out.println("x value is :"+x);
	}


}
public class StaticBlockDemo1
{
	public static void main(String[] args)
	{
		System.out.println("Main Method");
		System.out.println(Test.x);
	}
}


```

Note : static blocks are executed according to the order.
```java
class Foo
{
	static int x;

```

static
```java
	{
		System.out.println("x value is :"+x);
	}
}

public class StaticBlockDemo2
{
	public static void main(String[] args)
	{
		 new Foo();
	}
}

```

Note : static variables are also initialized with default value at prepare phase of class loading.
```java
class Demo
{

	final static int a ;	//Blank static final variable

```

static
```java
	{
		a = 100; //Initailization is compulsory here
		System.out.println(a);
	}
}
public class  StaticBlockDemo3
{
	public static void main(String[] args)
		{
	         System.out.println("a value is :"+Demo.a);
	    }
}
```

```java
package com.ravi.oop;

class Foo
{
	static final int A; //static blank final field

```

static
```java
	{
		display();
		A = 100;
	}

	public static void display()
	{
		System.out.println(A);
	}
}



public class StaticBlankFinalField {

	public static void main(String[] args)
	{
		System.out.println(Foo.A);
	}

}

```

Note : static blank final field also have default value.
```java
class  A         //AD  BC  EF
{
```

static
```java
	{
		System.out.println("A");
	}


	{
		System.out.println("B");
	}

	A()
	{
		System.out.println("C");
	}
}
class B extends A
{
```

static
```java
	{
		System.out.println("D");
	}


	{
		System.out.println("E");
	}

	B()
	{
		System.out.println("F");
	}

}
public class StaticBlockDemo4
{
	public static void main(String[] args)
	{
		new B();
	}
}

```


## static blocks are executed only once.

```java
//illegal forward reference

class Demo
{
```

static
```java
	{
		i = 100;

	}

    static int i;
}

public class StaticBlockDemo5
{

    public static void main(String[] args)
	{
        System.out.println(Demo.i);
	}
}

```

Without declaration of static variable, we can initialize inside static block because in the prepare phase memory is already allocated for static variable.
```java
class Demo
{
```

static
```java
	{
		i = 100; //Initialization is possible
		System.out.println(i); //Invalid Illegal Forward Reference
		System.out.println(Demo.i); //valid
        }

    static int i;
}

public class StaticBlockDemo6
{

    public static void main(String[] args)
	{
		System.out.println(Demo.i);
	}
}

```

without declaration static variable, in static block we can initialize but we can't perform direct read opeartion, for this class name is required so compiler will get the idea to search the variable in a particular location i.e class area.
```java
class StaticBlockDemo7
{
```

static
```java
	{
      System.out.println("Static Block");
	  return;
	}

	public static void main(String[] args)
	{
		System.out.println("Main Method");
	}
}


```


> **Note :- we can't write return keyword inside static or non static block**


### How many ways we can load the .class file into JVM memory

There are so many ways to load the .class file into JVM memory but the following are the common examples

1) By using java command

```java
   public class Test
   {
   }

   javac Test.java
   java Test

```

Here we are making a request to class loader sub system to load
Test.class file into JVM memory


2) By using Constructor (new keyword at the time of creating object).

3) By accessing static data member of the class.

4) By using inheritance

5) By using Reflection API
```java
//Program that describes we can load a .class file by using new keyword (Object creation) OR by accessing static data member of the class.

class Demo
{
	static int x = 10;
```

static
```java
	{
		System.out.println("Static Block of Demo class Executed!!! :"+x);
	}
}
public class ClassLoading
{
	public static void main(String[] args)
	{
		System.out.println("Main Method");
		//new Demo();
	    System.out.println(Demo.x);
	}
}
```

```java
//Program that describes whenever we try to load sub class, first of all super class will be loaded. [before parent child can't exist]

class Alpha
{
```

static
```java
	{
		System.out.println("Static Block of super class Alpha!!");
	}
}
class Beta extends Alpha
{
```

static
```java
	{
		System.out.println("Static Block of Sub class Beta!!");
	}
}
class InheritanceLoading
{
	public static void main(String[] args)
	{
		 new Beta();
	}
}
```


### Variable Memory Allocation and Initialization


### 1) static field OR Class variable

Memory allocation done at prepare phase of class loading and initialized with default value even variable is final.

It will initialized with Original value (If provided by user at the time of declaration) at class initialization phase.

When JVM will shutdown then during the shutdown phase class will be un-loaded so static data members are destroyed. They have long life.

2) Non static field OR Instance variable
Memory allocation done at the time of object creation using new keyword (Instantiation) and initialized as a part of Constructor with default values even the variable is final. [Object class-> at the time of declaration -> instance block -> constructor]

When object is eligible for GC then object is destroyed and all the non static data memebers are also destroyed with corresponding object. It has lower life in comparison to static data members becuase they belongs to object.

3) Local Variable
Memory allocation done at stack area (Stack Frame) and developer is responsible to initialize the variable before use. Once metod execution is over, It will be deleted from stack Frame henec it has shortest life.

4) Parameter variable
Memory allocation done at stack area (Stack Frame)  and end user is responsible to pass the value at runtime. Once metod execution is over, It will be deleted from stack Frame henec it has shortest
life.

## 11-06-2024


### Can we write a program without main method ?

Before JDK 1.7 we can write a java program without main method by declaring static block but from Java 1.7v main method is compulsory because at the time of loading the .class file, first of all class loader will verify the presence of main method.

Example :
```java
class WithoutMain
{
```

static
```java
	{
	System.out.println("Hello world");
	System.exit(0);
	}
}
```

The above program was possible to execute upto JDK 1.6.

### Loading the .class file by using Reflection API

java.lang.Class class has provided a predefined static method called
forName(String className), by using this forName(String className) we can load the .class file into JVM memory dynamically.

This forName(String className) method return type is java.lang.Class

Class cls = Class.forName(String className);  //factory Method

It throws a checked Exception ClassNotFoundException.

2 files :
Test.java
```java
package com.ravi.dynamic_loading;

public class Test
{
```

static
```java
   {
	   System.out.println("static block of Test class");
   }
}

```

DynamicLoading.java
```java
package com.ravi.dynamic_loading;

public class DynamicLoading
{
	public static void main(String[] args) throws Exception
	{
		//Dynamically load a class
		Class.forName("com.ravi.dynamic_loading.Test");

	}

}

```





## What is factory Method in java ?

The method which returns the class name itself by creating the object for that particular class is called Factory Method.

```java
Class cls = Class.forName("com.ravi.Test");

```

Here Test.class will be loaded into JVM memory and it will return Class class object so further we can call any method of
java.lang.Class class.


```java
package com.ravi.dynamic_loading;

public class FactoryMethod {

	public static void main(String[] args) throws ClassNotFoundException
	{
		Class cls = Class.forName("com.ravi.dynamic_loading.Test");
		System.out.println(cls.getName());

	}

}
```




*What is the limitation of 'new' keyword ?
OR
What is the difference between new keyword and newInstance() method?
OR
How to create the Object for the classes which are coming dynamically from the database or from some file.

The limitation with new keyword is, It demands the class name at the begning or at the time of compilation so new keyword is not suitable to create the object for the classes which are coming from database or files at runtime dynamically.

In order to create the object for the classes which are coming at runtime from database or files, we should use newInstance() method available in java.lang.Class class.
```java
class Employee{}

class Person
{
}

class Manager
{
}

class Sample
{
}

public class DynamicObjectCreation
{
	public static void main(String[] args) throws Exception
	{
	  Object obj = Class.forName(args[0]).newInstance();
	  System.out.println("Object created for :"+obj.getClass().getName());
	}
}
```

```java
class Manager
{
	public void greet()
	{
		System.out.println("Greeting from manager");
	}
}

class Employee
{
	public void greet()
	{
		System.out.println("Greeting from employee");
	}
}

public class DynamicObjectCreation1
{
	public static void main(String[] args) throws Exception
	{
		Object obj = Class.forName(args[0]).newInstance();

        if(obj instanceof Employee)
		{
			Employee e1 = (Employee) obj;
			e1.greet();
		}

        else if(obj instanceof Manager)
		{
			Manager m1 = (Manager) obj;
			m1.greet();
		}

	}
}
```

** What is the difference between java.lang.ClassNotFoundException and java.lang.NoClassDefFoundError

java.lang.ClassNotFoundException :-
It occurs when we try to load the required .class file at runtime by using Class.forName(String className) statement or loadClass() static of ClassLoader class and if the required .class file is not available at runtime then we will get an exception i.e java.lang.ClassNotFoundException


> **Note :- It does not have any concern at compilation time, at run time, JVM will simply check whether the required .class file is available or not.**


```java
class Foo
{
```

static
```java
	{
		System.out.println("Foo class static block");
	}
}

public class ClassNotFoundDemo
{
	public static void main(String[] args) throws Exception
	{
		Class.forName("Ravi");
	}
}

```

here Ravi.class file is not available so class loader is unable to load the .class file hence we will get java.lang.ClassNotFoundException.

java.lang.NoClassDefFoundError :
It occurs when the class was present at the time of COMPILATION but at runtime the required .class file is not available(manualy deleted by user ) Or it is not available in the current directory (Misplaced) then we will get an exception i.e java.lang.NoClassDefFoundError.

```java
class Hello
{
	public void greet()
	{
		System.out.println("Greetings");
	}
}
public class NoClassDefFoundErrorDemo
{
	public static void main(String[] args)
	{
		Hello h = new Hello();
		h.greet();
	}
}

```

After compilation, remove Hello.class or place it into another folder then we will get java.lang.NoClassDefFoundError

## 12-06-2024


### Runtime Data Areas

It is also known as Memory Area.

Once a class is loaded then based on variable type method type it is divided into different memory areas which are as follows :

1) Method Area
2) HEAP Area
3) Stack Area
4) PC Register
5) Native Method Stack

Actually the .class file is dumped inside method area and returns java.lang.Class class object.

Method Area :
Whenever a class is loaded then the class is dumpped inside method area and returns java.lang.Class class.

It provides all the information regarding the class like name of the class, name of the package, static and non static fields available in the class, methods available in the class and so on.

We have only one method area per JVM that means for a single JVM we have only one Method area.

This Method Area OR Class Area is sharable by all the objects.
Program to Show From Method Area we can get complete information of the class. (Reflection API)

2 files :
Foo.java
```java
package com.ravi.class_description;

public class Foo
{
  int a = 100;
  static int b = 200;
  Foo c = new Foo();
  int d = 90;

  public void input() {}
  public static void show() {}
  public void accept() {}

}

```

ClassDescriptionDemo.java
```java
package com.ravi.class_description;

import java.lang.reflect.Field;
import java.lang.reflect.Method;

public class ClassDescriptionDemo {

	public static void main(String[] args) throws Exception
	{
		Class cls = Class.forName(args[0]);

		System.out.println("Class name is :"+cls.getName());
		System.out.println("Package Name is :"+cls.getPackageName());

		System.out.println("Fields Name :");

		Field[] fields = cls.getDeclaredFields();
		int count = 0;

		for(Field field : fields)
		{
			count++;
			System.out.println(field.getName());
		}
		System.out.println("Total number of Fields are :"+count);

		System.out.println("Methods Name :");
		Method [] methods = cls.getDeclaredMethods();
		count = 0;
		for(Method method : methods)
		{
			count++;
			System.out.println(method.getName());
		}
		System.out.println("Total number of methods are :"+count);
	}

}

```


> **Note :- getDeclaredMethods() is a predefined non static method available in java.lang.Class class , the return type of this method is Method array where Method is a predefined class available in java.lang.reflect sub package.**


getDeclaredFields() is a predefined non static method available in java.lang.Class class , the return type of this method is Field array where Field is a predefined class available in java.lang.reflect sub package.

Field and Method both the classes are providing getName() method to get the name of the field and Method.

### HEAP Area

It is a special area where we can store the objects as well as all properties.

We have only one HEAP AREA per JVM.

This HEAP area is sharable by Method Area. From java9 version onwrads now we have PermGen memory so this heap area can be dynamically growable so now Method area is also the part of HEAP area in a class_data section.

STACK Area :
All the methods are executed as a part of Stack Area.

Whenever we call a method in java then internally one stack Frame will be created to hold method related information.

Every Stack frame contains 3 parts
1) Local Variable
2) Frame Data
3) Operand Stack.

We have multiple stack area for a single JVM.

JVM creates a separate thread for every runtime Stack.
HEAP and STACK Diagram for Employee.java
```java
public class Employee
{
	int id = 100;

	public static void main(String[] args)
	{
		int val = 200;

		Employee e1 = new Employee();

		e1.id = val;

		update(e1);

		System.out.println(e1.id);

        Employee e2 = new Employee();

		e2.id = 900;

		switchEmployees(e2,e1); //3000x and 1000x

		  //GC []

			System.out.println(e1.id);
		    System.out.println(e2.id);
	    }

	 public static void update(Employee e)
	 {
        e.id = 500;
		e = new Employee();
		e.id = 400;
		System.out.println(e.id);
	 }

	 public static void switchEmployees(Employee e1, Employee e2)
	  {
		 int temp = e1.id;
```

e1.id = e2.id; //500
```java
		 e2 = new Employee();
		 e2.id = temp;
	  }
   }
```

HEAP and STACK Diagram for Beta.java
```java
class Alpha
{
	int val;
	static int sval = 200;
	static Beta b = new Beta();

	public Alpha(int val)
	{
      this.val = val;
	}
}

public class Beta
{
	public static void main(String[] args)
	{
		Alpha am1 = new Alpha(9);
		Alpha am2 = new Alpha(2);

		Alpha []ar = fill(am1, am2);

		ar[0] = am1;
        System.out.println(ar[0].val);
        System.out.println(ar[1].val);
	}

	public static Alpha[] fill(Alpha a1, Alpha a2)
	{
		a1.val = 15;

        Alpha fa[] = new Alpha[]{a2, a1};

		return fa;
	}
}
```


## 13-06-2024


### PC Register

It stands for Program counter Register.

In order to hold the current executing instruction of running thread we have separate PC register for each and every thread.

### Native Method Stack

Native method means, the java methods which are written by using native languages like C and C++. In order to write native method we need native method library support.

Native method stack will hold the native method information in a separate stack.

### Execution Engine

Interpreter
In java, JVM is an interpreter which executes the program line by line. JVM (Interpreter) is slow in nature because at the time of execution if we make a mistake at line number 9 then it will throw the execption at line number 9 and after solving the execption again it will start the execution from line number 1 so it is slow in execution that is the reason to boost up the execution java software people has provided JIT compiler.

JIT Compiler :
It stands for just in time compiler. The main purpose of JIT compiler to boost up the execution so the execution of the program will be completed as soon as possible.

JIT compiler holds the repeated instruction like method signature, variables, native method code and make it available to JVM at the time of execution so the overall execution becomes very fast.

## Abstraction


### As we know we can achieve abstraction by using 2 ways


1) Abstract class and abstract method (Partial abstraction 0 to 100%)
2) interface (100% abstraction)


## Abstract class and abstract methods

A class that does not provide complete implementation (partial implementation) is defined as an abstract class.

An abstract method is a common method which is used to provide easiness to the programmer because the programmer faces complexcity to remember the method name.

An abstract method observation is very simple because every abstract method contains abstract keyword, abstract method does not contain any method body and at the end there must be a terminator i.e ; (semicolon)

In java whenever action is common but implementations are different then we should use abstract method, Generally we declare abstract method in the super class and its implementation must be provided in the sub classes.

```java
if a class contains at least one method as an abstract method then we should compulsory declare that class as an abstract class.

```

Once a class is declared as an abstract class we can't create an object for that class.

*All the abstract methods declared in the super class must be overridden in the sub classes otherwise the sub class will become as an abstract class hence object can't be created for the sub class as well.

In an abstract class we can write all abstract method or all concrete method or combination of both the method.

It is used to acheive partial abstraction that means by using abstract classes we can acheive partial abstraction(0-100%).

*An abstract class may or may not have abstract method but an abstract method must have abstract class.


> **Note :- We can't declare an abstract method as final, private and static (illegal combination of modifiers)**


We can't declare an abstract class as a final.
```java
package com.ravi.abstract_demo;

```


## abstract class Shape

```java
{
	public abstract void draw();
}

class Square extends Shape
{
	@Override

	public void draw()
	{
		System.out.println("Drawing Square");
	}
}

class Rectangle extends Shape
{
	@Override
	public void draw()
	{
		System.out.println("Drawing Rectangle");
	}
}
public class AbstractDemo1
{
	public static void main(String[] args)
	{
		Shape s ;
		s = new Square(); s.draw();
        s = new Rectangle(); s.draw();
	}

}
```

```java
package com.ravi.abstract_demo;

```


## abstract class Car

```java
{
	protected int speed = 90;

	public Car()
	{
		System.out.println("Car class constructor..");
	}

	public void carDetails()
	{
		System.out.println("It has 1 engine and 4 wheels ");
	}

	public abstract void run();
}

class Honda extends Car
{
	@Override
	public void run()
	{
		System.out.println("Honda car is running");
	}
}

public class IQ
{
	public static void main(String[] args)
	{
		Car c = new Honda();
		System.out.println("Car Speed is :"+c.speed);
		c.carDetails();
		c.run();
	}

}

```


## abstract class constructor will be executed with the help sub class object by using super keyword.


## 14-06-2024


### IQ

If we can't create an object for abstract class then what is the advantage of writing constructor in abstract class?


## abstract class contains object properties (Instance variable), so those

properties, we need to initialize through constructor so we should write constructor inside abstract class and it will be exceuted with sub class object using super keyword.
```java
//Program that describes all the abstract methods must be overridden in the sub classes.

package com.nit.abstract_demo;

```


## abstract class Alpha

```java
{
	public abstract void show();
	public abstract void demo();
}

```


## abstract class Beta extends Alpha

```java
{
	@Override
	public void show()
	{
		System.out.println("Show method overridden in Beta class");
	}
}
class Gamma extends Beta
{
	@Override
	public void demo()
	{
		System.out.println("Demo method implemented in Gamma class");
	}
}

public class AbstractDemo
{
	public static void main(String[] args)
	{
		Gamma g = new Gamma();
		g.show();  g.demo();

	}

}
```

Program that describes how to initialize abstract class properties
from sub class object using super keyword.

```java
package com.nit.abstract_demo;

```


## abstract class Shape

```java
{
	protected String shapeType;

	public Shape(String shapeType)
	{
		super();
		this.shapeType = shapeType;
	}

	public abstract void draw();
}

class Square extends Shape
{
	public Square(String shape)
	{
		super(shape);
	}

	@Override
	public void draw()
	{
		System.out.println("Drawing :"+shapeType);
	}
}
class Rectangle extends Shape
{
	public Rectangle(String shape)
	{
		super(shape);
	}

	@Override
	public void draw()
	{
		System.out.println("Drawing :"+shapeType);
	}
}

public class AbstractDemo1 {

	public static void main(String[] args)
	{
		Square ss = new Square("Square");
		ss.draw();

		Rectangle rr = new Rectangle("Rectangle");
		rr.draw();

	}

}
```


### Program with array and abstract class to show dynamic polymorphism

```java
package com.nit.abstract_demo;

```


## abstract class Animal

```java
{
	public abstract void checkup();
}

class Dog extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Dog Checkup");
	}

}
class Lion extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Lion Checkup");
	}
}
class Bird extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Bird Checkup");
	}

}

public class AbstractDemo2 {

	public static void main(String[] args)
	{
	  Lion []lions = {new Lion(), new Lion(), new Lion()};

	  Dog []dogs = {new Dog(), new Dog()};

	  Bird []birds = {new Bird(), new Bird(), new Bird(), new Bird() };

	  checkAnimals(lions);
	  checkAnimals(dogs);
	  checkAnimals(birds);
	}

	public static void checkAnimals(Animal []animals)
	{
		for(Animal animal : animals)
		{
			animal.checkup();
		}
	}


}
```


*********IMP*********
```java
interface upto java 1.7
```

An interface is a keyword in java which is similar to a class which defines working functionality of a class.

Upto JDK 1.7 an interface contains only abstract method that means there is a guarantee that inside an interfcae we don't have concrete or general or instance methods.

From java 8 onwards we have a facility to write default and static methods.

By using interface we can achieve 100% abstraction concept because it contains only abstract methods.

In order to implement the member of an interface, java software people has provided implements keyword.

All the methods declared inside an interface is by default public and abstract so at the time of overriding we should apply public access modifier to sub class method.

All the variables declared inside an interface is by default public, static and final.

We should override all the abstract methods of interface to the sub classes otherwise the sub class will become as an abstract class hence object can't be created.

We can't create an object for interface, but reference can be created.

By using interfcae we can acheive multiple inheritance in java.

We can achieve loose coupling using inetrface.


> **Note :- inside an interface we can't declare any blocks (instance, static), instance variables (No properties) as well as we can't write constructor inside an interface.**

```java
package com.ravi.interface_demo;

interface Moveable
{
	int SPEED = 100;

	void move();
}

class Car implements Moveable
{
	@Override
	public void move()
	{
		//SPEED = 120;	//Invalid
		System.out.println("My car speed is :"+SPEED);
	}
}

public class InterfaceDemo
{
	public static void main(String[] args)
	{
		Moveable m = new Car() ;
		m.move();
        System.out.println("Speed of the car is :"+Moveable.SPEED);

	}

}
```

```java
package com.ravi.interface_demo;

interface Calculator
{
	void doSum(int x, int y);
	void doSub(int x, int y);
	void doMul(int x, int y);
}

class ArithmeticOperation implements Calculator
{
	@Override
	public void doSum(int x, int y)
	{
       int sum = x + y;
       System.out.println("Sum is :"+sum);
	}

	@Override
	public void doSub(int x, int y)
	{
		  int sub = x - y;
	       System.out.println("Sub is :"+sub);

	}

	@Override
	public void doMul(int x, int y)
	{
		  int mul = x * y;
	      System.out.println("Mul is :"+mul);
	}

}


public class InterfaceDemo1
{
	public static void main(String[] args)
	{
		ArithmeticOperation a = new ArithmeticOperation();
		a.doSum(12, 24);
		a.doSub(200, 110);
		a.doMul(12, 10);

	}

}

```


> **Note :- From this program it is clear that we need to override all the methods of interface.**


## 17-06-2024

```java
package com.ravi.interface_demo;

interface Bank
{
	void deposit(int amount);
	void withdraw(int amount);
}
class Customer implements Bank
{
	protected double balance = 10000;
	@Override
	public void deposit(int amount)
	{
		if(amount <=0)
		{
			System.err.println("Amount can't be deposited");
		}
		else
		{
			this.balance = this.balance + amount;
			System.out.println("Amount after deposit :"+this.balance);
		}
	}

	@Override
	public void withdraw(int amount)
	{
		if(amount > balance)
		{
			System.err.println("Withdraw is not possible, Insufficient Balance");
		}
		else
		{
			this.balance = this.balance - amount;
			System.out.println("Amount after withdraw is :"+this.balance);
		}

	}
}

public class BankDemo {

	public static void main(String[] args)
	{
		Customer c1 = new Customer();
		c1.deposit(20000);
		c1.withdraw(30000);
	}

}
```

```java
//Program on loose coupling :
```


### Program on loose coupling

Loose Coupling :- If the degree of dependency from one class object to another class is very low then it is called loose coupling.

Tightly coupled :- If the degree of dependency of one class to another class is very high then it is called Tightly coupled.

According to IT industry standard we should always prefer loose coupling so the maintenance of the project will become easy.

High Cohesion [Encapsulation]:
Our private data must be accessible via public methods (setter and getters) so, in between data and method we must have high cohesion.
(tight coupling) so, validation of outer data is possible.

### 6 files

HotDrink.java(I)
```java
package com.ravi.interface_demo;

public interface HotDrink
{
  void prepare();
}


```

Tea.java(c)
```java
package com.ravi.interface_demo;

public class Tea implements HotDrink
{
	@Override
	public void prepare()
	{
		System.out.println("Preparing Tea");
	}

}

```

Coffee.java
```java
package com.ravi.interface_demo;

public class Coffee implements HotDrink
{
	@Override
	public void prepare()
	{
		System.out.println("Preparing Coffee");
	}

}


```

Horlicks.java
```java
package com.ravi.interface_demo;

public class Horlicks implements HotDrink
{
	@Override
	public void prepare()
	{
		System.out.println("Preparing Horlicks");
	}

}


```

Restaurant.java
```java
package com.ravi.interface_demo;

public class Restaurant
{
   public static void acceptObject(HotDrink hd)
   {
	   hd.prepare();
   }
}


```

LooseCoupling.java
```java
package com.ravi.interface_demo;

public class LosseCoupling {

	public static void main(String[] args)
	{
		Restaurant.acceptObject(new Tea());
		Restaurant.acceptObject(new Coffee());
		Restaurant.acceptObject(new Horlicks());
	}

}
```


It is always better to take method return type as interface so we can return any implementer class object as shown in the example below

```java
public HotDrink accept()
{
   return new Tea() OR new Coffee() OR new Horlicks() OR any future
```

implementer class object...........................
```java
}
```


### Multiple Inheritance by using interface

In a class we have a constructor so, it is providing ambiguity issue but inside an interface we don't have constructor so multiple inheritance is possible using interface.

The sub class constructor super keyword will move to Object class
constructor.(17-JUNE)

MultipleInheritance.java
```java
package com.ravi.interface_demo;

interface Alpha
{
	void m1();
}
interface Beta
{
	void m1();
}
class Implementer implements Alpha,Beta
{
	@Override
	public void m1()
	{
		System.out.println("Multiple inheritance using interface");
	}
}

public class MultipleInheritance {

	public static void main(String[] args)
	{
	  new Implementer().m1();
	}

}
```


### Extending interface

One interface can extends another interface, it cannot implement because interface cannot provide implementation for the abstract method.

ExtendingInterface.java
```java
package com.ravi.interface_demo;

interface I
{
	void m1();
}
interface J extends I
{
	void m2();
}

class C implements I,J
{

	@Override
	public void m2()
	{
		System.out.println("m2 method implemented!!!");
	}

	@Override
	public void m1()
	{
		System.out.println("m1 method implemented!!!");
	}
}

public class ExtendingInterface {

	public static void main(String[] args)
	{
		C c1 = new C(); c1.m1();  c1.m2();

	}

}
```


### interface from JDK 1.8 onwards



### Limitation of abstract method

OR
Maintenance problem with interface in an Industry upto JDK 1.7
The major maintenance problem with interface is, if we add any new abstract method at the later stage of development inside an existing interface then all the implementer classes have to override that abstract method otherwise the  implementer class will become as an abstract class so it is one kind of boundation.

We need to provide implementation for all the abstract methods available inside an interface whether it is required or not?

To avoid this maintenance problem java software people introduced default method inside an interface.


## What is default Method inside an interface?

default method is just like concrete method which contains method body and we can write inside an interface from java 8 onwards.

default method is used to  provide  specific implementation for the implementer classes which are implmenting from interface because we can override default method inside the sub classes to provide our own specific implementation.

*By using default method there is no boundation to override the default method in the sub class, if we really required it then we can override to provide my own implementation.

by default, default method access modifier is public so at the time of overriding we should use public access modifier.

default method we can write inside an interface only but not inside a class.

### Program on default method


### 4 files

Vehicle.java(I)
```java
package com.ravi.interface_new_feature;

public interface Vehicle
{
  void run();
  void horn();

```

default void digitalMeter()
```java
  {
	  System.out.println("Digital Meter Facility coming soon");
  }

}

```

Car.java(C)
```java
package com.ravi.interface_new_feature;

public class Car implements Vehicle
{
	@Override
	public void run()
	{
		System.out.println("Car is running");
	}

	@Override
	public void horn()
	{
		System.out.println("Car has horn ");
	}

	@Override
	public void digitalMeter()
	{
		  System.out.println("Car has Digital Meter Facility");
	 }





}

```

Bike.java(C)
```java
package com.ravi.interface_new_feature;

public class Bike implements Vehicle
{
	@Override
	public void run()
	{
		System.out.println("Bike is running");
	}

	@Override
	public void horn()
	{
		System.out.println("Bike has horn ");
	}



}


```

Main.java(C)
```java
package com.ravi.interface_new_feature;

public class Main {

	public static void main(String[] args)
	{
		Vehicle v = null;
		v = new Car(); v.run(); v.horn(); v.digitalMeter();
		v = new Bike(); v.run(); v.horn(); v.digitalMeter();
	}

}

```


> **Note :- abstract method is a common method which is used to provide easiness to the programmer so, by looking the abstract method we will get confirmation that this is common behavior for all the sub classes and it must be implemnted in all the sub classes.**


### Priority of deafult and concrete method

While working with class and interface, default method is having low
priority than concrete method, In the same way class is more powerfult than interface.

```java
class C extends B implements A  {}  //Valid

class C implements A extends B {} //Invalid






```

4 files :
A.java
```java
package com.ravi.interface_demo;

public interface A
{
```

default void m1()
```java
  {
	  System.out.println("M1 method of interface");
  }
}


```

B.java
```java
package com.ravi.interface_demo;

public class B
{
  public void m1()
  {
	  System.out.println("M1 method of class");
  }
}


```

C.java
```java
package com.ravi.interface_demo;

public class C extends B implements A
{

}



```

Main.java
```java
package com.ravi.interface_demo;

public class Main {

	public static void main(String[] args)
	{
		C c1 = new C();
		c1.m1();
	}

}
```


### Multiple Inheritance by using default Method

Multiple inheritance is possible in java by using default method inside an interface, here we need to use super keyword to differenciate the super interface methods.
Before java 1.8, we have abstract method inside an interface but now we can write method body so to execute the default method inside an interface we need to take super keyword with interface name(A.super.m1()).

4 files :
A.java(I)
```java
package com.ravi.interface_demo;

public interface A
{
```

default void m1()
```java
  {
	  System.out.println("default method of interface A");
  }
}


```

B.java(I)
```java
package com.ravi.interface_demo;

public interface B
{
```

default void m1()
```java
	{
		  System.out.println("default method of interface B");
	}
}


```

Implementer.java(C)
```java
package com.ravi.interface_demo;

public class Implementer implements A,B
{
	@Override
	public void m1()
	{
		System.out.println("Multiple Inheritance is possible");
		A.super.m1();
		B.super.m1();

	}
}


```

Main.java(C)
```java
package com.ravi.interface_demo;

public class Main {

	public static void main(String[] args)
	{
		new Implementer().m1();
	}

}
```


### What is static method inside an interface?

We can define static method inside an interface from java 1.8 onwards.

```java
static method is only available inside the interface where it is defined that means we cannot invoke static method from the implementer classes with the help of implementer class.

```

It is used to provide common functionality which we can apply/invoke from any BLC/ELC class.

By default static method of an inetrafce contains public  access
modifier.


### 2 files

Calculate.java(I)
```java
package com.ravi.static_method_interface;

public interface Calculate
{
    static double doSum(int x, int y)
    {
	     return (x+y);
    }

    static double getCube(int num)
    {
    	return (num*num*num);
    }
}

```

Main.java
```java
package com.ravi.static_method_interface;

public class Main {

	public static void main(String[] args)
	{
		double result = Calculate.doSum(12, 24);
		System.out.println("Sum is :"+result);

		result = Calculate.getCube(9);
		System.out.println("Cube is :"+result);


	}

}

```

Note : static method of an interface is by default public and it is accessible through interface name only.
```java
//Program that describes interface static method is not available to implementer classes , It can be accessible throuh interface name only

package com.ravi.static_method_interface;

interface Drawable
{
	public static void m1()
	{
		System.out.println("m1 static method of interface");
	}
}

public class InterfaceStatic implements Drawable
{
	public static void main(String[] args)
	{
		 m1();  //Invalid
```

InterfaceStatic.m1();  //Invalid

```java
		InterfaceStatic is = new InterfaceStatic();
```

is.m1();  //Invalid

```java
		Drawable.m1();

	}

}

```


> **Note :- It is clear that interface static method is not available to implementer class.**

```java
package com.ravi.static_method_interface;

public interface Executer
{
  public static void main(String[] args)
  {
	  System.out.println("Main method inside an interface ");
  }
}


```

Note : We can write main method inside an interface from JDK 1.8 and
It will be executed because for any interface, internally .class file is created.

### Interface Static Method

a) Accessible using the interface name.
b) Cannot be overridden by implementing classes.(Not Available)
c) Can be called using the interface name only.

Class Static Method:
a) Accessible using the class name.
b) Can be hidden (not overridden) in subclasses by redeclaring a static method with the same signature.
c) Can be called using the super class, sub class name as well as sub class object also as shown in the program below.

```java
package com.nit.static_method;

class Super
{
	public static void m1()
	{
		System.out.println("static method of super class");
	}
}
class Sub extends Super
{

}

public class StaticMethod {

	public static void main(String[] args)
	{
	        Super.m1();
		Sub.m1();
		Sub s1 = new Sub();  s1.m1();


	}

}
```


### Anonymous inner class

If we write a class without any name then it is called anonymous inner class.

The main purpose of anonymous inner class to extend a class or implement an interface.

An anonymous inner class always end with semicolon.

```java
//Anonymous inner class with concrete class :
```

```java
package com.ravi.anonymous;

class Super
{
	public void show()
	{
		System.out.println("show method of super class");
	}
}

public class AnonymousWithConcrete
{
	public static void main(String[] args)
	{
		//Anonymous inner class (class without any name)
```

Super sub = new Super()
```java
		{
			@Override
			public void show()
			{
				System.out.println("Show method of sub class");
			}
		};

		sub.show();

	}

}
```

```java
//Anonymous inner class with abstract class :
```

```java
package com.ravi.anonymous;

```


## abstract class Animal

```java
{
	public abstract void roam();
}

public class AnonymousWithAbstract {

	public static void main(String[] args)
	{
```

Animal bird = new Animal()
```java
		{
			@Override
			public void roam()
			{
				System.out.println("Bird is roaming");
			}

		};

```

Animal lion = new Animal()
```java
		{
			@Override
			public void roam()
			{
				System.out.println("Lion is roaming");
			}

		};

		bird.roam();  lion.roam();

	}

}
```


## 19-06-2024


## What is a Functional interface in java ?

If an interface contains exactly one abstract method then it is called Functional interface.

A functional interface may contain 'n' number of static and default methods but it must contain only one abstract method. [SAM = Single abstract method]

We can provide @FunctionInterface annotation to define an interface as a Functional interface.

```java
package com.nit.functional_interface;

@FunctionalInterface
interface Student
{
	void writeExam();
}

public class FunctionalInterfaceDemo
{
	public static void main(String[] args)
	{
		//Anonymous inner class
```

Student science = new Student()
```java
		{
			@Override
			public void writeExam()
			{
				System.out.println("Science Students are Writing Exam!");
			}
		};

		// Anonymous inner class
```

Student commerce = new Student()
```java
		{
			@Override
			public void writeExam()
			{
				System.out.println("Commerce Students are Writing Exam!");
			}

		};

		science.writeExam();  commerce.writeExam();
	}

}
```


## What is Lambda Expression in java ?

It is a new feature introduced in java from JDK 1.8 onwards.
It is an anonymous function i.e function without any name.
In java it is used to enable functional programming.
It is used to concise our code as well as we can remove boilerplate code.
It can be used with functional interface only.
If the body of the Lambda Expression contains only one statement then curly braces are optional.
We can also remove the variables type while defining the Lambda Expression parameter.
If the lambda expression method contains only one parameter then we can remove () symbol also.

In lambda expression return keyword is optional but if we use return keyword then {} are compulsory.

Independently Lamda Expression is not a statement.

It requires a target variable i.e functional interface reference only.

Lamda target can't be class or abstract class, it will work with functional interface only.

### Programs on Lambda Expression

LambdaDemo1.java
```java
package com.ravi.lambda;

@FunctionalInterface
interface Printable
{
	void print();
}

public class LambdaDemo1
{
	public static void main(String[] args)
	{
		Printable p = () -> System.out.println("Printing");
		p.print();

	}

}
```

```java
package com.ravi.lambda;

@FunctionalInterface
interface Calculate
{
	void doSum(int x, int y);
}


public class LambdaDemo2
{
	public static void main(String[] args)
	{
		Calculate c = (a, b)-> System.out.println("Sum is :"+(a+b));
		c.doSum(12, 24);
	}

}
```

```java
package com.ravi.lambda;

import java.util.Scanner;

@FunctionalInterface
interface Length
{
	int getLength(String str);
}

public class LambdaDemo3 {

	public static void main(String[] args)
	{
		Length l = str -> str.length();

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter the name to find out the length :");
		String name = sc.nextLine();

		System.out.println("Length of "+name+" is :"+l.getLength(name));
		sc.close();


	}

}
```

```java
package com.ravi.lambda;

@FunctionalInterface
interface Vehicle
{
	void run();  //[SAM -> Single Abstract Method]
}

public class LambdaDemo4
{
	public static void main(String[] args)
	{
		Vehicle car = ()-> System.out.println("Car is Running");

		Vehicle bike = ()-> System.out.println("Bike is Running");

		Vehicle bus = ()-> System.out.println("Bus is Running");

		car.run();  bike.run();  bus.run();

	}

}
```


### Working with predefined functional interfaces without Type parameter

There is a predefined functional interface provided by java software people called Runnable available in java.lang pacakge.

It is also a Functional interafce because it contains only one abstract method as shown below :

```java
@FunctionalInterface
public interface Runnable
{
  void run();
}

```

LambdaDemo5.java
```java
package com.ravi.lambda;

public class LambdaDemo5
{
	public static void main(String[] args)
	{
		Runnable r1 = ()-> System.out.println("Running");
		r1.run();

	}

}
```


## 20-06-2024


### Type parameter in java <T> ?

It is a technique through which we can make our application indepenedent of data type. It is represented by <T>

In java we can pass Wrapper classes as well as User-defined classes to this type parameter.

We cannot pass any primitive type to this type parameter.

```java
package com.ravi.functional_interface;

class Accept<T>
{
	private T x;

	public Accept(T x)
	{
		super();
		this.x = x;
	}

	public T getX()
	{
		return x;
	}
}

public class TypeParameterDemo
{
	public static void main(String[] args)
	{
		Accept<Integer> intType = new Accept<Integer>(12);
		System.out.println("Integer type :"+intType.getX());

	   Accept<Double> doubleType = new Accept<Double>(12.90);
	   System.out.println("Double type :"+doubleType.getX());

	   Accept<Boolean> booleanType = new Accept<Boolean>(true);
	   System.out.println("Boolean type :"+booleanType.getX());

	   Accept<Student> studType = new Accept<Student>(new Student(111));
	   System.out.println("Student type :"+studType.getX());

	}

}

class Student
{
	private int studentId;

	public Student(int studentId)
	{
		super();
		this.studentId = studentId;
	}

	@Override
	public String toString()
	{
		return "Student [studentId=" + studentId + "]";
	}
}
```


### Working with predefined functional interfaces

In order to help the java programmer to write concise  java code in day to day programming java software people has provided the following predefined functional interfaces

1) Predicate<T>
2) Consumer<T>
3) Function<T,R>
4) Supplier<T>
5) BiPredicate<T,U>
6) BiConsumer<T, U>
7) BiFunction<T,U,R>


> **Note :-**

All these predefined functional interfaces are provided as a part of java.util.function sub package.

Predicate<T> functional interface  :
It is a predefined functional interface available in java.util.function sub package.

It contains an abstract method test() which takes type parameter <T> and returns boolean value. The main purpose of this interface to test one argument boolean expression.

```java
@FunctionalInterface
public interface Predicate<T>
{
  boolean test(T x);
}


```


> **Note :- Here T is a "type parameter" and it can accept any type of User defined class as well as  Wrapper class like Integer, Float, Double and so on.**


We can't pass primitive type.

### Programs on Predicate<T> functional interface

```java
package com.ravi.predicate_demo;

import java.util.Scanner;
import java.util.function.Predicate;

public class PredicateDemo
{
	public static void main(String[] args)
	{
		//Verify whether a number is even or odd
		Predicate<Integer> p = num -> num % 2==0;

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter a number :");
		int no = sc.nextInt();

		System.out.println(no+" is even ?"+p.test(no));
		sc.close();

	}

}
```

```java
package com.ravi.predicate_demo;

import java.util.Scanner;
import java.util.function.Predicate;

public class PredicateDemo2 {

	public static void main(String[] args)
	{
	  //verify whether a person is eligible for voting or not
	  Predicate<Integer> p2 = age -> age > 18;

	  Scanner sc = new Scanner(System.in);
	  System.out.print("Enter your Age :");
	  int age = sc.nextInt();

	  System.out.println(" Are u eligible 4 voting :"+p2.test(age));


	}

}
```

```java
package com.ravi.predicate_demo;

import java.util.Scanner;
import java.util.function.Predicate;

public class PredicateDemo3 {

	public static void main(String[] args)
	{
	 //Verify whether my name starts with character 'R' or not
	 Predicate<String> p3 = str -> str.startsWith("R");

	  Scanner sc = new Scanner(System.in);
	  System.out.print("Enter your Name :");
	  String name = sc.nextLine();

	  System.out.println("Name "+name+" starts with R ?"+p3.test(name));
      sc.close();
	}

}
```

```java
package com.ravi.predicate_demo;

import java.util.function.Predicate;

public class PredicateDemo4
{
	public static void main(String[] args)
	{
		//Verify whether you are Sachin or not

		Predicate<String> p4 = str -> str.equals("Sachin");
		System.out.println("Are u sachin :"+p4.test("Rohit"));

	}

}
```


### Assignment


### By using Predicate verify whether a year is leap year or not?



Consumer<T> functional interface :
It is a predefined functional interface available in java.util.function sub package.

It contains an abstract method accept() and returns nothing. It is used to accept the parameter value or consume the value.

```java
@FunctionalInterface
public interface Consumer<T>
{
    void accept(T x);
}
```

```java
package com.ravi.consumer_demo;

import java.util.function.Consumer;

public class ConsumerDemo1 {

	public static void main(String[] args)
	{
		Consumer<Integer> conInt = num -> System.out.println(num);
		conInt.accept(12);

		Consumer<Character> conChar = c -> System.out.println(c);
        conChar.accept('A');

        Consumer<Student> conStud = stud -> System.out.println(stud);
        conStud.accept(new Student(999));
	}

}

class Student
{
	private int studentId;

	public Student(int studentId)
	{
		super();
		this.studentId = studentId;
	}

	@Override
	public String toString()
	{
		return "Student [studentId=" + studentId + "]";
	}
}
```


### Function<T,R> functional interface


### Type Parameters

T - the type of the input to the function.
R - the type of the result of the function.

It is a predefined functional interface available in java.util.function sub package.

It provides an abstract method apply that accepts one argument(T) and produces a result(R).


> **Note :- The type of T(input) and the type of R(Result) both will be decided by the user.**


```java
@FunctionalInterface
public interface Function<T,R>
{
   public abstract R apply(T x);
}
```

```java
package com.ravi.function_demo;

import java.util.Scanner;
import java.util.function.Function;

public class FunctionDemo1 {

	public static void main(String[] args)
	{
		//finding the cube of the number
		Function<Integer,Integer> fn1 = num -> num*num*num;

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter a number :");
		int no = sc.nextInt();

		System.out.println("Cube of "+no+" is :"+fn1.apply(no));
		sc.close();

	}

}
```

```java
package com.ravi.function_demo;

import java.util.Scanner;
import java.util.function.Function;

public class FunctionDemo2 {

	public static void main(String[] args)
	{
		//Finding the length of city
		Function<String,Integer> fn2 = str -> str.length();

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter your city Name :");
		String city = sc.nextLine();

		System.out.println("Length of "+city+" is :"+fn2.apply(city));
		sc.close();

	}

}
```

```java
package com.ravi.function_demo;

import java.util.Scanner;
import java.util.function.Function;

public class FunctionDemo3 {

	public static void main(String[] args)
	{
		//Verify whether name starts with A or not
		Function<String,Boolean> fn3 = str -> str.startsWith("A");

		Scanner sc = new Scanner(System.in);
		System.out.print("Enter your Name :");
		String name = sc.nextLine();

		System.out.println(name+" starts with 'A' ?"+fn3.apply(name));
		sc.close();

	}

}
```


## 21-06-2024


### Supplier<T> prdefined functional interface

It is a predefined functional interface available in java.util.function sub package. It provides an abstract method get() which does not take any argument but produces/supply a value of type T.

```java
@FunctionalInterface
public interface Supplier<T>
{
   T get();
}
```

```java
package com.ravi.supplier_demo;

import java.util.function.Supplier;

public class SupplierDemo1
{
	public static void main(String[] args)
	{
		Supplier<String> s1 = () -> 90 + 90 + "NIT"+ 45 + 45;

		System.out.println(s1.get());
	}

}

```

Note : Here in the Supplier, we are accepting String value so the
```java
return type of get method will be String.
```


## Record class in java

```java
public abstract class Record extends Object.

```

It is a new feature introduced from java 17.(In java 14 preview version)

As we know only objects are moving in the network from one place to another place so we need to write BLC class with nessacery requirements to make BLC class as a Data carrier class.

Records are immutable data carrier so, now with the help of record we can send our immutable data from one application to another application.

It is also known as DTO (Data transfer object) OR POJO classes.

It is mainly used to concise our code as well as remove the boiler plate code.

In record, automatically constructor will be generated which is known as canonical constructor and the variables which are known as components are by default final.

In order to validate the outer world data, we can write our own constructor which is known as compact constructor.

Record will automatically generate the implemenation of toString(), equals(Object obj) and hashCode() method.

We can define static and non static method as well as static variable inside the record. We cannot define instance variable and instance block inside the record.

We cann't extend or inherit records because by default every record is implicilty final and It is extending from java.lang.Reocrd class, which is an abstract class.

We can implement an interface by using record.

We don't have setter facility in record because by default components are final.

### 3 files

EmployeeClass.java(C)
```java
package com.ravi.record_demo;

import java.util.Objects;

public class EmployeeClass
{
	private int employeeId;
	private String employeeName;

	public EmployeeClass(int employeeId, String employeeName)
	{
		super();
		this.employeeId = employeeId;
		this.employeeName = employeeName;
	}

	public int getEmployeeId() {
		return employeeId;
	}

	public void setEmployeeId(int employeeId) {
		this.employeeId = employeeId;
	}

	public String getEmployeeName() {
		return employeeName;
	}

	public void setEmployeeName(String employeeName) {
		this.employeeName = employeeName;
	}

	@Override
	public String toString() {
		return "EmployeeClass [employeeId=" + employeeId + ", employeeName=" + employeeName + "]";
	}

	@Override
	public int hashCode() {
		return Objects.hash(employeeId, employeeName);
	}

	@Override
	public boolean equals(Object obj) {
		if (this == obj)
			return true;
		if (obj == null)
			return false;
		if (getClass() != obj.getClass())
			return false;
		EmployeeClass other = (EmployeeClass) obj;
		return employeeId == other.employeeId && Objects.equals(employeeName, other.employeeName);
	}

}


```

EmployeeRecord.java(R)
```java
package com.ravi.record_demo;

              //Canonical Constructor
public record EmployeeRecord(int employeeId, String employeeName)
{
	//Compact constructor
	public EmployeeRecord()
	{
		if(employeeId <= 0)
		{
			System.err.println("Invalid id");
		}

	}
}

```

Main.java
```java
package com.ravi.record_demo;

public class Main {

	public static void main(String[] args)
	{
		//Comparison of class and record

		EmployeeClass e1 = new EmployeeClass(111, "Scott");
		System.out.println(e1);
		System.out.println(e1.getEmployeeName());
		EmployeeClass e2 = new EmployeeClass(111, "Scott");
		System.out.println(e1.equals(e2));

		System.out.println("................................");

		EmployeeRecord r1 = new EmployeeRecord(-222, "Smith");
		System.out.println(r1);
		System.out.println(r1.employeeName());
		EmployeeRecord r2 = new EmployeeRecord(222, "Smith");
		System.out.println(r1.equals(r2));



	}

}
```


### Remainig Program on Supplier<T> interface

```java
package com.ravi.supplier_demo;

import java.util.function.Supplier;

```

record Employee(int empId, String empName, double empSalary)
```java
{

}

public class SupplierDemo2
{
	public static void main(String[] args)
	{
```

Supplier<Employee> s2 = ()->
```java
		{
			Employee e1 = new Employee(1, "A", 23567);
			return e1;
		};

		Employee emp = s2.get();
		System.out.println(emp);
	}

}
```

```java
package com.ravi.supplier_demo;

import java.util.Scanner;
import java.util.function.Supplier;

```

record Player(int playerId, String playerName, double basePrice)
```java
{
}


public class SupplierDemo3 {

	public static void main(String[] args)
	{
```

Supplier<Player> s3 = ()->
```java
		{
			Scanner sc = new Scanner(System.in);
			System.out.print("Enter Player id :");
			int id = sc.nextInt();

			System.out.print("Enter player name :");
			String name = sc.nextLine();
			name = sc.nextLine();

			System.out.print("Enter Player base Price :");
			double basePrice = sc.nextDouble();


			return new Player(id, name, basePrice);
		};

		Player obj = s3.get();
		System.out.println(obj);

	}

}
```


### BiPredicate<T,U> functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents a predicate (a boolean-valued function) OF TWO ARGUMENTS.

The BiPredicate interface has method named test, which takes two parameters and returns a boolean value, basically this BiPredicate is same with the Predicate, instead, it takes 2 arguments for the test.

```java
@FunctionalInterface
public interface BiPredicate<T, U>
{
    boolean test(T t, U u);
}

```

Type Parameters:

T - the type of the first argument to the predicate
U - the type of the second argument the predicate
```java
import java.util.function.*;
public class Lambda11
{
	public static void main(String[] args)
    {
```

BiPredicate<String, Integer> filter = (x, y) ->
```java
		{
            return x.length() == y;
        };

        boolean result = filter.test("Ravi", 4);
        System.out.println(result);

        result = filter.test("Hyderabad", 10);
        System.out.println(result);
	}
}
```

```java
import java.util.function.BiPredicate;

public class Lambda12
{
  public static void main(String[] args)
  {
    // BiPredicate to check if the sum of two integers is even
    BiPredicate<Integer, Integer> isSumEven = (a, b) -> (a + b) % 2 == 0;

        System.out.println(isSumEven.test(2, 3));
        System.out.println(isSumEven.test(5, 7));
    }
}
```


### BiConsumer<T, U> functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents an operation that accepts two input arguments and returns no result.

It takes a method named accept, which takes two parameters and performs an action without returning any result.

```java
@FunctionalInterface
public interface BiConsumer<T, U>
{
    void accept(T t, U u);
}
```

```java
import java.util.function.BiConsumer;

public class Lambda13
{
   public static void main(String[] args)
   {
```

BiConsumer<Integer, String> updateVariables =  (num, str) ->
```java
		 {
            num = num * 2;
            str = str.toUpperCase();
            System.out.println("Updated values: " + num + ", " + str);
        };


        int number = 15;
        String text = "nit";

        updateVariables.accept(number, text);

        // Values after the update (note that the original values are unchanged)
        System.out.println("Original values: " + number + ", " + text);
    }
}
```


### BiFunction<T, U, R> Functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents a function that accepts two arguments and produces a result R.

The BiFunction interface has a method named apply that takes two arguments and returns a result R.

```java
@FunctionalInterface
public interface BiFunction<T, U, R>
{
    R apply(T t, U u);
}

import java.util.function.BiFunction;

public class Lambda14
{
  public static void main(String[] args)
  {
        // BiFunction to concatenate two strings
    BiFunction<String, String, String> concatenateStrings = (str1, str2) -> str1 + str2;

        String result = concatenateStrings.apply("Hello", " Java");
        System.out.println(result);


      // BiFunction to find the length two strings
    BiFunction<String, String, Integer> concatenateLength = (str1, str2) -> str1.length() + str2.length();

        Integer result1 = concatenateLength.apply("Hello", "Java");
        System.out.println(result1);


  }
}
```


## 22-06-2024

Interface from java 9v version
Yes, From java 9 onwards we can also write private static and private non-static methods inside an interface.

These private methods will improve code re-usability inside interfaces.

For example, if two default methods needed to share common and confidential code, a private method would allow them to do so, but without exposing that private method to it�s implementing classes.

Using private methods in interfaces have four rules :

1) private interface method cannot be abstract.
2) private method can be used only inside interface.
3) private static method can be used inside other static and non-static interface methods.
4) private non-static methods cannot be used inside private static methods.

```java
package com.ravi.interface_9_fetures;

interface Drawable
{
	void m1();

```

default void m2()
```java
	{
		m4();
		m5();
	}

	static void m3()
	{
		m4();
	}

	private static void m4()
	{
		System.out.println("Private Static method");
	}

	private  void m5()
	{
		System.out.println("Private Non Static method");
	}

}
class Implementer implements Drawable
{
	@Override
	public void m1()
	{
		System.out.println("m1 method overridden");
	}
}

public class InterfaceDemo
{
	public static void main(String[] args)
	{
		Drawable d = new Implementer();
		d.m1();
		d.m2();


		Drawable.m3();

	}

}
```


### Can an interface extend a class like Object class ?

No Interface does not inherits Object class,but it provide accessibility to all methods of Object class.

This is because, for every public method in Object class, there is an implicit abstract and public method declared in every interface which does not have direct super interfaces. (Java language Specification 9.2 about interface members)
```java
-----------------------------------------------------------------------package com.ravi.interface_9_fetures;

interface A
{


}

public class InterfaceMember
{
	public static void main(String[] args)
	{
		A a = null;
		a.hashCode();
		a.toString();
		a.equals(a);
	}

}
```

```java
package com.ravi.interface_9_fetures;

@FunctionalInterface
interface Hello
{
	void m1();
	public String toString();
	public int hashCode();
	public boolean equals(Object obj);

}

public class InterfaceMember1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

	}

}
```


### Can a default method override Object class method inside a interface ?

default method can't override Object class method which are re-declared inside an interface.

```java
package com.ravi.interface_9_fetures;

interface L
{
	public default String toString()  //error
	{
		return "Hello";
	}
}


public class InterfaceMember2
{
	public static void main(String[] args) {
		// TODO Auto-generated method stub

	}

}
```


## What is marker interface in java ?

If an interface does not contain any field or method, basically an empty interface is known as Marker OR tag OR Empty interface.

Example :
```java
interface A
{
}


```

The main purpose of marker interface to provide additional information
to JVM regarding the object like Object is serializable, cloneable and
random accessible or not.

Example of Marker interface :
In java we have following predefined marker interfaces are available

java.lang.Cloneable
java.io.Serializable
java.util.RandomAccess

Example of marker interface :
```java
interface Serializable //Marker interface
{

}


class Customer  implements Serializable
{

}


Serializable c = new Customer();

if(c instanceof Customer)
{
```

Now perform serialization
```java
}
```

****What is difference between abstract class and interface ?
The following are the differences between abstract class and interface.

1) An abstract class can contain instance variables but interface variables are by default public , static and final.

2) An abstract class can have state (properties) of an object but interface can't have state of an object.

3) An abstract class can contain constructor but inside an interface we can't define constructor.

4) An abstract class can contain instance and static blocks but inside an interface we can't define any blocks.

5) Abstract class can't refer Lambda expression but using Functional interface we can refer Lambda Expression.

6) By using abstract class multiple inheritance is not possible but by using interface we can achieve multiple inheritance.

---------------OOPs completed-----------------------------------------


## Exception Handling


### What is an execption ?

An execption is a runtime error.

An execption is an abnormal situation or un-expected situation in a noraml execution flow.

An exception encounter due to dependency, if one part of the program is dependent to another part then there might be a chance of getting Exception.

AN EXCEPTION ALSO ENCOUNTER DUE TO WRONG INPUT GIVEN BY THE USER.


## 24-06-2024


## Exception Hierarchy

This Exception hierarchy is available in the diagram (Exception_Hierarchy.png)


> **Note :- As a developer we are responsibe to handle the Exception. System admin is responsibe to handle the error because we cannot recover from error.**


### Different Crieteria of Exception

The following are the different criteria for exception

1) java.lang.ArithmeticException
Whenever we divide a number by zero (an int value) then we will get
an exception i.e java.lang.ArithmeticException

Example :
```java
   System.out.println(10/0);

```

2) java.lang.NullPointerException
Whenever we want to call any non static field or non static method and if the reference is holding null then we will get
java.lang.NullPointerException.

Example :
```java
   String str = null;
   System.out.println(str.length());


```

3) java.lang.NumberFormatException
Whenever we try to convert a String into integer or any other type and if the number is not in a proper format then we will get an
Exception java.lang.NumberFormatException

Example :
```java
   String str = "NIT";
   System.out.println(Integer.parseInt(str));

```

4) java.lang.ArrayIndexOutOfBoundsException
If we try to access the the index of an array and if the index is
out of the bound then we will get java.lang.ArrayIndexOutOfBoundsException

Example :
```java
    int []arr = {10,20,30};
    System.out.println(arr[3]);

```

5) java.lang.NegativeArraySizeException
At the time of declaration we can't pass the sixe of an array in
Negative.

Example :
```java
   int []arr = new int[-2];

```

6) java.util.InputMismatchException
At the time of taking the input, if the input is not matching with
proper format then we will get java.util.InputMismatchException

Example :
```java
   Scanner sc = new Scanner(System.in);
   System.out.print("Enter your Roll numebr :");
   int roll = sc.nextInt();
```


### Exception format

Whenever we print exception object using System.out.println() statement
the format of exception is as follows :

Fully Qualified Name : errorMessage
WAP that describes Exception is the super class of all the
exceptions we have in java.

```java
package com.ravi.exception;

public class ExceptionDemo {

	public static void main(String[] args)
	{
		Exception e1 = new ArithmeticException();
		System.out.println(e1.toString());

		Exception e2 = new ArithmeticException("Number is divided by 0");
		System.out.println(e2.toString());

	}

}
```

WAP that describes that whenever an exception is encounter in the program then program will be terminated in the middle.

```java
package com.ravi.exception;

import java.util.Scanner;

public class ExceptionEncounter {

	public static void main(String[] args)
	{
		System.out.println("Main method Started!!!");

		Scanner sc = new Scanner(System.in);

		System.out.print("Enter the value of x :");
		int x = sc.nextInt();

		System.out.print("Enter the value of y :");
		int y = sc.nextInt();

		int result = x /y;
		System.out.println("Result is :"+result);

		System.out.println("Main method Completed");
		sc.close();

	}

}

```

In the above program, if we provide the value of y as 0 then our program will be terminated in the middle which is known as
abnormal termination, Here JVM has a default exception handler which will handle the exception and provide the exception message as well as terminate the program abnormally.

### In order to work with exception, java software people has provided the following keywords


1) try block
2) catch block
3) finally block (try with resourses 1.7v)
4) throw
5) throws


### Key points to remember

-> With try block we can write either catch block or finally block or both.
-> In between try and catch we can't write any kind of statement.
-> try block will trace our program line by line.
-> If we have any exception inside the try block,With the help of JVM, try block will automatically  create the appropriate Exception object and then throw the Exception Object to the nearest catch block.
-> In the try block whenever we get an exception the control will directly jump to the nearest catch block so the remaining code of try block will not be executed.
-> catch block is responsible to handle the exception.
-> catch block will only execute if there is an exception inside try block.
```java
try block :
```

Whenever our statement is error suspecting statement OR Risky statement then we should write that statement inside the try block.

```java
try block must be followed either by catch block or finally block or both.

```

*try block is responsible to trace our code line by line, if any execption encounter then with the help of JVM, TRY BLOCK WILL CREATE APPROPRIATE EXECPTION OBJECT, AND THROW THIS EXCEPTION OBJECT to the nearest catch block.

After the execption in the try block, the remaining code of try block will not be executed because control will directly transfer to the catch block.

In between try and catch block we cannot write any kind of statement.

```java
catch block :
```

The main purpose of catch block to handle the exception which is thrown by try block.

```java
catch block will only executed if there is an exception in the try block.
```


## 25-06-2024

```java
package com.ravi.exception;

import java.util.Scanner;

public class TryDemo {

	public static void main(String[] args)
	{
        System.out.println("Main method Started!!!");

		Scanner sc = new Scanner(System.in);

```

try
```java
		{
			System.out.print("Enter the value of x :");
			int x = sc.nextInt();

			System.out.print("Enter the value of y :");
			int y = sc.nextInt();

			int result = x /y;
			System.out.println("Result is :"+result);

			System.out.println("End of try block");
		}
		catch(Exception e)
		{
			System.out.println("Inside Catch");
			System.err.println(e);
		}

		System.out.println("Main method Completed");
		sc.close();
	}

}

```

In the above program if we put the value of y as 0 but still program will be executed normally because we have used try-catch so it is a
normal termination even we have an exception in the program.
```java
package com.ravi.exception;

public class ThrowDemo
{
	public static void main(String[] args)
	{
```

try
```java
		{
		  throw	new ArithmeticException("Dividing by zero");
		}
		catch(Exception e)
		{
			System.out.println("Inside catch Block");
			System.err.println(e);
		}
		System.out.println("Main completed");

	}

}

```

From the above progran it is clear that try block implicitly creating the exception object with the help of JVM and throwing the execption object to the nearest catch block.
The main purpose of Exception handling to provide user-friendly message to our end user as shown in the program.

```java
package com.ravi.exception;

import java.util.Scanner;

public class CustomerDemo {

	public static void main(String[] args)
	{
		   System.out.println("Hello Client!! Welcome to my Application");

			Scanner sc = new Scanner(System.in);
```

try
```java
			{
				System.out.print("Enter your Employee Id :");
				int id = sc.nextInt();
				System.out.print("Enter your Employee Name :");
				String name = sc.nextLine();
				name = sc.nextLine();

		System.out.println("Hello "+name+ " your employee id is :"+id);
		System.out.println("You have registered successfully!!!");

			}
			catch(Exception e)
			{
				System.err.println("Please provide only numeric values");
			}

			System.out.println("Thank you for Visiting my application.");
			sc.close();

	}

}
```


### Throwable class method


### Throwable class has provided the following three methods


1) public String getMessage() :- It will provide only error message.

2) public void printStackTrace() :-  It will provide the complete details regarding exception like exception class name, exception error message, exception class location, exception method name and exception line number.

3) public String toString() :- It will convert the exception into String representation.

```java
package com.ravi.basic;

public class PrintStackTrace
{
	public static void main(String[] args)
	{
		System.out.println("Main method started...");
```

try
```java
		{
			String x = "NIT";
			int y = Integer.parseInt(x);
			System.out.println(y);
		}
		catch(Exception e)
		{
```

e.printStackTrace(); //For complete Exception details
```java
			System.out.println("---------------------------");
			System.out.println("............................");
			System.err.println(e.getMessage()); //only for Exception message
			System.out.println("..............");
			System.err.println(e.toString());
		}
		System.out.println("Main method ended...");

	}

}
```


### Working with Specific Exception

While working with exception, in the corresponding catch block we can take Exception (super class) which can handle any type of Exception.

On the other hand we can also take specific type of exception (ArithmetiException, NullPointerException and so on) which will handle only one type i.e specific type of exception.
```java
package com.ravi.basic;

import java.util.InputMismatchException;
import java.util.Scanner;

public class SpecificException
{
	public static void main(String[] args)
	{
		System.out.println("Main started");

		Scanner sc = new Scanner(System.in);

```

try
```java
		{
			System.out.print("Enter your Roll :");
			int roll = sc.nextInt();
			System.out.println("Your Roll is :"+roll);
		}
		catch(InputMismatchException e)
		{
			System.err.println("Input is not in proper format");
		}
		sc.close();
		System.out.println("Main ended");
	}
}
```

```java
class Test
{
    public static void main(String[] args)
    {
```

try
```java
       {
		   throw new OutOfMemoryError();
       }
       catch (Error e)
       {
		   e.printStackTrace();
       }
	   System.out.println("Main Completed");
    }
}

```

Note : From the try block we are throwing the OutOfmemoryError so , Error OR Throwable is required in the catch block for handling purpose.

## 26-06-2024


### Working with Infinity and Not a number(NaN)

10/0    -> Infinity (Java.lang.ArithmeticException)
10/0.0  -> Infinity  (POITIVE_INFINITY)

0/0     -> Undefined (Java.lang.ArithmeticException)
0/0.0   -> Undefined  (NaN)


While working with Integral literal in both the cases i.e Infinity (10/0) and Undefined (0/0) we will get java.lang.ArithmeticException because java software people has not provided any final, static variable support to deal with Infinity and Undefined.

On the other hand while working with floating point literal in the both cases i.e Infinity (10/0.0) and Undefined (0/0.0) we have final, static variable support so the program will not be terminated in the middle which are as follows

10/0.0 = POSITIVE_INFINITY
-10/0.0 = NEGATIVE_INFINITY
0/0.0 = NaN
```java
package com.ravi.basic;

public class InfinityFloatingPoint
{
	public static void main(String[] args)
	{
	   System.out.println("Main Started");
	   System.out.println(10/0.0);
	   System.out.println(-10/0.0);
	   System.out.println(0/0.0);
	   System.out.println(10/0);
	   System.out.println("Main Ended");
	}

}
```


### Working with multiple try catch


### According to our application requirement we can provide multiple try catch in the same application as shown below


try
```java
{
int x = 10/0;
}
catch(ArithmeticException e)
{
}

```

try
```java
{
int []arr = {10,20,30};
System.out.println(arr[3]);
}
catch(ArrayIndexOutOfBoundsException e)
{
}

```

Here all the catch block will be executed at once so user will get so many exception message as showm in the program.

```java
package com.ravi.basic;
public class MultipleTryCatch
{
	public static void main(String[] args)
	{
	  System.out.println("Main method started!!!!");

```

try
```java
	  {
		  int arr[] = {10,20,30};
		  System.out.println(arr[3]);
	  }
	  catch(ArrayIndexOutOfBoundsException e)
	  {
		  System.err.println("Array index is out of limit!!!");
	  }

```

try
```java
	  {
		 String str = null;
		 System.out.println(str.length());
	  }
	  catch(NullPointerException e)
	  {
		  System.err.println("ref variable is pointing to null");
	  }

	  System.out.println("Main method ended!!!!");
	}
}

```

From the above program we are getting two exception messages so end user will get all the exception message at a time which is not a recommended way so we introduced try with multiple catch blocks.
* Single try with multiple catch block :
According to industry standard we should write try with multiple catch block so we can provide proper information for each and every exception.

While working with multiple catch block always the super class catch block must be last catch block.

From java 1.7v this multiple exceptions we can write in a single catch block by using | symbol.

If try block is having more than one exception then always try block will handle only first exception because control will transfer to the nearest catch block.
```java
package com.ravi.basic;
public class MultyCatch
{
	public static void main(String[] args)
	{
		System.out.println("Main Started...");
```

try
```java
		{
			int c = 10/0;
			System.out.println("c value is :"+c);

			int []x = {12,78,56};
			System.out.println(x[3]);
		}

		catch(ArrayIndexOutOfBoundsException e1)
		{
			System.err.println("Array is out of limit...");
		}
		catch(ArithmeticException e1)
		{
			System.err.println("Divide By zero problem...");
		}
		catch(Exception e1)
		{
			System.out.println("General");
		}

		System.out.println("Main Ended...");
	}
}
```

```java
package com.ravi.basic;

public class MultyCatch1
{
	public static void main(String[] args)
	{
		System.out.println("Main method started!!!");
```

try
```java
		{
		   String str1 = "null";
		   System.out.println(str1.toUpperCase());

		   String str2 = "Ravi";
		   int x = Integer.parseInt(str2);
		   System.out.println("Number is :"+x);
		}
		catch(NumberFormatException | NullPointerException  e)
		{
			e.printStackTrace();
		}

		System.out.println("Main method ended!!");
	}

}
```


```java
finally block [100% Guaranteed for Exceution]
```

```java
finally is a block which is meant for Resource handling purposes.

```

According to Software Engineering, the resources are memory creation, buffer creation, opening of a database, working with files, working with network resourses and so on.

Whenever the control will enter inside the try block always the finally block would be executed.

We should write all the closing statements inside the finally block because irrespective of exception finally block will be executed every time.

If we use the combination of try and finally then only the resources will be handled but not the execption, on the other hand if we use try-catch and finally then execption and resourses both will be handled.
```java
package com.ravi.basic;

public class FinallyBlock
{
	public static void main(String[] args)
	{
		System.out.println("Main method started");

```

try
```java
		{
			System.out.println(10/0);
		}

		finally
		{
			System.out.println("Finally Block");
		}

		System.out.println("Main method ended");
	}

}

```


> **Note :- Finally block will be executed irrespective of exception.**

```java
package com.ravi.basic;

public class FinallyWithCatch
{
	public static void main(String[] args)
	{

```

try
```java
		{

		    int []x = new int[-2];	//We can't pass negative size of an array in negative
		    x[0] = 12;
		    x[1] = 15;
		    System.out.println(x[0]+" : "+x[1]);


		}
		catch(NegativeArraySizeException e)
		{
			System.err.println("Array Size is in negative value...");

		}
		finally
		{
		   System.out.println("Resources will be handled here!!");
		}
		System.out.println("Main method ended!!!");
	}
}

```

In the above program exception and resourses both are handled because we have a combination of try-catch and finally.


> **Note :- In the try block if we write System.exit(0) and if this line is executed then finally block will not be executed.**


### Limitation of finally Block


### The following are the limitation of finally block


1) In order to close the resourses, user is responsible to write finally block manualy.

2) Due to finally block the length of the program will be increased.

3) In order to close the resourses inside the finally block, we need
to define the resourses outside of try block.


```java
package com.ravi.exception;

import java.util.InputMismatchException;
import java.util.Scanner;

public class TryWithResourse {

	public static void main(String[] args)
	{
		Scanner sc = null;
```

try
```java
		{
		  sc = new Scanner(System.in);
		  System.out.print("Enter your Age :");
		  int age = sc.nextInt();
		  System.out.println("Your Age is :"+age);
		}
		catch(InputMismatchException e)
		{
			System.err.println("Input is not in a proper format");
		}
		finally
		{
			sc.close();
			System.out.println("Scanner closed ");
		}

	}

}
```


## 27-06-2024


```java
try with resources :
```

To avoid all the limitation of finally block, Java software people introduced a separate concept i.e try with resources from java 1.7 onwards.

Case 1:
```java
try(resource1 ; resource2)  //Only the resources will be handled
{
}

```

Case 2 :
```java
//Resources and Exception both will be  handled
try(resource1 ; resource2)
{
}
catch(Exception e)
{
}

```

Case 3 :
```java
try with resourses enhancement from java 9v

Resourse r1 = new Resourse();
Resourse r2 = new Resourse();

try(r1; r2)
{
}
catch(Exception e)
{
}


```

There is a predefined interface available in java.lang package called AutoCloseable which contains predefined abstract method i.e close() which throws Exception.

There is another predefined interface available in java.io package called Closeable, this Closeable interface is the sub interface for AutoCloseable interface.

```java
public interface java.lang.AutoCloseable
{
   public abstract void close() throws Exception;
}
public interface java.io.Closeable extends java.lang.AutoCloseable
{
   void close() throws IOException;
}

```

Whenever we pass any resourse class as part of try with resources then that class must implements either Closeable or AutoCloseable interface so, try with resourses will automatically call the respective class
```java
close() method even an exception is encountered in the try block.

```

ResourceClass rc = new ResourceClass()
```java
try(rc)
{
}
catch(Exception e)
{

}

//This ResourceClass must implements either Closeable or AutoCloseable interface so, try block will automatically call the close() method as well as try block will get the gurantee of close() method support in the respective class.


```

The following program explains how try block is invoking the close() method available in DatabaseResource class and FileResourse class.

3 files :
DatabaseResource.java
```java
package com.ravi.auto_closing;

public class DatabaseResourse implements AutoCloseable
{
	@Override
	public void close() throws Exception
	{
		System.out.println("Database resourse Closed successfully");
	}

}

```

FileResourse.java
```java
package com.ravi.auto_closing;

import java.io.Closeable;
import java.io.IOException;

public class FileResourse implements Closeable
{
	@Override
	public void close() throws IOException
	{
		System.out.println("File resourse closed successfully");

	}

}

```

Main.java
```java
package com.ravi.auto_closing;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) throws Exception
	{
		FileResourse fr = new FileResourse();
		DatabaseResourse dr = new DatabaseResourse();

		try(dr; fr)
		{
		  System.out.println(10/0);
		}
		catch(ArithmeticException e)
		{
			System.err.println("Divide by zero problem");
		}

	}

}
```

```java
//Program to close Scanner class automatically using try with resourses

package com.ravi.auto_closing;

import java.util.InputMismatchException;
import java.util.Scanner;

public class TryWithResourses
{
	public static void main(String[] args)
	{
		var sc = new Scanner(System.in);

		try(sc)
		{
			System.out.print("Enter Player id :");
			int id = sc.nextInt();
			System.out.println("Player id is :"+id);
		}
		catch (InputMismatchException e)
		{
			System.err.println("Input is not in a proper format");
		}
		System.out.println("Program completed");
	}

}

```


> **Note :- Scanner class internally implementing Closeable interface so it is providing auto closing facility from java 1.7, as a user we need to pass the reference of Scanner class inside try with resources try()**


### Nested try block

If we write a try block inside another try block then it is called Nested try block.

```java
try  //Outer try
{
  statement1;
     try  //Inner try
     {
        statement2;
     }
     catch(Exception e) //Inner catch
     {
     }
}
catch(Exception e) //Outer Catch
{
}

```

The execution of inner try block depends upon outer try block that means if we have an exception in the Outer try block then inner try block will not be executed.
```java
package com.ravi.basic;

public class NestedTryBlock
{
	public static void main(String[] args)
	{
	      try  //outer try
	      {
	    	    String x = "null";
	    	    System.out.println("It's length is :"+x.length());

		    	  try  //inner try
		    	  {
		    		 String y = "NIT";
		    		 int z = Integer.parseInt(y);
		    		 System.out.println("z value is :"+z);
		    	  }
		    	  catch(NumberFormatException e)
		    	  {
		    		System.err.println("Number is not in a proper format");
		    	  }
	      }
	      catch(NullPointerException e)
	      {
	    	  System.err.println("Null pointer Problem");
	      }
	}
}
```


### Writing try-catch inside catch block

We can write try-catch inside catch block but this try-catch block will be exceuted if the catch block will executed that means if we have an exception in the try block.

```java
package com.ravi.basic;

import java.util.InputMismatchException;
import java.util.Scanner;

public class TryWithCatchInsideCatch
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);

		try(sc )
		{
			System.out.print("Enter your Roll number :");
			int roll = sc.nextInt();
			System.out.println("Your Roll is :"+roll);

		}
		catch(InputMismatchException e)
		{
			System.err.println("Provide Valid input!!");

```

try
```java
			{
				System.out.println(10/0);
			}
			catch(ArithmeticException e1)
			{
			  System.err.println("Divide by zero problem");
			}

		}
		finally
		{
```

try
```java
			{
				throw new ArrayIndexOutOfBoundsException("Array is out of bounds");
			}
			catch(ArrayIndexOutOfBoundsException e)
			{
				System.err.println("Array is out of Bounds");
			}
		}
	}

}
```

try-catch with return statement
If we write try-catch block inside a method and that method is returning some value then we should write return statement in both the places i.e inside the try block as well as inside the catch block.

We can also write return statement inside the finally block only, if the finally block is present. After this return statement we cannot write any kind of statement. (Unrechable)

Always finally block return statement having more priority then try-catch return statement.

```java
package com.ravi.return_try_catch;

public class ReturnWithTryCatch {

	public static void main(String[] args)
	{
		System.out.println(m1());

	}

	public static int m1()
	{
```

try
```java
		{

			return 10;
		}
		catch(Exception e)
		{
			return 20;
		}
	}

}

```

```java
package com.ravi.return_try_catch;

public class ReturnWithTryCatch1
{

	public static void main(String[] args)
	{
		System.out.println(m1());

	}

	public static int m1()
	{
```

try
```java
		{

			return 10;
		}
		catch(Exception e)
		{
			return 20;
		}
		finally
		{
			return 30;
		}

	}

}
```

```java
package com.ravi.return_try_catch;

public class ReturnWithTrycatch2 {

	public static void main(String[] args)
	{
		System.out.println(m1());

	}

	public static int m1()
	{
```

try
```java
		{

			return 10/0;
		}
		catch(Exception e)
		{
			return 20;
		}
	}

}
```


### Initialization of a variable in try and catch

A local variable must be initialized inside try block as well as catch block OR at the time of declaration.

If we initialize inside the try block only then from catch block we cannot access local variable value, Here initialization is compulsory inside catch block.

```java
package com.ravi.return_try_catch;

public class VariableInitialization {

	public static void main(String[] args)
	{
		int i;
```

try
```java
		{
			i = 300;
			System.out.println(i);
		}
		catch(Exception e)
		{
			i = 300;
			System.out.println(i);

		}
	}

}
```

**Difference between Checked Exception and Unchecked Exception :

### Checked Exception

In java some exceptions are very common exceptions are called Checked excption here compiler takes very much care and wanted the clarity regarding the exception by saying that, by using this code you may face some problem at runtime and you did not report me how would you handle this situation at runtime are called Checked exception, so provide either try-catch or declare the method as throws.

All the checked exceptions are directly sub class of java.lang.Exception

Eg:
FileNotFoundException, IOException, InterruptedException,ClassNotFoundException, SQLException, CloneNotSupportedException, EOFException and so on

Unchecked Exception :-
The exceptions which are rarely occurred in java and for these kinds of exception compiler does not take any care are called unchecked exception.

Unchecked exceptions are directly entertain by JVM because they are rarely occurred in java.

All the un-checked exceptions are sub class of RuntimeException

RuntimeException is also Unchecked Exception.

Eg:
ArithmeticException, ArrayIndexOutOfBoundsException, NullPointerException, NumberFormatException, ClassCastException, ArrayStoreException and so on.

### Some Bullet points regarding Checked and Unchecked


### Checked Exception

1) Common Exception
2) Compiler takes care (Will not compile the code)
3) Handling is compulsory (try-catch OR throws)
4) Directly the sub class of java.lang.Exception

Unchecked Exception :
1) Rare Exception
2) Comiler will not take any care
3) Handling is not Compulsory
4) Sub class of RuntimeException

## 28-06-2024


### When to provide try-catch or declare the method as throws

We should provide try-catch if we want to handle the exception by own as well as if we want to provide user-defined messages to the client but on the other hand we should declare the method as throws when we are not interested to handle the exception and try to send it to the JVM for handling purpose.


> **Note :- It is always better to use try catch so we can provide appropriate user defined messages to our client.**

*Why compiler takes very much care regarding the checked Exception ?
As we know Checked Exceptions are very common exception so in case of checked exception "handling is compulsory" because checked Exception depends upon other resources as shown below.

```java
IOException  (we are depending upon System Keyboard OR Files )
FileNotFoundException(We are depending upon the file)
InterruptedException (Thread related problem)
ClassNotFoundException (class related problem)
SQLException (SQL related or database related problem)
CloneNotSupportedException (Object is the resourse)
EOFException(We are depending upon the file)
```

* What is the difference between throw and throws :
```java
throw [THROWING THE EXCEPTION OBJCET EXPLICITLY.]
```

We should use throw keyword to throw the exception object explicitly, In case of try block, try block is responsible to create the exception object as well as throw the exception object to the nearest catch block
but if we want to throw exception object explicitly then we use throw
keyword.

```java
           throw new ArithmeticException();
	   throw new LowBalanceException();

```

after using throw keyword the control will transfer to the nearest catch block so after throw keyword statement, the remaining statements are un-reachable.

```java
throws :-
```

In case of checked Exception if a user is not interested to handle the exception and wants  to throw the exception to JVM, wants to skip from the current situation then we should declare the method as throws.
It is mainly used to work with Checked Exception.


### Types of exception in java


### Exception can be divided into two types


1) Predefined Exception OR Built-in Exception

2) Userdefined Exception OR Custom Exception

Predefined Exception :-
The Exceptions which are already defined by Java software people for some specific purposes are called predefined Exception or Built-in exception.
Ex :
IOException, ArithmeticException and so on

Userdefined Exception :-
The exceptions which are defined by user according to their own use and requirement are called User-defined Exception.

Ex:-
InvalidAgeException, GreaterMarksException

## How to develop User-defined Exceptions

As a developer we can develop user-defined checked and user-defined
unchecked exception.

If we want to develop checked exception then our user-defined class must extends from java.lang.Exception, on the other hand if we want to develop un-checked exception then our user-defined class must extends from java.lang.RuntimeException.

In the user-defined exception class we should write No argument constructor(in case if we don't want to pass any error message) and we should write parameterized constructor with String errorMessage as a parameter (in case if we  want to pass any error message) with super keyword.

In order to throw the exception object explicitly we should use throw
keyword as well as our user-defined class object must be of Throwable type.

```java
//Program to create user-defined checke exception :
```

```java
package com.ravi.user_defined_exception;

import java.util.Scanner;

@SuppressWarnings("serial")
class InvalidAgeException extends Exception
{
	public InvalidAgeException()
	{
	}

	public InvalidAgeException(String errorMessage)
	{
		super(errorMessage);
	}
}

public class CheckedExceptionDemo
{
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		try(sc)
		{
			System.out.print("Enter your Age :");
			int age = sc.nextInt();

			if(age < 18)
			{
				throw new InvalidAgeException("Age is Invalid");
			}
			else
			{
				System.out.println("Welcome to voting Application");
			}
		}
		catch(InvalidAgeException e)
		{
			System.err.println(e);
		}
		System.out.println("Main method completed");
	}

}
```


### Assignment


### create a user-defined exception which is unchecked exception


### Some important rules while working with Checked Exception

a) If the try block does not throw any checked exception then in the corresponding catch block we can't handle checked exception.It will generate compilation error i.e "exception never thrown from the corresponding try statement"

Example :-

```java
public class Test
{
	public static void main(String[] args)
	{
```

try
```java
		{
	          //try block is not throwing checked exception
		  //i.e. InterruptedException
		}
		catch (InterruptedException e) //error
		{
		}

	}

}

```


> **Note :- The above rule is not applicable for Unchecked Exception**


try
```java
		{

		}
		catch(ArithmeticException e)  //Valid
		{
			e.printStackTrace();
		}
```

b) If the try block does not throw any exception then in the corresponding catch block we can write Exception, Throwable because both are the super classes for all types of Exception whether it is checked or unchecked.

```java
package com.ravi.method_related_rule;

public class CatchingWithSuperClass
{
	public static void main(String[] args)
	{

```

try
```java
		{

		}
		catch(Exception e)  //Exception OR Throwable
		{
          e.printStackTrace();
		}

	}

}
```

c) At the time of method overriding if the super class method does
not reporting or throwing checked exception then the overridden method of sub class not allowed to throw checked exception otherwise it will generate compilation error but overridden method can throw Unchecked Exception.

```java
package com.ravi.method_related_rule;

class Super
{
	public void show()
	{
		System.out.println("Super class method not throwing checked Exception");
	}
}
class Sub extends Super
{
	@Override
	public void show() throws InterruptedException
	{
		System.out.println("Sub class method should not throw checked Exception");
	}
}

public class MethodOverridingWithChecked {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

	}

}
```

d) If the super class method declare with throws keyword to throw a checked exception, then at the time of method overriding, sub class method may or may not use throws keyword.
If the Overridden method is also using throws
keyword to throw checked exception then it must be either same exception class or sub class, it should not be super class as well as we can't add more exceptions in the overridden method.

```java
package com.ravi.method_related_rule;

import java.io.FileNotFoundException;
import java.io.IOException;

class Base
{
	public void show() throws FileNotFoundException
	{
		System.out.println("Super class method ");
	}
}
class Derived extends Base
{
	public void show() //throws IOException
	{
		System.out.println("Sub class method ");
	}
}

public class MethodOverridingWithThrows
{
	public static void main(String[] args)
	{
	  System.out.println("Overridden method may or may not throw checked exception but if it is throwing then must be same or sub class");
	}

}
```

e) Just like return keyword we can't use throw keyword inside static and non static block because all initializers must be executed normally.

We can use throw keyword in the protection of try-catch so the code will be executed normally.

```java
class ExceptionDemo
{

```

static
```java
	{
		throw new ArithmeticException();  //Invalid
	}

	public static void main(String[] args)
	{

	}
}

```

Note : Here code will not compile because it is abnormal termination
```java
class ExceptionDemo
{

```

static
```java
	{
```

try
```java
		{
			throw new ArithmeticException();
		}
		catch (ArithmeticException e)
		{
		}
	}

	public static void main(String[] args)
	{

	}
}

```

Here It is valid becuase it is normal termination.

## 29-06-2024


## Exception propagation

Whenever we call a method and if the the callee method contains any kind of exception and if callee method doesn't contain any kind of exception handling mechanism (try-catch) then JVM will propagate the exception to caller method for handling purpose. This is called Exception Propagation.

If the caller method also does not contain any exception handling mechanism then JVM will terminate the method from the stack frame hence the remaining part of the method(m1 method) will not be executed even if we handle the exception in another caller method like main.

If any of the the caller method does not contain any exception handling mechanism then exception will be handled by JVM, JVM has default exception handler which will provide the exception message and terminates the program abnormally. [29-JUN]
```java
package com.ravi.exception;

public class ExceptionPropagation
{
	public static void main(String[] args)
	{
		System.out.println("Main method started!!");
```

try
```java
		{
			m1();
		}
		catch(ArithmeticException e)
		{
			System.err.println("Handled in Main method");
		}
		System.out.println("Main method ended!!");
	}

	public static void m1()
	{
		System.out.println("M1 method started!!");
		m2();
		System.out.println("M1 method ended!!"); //This line not executed
	}

	public static void m2()
	{
		System.out.println(10/0);
	}
}

```

In the above program exception is handled by main method so m2 and m1 both the methods are terminated by JVM so the remaining part of m1() method will not be executed, even we handled the exception in main method.

### Handling Exception while calling a method ?

Whenever we are calling a method and if that method is throwing any checked Exception OR (Exception) by using throws keyword then at the time of calling caller method, It must be protected either by try-catch or declare the method as throws

MethodCalling.java
```java
package com.ravi.exception;

public class MethodCalling {

	public static void main(String[] args)
	{
		m1();  //error, try catch OR throws required
	}

	public static void m1() throws Exception
	{

	}

}
```

```java
package com.ravi.exception;

public class MethodCalling {

	public static void main(String[] args)
	{
		m1(); //Valid because method is throwing un-checkeed
	}

	public static void m1() throws NullPointerException
	{

	}

}
```

```java
package com.ravi.exception;

public class MethodCalling {

	public static void main(String[] args)
	{
```

try
```java
		{
			m1();
		}
		catch(InterruptedException e)
		{

		}
	}

	public static void m1() throws InterruptedException
	{

	}

}

```

Note : If method is throwing any checked excetion then caller must
required either the protection of try catch or we should
declare the method as throws

### Input Output in java

In order to perform input and output operation, Java software people
has provided a separate package called java.io.

By using this io package we can read the data from the source, can create a file, performing read and write operation with file and so on.

How to read the data from the client :
As we know, In order to read the data we are using Scanner class which is available from JDK 1.5 onwards.

Before java5, to read the data from end user, we are using the following two classes of java.io package

1) java.io.DataInputStream
2) java.io.BufferedReader

How to create the object for the above classes :

### DataInputStream

```java
DataInputStream din = new DataInputStream(System.in);


```

BufferedReader
```java
InputStreamReader isr = new InputStreamReader(System.in);
BufferedReader br = new BufferedReader(isr);

```

OR

```java
BufferedReader br = new BufferedReader(new InputStreamReader(System.in));

```

BufferedReader provides fast execution technique because Internally it uses buffer concept.

Methods available in the above classes :
1) public int read() : Used to read a single character from the source
The return type of this method is int because
it returns the UNICODE value of that character.
If the data is not available with source then
It will return -1 which represents EOF (End of
file)

2) public String readLine() : Used to read multiple characters or
complete line from the source, return type is String.

Note : readLine() method of DataInputStream class is deprecated.
```java
//Program to read name from the keyboard
import java.io.*;
public class ReadName
{
	public static void main(String[] args) throws IOException
	{
      DataInputStream din = new DataInputStream(System.in);
	  System.out.print("Enter your Name :");
      String name = din.readLine();
      System.out.print("Your Name is :"+name);
	}
}
```

```java
//Reading age from the keyboard
package com.ravi.io;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class ReadAge
{

	public static void main(String[] args)
	{
		var br = new BufferedReader(new InputStreamReader(System.in));
		try(br)
		{
			System.out.println("Enter your Age :");
			int age = Integer.parseInt(br.readLine());
			System.out.println("Your Age is :"+age);
		}
		catch(IOException e)
		{
			System.err.println("IOException encounter");
		}
		catch(NumberFormatException e)
		{
			System.err.println("Please provide your age in numebrs only");
		}

	}

}
```

```java
//Reading the salary from the keyboard

package com.ravi.io;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class ReadSalary {

	public static void main(String[] args)
	{
		var br = new BufferedReader(new InputStreamReader(System.in));
		try(br)
		{
			System.out.println("Enter your Salary :");
			double salary = Double.parseDouble(br.readLine());
			System.out.println("Your Salary is :"+salary);
		}
		catch(IOException e)
		{
			System.err.println("IOException encounter");
		}
		catch(NumberFormatException e)
		{
			System.err.println("Please provide your salary in numebrs only");
		}

	}

}
```

```java
//Reading the gender from keyboard :
```

```java
package com.ravi.io;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class ReadGender {

	public static void main(String[] args)
	{
		var br = new BufferedReader(new InputStreamReader(System.in));
		try(br)
		{
			System.out.print("Enter your Gender :");
			char gen = (char) br.read();
			System.out.println("Your Gender is :"+gen);

		}
		catch(IOException e)
		{
			System.err.println("IOException encounter");
		}

	}

}
```

```java
package com.ravi.io;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class ReadEmployeeData {

	public static void main(String[] args) throws IOException
	{
		var br = new BufferedReader(new InputStreamReader(System.in));

		System.out.print("Enter Employee Id :");
		int id = Integer.parseInt(br.readLine());

		System.out.print("Enter Employee Gender :");
		//char gender = (char) br.read();  //Buffer problem
		char gender = br.readLine().charAt(0);

		System.out.print("Enter Employee Name :");
		String name = br.readLine();

		System.out.println("Employee id is :"+id);
		System.out.println("Employee Gender is :"+gender);
		System.out.println("Employee Name is :"+name);
		br.close();

	}

}
```


## What is the need of File Handling ?

As we know variables are used to store some meaningful value in our program but once the execution of the program is over, now we can't get those values so to hold those values permanently in our memory we use files.

Files are stored in the secondary storage devices so, we can use/read the data stored in the file anytime according to our requirement.

In order to work with File system java software people has provided number of predefined classes like File, FileInputStream, FileOutputStream and so on. All these classes are available in java.io package. We can read and write the data in the form of Stream.

## 01-07-2024


## Streams in java

A Stream is nothing but flow of data or flow of characters to both the end.
Stream is divided into two categories

1) byte oriented Stream :-
It used to handle characters, images, audio and video file in binary format.

2) character oriented Stream :-
It is used to handle the data in the form of characters or text.

Now byte oriented or binary Stream can be categorized as "InputStream" and "OutputStream". input streams are used to read or receive the data where as output streams are used to write or send the data.

Again Character oriented Stream is divided into Reader and Writer. Reader is used to read() the data from the file where as Writer is used to write the data to the file.

All Streams are represented by classes in java.io package.

InputStream is the super class for all kind of input operation where as OutputStream is the super class for all kind of output Operation for byte oriented stream.

Where as Reader is the super class for all kind reading operation where as Writer is the super class for all kind of writing operation in character oriented Stream.

### File

File :
It is a predefined class in java.io package through which we can create file and directory. By using this class we can verify whether the file is existing or not.

```java
File f = new File("abc.txt");

```

The above statement will not create any file, It actually create the file object and perform one of the following two task.
a) If abc.txt does not exist, It will not create it
b) if abc.txt does exist, the new file object will be refer to the referenec variable f

Now if the file does not exist then to create the file and verify whether file is existing or not, we should use the following two methods :

1) public boolean exists() : Will verify whether file is existing or not and based on that, It will return true or false.

2) public boolean createNewFile() : Will Create a new file only if file is not available, if file is already available then return false.

File class has also a predefined method called getName(), to get the name of the file.
```java
import java.io.*;
public class File0
	{
		public static void main(String[] args)
		{
```

try
```java
				{
					File f = new File("C:\\new\\Batch33.txt");

                    if(f.exists())
					{
						System.out.println("File is existing");
					}
					else
					{
						System.out.println("File is not existing");
					}

					if (f.createNewFile())
					   {
						 System.out.println("File created: " + f.getName());
                       }
					   else
						{
                             System.out.println("File is already existing....");
                         }
                  }
				 catch (IOException e)
                 {
					System.err.println(e);
				}
		}
}
```


### Assignment

Create a folder/directory by using File class.
FileOutputStream  [Create a file (Override) + Write the binary data]
It is a predefined class available in java.io package.

It is used to create the file as well as write the data to the files.

It will override the existing file that means if file is already available then it will replace the file.

It is binary oriented Stream, so we can only write binary data to the
files or in other words our data must be available in binary format.

How to convert the String data into binary format :
```java
String class has provided a predefined method getBytes() through which we can convert String data into binary format.

     public byte[] getBytes();


```

Example :
```java
public class ConvertToBinary {

	public static void main(String[] args)
	{
		String str = "ABCDEF";

		byte[] b = str.getBytes();

		for(byte c : b)
		{
			System.out.println(c); //65 66 67 68..70
		}


	}

}
```

```java
//Creating and writing the data to the file

import java.io.*;
public class File1
{
     public static void main(String args[]) throws IOException
     {
		var fout = new FileOutputStream("C:\\new\\Hyderabad.txt");
        try(fout)
         {
         String s = "Hyd is a popular IT City in India ";
		 byte b[] = s.getBytes();

		 fout.write(b);


		 System.out.println("Success....");
		 }
		 catch(Exception e)
		 {
			 e.printStackTrace();
		 }
     }
}
```


### FileInputStream

It is a predefined class available in java.io package.

It is used to read the data from the file character by character using read() method.

If the data is not available in the file then read() method will return -1 which represents EOF.

It is binary stream.


> **Note :- If we want to write the data in the file then the data must be converted into byte, on the other hand if we want to print the data on the console then data must be available in binary format.**


```java
//Reading tha data from the file
import java.io.*;
public class File2
{
     public static void main(String s[]) throws IOException
     {
		var fin = new FileInputStream("C:\\new\\Hyderabad.txt");

		 try(fin)
		 {

             while(true)
			 {
				 int i = fin.read();
				 if(i==-1)
					 break;
				 System.out.print((char)i);
			 }

		 }
		 catch(Exception e)
		 {
			 System.out.println(e);
		 }
		 System.out.println();
     }
}
```

```java
//wap in java to read the data from one file and to write the data to another file.
import java.io.*;
public class File3
{
     public static void main(String s[]) throws IOException
     {
	    //Outside of try (Java 9 enhancement in try with resource)

	   var fin = new FileInputStream("File2.java");

	   var fout = new FileOutputStream("C:\\new\\f2.java");

	   try(fin; fout)
		 {
         while(true)
		 {
		     int i = fin.read();
			 if(i==-1) break;
			 System.out.print((char)i);
			 fout.write((byte)i);
		 }
		 }
		 catch(IOException e)
		 {
			 e.printStackTrace();
		 }
     }
}
```


### Limitation of FileInputStream class

FileInputStream class can read the data from single file only so It is not suitable for reading the data from two files at the same time, If we want to read the data from two files at the same time then we should use a separate stream called SequenceInputStream.

SequenceInputStream :
It is a predefined class available in java.io pacakge.

Using this class we can read the from two files at the same time.

SequenceInputStream sis = new SequenceInputStream(InputStream i1,
```java
                                                  InputStream i2);


//Proram to read the data from two files at the same time
import java.io.*;
public class File4
{
     public static void main(String args[]) throws IOException
     {
         var f1 = new FileInputStream("File1.java");
         var f2 = new FileInputStream("File2.java");

         var s = new SequenceInputStream(f1,f2);

		 try(f1; f2; s)
		 {
         int i;
         while(true)
		 {
			  i = s.read();
			   if(i==-1)
				  break;
			  System.out.print((char)i);
		 }
		 }
		 catch(IOException e)
		 {
			 e.printStackTrace();
		 }
     }
}
```

```java
//Reading the data from two files and writing the data to a single file
import java.io.*;
public class File5
{
	public static void main(String x[]) throws IOException
	{
		   var f1 = new FileInputStream("File3.java");
           var f2 = new FileInputStream("File4.java");

           var fout = new FileOutputStream("C:\\new\\FileData.txt");

           var s = new SequenceInputStream(f1,f2);

           int i;
		   try(f1; f2; fout; s)
		   {
           while(true)
           {
			   i = s.read();
			   if(i==-1)
				    break;
               System.out.print((char)i);
               fout.write((byte)i);
           }
		   }
		   catch(IOException e)
		   {
			   e.printStackTrace();
		   }
		   System.out.println("File Created Successfully");
     }
}
```


## 02-07-2024


### Limitation of FilOutputStream

By using FileOutputStream class we can write the data to a single file only. If we want to write the data to multiple files then we should
use a separate Stream called ByteArrayOutputStream class.

ByteArrayOutputStream :
It is a predefined class available in java.io package.

By using ByteArrayOutputStream class, We can write the data to multiple files, we have a method called writeTo() through which we can write the data to multiple files.

```java
//Program to write the data on multiple files.
import java.io.*;
public class File6
{
     public static void main(String args[]) throws IOException
     {
			var fin = new FileInputStream("File1.java");

			var f1 = new FileOutputStream("C:\\new\\a1.txt");
			var f2 = new FileOutputStream("C:\\new\\b1.txt");
			var f3 = new FileOutputStream("C:\\new\\c1.txt");

			var bout = new ByteArrayOutputStream();

			try(fin; f1; f2; f3; bout)
		    {
             int i;
			while((i = fin.read()) != -1)
            {
```

bout.write((byte)i); //writing tha data to ByteArrayOutputStream
```java
            }

           bout.writeTo(f1);
           bout.writeTo(f2);
		   bout.writeTo(f3);

```

bout.flush();  //clear the buffer for reusing of ByteArrayOutputStream
```java
           System.out.println("Success");
			}
			catch(IOException e)
		    {
				e.printStackTrace();
		    }
     }
}
```

```java
//Working with images
import java.io.*;
public class File7
{
	public static void main(String[] args) throws IOException
	{
		 var fin = new FileInputStream("C:\\new\\abc.jpg");

         var f1 = new FileOutputStream("C:\\new\\a1.jpg");
         var f2 = new FileOutputStream("C:\\new\\a2.jpg");
		 var f3 = new FileOutputStream("C:\\new\\a3.jpg");

         var bout = new ByteArrayOutputStream();

         try(fin; f1; f2; f3; bout)
		 {
         int i;
         while((i = fin.read()) != -1)
         {
               bout.write((byte)i);
         }

         bout.writeTo(f1);
         bout.writeTo(f2);
		 bout.writeTo(f3);
         System.out.println("success...");
		 bout.flush();
         }
		 catch(IOException e)
		{
			 e.printStackTrace();
		}
	}
}
```


### BufferedOutputStream

It is a predefined class available in java.io package.

Whenever we use the class FileOutputStream the data will be available on the Stream but not in the buffer so there may be chance of miss memory management, It is always preferable that we should perform read and write operation by using buffer.

By using this BufferedOutputStrean now the data is in the buffer so the execution will become more faster.

```java
//Program to put the data in the buffer for fast execution
import java.io.*;
class File8
{
      public static void main(String args[]) throws IOException
      {
        var fout = new FileOutputStream("C:\\new\\Hyderabad.txt");

           var bout = new BufferedOutputStream(fout);

		   try(fout ; bout)
		   {
           String s = "Hyderabad is a nice city";
           byte b[] = s.getBytes();
           bout.write(b);
		   System.out.print("success...");
		  }
		  catch(IOException e)
		  {
			  e.printStackTrace();
		  }
      }
}
```


### BufferedInputStream

It is a predefined class available in java.io package.

Whenever we use FileInputStream to read the data/content from the file the data will be available on the Stream but not in the buffer so there may be a chance of miss memory management so we should take the data into the buffer by using BufferedInputStream class so overall the execution will become faster.

```java
//BufferedInputStream
import java.io.*;
public class File9
{
      public static void main(String args[]) throws IOException
      {
           var fin = new FileInputStream("File1.java");
           var bin = new BufferedInputStream(fin);

		   try(fin ; bin)
		   {
           int i;
           while((i = bin.read()) != -1)
           {
                System.out.print((char)i);
           }
           }
		   catch(IOException e)
		  {
			   e.printStackTrace();
		  }
		  System.out.println();
      }
}
```


### Reading and Writing the primitive data to the files

It is possible to write the primitive data(byte,short,int, long, float, double, char and boolean) to the file.

In order to write primitive data to the file we should use a predefined class available in java.io package called DataOutputStream.

```java
var fos = new FileOutputStream("data.txt");
var dos = new DataOutputStream(fos);

```

now by using this  we can write primitive data to the file.

It provides various methods like writeByte(), writeShort(), writeInt() and so on to write the primitive data to the file.

If we want to read the primitive data from the file we can use a predefined class available in java.io package called DataInputStream, this class provides various methods like readByte(), readShort(), readInt() and so on.

```java
var fin = new FileInputStream("data.txt");
var dis = new DataInputStream(fin);

```


> **Note :- For writing String into a file we have writeBytes() and to read the String data from the file we have readLine() method.**


[DataInputStream class readLine() method is deprecated now, so compilation warning]


> **Note :- The writing and reading format of primitive data should be**

same format otherwise we will get wrong format data.
```java
//DataOutputStream and DataInputStream
import java.io.*;
public class File10
{
      public static void main(String args[]) throws IOException
      {
		  var fout = new FileOutputStream("C:\\new\\Primitive.txt");
          var dout = new DataOutputStream(fout);

		  try(fout ; dout)
		  {
          dout.writeBoolean(true);
          dout.writeChar('A');
          dout.writeByte(Byte.MAX_VALUE);
          dout.writeShort(Short.MAX_VALUE);
          dout.writeInt(Integer.MAX_VALUE);
          dout.writeLong(Long.MAX_VALUE);
          dout.writeFloat(Float.MAX_VALUE);
```

dout.writeDouble(Math.PI);//PI is a final static variable
```java
		  dout.writeBytes("Hello India...");
```

dout.flush();//For reuse purpose
```java
          }
		  catch(IOException e)
		  {
			  e.printStackTrace();
		  }

		  System.out.println("Reading the Primitive data from the file!!!");

		  var fin = new FileInputStream("C:\\new\\Primitive.txt");
          var din = new DataInputStream(fin);

		  try(fin ; din)
		  {
          boolean f = din.readBoolean();
          char c = din.readChar();
          byte b = din.readByte();
          short s = din.readShort();
          int i = din.readInt();
          long l = din.readLong();
          float ft = din.readFloat();
          double d = din.readDouble();
		   String x =  din.readLine();//for reading String (deprecated)

          System.out.println(f +"\n"+c+"\n"+b+"\n"+s+"\n"+i+"\n"+l+"\n"+ft+"\n"+d+"\n"+x);
		  }
		  catch(IOException e)
		  {
			  e.printStackTrace();
		  }

      }
}
```

*** Serialization and De-serialization :
** Serialization and De-serialization :
It is a technique through which we can store the object data in a file. Storing the object data into a file is called Serialization on the other hand Reading the object data from a file is called De-serialization.

In order to perform serialization, a class must implements Serializable interfcae, predefined marker interface in java.io package.

Java.io package has also provided a predfined class called ObjectOutputStream to perform serialization i.e writing Object data to a file using writeObject() method.

```java
public void writeObject(Object obj)


```

where as ObjectInputStream is also a predefined class available in java.io package through which we can read the Object data from a file using readObject(). The return type of readObject() is Object.

```java
public Object readObject()


```

While reading the object data from the file, if the object is not available in the file then it will throw checked execption java.io.EOFException. (End of file Exception). It is a checked
Exception.

3 files :
Employee.java
```java
package com.ravi.serialization_deserialization;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.io.Serializable;

public class Employee implements Serializable
{
	private Integer employeeId;
	private String employeeName;
	private Double employeeSalary;

	public Employee(Integer employeeId, String employeeName, Double employeeSalary) {
		super();
		this.employeeId = employeeId;
		this.employeeName = employeeName;
		this.employeeSalary = employeeSalary;
	}

	public static Employee getEmployeeObject() throws Exception, IOException
	{
		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		System.out.print("Enter Employee Id :");
		Integer id = Integer.parseInt(br.readLine());

		System.out.print("Enter Employee Name :");
		String name = br.readLine();

		System.out.print("Enter Employee Salary :");
		Double salary = Double.parseDouble(br.readLine());

		return new Employee(id, name, salary);

	}


	@Override
	public String toString() {
		return "Employee [employeeId=" + employeeId + ", employeeName=" + employeeName + ", employeeSalary="
				+ employeeSalary + "]";
	}

}

```

SerializationDemo.java
```java
package com.ravi.serialization_deserialization;

import java.io.FileOutputStream;
import java.io.IOException;
import java.io.ObjectOutputStream;
import java.util.Scanner;

public class SerializationDemo {

	public static void main(String[] args) throws IOException
	{
		var fout = new FileOutputStream("C:\\new\\EmpData.txt");
		var oos = new ObjectOutputStream(fout);
		Scanner sc = new Scanner(System.in);

		try(fout; oos; sc)
		{
			System.out.print("How many object u want to write :");
			int noOfObj = sc.nextInt();

			for(int i=1; i<=noOfObj; i++)
			{
				Employee emp = Employee.getEmployeeObject();
				oos.writeObject(emp);
			}

		}
		catch(Exception e)
		{
			e.printStackTrace();
		}

	    System.out.println("Employee data stored Successfully");
	}

}

```

DeSerializationDemo.java
```java
package com.ravi.serialization_deserialization;

import java.io.EOFException;
import java.io.FileInputStream;
import java.io.IOException;
import java.io.ObjectInputStream;

public class DeSerializationDemo {

	public static void main(String[] args) throws IOException, ClassNotFoundException
	{
		var fin = new FileInputStream("C:\\new\\EmpData.txt");
		var ois = new ObjectInputStream(fin);

		Employee e1 = null;

		try(fin ;ois)
		{

			while((e1 = (Employee) ois.readObject())!=null)
			{
				System.out.println(e1);
			}

		}
		catch(EOFException e)
		{
			System.err.println("End of file has reached");
		}


	}

}
```


## 03-07-2024


### transient keyword in java

While performing serialization operation, If we don't want to serialize any particular field then we should declare that field with transient
keyword.
Decalring transient keyword on a particular field will not serailzed that field and we will get default value.

3 files :
Product.java
```java
package com.ravi.ser_deser;

import java.io.Serializable;
import java.time.LocalDate;
import java.util.Scanner;

public class Product implements Serializable
{
	private transient int productId;
	private String productName;
	private transient double productPrice;
	private LocalDate manufactureDate;

	public Product(int productId, String productName, double productPrice, LocalDate manufactureDate) {
		super();
		this.productId = productId;
		this.productName = productName;
		this.productPrice = productPrice;
		this.manufactureDate = manufactureDate;
	}

	public static Product getProductObject()
	{
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter Product Id :");
		int pid = sc.nextInt();

		System.out.print("Enter Product Name :");
		String pname = sc.nextLine();
		pname = sc.nextLine();


		System.out.print("Enter Product Price :");
		double price = sc.nextDouble();

		LocalDate date = LocalDate.now();

		return new Product(pid, pname, price, date);
	}

	@Override
	public String toString() {
		return "Product [productId=" + productId + ", productName=" + productName + ", productPrice=" + productPrice
				+ ", manufactureDate=" + manufactureDate + "]";
	}


}

```

Serialization.java
```java
package com.ravi.ser_deser;

import java.io.FileOutputStream;
import java.io.IOException;
import java.io.ObjectOutputStream;
import java.util.Scanner;

public class Serialization {

	public static void main(String[] args) throws IOException
	{
		var fos = new FileOutputStream("C:\\new\\Product.txt");
		var oos = new ObjectOutputStream(fos);
		var sc = new Scanner(System.in);

		try(fos; oos; sc)
		{
		  System.out.print("How many Objects u want to write ");
		  int no = sc.nextInt();

		  for(int i=1; i<=no; i++)
		  {
			  Product productObject = Product.getProductObject();
			  oos.writeObject(productObject);
		  }


		}
		catch(Exception e)
		{
			e.printStackTrace();
		}

		System.out.println("Product Object stored Successfully");



	}

}

```

DeSerialization.java
```java
package com.ravi.ser_deser;

import java.io.EOFException;
import java.io.FileInputStream;
import java.io.IOException;
import java.io.ObjectInputStream;

public class Deserialization {

	public static void main(String[] args) throws IOException, ClassNotFoundException
	{
		var fin = new FileInputStream("C:\\new\\Product.txt");
		var ois = new ObjectInputStream(fin);

		Product prod = null;

		try(fin; ois)
		{
			while((prod = (Product)ois.readObject())!=null)
			{
				System.out.println(prod);
			}
		}
        catch(EOFException e)
		{
        	System.out.println("File is ended");
		}
	}

}

```

Note : Here we have declared productId and productPrice with transient
keyword so we will get default value for productId and
productPrice

### Working With Character Oriented Stream

In order to work with character oriented Stream, if we two super classes Reader and Writer.

Both are abstract classes and Reader is the super class for all types of reading operation, on the other hand Writer is the super class for all types of writing operation.

Here we can directly work with characters.

FileWriter class :
It is a predefined class available in java.io package,By using this class we can create a file and write character data to the file.

By using this class we can directly write String (collection of characters) Or character array to the file.

Actually It is a character oriented Stream where as if we work with FileOutputStream class, It is byte oriented Stream.

```java
//FileWriter
import java.io.*;
public class File11
{
    public static void main(String args[]) throws IOException
    {
         var fw = new FileWriter("C:\\new\\HelloIndia.txt");
		 var bw = new  BufferedWriter(fw);

		 try(fw; bw)
		 {
         bw.write("India, It is in Asia");
         System.out.println("Success....");
		 }
		 catch(IOException e)
		  {
			  e.printStackTrace();
		  }
    }
}
```

```java
//FileWriter
import java.io.*;
class File12
{
    public static void main(String args[]) throws IOException
    {
		var fw = new FileWriter("C:\\new\\Data.txt");
		var bw = new  BufferedWriter(fw);

        try(fw;bw)
		{
		 char c[ ] =  {'H','E','L','L','O', ' ',' ','W','O','R','L','D'};

         bw.write(c);
         System.out.println("Success....");
		}
		catch(Exception e)
		{
			e.printStackTrace();
		}
    }
}
```


### FileReader class

It is a predefined class available in java.io package, It is a character oriented Stream. The main purpose of this class to read the data in the character format directly from the file.

```java
//FileReader
import java.io.*;
public class File13
{
    public static void main(String args[]) throws IOException
    {
```

var fr = new FileReader(args[0]); //Command Line Arg
```java
		 var br = new BufferedReader(fr);

		 try(fr ; br)
		 {
         while(true)
         {
              int i = br.read();
              if(i == -1)
                   break;
              System.out.print((char)i);
         }
		 }
		 catch(IOException e)
		 {
			  e.printStackTrace();
		 }
    }
}
```

```java
import java.io.*;
public class File14
{
  public static void main(String[] args) throws IOException
	{
       var fr = new FileReader("C:\\new\\abc.jpg");
	   var  fw = new FileWriter("C:\\new\\NIT.jpg");

		try(fr;fw)
		{
		     int i;
		    while((i=fr.read())!= -1)
			{
				fw.write(i);
			}
		}
		catch(Exception e)
		{
		}
		System.out.println("Success");
    }
}

```


> **Note :- In the above program the image file will not be created in a proper format because images are created by using binary data but FileReader and FileWriter can work with Character data.**


### PrintWriter

It is a predefined class avilable in java.io package under Writer abstracrt class.

It is used to write primitive data into the file in text format.

By using PrintWriter class we can create a file as well as write the primitive data into text format.

It contains a predfined non static method called printf() which accept two parameters
1) Formatted String
2) Actual Data.

```java
//PrintWriter
import java.io.*;
public class File15
{
  public static void main(String[] args) throws IOException
	{
	  PrintWriter writeData = new PrintWriter("C:\\new\\Roll.txt");

     try(writeData)
	 {
      int roll = 15;
      //Writing primitive data into text format
      writeData.printf("My roll number is : %d ", roll);
    }
    catch(Exception e)
	{
      e.printStackTrace();
    }
  }
}
```


### How to append the data in the existing file

```java
import java.io.FileWriter;
import java.io.BufferedWriter;
import java.io.IOException;

public class File16
{
    public static void main(String[] args) throws IOException
	{
        var filename = "C:\\new\\append.txt";
		//wants to write the data in the existing file
		var fileWriter = new FileWriter(filename, true);

        var bufferedWriter = new BufferedWriter(fileWriter);

        try(fileWriter;bufferedWriter)
		{

            // Append text to the file
            String textToAppend = "My Name is Raj";
            bufferedWriter.write(textToAppend);

			//Moving the cursor to the next line
            bufferedWriter.newLine();

            textToAppend = "I lives in hyderabad";
            bufferedWriter.write(textToAppend);


            System.out.println("Text appended successfully to the file.");
        }
		catch (IOException e)
		{
            System.out.println("An error occurred while appending the text to the file: " + e.getMessage());
        }
    }
}

```

Note : FileWriter and FileOutputStream class takes 2nd parameter is
```java
       boolean append in the constructor so we can append the text in
```

the existing file.

## 04-07-2024


### enum in java

An enum is class in java that is used to represent group of universal constants. It is introduced from JDK 1.5 onwards.

In order to craete an enum, we should use enum keyword and all the univarsal constants of the enum must be separeted by comma. Semicolon is optional at the end.

Example:-

```java
enum Color
{
```

RED, BLUE, BLACK, PINK     //public + static + final

```java
 }

```

The enum constants are by default public, static and final.

An enum we can define inside the class, outside of the class and even inside of the method.

If we define an enum inside the class then we can apply public, private, protected and static.

Every enum in java extends java.lang.Enum class so an enum can implement many interfaces but can't extends a class.

By deafult every enum is implicitly final so we can't inherit an enum.

In order to get the constant value of an enum we can use values() method which returns enum array, but this method is added by compiler to each and every enum at the time of compilation.

In order to get the order position of enum constants we can use ordinal() method which is given inside the enum class and the return type of this method is int. The order position of enum constant will start from 0.

As we know an enum is just like a class so we can define any method, constructor inside an enum. Constructor must be either private or default.

*All the enum constants are by default object of type enum.

Enum constants must be decalred at the first line of enum otherwise we will get compilation error.

From java 1.5 onwards we can pass an enum in a switch statement.

In order to compare two enum constants we have final equals(Object obj)
method in the java.lang.Enum class which will compare two objects based on the memory reference same as == operator.

In the Enum class name() and ordinal() both are final method so we can't change the name and order position of an enum constant but Enum class has also provided toString() methof through which we can provide our own user-defined name by overriding toString() method in the enum constant.
```java
public class Test1
{
	public static void main(String[] args)
	{
		enum Month
		{
```

JANUARY, FEBRUARY,MARCH     //public + static + final
```java
		}

		System.out.println(Month.MARCH);
	}
}
```

```java
enum Month
{
```

JANUARY,FEBRUARY,MARCH
```java
}
public class Test2
{
	enum Color { RED,BLUE,BLACK }

    public static void main(String[] args)
	{
		enum Week {SUNDAY, MONDAY, TUESDAY }

		System.out.println(Month.FEBRUARY);
		System.out.println(Color.RED);
		System.out.println(Week.SUNDAY);
	}
}

```


> **Note :- From the above Program it is clear that we can define an enum inside a class, outside of a class and inside a method as well.**

```java
//Comapring the constant of an enum
public class Test3
{
	enum Color { RED,BLUE }

     public static void main(String args[])
     {
          Color c1 = Color.RED;
          Color c2 = Color.RED;

          if(c1 == c2)
          {
                System.out.println("==");
          }
          if(c1.equals(c2))
          {
                 System.out.println("equals");
          }
     }
}

```

Here == operator and equals(Object obj) method both will return true because equals(Object obj) method internally uses == operator only.
```java
public class Test4
{
	private enum Season   //private, public, protected, static
	{
	SPRING, SUMMER, WINTER, RAINY;
	}

	public static void main(String[] args)
	{
		System.out.println(Season.RAINY);
	}
}
```

```java
//Interview Question
class Hello
{
	int x = 100;
}

enum Direction extends Hello
{
```

EAST, WEST, NORTH, SOUTH
```java
}

class Test5
{
	public static void main(String[] args)
	{
		System.out.println(Direction.SOUTH);
	}
}

```

Note : Every enum by default extends from java.lang.Enum class so enum can't extend any other class.
```java
//All enums are by default final so can't inherit

enum Color
{
	RED, BLUE, PINK;
}
class Test6 extends Color
{
	public static void main(String[] args)
	{
		System.out.println(Color.RED);
	}
}

```

Note : Every enum is implicitly final so any class can't extend enum
```java
//values() to get all the values of enum

class Test7
{
	enum Season
	{
```

SPRING, SUMMER, WINTER, FALL, RAINY
```java
	}

	public static void main(String[] args)
	{
		Season [] values=  Season.values();

		 for(Season value : values)
		  System.out.println(value);
	}
}

values() static method is used to take all the enum values so the return type is enum array.
```

```java
//ordinal() to find out the order position
class Test8
{
	static enum Season
	{
```

SPRING, SUMMER, WINTER, FALL, RAINY
```java
	}


	public static void main(String[] args)
	{
		Season s1[] = Season.values();

		for(Season x : s1)
			System.out.println(x.name()+" order is :"+x.ordinal());
	}
}

```

Note : public int ordinal() method is used to find out the order
position.
```java
//We can take main () inside an enum

enum Test9
{
```

TEST1, TEST2, TEST3;  //Semicolon is compulsory

```java
	public static void main(String[] args)
	{
		System.out.println("Enum  main method");
	}
}
```

```java
//constant must be in first line of an enum

enum Test10
{

	public static void main(String[] args)
	{
		System.out.println("Enum  main method");
	}

    HR, SALESMAN, MANAGER;

}
```

```java
//Writing constructor in enum
enum Season
{
```

WINTER, SUMMER, SPRING, RAINY;   //All are object of type enum


```java
	private Season()
	{
		System.out.println("Constructor is executed....");
	}
}
class Test11
{
	public static void main(String[] args)
	{
		System.out.println(Season.WINTER);
		System.out.println(Season.SUMMER);

	}
}
```

```java
   //Writing constructor with message
   enum Season
	{
	   SPRING("Pleasant"), SUMMER("UnPleasent"), RAINY("Rain"), WINTER;

        String msg;

	    private Season(String msg)
		{
		  this.msg = msg;
		}

		private Season()
		{
			this.msg = "Cold";
		}

		public String getMessage()
		{
			return msg;
		}
	}
class Test12
{
	public static void main(String[] args)
	{
		Season s1[] = Season.values();

		for(Season x : s1)
			System.out.println(x+"  is :"+x.getMessage());
	}
}
```

```java
enum MyType
{
```

ONE
```java
{
	@Override
    public String toString()
	{
        return "this is one";
    }
},

```

TWO
```java
{
	@Override
    public String toString()
	{
        return "this is two";
    }
}
}
public class Test13
{
	public static void main(String[] args)
	{
		System.out.println(MyType.ONE); //Passing Object ref
		System.out.println(MyType.TWO); //Passing Object ref

	}
}
```

```java
public class Test14
{
	enum Day
		{
```

SUNDAY, MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY
```java
		}

public static void main(String args[])
{
	Day day  = Day.MONDAY;

	switch(day)
	{
	 case SUNDAY:
	 System.out.println("Sunday");
	 break;
	 case MONDAY:
	 System.out.println("Monday");
	 break;
```

default:
```java
	 System.out.println("other day");
    }

  }
}
```

```java
enum Shape
{
    CIRCLE, SQUARE, TRIANGLE;

```

static
```java
	{
        System.out.println("static block ");
    }

    {
        System.out.println("instance block");
    }

    private Shape()
	{
		System.out.println("Constructor");
	}


}
public class Test15
{
  public static void main(String[] args)
	{
	  System.out.println(Shape.CIRCLE);
	}
}

```


> **Note :- Inside an enum static block will be executed after the constructor body execution because the first priority goes to static variable and when static variables are initializing with original value, repective constructors are executed.**


## Nested classes in java

In java it is possible to define a class (inner class) inside another class (outer class) called nested class.

In the same way, It is also possible to define a class/interface/enum/
annotation/record inside another class/interface/enum/annotation and record as shown below.

Demo1.java
```java
package com.ravi.basic;

public class Demo1
{
	class MyClass
	{
	}

```

record MyRecord()
```java
	{
	}

	interface MyInterface
	{
	}

	enum MyEnum
	{
	}

	@interface MyAnnotation
	{
	}

}

```

Demo2.java
```java
package com.ravi.basic;

public record Demo2()
{
  class MyClass
  {

  }
```

record MyRecord()
```java
  {

  }
  interface MyInterface
	{
	}

	enum MyEnum
	{
	}

	@interface MyAnnotation
	{
	}
}

```

Demo3.java
```java
package com.ravi.basic;

public interface Demo3
{
	class MyClass
	  {

	  }
```

record MyRecord()
```java
	  {

	  }
	  interface MyInterface
		{
		}

		enum MyEnum
		{
		}

		@interface MyAnnotation
		{
		}
}

```

Demo4.java
```java
package com.ravi.basic;

public enum Demo4
{
	A,B,C;

	class MyClass
	  {

	  }
```

record MyRecord()
```java
	  {

	  }
	  interface MyInterface
		{
		}

		enum MyEnum
		{
		}

		@interface MyAnnotation
		{
		}
}

```

Demo5.java
```java
package com.ravi.basic;

public @interface Demo5
{
	class MyClass
	  {

	  }
```

record MyRecord()
```java
	  {

	  }
	  interface MyInterface
		{
		}

		enum MyEnum
		{
		}

		@interface MyAnnotation
		{
		}
}


```

Inner classes in Java create a strong encapsulation and  HAS-A  relationship between the inner class and its outer class.

An inner class, .class file will be represented by $ symbol.

Advantages of inner class :
1) It is a way of logically grouping classes that are only used in one place.

2) It is used to achieve strong encapsulation.

3) It enhance the readability and maintainability of the code.

Types of Inner classes in java :

### There are 4 types of inner classes in java


1) Non Static Nested class OR Regular class
2) Static Nested class
3) Method / Method local class
4) Anonymous inner class

Non static Nested class :
If a non static class declared inside the another class but outside of the method then it is called non static nested class.

We can apply private, default, protected, public, abstract and final modifiers on non static nested class.

With the help of outer class we can load inner class also, If inner class contains non static member then object is required for Outer class as well as inner class.

Inner class we can't represent directly, we need to take the support of Outer class because inner class is a non static member of Outer class.

It is also known as Regular OR Mebmer class.
```java
class Outer
{
	private int a = 15;

	class Inner
	{
		public void displayValue()
		{
			System.out.println("Value of a is " + a);
		}
	}
}
public class Test1
{
	public static void main(String... args)
	{
		Outer out = new Outer();

		Outer.Inner in = out.new Inner();

		in.displayValue();

	}
}

```

Note : An inner class can directly access the private data of Outer class.
```java
class MyOuter
{
      private int x = 7;
      public void makeInner()
      {
            MyInner in = new MyInner();
			System.out.println("Inner y is "+in.y);
            in.seeOuter();
      }

      class MyInner
      {
		    private int y = 15;
            public void seeOuter()
            {
                  System.out.println("Outer x is "+x);
            }
      }
}
public class Test2
{
      public static void main(String args[])
      {
            MyOuter m = new MyOuter();
            m.makeInner();
      }
}
```


## Variable Shadow in Nested class

If outer class and inner class variable name then inner class variable will be access with inner class object (Variable Shadow bacause in the same scope), If we want to access Outer class object from inner class then we need ClassName.this.variableName.

```java
class Outer
{
	private int x = 100;

	public class Inner
	{
		private int x = 200;  //variable Shadow

        public void access()
		{
			System.out.println("Outer class :"+Outer.this.x);
			System.out.println("Inner class "+this.x);
		}

	}


}

public class Demo
{

	public static void main(String[] args)
	{
	   new Outer().new Inner().access();
	}
}
```

```java
class MyOuter
{
      private int x = 15;
      class MyInner
      {
            public void seeOuter()
            {
                  System.out.println("Outer x is "+x);
            }
      }
}
public class Test3
{
      public static void main(String args[])
      {
		  //Creating inner class object in a single line
           MyOuter.MyInner m = new MyOuter().new MyInner();
			m.seeOuter();
      }
}
```

```java
class MyOuter
{
      static int x = 7;
	  class MyInner
      {
            public static void seeOuter()  //MyInner.seeOuter();
            {
                  System.out.println("Outer x is "+x);
            }
      }
}

public class Test4
{
      public static void main(String args[])
      {
          MyOuter.MyInner.seeOuter();
      }
}
```

```java
class Car
{
    private String make;
    private String model;
    private Engine engine;

   public Car(String make, String model, int horsePower)
   {
        this.make = make;
        this.model = model;
        this.engine = new Engine(horsePower);
    }

   //Inner class
   private class Engine
   {
      private int horsePower;

       public Engine(int horsePower)
	   {
            this.horsePower = horsePower;
        }

        public void start()
		{
            System.out.println("Engine started! Horsepower: " + horsePower);
        }

        public void stop()
	    {
            System.out.println("Engine stopped.");
        }
    }

    public void startCar()
	{
        System.out.println("Starting " + make + " " + model);
        this.engine.start();
    }

    public void stopCar()
	{
        System.out.println("Stopping " + make + " " + model);
        this.engine.stop();
    }
}
public class Test5
{

    public static void main(String[] args) {

        Car myCar = new Car("Swift", "Desire", 1200);

        myCar.startCar();

        myCar.stopCar();
    }
}
```

```java
class Laptop
{
    private String brand;
    private String model;
    private Motherboard motherboard;

    public Laptop(String brand, String model, String motherboardModel, String chipset)
	{
        this.brand = brand;
        this.model = model;
        this.motherboard = new Motherboard(motherboardModel, chipset);
    }


    public void switchOn()
	{
        System.out.println("Turning on " + brand + " " + model);
        this.motherboard.boot();
    }

   //Motherboard inner class
   public class Motherboard
   {
        private String model;
        private String chipset;


        public Motherboard(String model, String chipset)
		{
            this.model = model;
            this.chipset = chipset;
        }


        public void boot()
		{
            System.out.println("Booting " + brand + " " + model + " with " + chipset + " chipset");
        }
    }
}
public class Test6
{
    public static void main(String[] args)
	{

        Laptop laptop = new Laptop("HP", "ENVY", "IRIS", "Intel");

        laptop.switchOn();
    }
}
```

```java
class Person
{
    private String name;
    private int age;
    private Heart heart;

    public Person(String name, int age)
	{
        this.name = name;
        this.age = age;
        this.heart = new Heart();
    }

    public void describe()
	{
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Heart beats per minute: " + this.heart.getBeatsPerMinute());
    }

    // Inner class representing the Heart
    private class Heart
	{
        private int beatsPerMinute;

        public Heart()
		{
            this.beatsPerMinute = 72;
        }

        public int getBeatsPerMinute()
		{
            return this.beatsPerMinute;
        }

        public void setBeatsPerMinute(int beatsPerMinute)
		{
            this.beatsPerMinute = beatsPerMinute;
        }
    }
}
public class Test7
{
    public static void main(String[] args)
	{
        Person person = new Person("Virat", 30);
        person.describe();
    }
}
```

```java
class University
{
    private String name;

    public University(String name)
	{
        this.name = name;
    }

    public void displayUniversityName()
	{
        System.out.println("University Name: " + name);
    }

    public class Department
	{
        private String name;
        private String headOfDepartment;

        public Department(String name, String headOfDepartment)
		{
            this.name = name;
            this.headOfDepartment = headOfDepartment;
        }

        // Method to display department details
        public void displayDepartmentDetails()
		{
			displayUniversityName();
            System.out.println("Department Name: " + name);
            System.out.println("Head of Department: " + headOfDepartment);

        }
    }
}
public class Test8
{
    public static void main(String[] args)
	{

        University university = new University("JNTU");

       University.Department cs = university.new Department("Computer Science", "Dr. John");

        University.Department ee = university.new Department("Electrical Engineering", "Dr. Scott");


        cs.displayDepartmentDetails();
        ee.displayDepartmentDetails();
    }
}
```

```java
class OuterClass
{
	private int x = 200;

	class InnerClass
	{
		public void display()  //Inner class display method
		{
		System.out.println("Inner class display method");
		}

		public void getValue()
		{
			display();
			System.out.println("Can access outer private var :"+x);
		}
	}

		public void display()  //Outer class display method
		{
			System.out.println("Outer class display");
		}
}
public class Test9
{
	public static void main(String [] args)
	{
		OuterClass.InnerClass inobj = new OuterClass().new InnerClass();
		inobj.getValue();

		new OuterClass().display();

	}
}
```

```java
class OuterClass
{
	int x;
	public class InnerClass  //private, def, prot, public, abstract and final
	{
		int x;
	}
}
public class Test10
{
}

```

Note : In a non static nested inner class we can apply private, default. protected, public, abstract and final modifiers.

## 08-07-2024


### Static nested inner class

If we decalre a static class inside another class then it is called Static nested inner class.

For static nested inner class, Outer class object is not required.

If static nested inner class contains only static memebr then inner class object is also not required.

If static nested inner class contains non static member then inner class object is required.

We cann't access non static member of Outer class from static nested inner class [Static context].
```java
//static nested inner class
class BigOuter
{
     static class Nest   //static nested inner class
     {
          void go()  //Instance method of static inner class
          {
               System.out.println("Hello welcome to static nested class");
          }
     }
}
class Test11
{
      public static void main(String args[])
      {
          BigOuter.Nest n = new BigOuter.Nest();
          n.go();


      }
}
```

```java
package com.ravi.static_nested_demo;

class Outer
{
    static int x = 200;
```

static
```java
	{
		System.out.println("Outer class static block");
	}

	static class Inner
	{
```

static
```java
		{
			System.out.println("Inner class static block");
		}

		public static void m1()
		{
			System.out.println("Inner class Static Method :"+x);
		}
	}
}

public class StaticNestedDemo
{
	public static void main(String[] args)
	{
		Outer.Inner.m1();
	}

}

```

Here We are accessing inner class static method from main method so, first of all inner class static block will be executed and from inner class static method, we are accessing Outer class static variable so Outer class will be loaded and static block will be executed.
```java
class Outer
{
	  static int x = 15;

	  static class Inner
	  {
			    void msg()
				{
					System.out.println("x value is  "+x);
				}
	  }
}
class Test12
{
	public static void main(String args[])
	{
		Outer.Inner obj=new Outer.Inner();
		obj.msg();
	}
}
```

```java
class Outer
{
	  static int x = 25;

	  static class Inner
	  {
			static void msg()
				{
					System.out.println("x value is  "+x);
				}
	  }
}
class Test13
{
	public static void main(String args[])
	{
		Outer.Inner.msg();
	}
}
```

```java
class Outer
{
	  int x=15;  //error (not possible because try to access instance variable)
	  static class Inner
	  {
			void msg()
				{
					System.out.println("x value is  "+x);
				}
	  }
}
class Test14
{
	public static void main(String args[])
	{
		Outer.Inner obj=new Outer.Inner();
		obj.msg();
	}
}
```


### Local OR Method Local inner class

If we declare a class inside a method with name then it is called
Local OR Method local inner class.

The Scope of this method local inner class within the same stack frame
only so we can't use local inner class outside of the method.

It is used to perform some opertion within the method only.

We can't apply any kind of access modifier on method local inner class except final and abstract.
```java
//program on method local inner class
class MyOuter3
{
      private String x = "Outer class private data";

      public void doSttuff()
      {
           String z = "local variable";

           class MyInner  //Only final and abstract applicable
           {
                 public void seeOuter()
                 {
                      System.out.println("Outer x is "+x);
                      System.out.println("Local variable z is : "+z);
                 }
           }
		  MyInner mi = new MyInner();
            mi.seeOuter();

      }

}
public class Test15
{
      public static void main(String args[])
      {
            MyOuter3 m = new MyOuter3();
            m.doSttuff();
      }
}
```

```java
package com.ravi.static_nested_demo;

class MyOuter
{
	private int x = 100;

	public void accept()
	{
		class Inner
		{
			private int x = 200;

			public void show()
			{
				System.out.println("Inner class x variable :"+this.x);
				System.out.println("Outer class x variable :"+MyOuter.this.x);
			}
		}

		new Inner().show();
	}

}


public class Test16 {

	public static void main(String[] args)
	{
		new MyOuter().accept();

	}

}
```

```java
package com.ravi.static_nested_demo;

class MyOuter
{

	public void accept()
	{
		int x = 100;  //local variable
		class Inner
		{
			private int x = 200;

			public void show()
			{
				System.out.println("Y value is "+ x);
				System.out.println("x value is :"+this.x);
			}
		}

		new Inner().show();
	}

}


public class Test16 {

	public static void main(String[] args)
	{
		new MyOuter().accept();

	}

}
```

```java
package com.ravi.static_nested_demo;

class MyOuter
{

	public void accept()
	{
		class Inner
		{
			public void show()
			{

			}
		}

	}
	Inner i = new Inner();

}


public class Test16 {

	public static void main(String[] args)
	{
		new MyOuter().accept();

	}

}

```

Note : Local inner class we can use from same method only

### Anonymous inner class

If we define class inside a method body without any name then it is called anonymous inner class.

The main purpose of anonymous inner class to extend a class or implement an ineterface that means creating sub type of a class or interface.

Anonymous inner class object will be created at the time of declaration the class body.

Anonymous inner class is used to create singleton object because for 1 anonymous inner class only 1 object will be created.


A normal concrete class can extend only one class as well as implement many number of interfacs but an anoymous inner class can either extend only one class OR can implement only one interaface only.

Inside an anonymous inner class we can write static , non static variable, static block and non-static block. Here we can't write abstract method and constructor.
```java
//Anonymous inner class
class Tech
{
       public void tech()
       {
	      System.out.println("Tech");
       }
}
public class Test17
{
       public static void main(String... args)
       {

```

Tech a = new Tech()  //Anonymous inner class
```java
			{

				    @Override
					public void tech()
					{
						 System.out.println("anonymous tech");
					}

			};
			a.tech();
       }
}
```

```java
@FunctionalInterface
interface Vehicle
{
	void move();  //SAM(Single Abstract Method)
}

class Test18
{
	public static void main(String[] args)
	{
```

Vehicle car = new Vehicle()
```java
		{
			@Override
			public void move()
			{
				System.out.println("Moving with Car...");
			}
		};
		car.move();

```

Vehicle bike = new Vehicle()
```java
		{
			@Override
			public void move()
			{
				System.out.println("Moving with Bike...");
			}
		};
		bike.move();
	}
}
```

```java
package com.ravi.static_nested_demo;

class MyOuter
{
	void m1()
	{

	}

}


public class Test16 {

	public static void main(String[] args)
	{
```

MyOuter m = new MyOuter()
```java
		{
			{
				System.out.println("Instance block");
			}

```

static
```java
			{
				System.out.println("static block");
			}


			void m1()
			{
				System.out.println("M1");
			}


		};

		m.m1();

	}

}
```


## 09-07-2024


### Multithreading



### Uniprocessing

In uniprocessing, only one process can occupy the memory So the
major drawbacks are

1) Memory is westage
2) Resources are westage
3) Cpu is idle

To avoid the above said problem, multitasking is introduced.

In multitasking multiple task can concurrently work with CPU so, our task will be completed as soon as possible.

Multitasking is further divided into two categories.

a) Process based Multitasking
b) Thread based Multitasking


Process based Multitasking :
If a CPU is switching from one subtask(Thread) of one process to
another subtask of another process then it is called Process based Multitasking.


## Thread based Multitasking

If a CPU is switching from one subtask(Thread) to another subtask within the same process then it is called Thread based Multitasking.


## Thread

A thread is light weight process and it is the basic unit of CPU which can run concurrently with another thread within the same context (process).

It is well known for independent execution. The main purpose of multithreading to boost the execution sequence.

A thread can run with another thread at the same time so our task will be completed as soon as possible.

In java whenever we define main method then JVM internally creates a thread called main thread.

Program that describes that main is a Thread :
Whenever we define main method then JVM will create main thread internally under main group, the purpose of this main thread to execute the entire main method.

In java there is a predefined class called Thread available in java.lang package, this class contains a predefined static method currentThread() which will provide currently executing Thread.


## Thread t = Thread.currentThread(); //Factory Method



## Thread class has provided predefined method getName() to get the name of the Thread.


```java
package com.ravi.thread;

public class ThreadDemo
{
	public static void main(String[] args)
	{
```


## Thread t = Thread.currentThread();

```java
         System.out.println("Current Thread name is :"+t.getName());

                   //OR

         String name = Thread.currentThread().getName();
         System.out.println("Name of the current thread is :"+name);
	}

}
```


### How to create user-defined thread ?

We can create user-defined thread by using the following two packages

1) By using java.lang package
2) By using java.util.concurrent package

Creating user-defind Thread by using java.lang package :

### By using java.lang package we can create user-defined thread by using anyone of the following two approaches


1) By extending java.lang.Thread class
2) By implementing java.lang.Runnable interface


> **Note :- Thread is a predefined class available in java.lang package where as Runnable is a predefined interface available in java.lang Package.**


## 10-07-2024


### How to create user thread by using extending Thread class approach

```java
package com.ravi.multi_threading;

class MyThread extends Thread
{
   @Override
   public void run()
   {
	   System.out.println("Child Thread is running!!!");
   }
}

public class UserThreadDemo
{
	public static void main(String[] args)
	{
		System.out.println("Main Thread started....");
		MyThread mt = new MyThread();
		mt.start();
		System.out.println("Main Thread ended.....");
	}

}

```

Here we have two threads, main thread which is responsible to execute
main method and Thread-0 thread which is responsible to execute run()
method. [10-JULY-24]

In entire Multithreading start() is the only method which is responsible to create a new thread.
```java
public synchronized void start() :
```


### start() is a predefined non static method of Thread class which internally performs the following two tasks


1) It will make a request to the O.S to assign a new thread for concurrent execution.

2) It will implicitly call run() method.
```java
public boolean isAlive() :-
```


### It is a predefined non static method of Thread class through which we can find out whether a thread has started or not ?


As we know a new thread is created/started after calling start() method so if we use isAlive() method before start() method, it will return false but if the same isAlive() method if we invoke after the start() method, it will return true.

We can't restart a thread in java if we try to restart then It will generate an exception i.e java.lang.IllegalThreadStateException
```java
package com.ravi.basic;

class Foo extends Thread
{
	@Override
	public void run()
	{
		System.out.println("Child thread is running...");
		System.out.println("It is running with separate stack");
	}
}
public class IsAlive
{
	public static void main(String[] args)
	{
		System.out.println("Main Thread is started..");
		Foo f = new Foo();
        System.out.println("Thread has not started yet so :"+f.isAlive());

```

f.start(); //new Thread has created

```java
		System.out.println("Thread has started  so :"+f.isAlive());
```

f.start();   //java.lang.IllegalThreadStateException

```java
    }
}
```

```java
package com.ravi.basic;

class Stuff extends Thread
{
	@Override
	public void run()
	{
		System.out.println("Child Thread is Running!!!!");
	}
}
public class ExceptionDemo
{
	public static void main(String[] args)
	{
		System.out.println("Main Thread Started");

		Stuff s1 = new Stuff();
		Stuff s2 = new Stuff();


		s1.start();
		s2.start();

		System.out.println(10/0);

		System.out.println("Main Thread Ended");
	}

}

```


> **Note :- Here main thread is interrupted due to AE but still child thread will be executed because child thread is executing with separate Stack**

```java
package com.ravi.basic;

class Sample extends Thread
{
	@Override
	public void run()
	{
		String name = Thread.currentThread().getName();

		for(int i=1; i<=10; i++)
		{
		System.out.println("i value is :"+i+" by "+name+" thread");
		}
	}
}

public class ThreadLoop
{
	public static void main(String[] args)
	{
		new Sample().start();

        String name = Thread.currentThread().getName();

		for(int i=1; i<=10; i++)
		{
		System.out.println("i value is :"+i+" by "+name+" thread");
		}

		int x = 1;
```

do
```java
		{
			System.out.println("India");
			x++;
		}
		while(x<=10);

	}
}

```

Note : Here processor is frequently switching from main thread to Thread-0 thread so output is un-predicatable

### How to set and get the name of the Thread

Whenever we create a userdefined Thread in java then by default JVM assigns the name of thread is Thread-0, Thread-1, Thread-2 and so on.

If a user wants to assign some user defined name of the Thread, then Thread class has provided a predefined method called setName(String name) to set the name of the Thread.

On the other hand we want to get the name of the Thread then Thread class has provided a predefined method called getName().

```java
public final void setName(String name)  //setter

public final String getName()  //getter
```

```java
package com.ravi.basic;
class DoStuff extends Thread
{
	@Override
	public void run()
	{
		String name = Thread.currentThread().getName();
		System.out.println(name +" thread is running Here!!!!");
	}
}
public class ThreadName
{
	public static void main(String[] args)
	{
		DoStuff t1 = new DoStuff();
		DoStuff t2 = new DoStuff();


		t1.start();
		t2.start();

	System.out.println(Thread.currentThread().getName()+" thread is running.....");
	}
}


```


> **Note :- If we don't provide our user-defined name for the thread then by default the name would be Thread-0, Thread-1, Thread-2 and so on.**

```java
package com.ravi.basic;
class Demo extends Thread
{
	@Override
	public void run()
	{
		System.out.println(Thread.currentThread().getName()+" thread is running.....");
	}
}
public class ThreadName1
{
	public static void main(String[] args)
	{
```


## Thread t =  Thread.currentThread();

t.setName("Parent"); //Changing the name of the main thread

```java
	   Demo d1 = new Demo();
	   Demo d2 = new Demo();

	   d1.setName("Child1");
	   d2.setName("Child2");

	   d1.start();  d2.start();

	   String name = Thread.currentThread().getName();
	   System.out.println(name + " Thread is running Here..");
	}
}

```

In the above program we have assigned user-defined name to the Thread so it will take the name given by the user.

## 11-07-2024


## Thread.sleep(long millisecond)

If we want to put a thread into temporarly waiting state then we should use sleep() method.

The waiting time of the Thread depends upon the time specified by the user in millisecond as parameter to sleep() method.

It is a static method of Thread class.


## Thread.sleep(1000); //Thread will wait for 1 second



It is throwing a checked Exception i.e InterruptedException because there may be chance that this sleeping thread may be interrupted by a thread so provide either try-catch or declare the method
as throws.
```java
package com.ravi.basic;

class Sleep extends Thread
{
   @Override
   public void run()
   {
	   for(int i=1; i<=10; i++)
	   {
		   System.out.println("i value is :"+i);
```

try
```java
		   {
```


## Thread.sleep(1000);

```java
		   }
		   catch(InterruptedException e)
		   {
			   System.err.println(e);
		   }
	   }
   }

}
public class SleepDemo
{
	public static void main(String[] args)
	{
		Sleep s = new Sleep();
		s.start();

	}
}
```

```java
package com.ravi.basic;

class MyTest extends Thread
{
	@Override
	public void run()
	{
```


## Thread thread = Thread.currentThread();

```java
		System.out.println("Child Id is "+thread.getId());

		for(int i=1; i<=5; i++) //11    22    33     44   55
		{
			System.out.println("i value is :"+i);
```

try
```java
			{
```


## Thread.sleep(1000);

```java
			}
			catch(InterruptedException e)
			{
				System.err.println("Thread has Interrupted");
			}
		}
	}
}
public class SleepDemo1
{
	public static void main(String[] args)
	{
```


## Thread thread = Thread.currentThread();

```java
		System.out.println("Id Of Main Thread "+thread.getId());

		MyTest m1 = new MyTest();
		MyTest m2 = new MyTest();

		m1.start();
		m2.start();




	}
}
```


### Assignment


## Thread.sleep(long millis, int nanos)


## Thread life cycle

As we know a thread is well known for Independent execution and it contains a life cycle which internally contains 5 states (Phases).

During the life cycle of a thread, It can pass from thses 5 states. At a time a thread can reside to only one state of the given 5 states.

1) NEW State (Born state)

2) RUNNABLE state (Ready to Run state) [Thread Pool]

3) RUNNING state

4) WAITING / BLOCKED state

5) EXIT/Dead state


## Thread life cycle

As we know a thread is well known for Independent execution and it contains a life cycle which internally contains 5 states (Phases).

During the life cycle of a thread, It can pass from thses 5 states. At a time a thread can reside to only one state of the given 5 states.

1) NEW State (Born state)

2) RUNNABLE state (Ready to Run state) [Thread Pool]

3) RUNNING state

4) WAITING / BLOCKED state

5) EXIT/Dead state


New State :-
Whenever we create a thread instance(Thread Object) a thread comes to new state OR born state. New state does not mean that the Thread has started yet only the object or instance of Thread has been created.

Runnable state :-
Whenever we call start() method on thread object, A thread moves to Runnable state i.e Ready to run state. Here Thread schedular is responsible to select/pick a particular Thread from Runnable state and sending that particular thread to Running state for execution.

Running state :-
If a thread is in Running state that means the thread is executing its own run() method.

From Running state a thread can move to waiting state either by an order of thread schedular or user has written some method(wait(), join() or sleep()) to put the thread into temporarly waiting state.

From Running state the Thread may also move to Runnable state directly, if user has written Thread.yield() method explicitly.

Waiting state :-
A thread is in waiting state means it is waiting for it's time period to complete. Once the time period will be completed then it will re-enter inside the Runnable state to complete its remaining task.

Dead or Exit :
Once a thread has successfully completed its run method then the thread will move to dead state. Please remember once a thread is dead we can't restart a thread in java.

### IQ :- If we write Thread.sleep(1000) then exactly after 1 sec the Thread will re-start?


Ans :- No, We can't say that the Thread will directly move from waiting state to Running state.

The Thread will definetly wait for 1 sec in the waiting mode and then again it will re-enter into Runnable state which is control by Thread Schedular so we can't say that the Thread will re-start just after 1 sec.

### Anonymous inner class with Thread class ?

As we know, In order to create a thread, Thread class must be super class so instead of making Thread class as a super class. We can use
Anonmumous inner class concept.

1) Anonymous inner class with reference variable :
```java
  package anonymous_demo_wth_reference;

public class AnonymousWithRef {

	public static void main(String[] args)
	{
```


## Thread t1 = new Thread()

```java
		{
		   @Override
		   public void run()
		   {
			   String name = Thread.currentThread().getName();
			   System.out.println("Thread name is :"+name);
		   }
		};

		t1.start();
		 String name = Thread.currentThread().getName();
		 System.out.println("Current Threda name is :"+name);
	}

}
```


### 2) Anonymous inner class without reference varible

```java
package anonymous_demo_wth_reference;

public class AnonymousWithoutRef {

	public static void main(String[] args)
	{
		new Thread()
		{
			 @Override
			   public void run()
			   {
				   String name = Thread.currentThread().getName();
				   System.out.println("Thread name is :"+name);
			   }
		}.start();

	}

}
```


## 12-07-2024


### join() method of Thread class

The main purpose of join() method to put the current thread into waiting state until the other thread finish its execution.

Here the currently executing thread stops its execution and the thread goes into the waiting state. The current thread remains in the wait state until the thread on which the join() method is invoked has achieved its dead state.

It also throws checked exception i.e InterruptedException so better to use try catch or declare the method as throws.

It is a non static method so we can call this method with the help of Thread object reference.
```java
package com.ravi.basic;

class Join extends Thread
{
	@Override
	public void run()
	{
		for(int i=1; i<=5; i++)
		{
			System.out.println("i value is :"+i);
```

try
```java
			{
```


## Thread.sleep(1000);

```java
			}
			catch(InterruptedException e)
			{
				e.printStackTrace();
			}
		}
	}
}

public class JoinDemo
{
	public static void main(String[] args) throws InterruptedException
	{
		System.out.println("Main Thread Started!!!!!");
		Join j1 = new Join();
		Join j2 = new Join();
		Join j3 = new Join();

		j1.start();

		j1.join();

		j2.start();
		j3.start();

		System.out.println("Main Thread Ended");
	}

}
```

```java
package com.ravi.basic;

class Alpha extends Thread
{
	@Override
	public void run()
	{
```


## Thread t = Thread.currentThread();

```java
		String name = t.getName();	//Alpha_Thread is current thread

		Beta b1 = new Beta();
		b1.setName("Beta_Thread");
        b1.start();
```

try
```java
        {
```

b1.join(); //Alpha thread is waiting 4 Beta Thread to complete

```java
			System.out.println("Alpha thread re-started");
		}
        catch (InterruptedException e)
        {
			e.printStackTrace();
		}

		for(int i=1; i<=10; i++)
		{
			System.out.println(i+" by "+name);
		}

	}
}

public class JoinDemo2
{
	public static void main(String[] args)
	{
		Alpha a1 = new Alpha();
		a1.setName("Alpha_Thread");
		a1.start();
	}
}

class Beta extends Thread
{
	@Override
	public void run()
	{
```


## Thread t = Thread.currentThread();

```java
		String name = t.getName();
		for(int i=1; i<=15; i++)
		{
			System.out.println(i+" by "+name);
```

try
```java
			{
```


## Thread.sleep(500);

```java
			}
			catch(InterruptedException e) {

			}
		}
		System.out.println("Beta Thread Ended");
	}
}
```

```java
package com.ravi.basic;

public class JoinDemo1
{
	public static void main(String[] args) throws InterruptedException
	{
		System.out.println("Main Thread Started");

```


## Thread t = Thread.currentThread();

```java
		String name = t.getName();

		for(int i=1; i<=10; i++)
		{
			System.out.println("i value is :"+i+" by "+name);
```


## Thread.sleep(500);

```java
		}
```

t.join();  //Main thread is waiting for main thread to complete
```java
                     //[Deadlock]

		System.out.println("Main Thread Ended");

	}

}
```

Here, It is a deadlock state because main thread is waiting for main thread to complete.

### Assignment


```java
join(long millis)
join(long millis, long nanos)
```


### Assigning target by Runnable interface

```java
package com.ravi.basic;

class Ravi implements Runnable
{
   @Override
   public void run()
   {
	   String name = Thread.currentThread().getName();
	   System.out.println(name+" thread is running Here");
   }
}
public class RunnableDemo
{
   public static void main(String [] args)
   {
	   System.out.println("Main Thread is Running");

	   Ravi r1 = new Ravi();

```


## Thread thread = new Thread(r1,"Child1");


## thread.start();



```java
   }
}
```


## 13-07-2024


### How to assign the target for different Threads

```java
package com.ravi.runnable_demo;

class RegularBatch implements Runnable
{
	@Override
	public void run()
	{
		System.out.println("Regular Batch is going on");
	}

}
class PlacementBatch implements Runnable
{
	@Override
	public void run()
	{
		System.out.println("Placement Batch is going on");
	}
}

public class RunnableTarget {

	public static void main(String[] args) throws InterruptedException
	{
```


## Thread t1 = new Thread(new PlacementBatch());

```java
		t1.start();


```


## Thread t2 = new Thread(new RegularBatch());

```java
		t2.start();


	}

}
```


## Thread class constructor

We have total 9 constructors in the Thread class, The following are commonly used constructor in the Thread class

```java
1) Thread t1 = new Thread();

2) Thread t2 = new Thread(String name);

3) Thread t3 = new Thread(Runnable target);

4) Thread t4 = new Thread(Runnable target, String name);

5) Thread t5 = new Thread(ThredGroup tg, String name);

6) Thread t6 = new Thread(ThredGroup tg, Runnable target);

7) Thread t7 = new Thread(ThredGroup tg, Runnable target, String name);
```


### Case 1

Anonymous inner class by using Runnable interface :
```java
package com.ravi.runnable_demo;

public class AnonymousRunnable {

	public static void main(String[] args)
	{
```

Runnable r1 = new Runnable()
```java
		{
			@Override
			public void run()
			{
				String name = Thread.currentThread().getName();
				System.out.println("Current thread name is :"+name);
			}

		};
```


## Thread t1 = new Thread(r1);

```java
		t1.start();

	}

}
```


### Case 2

Anonymous inner class as a parameter to Thread Constructor :
```java
package com.ravi.runnable_demo;

public class AnonymousToThreadConstructor
{
	public static void main(String[] args)
	{
		 new Thread(new Runnable()
				{
				  @Override
				  public void run()
				  {
				String name = Thread.currentThread().getName();
			System.out.println("Current thread name is :"+name);
				  }

				},"Child1").start();

	}

}



```


### Case 3

Runnable interface by using Lambda :
```java
package com.ravi.runnable_demo;

public class LambdaByRunnable
{
	public static void main(String[] args)
	{
```

Runnable r1 = ()->
```java
		{
			String name = Thread.currentThread().getName();
			System.out.println("Current thread name is :"+name);
		};

		new Thread(r1).start();
	}

}
```


### Case 4

```java
package com.ravi.runnable_demo;

public class AnonymousToThreadConstructor
{
	public static void main(String[] args)
	{
		 new Thread(()-> System.out.println(Thread.currentThread().getName()),"Child1").start();

	}

}
```


### Program to assign different task to different Thread

```java
package com.ravi.runnable_demo;

class GetCube
{
	public void getCubeOfTheNumber(int num)
	{
		System.out.println("Cube of the number is :"+(num*num*num));
	}
}


public class GettingCubeByMultipleThreads
{
	public static void main(String[] args)
	{
		GetCube cube = new GetCube();

		new Thread()
		{
			@Override
			public void run()
			{
				cube.getCubeOfTheNumber(5);
			}

		}.start();

		new Thread()
		{
			@Override
			public void run()
			{
				cube.getCubeOfTheNumber(9);
			}

		}.start();
	}

}
```


### IQ

In between extends Thread and implements Runnable which one is better and why?

In between extends Thread and implements Runnable, implements Runnable is more better approach due to the following reasons.

1) In extend Thread class approach, We can't extend any other class further
(Multiple Inheritance not possible by using class) but we can implement multiple interfaces. On the other hand in implements Runnable approach we can extend a class as well as implement multiple interfaces.

2) In extends Thread class all the Thread class properties are available to
sub class so sub class is heavy weight, the same thing is not available
```java
   while implementing Runnable interface.

```

3) In extends Thread class approach we have same target for different

## Threads but by using implements we can provide different target for

different Threads.

4) In extends Thread class approach we don't have Lambda expression support
but by using Runnable interface we can implement Lambda.

Conclusion :
Implements Runnable Advantage
1) extend a single class
2) Light weight
3) Assigning different targets (Loose coupling)
3) Implemnting Lambda

### Drawback of Multithreading

Multithreading is very good to complete our task as soon as possible but in some situation, It provides some wrong data or wrong result.

In Data Race or Race condition, all the threads try to access the resource at the same time so the result will be corrupted.

In multithreading if we want to perform read operation and data is not updatable then multithreading is good but if the data is updatable data (modifiable data) then multithreading may produce some wrong result or wrong data as shown in the diagram.(13-JULY)
```java
package com.ravi.mt;

class Customer implements Runnable
{
   private int availableSeat = 1;
   private int wantedSeat;

   public Customer(int wantedSeat)
   {
	   this.wantedSeat = wantedSeat;
   }

	@Override
	public  void run()
	{
		String name = null;

		if(availableSeat >= wantedSeat)
		{
			name = Thread.currentThread().getName();
			System.out.println(wantedSeat+" seat is reserved for "+name);
			availableSeat = availableSeat - wantedSeat;

		}
		else
		{
			name = Thread.currentThread().getName();
			System.err.println("Sorry!!"+name+" seat is not available");
		}


	}

}


public class RailwayReservation
{
	public static void main(String[] args) throws InterruptedException
	{
		Customer cust = new Customer(1);

```


## Thread t1 = new Thread(cust,"Virat");


## Thread t2 = new Thread(cust,"Rohit");


```java
		t1.start(); t2.start();

	}

}

```

Here both the Threads will get the ticket
```java
package com.ravi.mt;

class Customer
{
	private double currentbalance = 20000;
	private double withdrawAmount;

	public Customer(double withdrawAmount)
	{
		super();
		this.withdrawAmount = withdrawAmount;
	}

	public void withrawAmount()
	{
		String name = null;
		if(currentbalance >= withdrawAmount)
		{
			name = Thread.currentThread().getName();
			System.out.println(withdrawAmount+ " amount withdraw by "+name);
			this.currentbalance = this.currentbalance - withdrawAmount;
		}
		else
		{
			name = Thread.currentThread().getName();
			System.err.println("Sorry " +name+" U have insufficient bal");
		}
	}




}

public class BankingApplication
{
	public static void main(String[] args)
	{
		Customer c1 = new Customer(20000);

		Runnable r1 = ()-> c1.withrawAmount();

```


## Thread t1 = new Thread(r1,"Person1");


## Thread t2 = new Thread(r1,"Person2");


```java
		t1.start(); t2.start();

	}

}

```

Here both the threads are getting the balance.

## 15-07-2024

**Synchronization :
In order to solve the problem of multithreading java software people has introduced synchronization concept.

In order to acheive synchronization in java we have a keyword called "synchronized".

It is a technique through which we can control multiple threads but accepting only one thread at all the time.

Synchronization allows only one thread to enter inside the synchronized area for a single object.

Synchronization can be divided into two categories :-

1) Method level synchronization

2) Block level synchronization

1) Method level synchronization :-
In method level synchronization, the entire method gets synchronized so all the thread will wait at method level and only one thread will enter inside the synchronized area as shown in the diagram.(15-JUL-24)
2) Block level synchronization
In block level synchronization the entire method does not get synchronized, only the part of the method gets synchronized so all the thread will enter inside the method but only one thread will enter inside the synchronized block as shown in the diagram (15-JUL-24)


> **Note :- In between method level synchronization and block level synchronization, block level synchronization is more preferable because all the threads can enter inside the method so only the PART OF THE METHOD GETS synchronized so only one thread will enter inside the synchronized block.**


### How synchronization logic controls multiple threads ?

Every Object has a lock(monitor) in java environment and this lock can be given to only one Thread at a time.

Actually this lock is available with each individual object provided by Object class.

The thread who acquires the lock from the object will enter inside the synchronized area, it will complete its task without any disturbance because at a time there will be only one thread inside the synchronized area(for single Object). *This is known as Thread-safety in java.

The thread which is inside the synchronized area, after completion of its task while going back will release the lock so the other threads (which are waiting outside for the lock) will get a chance to enter inside the synchronized area by again taking the lock from the object and submitting it to the synchronization mechanism.
This is how synchronization mechanism controls multiple Threads.


> **Note :- Synchronization logic can be done by senior programmers in the real time industry because due to poor synchronization there may be chance of getting deadlock.**



```java
//Program on Method Level Synchronization :
```

MethodLevelSynchronization.java
```java
package com.ravi.multi_threaing;

class Table
{
	public synchronized void printTable(int num)
	{
		for(int i=1; i<=10; i++)
		{
			System.out.println(num +" X "+i+" = "+(num*i));
```

try
```java
			{
```


## Thread.sleep(1000);

```java
			}
			catch(InterruptedException e)
			{
				e.printStackTrace();
			}
		}
		System.out.println("...............");
	}
}


public class MethodLevelSynchronization {

	public static void main(String[] args)
	{
```

Table obj = new Table();  //lock is created

```java
		Runnable r1 = ()-> obj.printTable(5);
		Runnable r2 = ()-> obj.printTable(10);

```


## Thread t1 = new Thread(r1);


## Thread t2 = new Thread(r2);


```java
		t1.start(); t2.start();

	}

}
```

```java
//Program on Block Level Synchronization :
```

```java
package com.ravi.advanced;

//Block level synchronization

class ThreadName
{
	public void printThreadName()
	{
	  String name = Thread.currentThread().getName();
	  System.out.println("Thread inside the method is :"+name);

		   synchronized(this)  //synchronized Block
		   {
			for(int i=1; i<=9; i++)
			{
				System.out.println("i value is :"+i+" by :"+name);
			}
			System.out.println(".............................");
		   }
	}
}
public class BlockSynchronization
{
	public static void main(String[] args)
	{
```


## ThreadName obj1 = new ThreadName(); //lock is created


```java
		Runnable r1 = () -> obj1.printThreadName();

```


## Thread t1 = new Thread(r1,"Child1");


## Thread t2 = new Thread(r1,"Child2");

```java
		t1.start(); t2.start();
	}
}
```


### Limitation/Drawback of Object Level Synchronization

From the given diagram it is clear that there is no interference between t1 and t2 thread because they are passing throgh Object1 where as on the other hand there is no interferenec even in between t3 and t4 threads because they are also passing through Object2 (another object).

But there may be chance that with t1 Thread, t3 or t4 thread can enter inside the synchronized area at the same time, simillarly it is also possible that with t2 thread, t3 or t4 thread can enter inside the synchronized area so the conclusion is, synchronization mechanism does not work with multiple Objects.(Diagram 15-JULY-24)
```java
package com.ravi.advanced;
class PrintTable
{
	    public synchronized void printTable(int n)
	    {
	       for(int i=1; i<=10; i++)
	       {
	    	   System.out.println(n+" X "+i+" = "+(n*i));
```

try
```java
	    	   {
```


## Thread.sleep(500);

```java
	    	   }
	    	   catch(Exception e)
	    	   {
	    	   }
	       }
	       System.out.println(".......................");
	    }
}

public class ProblemWithObjectLevelSynchronization
{
	public static void main(String[] args)
	{
```

PrintTable pt1 = new PrintTable(); //lock1
PrintTable pt2 = new PrintTable(); //lock2


## Thread t1 = new Thread()  //Anonymous inner class concept

```java
				{
			       @Override
			       public void run()
			       {
```

pt1.printTable(2);	//lock1
```java
			       }
				};

```


## Thread t2 = new Thread()

```java
				{
			       @Override
			       public void run()
			       {
```

pt1.printTable(3);	//lock1
```java
			       }
				};

```


## Thread t3 = new Thread()

```java
				{
			       @Override
			       public void run()
			       {
```

pt2.printTable(8);	//lock2
```java
			       }
				};

```


## Thread t4 = new Thread()

```java
				{
			       @Override
			       public void run()
			       {
```

pt2.printTable(9); //lock2
```java
			       }
				};
				 t1.start();	t2.start();	 t3.start();  t4.start();
	}
}

```

Note : From the above program, It is clear that even our method is synchronized but due to multiple locks (multiple object) we are getting
concurrncy.
In order to avoid the drawback of Object level synchronization, static synchronization is introduced.

Static Synchronization :
If we make our synchronized method as a static method then it is called
```java
static synchronization.

```

Here, To call static synchronized method, object is not required.

The thread will take the lock from class but not object because we can call the static method with the help of class name.

Unlike Object, we cann't create multiple classes in the same package.
```java
package com.ravi.advanced;
class MyTable
{
	 public static synchronized void printTable(int n)  //static synchronization
	    {
	       for(int i=1; i<=10; i++)
	       {
```

try
```java
	    	   {
```


## Thread.sleep(100);

```java
	    	   }
	    	   catch(InterruptedException e)
	    	   {
	    		  System.err.println("Thread is Interrupted...");
	    	   }
	    	   System.out.println(n+" X "+i+" = "+(n*i));
	       }
	       System.out.println("------------------------");
	    }
}
public class StaticSynchronization
{
	public static void main(String[] args)
	{
```


## Thread t1 = new Thread()

```java
					{
				      @Override
				      public void run()
				      {
				    	 MyTable.printTable(5);
				      }
					};

```


## Thread t2 = new Thread()

```java
					{
				      @Override
				      public void run()
				      {
				    	  MyTable.printTable(10);
				      }
					};

					Runnable r3 = ()-> MyTable.printTable(15);
```


## Thread t3 = new Thread(r3);


```java
					t1.start();
					t2.start();	t3.start();

		}
}
```


## 16-07-2024


## Thread Priority

It is possible in java to assign priority to a Thread. Thread class has provided two predefined methods setPriority(int newPriority) and getPriority() to set and get the priority of the thread respectively.

In java we can set the priority of the Thread in numbers from 1- 10 only where 1 is the minimum priority and 10 is the maximum priority.

Whenever we create a thread in java by default its priority would be 5 that is normal priority.

The user-defined thread created as a part of main thread will acquire the same priority of main Thread.


## Thread class has also provided 3 final static variables which are as follows



## Thread.MIN_PRIORITY  :- 01



## Thread.NORM_PRIORITY : 05



## Thread.MAX_PRIORITY  :- 10



> **Note :- We can't set the priority of the Thread beyond the limit(1-10) so if we set the priority beyond the limit (1 to 10) then it will generate an exception java.lang.IllegalArgumentException.**

Program describes that Child thread created as a part of main thread
will get the same Priority because the child thread is created as a
part of main thread.

```java
package com.ravi.thread_priority;

public class PriorityDemo1
{
	public static void main(String[] args)
	{
```


## Thread t = Thread.currentThread();

```java
		System.out.println("Main Thread priority is :"+t.getPriority());

```


## Thread t1 = new Thread();

```java
		System.out.println("Child Thread priority is :"+t1.getPriority());

	}

}
```

```java
package com.ravi.thread_priority;


public class PriorityDemo2
{
	public static void main(String[] args)
	{
```


## Thread t = Thread.currentThread();

```java
		t.setPriority(Thread.MIN_PRIORITY);
		System.out.println("Main Thread Priority is :"+t.getPriority());

		new Thread(()-> System.out.println("Child Thread Priority is :"+Thread.currentThread().getPriority())).start();


	}

}

```

Note : From the above program it is clear that child thread created as a part of main thread will acquire main thread priority.
```java
package com.ravi.thread_priority;

public class PriorityDemo3 {

	public static void main(String[] args)
	{
```


## Thread t = Thread.currentThread();

t.setPriority(11); //java.lang.IllegelArgumentException
```java
		System.out.println(t.getPriority());

	}

}
```

```java
package com.ravi.thread_priority;

class Priority
{
	public void accept()
	{
		int count =0;
		for(int i=1; i<=100000; i++)
		{
			count++;
		}

		System.out.println("After completion name of the Thread is :"+Thread.currentThread().getName());
		System.out.println("After completion Priority of the Thread is :"+Thread.currentThread().getPriority());
	}
}


public class PriorityDemo4 {

	public static void main(String[] args)
	{
		Priority p = new Priority();

		Runnable r1 = ()-> p.accept();

```


## Thread t1 = new Thread(r1,"LastThread");

```java
		t1.setPriority(Thread.MIN_PRIORITY);

```


## Thread t2 = new Thread(r1,"FirstThread");

```java
		t2.setPriority(Thread.MAX_PRIORITY);

		t1.start(); t2.start();

	}

}

```

Most of time the thread having highest priority will complete its task but we can't say that it will always complete its task first.

## Thread.yield()

It is a static method of Thread class.

It will send a notification to thread schedular to stop the currently executing Thread (In Running state) and provide a chance to Threads which are in Runnable state to enter inside the running state having same priority or higher priority. Here The running Thread will directly move from Running state to Runnable state.

The Thread schedular can ignore this notification message given by currently executing Thread.

Here there is no guarantee that  after using yield() method the running Thread will move to Runnable state and from Runnable state the thread can move to Running state.[That is the reason yield() method is throwing InterruptedExecption]

If the thread which is in runnable state is having low priority then the current executing thread in Running state, will continue its execution.

It is mainly used to avoid the over-utilisation a CPU by the current Thread.
```java
class Test implements Runnable
{
	@Override
	public void run()
	{
		for(int i=1; i<=10; i++)
		{
			String name = Thread.currentThread().getName();

			System.out.println("i value is :"+i+" by thread :"+name);

			if(name.equals("Child1"))
			{
```


## Thread.yield();  //Give a chance to Child2 Thread

```java
			}

		}
   }
}
public class ThreadYieldMethod
{
	public static void main(String[] args)
	{
		Test obj = new Test();

```


## Thread t1 = new Thread(obj, "Child1");


## Thread t2 = new Thread(obj, "Child2");


```java
		t1.start();  t2.start();
	}
}

```

Note : By using yield() we can make a request to thread schedular to avoid over utilisation of CPU by current Thread. ------------------------------------------------------------------------

## ThreadGroup

It is a predefined class available in java.lang Package.

By using ThreadGroup class we can put 'n' number of threads into a single group to perform some common operation.

By using ThreadGroup class constructor, we can assign the name of group
under which all the will be executed.


## ThreadGroup tg = new ThreadGroup(String groupName);



## ThreadGroup class has provided the following method


```java
public String getName() : To get the name of the Group

```

pubic int activeCounts() : How many thread are running under that
particular group.


## Thread class has provided constructor to put the thread into particular group.



## Thread t1 = new Thread(ThreadGroup tg, Runnable target, String name);


By using ThreadGroup class, multiple threads will be executed under
single group.
```java
package om.ravi.thread_group;

class JavaClass implements Runnable
{
	@Override
	public void run()
	{
		String name = Thread.currentThread().getName();
		for(int i=1; i<=3; i++)
		{
			System.out.println(i+" by "+name);
		}
	}

}

public class ThreadGroupDemo1
{

	public static void main(String[] args)
	{
```


## ThreadGroup tg = new ThreadGroup("Java_Group");



## Thread t1 = new Thread(tg, new JavaClass(), "Child 1" );


## Thread t2 = new Thread(tg, new JavaClass(), "Child 2" );

```java
		t1.start();
		t2.start();



		System.out.println("Thread group name is :"+tg.getName());
		System.out.println("Total threads which are Running in this group :"+tg.activeCount());

	}

}
```

```java
package om.ravi.thread_group;

public class ThreadGroupDemo2 {

	public static void main(String[] args)
	{
```


## Thread t = Thread.currentThread();

```java
		 System.out.println(t.toString());
	}

}

```

Output : Thread[main, 5, main]

Here first main is the name of the Thread, 5 is the priority and last main represents group name.

Whenever we define a main method then internally, main group is created and under this main group main thread is executed.
```java
package om.ravi.thread_group;

class TatkalTicket implements Runnable
{
	@Override
	public void run()
	{
		String name = Thread.currentThread().getName();
		System.out.println("Tatkal ticket booked by :"+name);

	}

}

class PremiumTatkal implements Runnable
{
	@Override
	public void run()
	{
		String name = Thread.currentThread().getName();
		System.out.println("Premium Tatkal ticket booked by :"+name);

	}
}

public class ThreadGroupDemo3
{
	public static void main(String[] args)
	{
```


## ThreadGroup tg1 = new ThreadGroup("Tatkal Ticket");


## ThreadGroup tg2 = new ThreadGroup("Premium Tatkal");



## Thread t1 = new Thread(tg1,new TatkalTicket(), "Scott");


## Thread t2 = new Thread(tg2,new PremiumTatkal(), "Smith");


```java
		t1.start(); t2.start();


	}

}
```

** Inter Thread Communication(ITC) :
It is a mechanism to communicate two synchronized threads within the context to achieve a particular task.

In ITC we put a thread into wait mode by using wait() method and other thread will complete its corresponding task, after completion of the task it will call notify() method so the waiting thread will get a notification to complete its remaining task.

ITC can be implemented by the following method of Object class.

1) public  final void wait() throws InterruptedException

2) public native final void notify()

3) public native final void notifyAll()


```java
public  final void wait() throws InterruptedException :-
```

It will put a thread into temporarly waiting state and it will release the lock.
It will wait till the another thread invokes notify() or notifyAll() method from the same object.

```java
public native final void notify() :-
```

It will wake up the single thread that is waiting on the same object.It will not release the lock immediatly, once synchronized area is completed then only it will release the lock.

```java
public native final void notifyAll() :-
```

It will wake up all the threads which are waiting on the same object.It will not release the lock immediatly, once synchronized area is completed then only it will release the lock.

*Note :- wait(), notify() and notifyAll() methods are defined in Object class but not in Thread class because these methods are related to lock(because we can use these methods from the synchronized area ONLY) and Object has a lock so, all these methods are defined inside Object class.

The following program explains, if we don't use these methods from synchronized are then we will get java.lang.IllegalMonitorStateException

```java
package com.ravi.inter_thread_communication;

public class Test
{
	public static void main(String[] args) throws InterruptedException
	{
		System.out.println("Wait Method");
		Object obj = new Object();
	    obj.wait();
	}

}
```

The following program explains, If we don't use co-ordination between two threads then we will get different output.

```java
package com.ravi.inter_thread_communication;

class ThreadA extends Thread
{
	int val = 0;

	@Override
	public void run()
	{
```

try
```java
		{
```


## Thread.sleep(200);

```java
		}
		catch(InterruptedException e)
		{
			e.printStackTrace();
		}

		for(int i=1; i<=10; i++)
		{
			val = val + i;  // 1   3    6     10     15
		}
	}
}

public class ITCProblem
{
	public static void main(String[] args) throws InterruptedException
	{
```


## ThreadA  a1 = new ThreadA();

```java
		a1.start();

```


## Thread.sleep(200);


```java
		System.out.println(a1.val);

	}

}

```

Here main thread is printing the value of val variable but var variable is frequently changing based on the loop iteration so may get some different output.
```java
package com.ravi.inter_thread_communication;

class SecondThread extends Thread
{
	int val = 0;

	@Override
	public void run()
	{
		synchronized(this)
		{
			for(int i=1; i<=100; i++)
			{
				val = val + i;
			}
			System.out.println("Sending notification");
			notify();

		}//Here actually the lock will be released
	}

}


public class ITCDemo1
{
	public static void main(String[] args) throws InterruptedException
	{
		System.out.println("Main Thread started!!");

		SecondThread b = new SecondThread();
		b.start();

		synchronized(b)
		{
			System.out.println("Main Thread is waiting Here");
			b.wait();
			System.out.println("Main Thread Wake up");
			System.out.println(b.val);

		}


	}

}

```

Here main thread will wait after releasing the lock so child thread will get the lock, complete the task and send the notification by using notify() method [Here notify() method will not relese the lock, the lock is available again for main thread after completing synchronized area of child thread], main thread will get the lock once again to complete its remaining task.
```java
package com.ravi.inter_thread_communication;

class Customer
{
	private double balance = 10000;

	public synchronized void withdraw(double amount)
	{
		System.out.println("Going To Withdraw!!");
		if(amount > balance)
		{
			System.out.println("Less Amount, Waiting 4 deposit");
```

try
```java
			{
				wait();
			}
			catch(InterruptedException e)
			{

			}
		}

		this.balance = this.balance - amount;
		System.out.println("Amount after Withdraw is :"+this.balance);


	}

	public synchronized void deposit(double amount)
	{
		System.out.println("Going to deposit!!");
		this.balance = this.balance + amount;
		System.out.println("Balance After deposit :"+this.balance);
		notify();
	}
}


public class ITCBalance
{
	public static void main(String[] args) throws InterruptedException
	{
		Customer c1 = new Customer();

```


## Thread son = new Thread()

```java
		{
			@Override
			public void run()
			{
				c1.withdraw(15000);
			}
		};
		son.start();

```


## Thread.sleep(1000);




## Thread father = new Thread()

```java
		{
			@Override
			public void run()
			{
				c1.deposit(10000);
			}
		};
        father.start();
	}

}
```


## 18-07-2024

```java
class Resource
{
    private boolean flag = false;

    public synchronized void waitMethod()
	{
		System.out.println("Wait");
       	while (!flag)
		{
```

try
```java
		  {
             System.out.println(Thread.currentThread().getName() + " is waiting...");
             wait();
          }
		  catch (InterruptedException e)
		  {
                e.printStackTrace();
          }
        }
        System.out.println(Thread.currentThread().getName() + " thread completed!!");
    }

    public synchronized void setMethod()
	{
		System.out.println("notifyAll");
		this.flag = true;
        System.out.println(Thread.currentThread().getName() + " has make flag value as a true");
        notifyAll(); // Notify all waiting threads that the signal is set
    }
}

public class InterThreadNotifyAll
{
    public static void main(String[] args)
		{
        Resource r1 = new Resource();

```


## Thread t1 = new Thread(() -> r1.waitMethod(), "Child1");


## Thread t2 = new Thread(() -> r1.waitMethod(), "Child2");


## Thread t3 = new Thread(() -> r1.waitMethod(), "Child3");


```java
		t1.start();
        t2.start();
        t3.start();


```


## Thread setter = new Thread(() -> r1.setMethod(), "Setter_Thread");




try
```java
		{
```


## Thread.sleep(2000);

```java
        }
		catch (InterruptedException e)
		{
            e.printStackTrace();
        }


        setter.start();
    }
}
```


### interrupt Method of Thread class

It is a predefined non static method of Thread class. The main purpose of this method to disturb the execution of the Thread, if the thread is in waiting or sleeping state.

Whenever a thread is interupted then it throws InterruptedException so the thread (if it is in sleeping or waiting mode) will get a chance to come out from a particular logic.

Points :-
If we call interrupt method and if the thread is not in sleeping or waiting state then it will behave normally.

If we call interrupt method and if the thread is in sleeping or waiting state then we can stop the thread  gracefully.

*Overall interrupt method is mainly used to interrupt the

## thread safely so we can manage the resources easily.


Methods :
1) public void interrupt () :- Used to interrupt the Thread but the thread must be in sleeping or waiting mode.

2) public boolean isInterrupted() :- Used to verify whether thread is interrupted or not.
```java
class Interrupt extends Thread
{
   @Override
   public void run()
	{
```


## Thread t = Thread.currentThread();

```java
	   System.out.println(t.isInterrupted());

	   for(int i=1; i<=10; i++)
		{
		   System.out.println(i);
```

try
```java
		   {
```


## Thread.sleep(1000);

```java
		   }
		   catch (Exception e)
		   {
			   System.err.println("Thread is Interrupted ");
			   e.printStackTrace();
		   }
		}
	}
}
public class  InterruptThread
{
	public static void main(String[] args)
	{
        Interrupt it = new Interrupt();
		System.out.println(it.getState());  //NEW
		it.start();
```

it.interrupt();  //main thread is interrupting the child thread
```java
	}
}

```

Note : Here main thread has interrupted child thread so child thread will execute the catch block only one time because sleep is interrupted only once.
```java
class Interrupt extends Thread
{
   public void run()
	{
```

try
```java
	   {
```


## Thread.currentThread().interrupt();


```java
	   for(int i=1; i<=10; i++)
		{
		   System.out.println("i value is :"+i);
```


## Thread.sleep(1000);

```java
		}

	   }
		catch (InterruptedException e)
		{
			System.err.println("Thread is Interrupted :"+e);
		}
		System.out.println("Child thread completed...");
	}
}
public class  InterruptThread1
{
	public static void main(String[] args)
	{
		Interrupt it = new Interrupt();
		it.start();
	}
}

```

Here Child thread is interrupting itself.
```java
public class InterruptThread2
{
    public static void main(String[] args)
	{
```


## Thread thread = new Thread(new MyRunnable());


## thread.start();


try
```java
		{
```


## Thread.sleep(3000);

```java
        }
		catch (InterruptedException e)
		{
            e.printStackTrace();
        }

```


## thread.interrupt();

```java
    }
}

class MyRunnable implements Runnable
{
    @Override
    public void run()
	{
```

try
```java
		{
            while (!Thread.currentThread().isInterrupted())
			{
                System.out.println("Thread is running by locking the resource");
```


## Thread.sleep(500);

```java
            }
        }
		catch (InterruptedException e)
		{
            System.out.println("Thread interrupted gracefully.");
        }
		finally
		{
            System.out.println("Thread resource can be release here.");
        }
    }
}
```


### Deadlock

It is a situation where two or more than two threads are in blocked state forever, here threads are waiting to acquire another thread resource without releasing it's own resource.

This situation happens when multiple threads demands same resource without releasing its own attached resource so as a result we get Deadlock situation and our execution of the program will go to an infinite state as shown in the diagram. (18-JULY-24)
```java
public class DeadlockExample
	{
  public static void main(String[] args)
	 {
     String resource1 = "Ameerpet";
     String resource2 = "S R Nagar";

    // t1 tries to lock resource1 then resource2

```


## Thread t1 = new Thread()

```java
		{
	  @Override
      public void run()
		  {
			  synchronized (resource1)
				  {
			   System.out.println("Thread 1: locked resource 1");
```

try
```java
				   {
```


## Thread.sleep(1000);

```java
				   }
				   catch (Exception e)
				   {}

			   synchronized (resource2) //Nested synchronized block
			   {
				System.out.println("Thread 1: locked resource 2");
			   }
             }
      }
    };


    // t2 tries to lock resource2 then resource1
```


## Thread t2 = new Thread()

```java
	{
      @Override
      public void run()
	  {
        synchronized (resource2)
			{
          System.out.println("Thread 2: locked resource 2");
```

try
```java
			  {
```


## Thread.sleep(1000);

```java
			  }
			  catch (Exception e)
			{}

          synchronized (resource1) //Nested synchronized block
		  {
            System.out.println("Thread 2: locked resource 1");
          }
        }
      }
    };
    t1.start();
    t2.start();
  }
}

```

Note : Here this situation is known as Deadlock situation because both the threads are waiting for infinite state.
Daemon Thread [Service Level Thread]
Daemon thread is a low- priority thread which is used to provide background maintenance.

The main purpose of of Daemon thread to provide services to the user thread.

JVM can't terminate the program till any of the non-daemon (user) thread is active, once all the user thread will be completed then JVM will automatically terminate all Daemon threads, which are running in the background to support user threads.

The example of Daemon thread is Garbage Collection thread, which is running in the background for memory management.

In order to make a thread as a  Daemon thread , we should use setDaemon(true) which is a non static method Thread class.
```java
public class DaemonThreadDemo1
{
  public static void main(String[] args)
	{
	    System.out.println("Main Thread Started...");

```


## Thread daemonThread = new Thread(() ->

```java
		{
            while (true)
			{
                System.out.println("Daemon Thread is running...");
```

try
```java
				{
```


## Thread.sleep(1000);

```java
                }
				catch (InterruptedException e)
				{
                    e.printStackTrace();
                }
            }
        });

        daemonThread.setDaemon(true);
        daemonThread.start();


```


## Thread userThread = new Thread(() ->

```java
		{
            for (int i = 1; i < = 9; i++)
			{
                System.out.println("User Thread: " + i);
```

try
```java
				{
```


## Thread.sleep(2000);

```java
                }
				catch (InterruptedException e)
				{
                    e.printStackTrace();
                }
            }
        });

        userThread.start();

        System.out.println("Main Thread Ended...");
    }
}
```


## 19-07-2024


### Remaining methods of Object class


### Object cloning in java

Object cloning is the process of creating an exact copy of an existing object in the memory.

Object cloning can be done by the following process :

1) Creating Shallow copy

2) Creating Deep copy

3) Using clone() method of java.lang.Object class

4) Passing Object reference to the Constructor.

Shallow Copy :
In shallow copy, we create a new reference variable which will point to same old existing object so if we make any changes through any of the reference variable then original object content will be modified.

Here we have one object and multiple reference variables.

Hashcode of the object will be same because all the reference variables are pointing to the same object.
```java
package com.ravi.clone_method;

class Student
{
	int id;
	String name;

	@Override
	public String toString()
	{
		return "Id is :" + id + "\nName is :" + name ;
	}

}
public class ShallowCopy
{
	public static void main(String[] args)
	{
		Student s1 = new Student();
		s1.id = 111;
		s1.name = "Ravi";

		System.out.println(s1);

		System.out.println("After Shallow Copy");

```

Student s2 = s1; //shallow copy
```java
		s2.id = 222;
		s2.name = "Shankar";

		System.out.println(s1);
		System.out.println(s2);

		System.out.println(s1.hashCode());
		System.out.println(s2.hashCode());
	}

}
```


### Deep Copy

In deep copy, We create a copy of object in a different memory location. This is called a Deep copy.

Here objects are created in two different memory locations so if we modify the content of one object it will not reflect another object.

Here hashcode of both the objects will be different.

```java
package com.ravi.clone_method;

class Employee
{
	int id;
	String name;

	@Override
	public String toString()
	{
		return "Employee [id=" + id + ", name=" + name + "]";
	}
}

public class DeepCopy
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee();
		e1.id = 111;
		e1.name = "Ravi";

		Employee e2 = new Employee();
		e2.id = e1.id;
		e2.name = e1.name;

		System.out.println(e1 +" : "+e2);

		e2.id = 222;
		e2.name = "shankar";
		System.out.println(e1 +" : "+e2);

		System.out.println(e1.hashCode() +" : "+e2.hashCode());
	}

}
```


```java
protected native Object clone() throws CloneNotSupportedException
```

Object cloning in Java is the process of creating an exact copy of the original object. In other words, it is a way of creating a new object by copying all the data and attributes from the original object.

The clone method of Object class creates an exact copy of an object.

In order to use clone() method , a class must implements Clonable interface because we can perform cloning operation on Cloneable objects only [JVM must have additional information].

We can say an object is a Cloneable object if the corresponding class implements Cloneable interface.

It throws a checked Exception i.e CloneNotSupportedException


> **Note :- clone() method is not the part of Clonable interface[marker interface], actually it is the method of Object class.**


clone() method of Object class follow deep copy concept so hashcode will be different as well as if we modify one object content then another object content will not be modified.

```java
clone() method of Object class has protected access modofier so we need to override clone() method in sub class.
```

```java
package com.ravi.clone_method;

class Customer implements Cloneable
{
	private Integer customerId;
	private String customerName;

	public Customer(Integer customerId, String customerName)
	{
		super();
		this.customerId = customerId;
		this.customerName = customerName;
	}



	public void setCustomerId(Integer customerId) {
		this.customerId = customerId;
	}



	public void setCustomerName(String customerName) {
		this.customerName = customerName;
	}



	@Override
	public String toString() {
		return "Customer [customerId=" + customerId + ", customerName=" + customerName + "]";
	}

	@Override
	public Object clone() throws CloneNotSupportedException
	{
		return super.clone();

	}


}


public class CloneMethod
{
	public static void main(String[] args) throws CloneNotSupportedException
	{
	   Customer c1 = new Customer(111, "Scott");
	   Customer c2 = (Customer)  c1.clone();

	   System.out.println(c1);
	   System.out.println(c2);

	   System.out.println("..............");
	   c2.setCustomerId(222);
	   c2.setCustomerName("Smith");

	   System.out.println(c1);
	   System.out.println(c2);

	   System.out.println(c1.hashCode());
	   System.out.println(c2.hashCode());




	}
}
```

```java
protected void finalize() throws Throwable  :
```

It is a predefined method of Object class.

Garbage Collector automatically call this method just before an object is eligible for garbage collection to perform clean-up activity.

Here clean-up activity means closing the resources associated with that object like file connection, database connection, network connection and so on we can say resource de-allocation.


> **Note :- JVM calls finalize method only one per object.**


```java
Diagram (19-JULY-24)
```

```java
package com.ravi.finalize_method;

public class Student
{
    int id;
    String name;

    public Student(int id, String name)
    {
    	this.id= id;
    	this.name = name;
    }

	@Override
	public String toString()
	{
		return "Id is :"+id+"\nName is :"+name;
	}

	@Override
	protected void finalize()
	{
      System.out.println("JVM call this finalize method...");
      System.out.println("Just before Student object destruction");
	}


	public static void main(String[] args) throws InterruptedException
	{
      Student s1 = new Student(111,"Ravi");
      System.out.println(s1.hashCode());
      System.out.println(s1);

      s1 = null;
      System.gc(); //Explicitly calling Garbage Collector
```


## Thread.sleep(3000);

```java
      System.out.println(s1);
	}

}
```

*What is the difference between final, finally and finalize

```java
final :- It is a keyword which is used to provide some kind of          restriction like class is final, Method is
```

final,variable is final.

```java
finally :- if we open any resource as a part of try block then
```

that particular resource must be closed inside
```java
	   finally block otherwise program will be terminated ab-normally and the corresponding resource will not be closed (because the remaining lines of try block will not be executed)

```

finalize() :- It is a method which JVM is calling automatically                      just before object  destruction so if any resource
(database, file and network) is associated with
that particular object then it will be closed
or de-allocated by JVM by calling finalize().

## 20-07-2024


### Method Reference in java

It is a new feature introduced from java 1.8 onwards.

It is mainly used to write concise coding.

By using method reference we can refer an existing method which is available at API level or Project level.

We can use this technique in the body of Lambda expression just to call method defination.

The enitire method body will be automatically placed into Lambda Expression.

It is used to enhance the code reusability.

It uses :: (Double Colon Operator)

While working with Lambda expression we need to write the Lambda Method Body but while working with Method reference we can refere an existing method which is already available in the package or Project.

There are 4 types of method reference

1) Static Method Reference(ClassName::methodName)
2) Instance Method Reference(objectReference::methodName)
3) Constructor Reference (ClassName::new)
4) Arbitrary Referenec (ClassName::instanceMethodName)

Example to make a difference between lambda body and Method Reference

### 3 files

Worker.java(I)
```java
package com.ravi.method_ref;

@FunctionalInterface
public interface Worker
{
   void work();
}


```

Employee.java(C)
```java
package com.ravi.method_ref;

public class Employee
{
   public void work()
   {
	   System.out.println("Employee is working ");
   }
}

```

MethodReferenceDemo1.java
```java
package com.ravi.method_ref;

public class MethodReferenceDemo1
{
  public static void main(String[] args)
  {
	  //By using Lambda Expression
	  Worker w1 = ()-> System.out.println("Worker is working");
	  w1.work();


	  //By Using Method Reference
	  Worker w2 = new Employee()::work;
	  w2.work();



  }
}
```

Method reference can be called by Functional Interface . Here Functional interface method argument and method return type must be same otherwise we will get compilation error.

3 files :

Worker.java(I)
```java
package com.ravi.method_ref;

@FunctionalInterface
public interface Worker
{
   void work();
}


```

Employee.java(C)
```java
package com.ravi.method_ref;

public class Employee
{
   public static void salary()
   {
	   System.out.println("Employee is working 4 salary ");
   }
}

package com.ravi.method_ref;

public class MethodReferenceDemo2
{
  public static void main(String[] args)
  {


	  //By Using Method Reference
	  Worker w2 = Employee::salary;
	  w2.work();



  }
}
```


### 3 files

Worker.java(I)
```java
package com.ravi.method_ref;

@FunctionalInterface
public interface Worker
{
   void work(double salary);
}

```

Employee.java
```java
package com.ravi.method_ref;

public class Employee
{
   public static void salary(double salary)
   {
	   System.out.println("Employee salary is : "+salary);
   }
}

```

MethodReferenceDemo3.java
```java
package com.ravi.method_ref;

public class MethodReferenceDemo3
{
  public static void main(String[] args)
  {
	  //By Using Method Reference
	  Worker w2 = Employee::salary;
	  w2.work(40000);

  }
}
```


### Working with static Method Reference

```java
package com.ravi.static_method_reference;

import java.util.Vector;
import java.util.function.Consumer;

class EvenOrOdd
{
	public static void isEven(int number)
    {
        if (number % 2 == 0)
        {
            System.out.println(number + " is even");
        }
        else
        {
            System.out.println(number + " is odd");
        }
    }
}
public class StaticMethodReferenceDemo1
{
	public static void main(String[] args)
    {
       Vector<Integer> numbers = new Vector<>();
       numbers.add(5);
       numbers.add(2);
       numbers.add(9);
       numbers.add(12);

       //By using Lambda Expression
	   numbers.forEach(num -> EvenOrOdd.isEven(num));

	   System.out.println("..........................");

	   //By Using Method Reference
	   numbers.forEach(EvenOrOdd::isEven);
    }
}
```


### Working with instance method Reference

```java
package com.ravi.instance_method_reference;

@FunctionalInterface
interface Trainer
{
  void getTraining(String name, int experience);
}

class InstanceMethod
{
   public void getTraining(String name, int experience)
   {
	   System.out.println("Trainer name is :"+name+" having "+experience+" years of experience.");
   }
}

public class InstanceMethodReferenceDemo
{
    public static void main(String[] args)
    {
    	//Using Lambda Expression
    	Trainer t1 = (name,  exp)-> System.out.println("Trainer name is :"+name+" and total experience is :"+exp);
    	t1.getTraining("Smith", 5);


    	//By using Method reference
    	Trainer t2 = new InstanceMethod()::getTraining;
    	t2.getTraining("Scott", 10);




    }
}
```


### By Using Constructor Reference

```java
package com.ravi.constructor_reference;

@FunctionalInterface
interface A
{
    Test createObject();
}

class Test
{
    public Test()
    {
        System.out.println("Test class Constructor invoked");
    }
}
public class ConstructorReferenceDemo1
{
    public static void main(String[] args)
    {
        //Lambda Expression
    	A a1 = () -> new Test();
    	a1.createObject();

    	System.out.println("..........");
    	//Method Reference
    	A a2 = Test::new;
    	a2.createObject();
    }
}
```

Program on Constructor Regerence (ClassName::new)
```java
package com.ravi.constructor_reference;

@FunctionalInterface
interface A
{
    Test createObject();
}

class Test
{
    public Test()
    {
        System.out.println("Test class Constructor invoked");
    }
}
public class ConstructorReferenceDemo1
{
    public static void main(String[] args)
    {
        //Lambda Expression
    	A a1 = () -> new Test();
    	a1.createObject();

    	System.out.println("..........");
    	//Method Reference
    	A a2 = Test::new;
    	a2.createObject();
    }
}
```

```java
package com.ravi.constructor_reference;

import java.util.function.Function;

class Accept
{
	int x;

	public Accept(int x)
	{
		this.x = x;
	}

	public int getX()
	{
		return this.x;
	}

}

public class ConstructorReferenceDemo2
{
	public static void main(String[] args)
	{
	    Function<Integer,Accept> fn1 = Accept::new;
	    Accept obj = fn1.apply(15);
	    System.out.println(obj.getX());
	}

}
```

```java
package com.ravi.constructor_reference;

import java.util.Arrays;
import java.util.function.Function;

class Person
{
    private String name;

    public Person(String name)
    {
        this.name = name;
    }

    public String getName()
    {
        return name;
    }

	@Override
	public String toString() {
		return "Person [name=" + name + "]";
	}


}

public class ConstructorReferenceDemo3
{
    public static void main(String[] args)
    {
    	Function<Integer,Person[]> fn2 = Person[]::new;
```

Person [] arr = fn2.apply(3); //3 is size if the array

```java
    	arr[0] = new Person("A");
    	arr[1] = new Person("B");
    	arr[2] = new Person("C");

    	System.out.println(Arrays.toString(arr));
    }
}
```

```java
package com.ravi.constructor_reference;

import java.util.Scanner;
import java.util.function.Function;

class Student
{
	private Integer studentId;
	private String studentName;

	public Student(Integer studentId, String studentName)
	{
		super();
		this.studentId = studentId;
		this.studentName = studentName;
	}

	@Override
	public String toString()
	{
		return "Student [studentId=" + studentId + ", studentName=" + studentName + "]";
	}
}

public class ConstructorReferenceDemo4
{
	public static void main(String[] args)
	{
	 Scanner sc = new Scanner(System.in);

	 Function<Integer,Student[]> fn1 = Student[]::new;
	 System.out.print("Enter the size of the Array :");
	 int size = sc.nextInt();
	 Student[] students = fn1.apply(size);

	 for(int i=0; i<students.length; i++)
	 {
		 System.out.print("Enter the Student id :");
		 int id = sc.nextInt();

		 System.out.print("Enter Student Name :");
		 String name = sc.nextLine();
		 name = sc.nextLine();

		 students[i] = new Student(id, name);
	 }


	 System.out.println("Fetching the data from Array Object :");
	 for(Student std : students)
	 {
		 System.out.println(std);
	 }


	}

}
```


## 22-07-2024


### Arbitrary Reference (ClassName::instanceMethodName)

By using Arbitrary reference we can access the non static method with
the help of class name.

Here JVM, internally passes the object i.e this keyword to acess the non static method.

```java
package com.ravi.arbitary_reference;

import java.util.Arrays;
import java.util.Collections;
import java.util.List;

public class ArbitaryRefDemo1
{
  public static void main(String[] args)
  {
	//By Using Lambda Expression
	String [] players = {"Virat", "Rohit", "Zaheer", "Rishab", "Abhishek"};
	Arrays.sort(players,(s1, s2)-> s2.compareTo(s1));
	System.out.println(Arrays.toString(players));

	//By using Method Reference
	String [] players1 = {"Virat", "Rohit", "Zaheer", "Rishab", "Abhishek"};
	Arrays.sort(players1, String::compareTo);
	System.out.println(Arrays.toString(players1));

  }
}

```

Note : Comparator<T> is a predefined functional interface available in
java.util package.

```java
       @FunctionalInterface
       interface Comparator<T>
       {
          public int compare(T x, T y);
       }

```

Arrays.sort(T[]obj, Comparator<T>), sort is an overloaded method which is accepting Object array and Comparator as a parameter so we write
Lambda OR Method reference for Comparator.
```java
package com.ravi.arbitary_reference;

import java.util.Arrays;
import java.util.Comparator;

class Person
{
    String name;

    public Person(String name)
    {
        this.name = name;
    }

    public int personInstanceMethod1(Person person)
    {
        return this.name.compareTo(person.name);
    }

	@Override
	public String toString() {
		return "Person [name=" + name + "]";
	}


}

public class ArbitraryRefDemo2
{
    public static void main (String[] args) throws Exception
    {

        Person[] personArray = {new Person("Zuber"),new Person("Raj"), new Person("Ankit"), new Person("Abhishek")};
        Arrays.sort(personArray, Person::personInstanceMethod1);

        System.out.println(Arrays.toString(personArray));

    }

}
```


## Collections Framework (40 - 45% IQ)

Collection Frawework in java (40 - 45% IQ)

## Collections framework is nothing but handling individual Objects(Collection Interface) and Group of objects(Map interface).


We know only object can move from one network to another network.

A collections framework is a class library to handle group of Objects.

It is implemented by using java.util package.

It provides an architecture to store and manipulate group of objects.

All the operations that we can perform on data such as searching, sorting, insertion and deletion can be done by using collections framework because It is the data structure of Java.

The simple meaning of collections is single unit of Objects.


### It provides the following sub interfaces


1) List (Accept duplicate elements)
2) Set (Not accepting duplicate elements)
3) Queue (Storing and Fetching the elements based on some order i.e FIFO)

Note : Collection is a predefined interface available in java.util package where as Collections is a predefined class which is available from JDK 1.2V which contains only static methods (Constructor is private)

## 23-07-2024


### Methods of Collection interface

a) public boolean add(E element) :- It is used to add an item/element in the in the collection.

b) public boolean addAll(Collection c) :- It is used to insert the specified collection elements in the existing collection(For merging the Collection)

c) public boolean retainAll(Collection c) :- It is used to retain all the elements from existing element. (Common Element)

d) public boolean removeAll(Collection c) :- It is used to delete all the elements from the existing collection.

e) public boolean remove(Object element) :- It is used to delete an element from the collection based on the object.

f) public int size() :- It is used to find out the size of the Collection [Total number of elements available]

g) public void clear() :- It is used to clear all the elements at once from the Collection.

All the above methods of Collection interface will be applicable to all the sub interfaces like List, Set and Queue.

### List interface

List interface is the sub interface of Collection.

It stores the element on the basis of index.

It can accept duplicate elements.

Collections.sort(List list) method is accepting List interface as a
parameter hence we can perform sorting operation on List interface.

### List interface Hierarchy

Hierarchy is available in the diagram [23-JULY-24]

### Behaviour of List interface Specific classes

* It stores the elements on the basis of index.
* It can accept duplicate, homogeneous and hetrogeneous elements.
* It stores everything in the form of Object.
* When we accept the collection classes without generic concept then
compiler generates a warning message because It is unsafe object.
* By using generic (<>) we can eliminate compilation warning and
still we can take homogeneous as well as hetrogeneous.(<Object>)
* In list interface few classes are dynamically Growable like Vector
and ArrayList. -------------------------------------------------------------------

## 24-07-2024


### Methods of List interface

1) public boolean isEmpty() :- Verify whether List is empty or not

2) public void clear() :- Will clear all the elements

3) public int size() :- To get the size of the Collections

4) public void add(int index, Object o) :- Insert the element based on the index position.

5) public boolean addAll(int index, Collection c) :- Insert the Collection based on the index position

6) public Object get(int index) :- To retrieve the element based on the index position

7) public Object set(int index, Object o) :- To override or replace the existing element based on the index position

8) public Object remove(int index) :- remove the element based on the index position

9) public boolean remove(Object element) :-  remove the element based on the object element, It is the Collection interface method extended by List interface

10) public int indexOf() :- index position of the element

11) public int lastIndex() :- last index position of the element

12) public Iterator iterator() :- To fetch or iterate or retrieve the elements from Collection in forward direction only.

13) public ListIterator listIterator() :- To fetch or iterate or retrieve the elements from Collection in forward and backward direction.
*** How many ways we can fetch the Collection object ?

### In order to fetch the Collection Object from Collection we can use the following 9 ways which are as follows


1) By using toString() method of respective Collection class.[JDK 1.0]
2) By using Ordinary for loop.[JDK 1.0]
3) By using for Each Loop. [JDK 1.5]
4) By using Enumeration interface [JDK 1.0]
5) By using Iterator interface [JDK 1.2]
6) By using ListIterator interface [JDK 1.2]
7) By using SplitIterator interface [JDK 1.8]
8) By using forEach(Consumer<T> cons) method [JDK 1.8]
9) By using Method Reference [JDK 1.8]

Among all these 9 ways Enumeration, Iterator, ListIterator, SplitIterator are the cursors so they can move from one
direction to another direction.


## Enumeration

It is a predefined interface available in java.util package from JDK 1.0 onwards(Legacy interface).

We can use Enumeration interface to fetch or retrieve the Objects one by one from the Collection because it is a cursor.

We can create Enumeration object by using elements() method of the legacy Collection class.

```java
public Enumeration elements();

```


## Enumeration interface contains two methods

1) public boolean hasMoreElements() :- It will return true if the Collection is having more elements.

2) public Object nextElement() :- It will return collection object so return type is Object and move the cursor to the next line.


> **Note :- It will only work with legacy Collections classes.**


## Iterator


## Iterator interface

It is a predefined interface available in java.util package available from 1.2 version.

It is used to fetch/retrieve the elements from the Collection in forward direction only because it is also a cursor.

```java
public Iterator iterator();

```

Example :

## Iterator itr = vector.iterator();


Now, Iterator interface has provided two methods


```java
public boolean hasNext() :-

```

It will verify, the element is available in the next position or not, if available it will return true otherwise it will return false.

```java
public Object next() :- It will return the collection object.
```


### ListIterator interface

It is a predefined interface available in java.util package and it is the sub interface of Iterator available from JDK 1.2v.

It is used to retrieve the Collection object in both the direction i.e in forward direction as well as in backward direction.

```java
public ListIterator listIterator();

```

Example :
```java
ListIterator lit =   v.listIterator();

```

1) public boolean hasNext() :-
It will verify the element is available in the next position or not, if available it will return true otherwise it will return false.

2) public Object next() :- It will return the next position collection object.

3) public boolean hasPrevious() :-
It will verify the element is available in the previous position or not, if available it will return true otherwise it will return false.


4) public Object previous () :- It will return the previous position collection object.


> **Note :- Apart from these 4 methods we have add(), set() and remove() method in ListIterartor interface**


### Spliterator interface

It is a predefined interface available in java.util package from java 1.8 version.

It is a cursor through which we can fetch the elements from the
Collection [Collection, array, Stream]

It is the combination of hasNext() and next() method.

It is using forEachRemaining(Consumer <T>) method for fetching the
elements.

### By using forEach() method

From java 1.8 onwards every collection class provides a method forEach() method, this method takes Consumer functional interface as a  parameter.
This method is avilable in java.lang.Iterable interface.

### How forEach(Consumer<T> cons ) method is working internally ?

```java
package com.ravi.collection;

import java.util.Vector;
import java.util.function.Consumer;

public class ForEachInternals {

	public static void main(String[] args)
	{
		Vector<String> fruits = new Vector<>();
		fruits.add("Orange");
		fruits.add("Apple");
		fruits.add("Mango");
		fruits.add("Banana");
		fruits.add("Gauva");
		fruits.add("KIWI");

```

Consumer<String> cons = new Consumer<String>()
```java
		{
			@Override
			public void accept(String fruit)
			{
				System.out.println(fruit.toUpperCase());
			}
		};

		fruits.forEach(cons);

	}

}
```

```java
package com.ravi.collection;

import java.util.Vector;
import java.util.function.Consumer;

public class ForEachInternals {

	public static void main(String[] args)
	{
		Vector<String> fruits = new Vector<>();
		fruits.add("Orange");
		fruits.add("Apple");
		fruits.add("Mango");
		fruits.add("Banana");
		fruits.add("Gauva");
		fruits.add("KIWI");

		Consumer<String> cons = (fruit)-> System.out.println(fruit);

		fruits.forEach(cons);

	}

}
```

```java
package com.ravi.collection;

import java.util.Vector;
import java.util.function.Consumer;

public class ForEachInternals {

	public static void main(String[] args)
	{
		Vector<String> fruits = new Vector<>();
		fruits.add("Orange");
		fruits.add("Apple");
		fruits.add("Mango");
		fruits.add("Banana");
		fruits.add("Gauva");
		fruits.add("KIWI");


		fruits.forEach((fruit)-> System.out.println(fruit));

	}

}
```


### The following program explain how to retrieve the Collection object by using 9 ways


```java
package com.ravi.collection;

import java.util.Enumeration;
import java.util.Iterator;
import java.util.ListIterator;
import java.util.Spliterator;
import java.util.Vector;

public class RetrievingCollectionObject
{
	public static void main(String[] args)
	{
		Vector<String> fruits = new Vector<>();
		fruits.add("Orange");
		fruits.add("Apple");
		fruits.add("Mango");
		fruits.add("Banana");
		fruits.add("Gauva");
		fruits.add("KIWI");

		System.out.println("BY USING TOSTRING METHOD :");
		System.out.println(fruits.toString());

		System.out.println("BY USING ORDINARY FOR LOOP :");
		for(int i=0; i<fruits.size(); i++)
		{
			System.out.println(fruits.get(i));
		}

		System.out.println("BY USING FOR EACH LOOP :");
		for(String fruit : fruits)
		{
			System.out.println(fruit);
		}

		System.out.println("BY USING ENUMERATION INTERFACE :");

```


## Enumeration<String> ele = fruits.elements();

```java
		while(ele.hasMoreElements())
		{
			System.out.println(ele.nextElement());
		}

		System.out.println("BY USING ITEARTOR INTERFACE :");

```


## Iterator<String> itr = fruits.iterator();


```java
		while(itr.hasNext())
		{
			System.out.println(itr.next());
		}

		System.out.println("BY USING LISTITEARTOR INTERFACE :");

	   ListIterator<String> lstItr = fruits.listIterator();

	   System.out.println("IN FORWARD DIRECTION ..");

	   while(lstItr.hasNext())
	   {
		   System.out.println(lstItr.next());
	   }

       System.out.println("IN BACKWARD DIRECTION ..");

	   while(lstItr.hasPrevious())
	   {
		   System.out.println(lstItr.previous());
	   }

	   System.out.println("BY USING SPLITITERATOR :");

	   Spliterator<String> splItr = fruits.spliterator();
	   splItr.forEachRemaining(fruit -> System.out.println(fruit));

	   System.out.println("BY USING FOR EACH METHOD :");
	   fruits.forEach(fruit -> System.out.println(fruit.toUpperCase()));

	   System.out.println("By USING METHOD REFERENCE :");
	   fruits.forEach(System.out::println);

	}

}
```


### Vector<E>

```java
public class Vector<E> extends AbstractList<E>  implements List<E>, Serializable, Clonable, RandomAccess

```

Vector is a predefined class available in java.util package under List interface.

Vector is always from java means it is available from jdk 1.0 version.

It can accept duplicate, null. homogeneous as well as hetrogeneous elements.

Vector and Hashtable, these two classes are available from jdk 1.0, remaining Collection classes were added from 1.2 version. That is the reason Vector and Hashtable are called legacy(old) classes.

The main difference between Vector and ArrayList is, ArrayList methods are not synchronized so multiple threads can access the method of ArrayList where as on the other hand most the methods are synchronized in Vector so performance wise Vector is slow.

*We should go with ArrayList when Threadsafety is not required on the other hand we should go with Vector when we need ThreadSafety for reterival operation.

It also stores the elements on index basis.It is dynamically growable with initial capacity 10. The next capacity will be 20 i.e double of the first capacity.

```java
new capacity = current capacity * 2;

```

It implements List, Serializable, Clonable, RandomAccess interfaces.

Constructors in Vector :
We have 4 types of Constructor in Vector

```java
1) Vector v1 = new Vector();
```

It will create the vector object with default capacity is 10

```java
2) Vector v2 = new Vector(int initialCapacity);
```

Will create the vector object with user specified capacity.

```java
3) Vector v3 = new Vector(int initialCapacity, int capacityIncrement);
     Eg :-     Vector v = new Vector(1000,5);

```

Initially It will create the Vector Object with initial capacity 1000 and then when  the capacity will be full then increment by 5 so the next capacity would be 1005, 1010 and so on.

```java
 4) Vector v4 = new Vector(Collection c);
```

We can achieve loose coupling

Program that shows performance wise Vector is not good in comparison to ArrayList

System is a predefined class available in java.lang package and it contains a predefined static method currentTimeMillis() , the return type of this method is long, actually it returns the current time of the system in ms.

```java
   public static native long currentTimeMillis()
```


```java
package com.ravi.performance;

import java.util.ArrayList;
import java.util.Vector;

public class PerformanceComparison {

	public static void main(String[] args)
	{
		long startTime = System.currentTimeMillis();

```


## ArrayList<Integer> al = new ArrayList<>();


```java
		for(int i=0; i<=1000000; i++)
		{
			al.add(i);
		}

		long endTime = System.currentTimeMillis();

		System.out.println("Time taken by ArrayList class :"+(endTime - startTime)+" ms");

        startTime = System.currentTimeMillis();

		Vector<Integer> v1 = new Vector<>();

		for(int i=0; i<=1000000; i++)
		{
			v1.add(i);
		}

		 endTime = System.currentTimeMillis();

		System.out.println("Time taken by Vector class :"+(endTime - startTime)+" ms");

	}

}

```

Note :
From the above program, It is clear that performance wise ArrayList is more better than Vector.
```java
//Vector Program on capacity
package com.ravi.performance;

import java.util.Vector;

public class VectorDemo1 {
	public static void main(String[] args)
	{
```

Vector<Integer> v = new Vector<>(100,5); // initial capacity is 100
```java
		System.out.println("Initial capacity is :" + v.capacity());

		for (int i = 0; i < 100; i++)
		{
			v.add(i);
		}

		System.out.println("After adding 100 elements  capacity is :" + v.capacity()); // 100
		v.add(101);
		System.out.println("After adding 101th elements  capacity is :" + v.capacity()); // 105

		for(Integer i : v)
		{
			System.out.print(i+"\t");
			if(i%5==0)
			{
				System.out.println();
			}
		}

	}
}
```

```java
package com.ravi.performance;

import java.util.Collections;
import java.util.Vector;

public class VectorDemo2 {

	public static void main(String[] args)
	{
		Vector<String> fruits = new Vector<>();
		fruits.add("Orange");
		fruits.add("Apple");
		fruits.add("Mango");
		fruits.add("Grapes");
		fruits.add("Gauva");
		fruits.add("Mango");
		System.out.println(fruits);

		fruits.remove(3);
		fruits.remove("Gauva");
		System.out.println("After removing the elements are :");
		fruits.forEach(System.out::println);

		Collections.sort(fruits);
		System.out.println("After Sorting the elements are :");
		fruits.forEach(System.out::println);

		System.out.println("Size is :"+fruits.size());
		System.out.println("Is the List is empty ?"+fruits.isEmpty());

	}

}
```


### Working with Custom Object

```java
package com.ravi.performance;

import java.util.List;
import java.util.Vector;

```

record Product(Integer productId, String productName)
```java
{

}

public class VectorDemo3
{
	public static void main(String[] args)
	{
		List<Product> listOfProducts = new Vector<>();
		listOfProducts.add(new Product(1,"Camera"));
		listOfProducts.add(new Product(2,"Mobile"));
		listOfProducts.add(new Product(3,"Laptop"));
		listOfProducts.add(new Product(4,"Head Phone"));

		listOfProducts.forEach(System.out::println);
	}

}
```

```java
package com.ravi.vector;

import java.util.Scanner;
import java.util.Vector;

public class VectorDemo4
{
    public static void main(String[] args)
    {
        Vector<String> toDoList = new Vector<>();

        Scanner scanner = new Scanner(System.in);

        int choice;
```

do
```java
        {
            System.out.println("ToDo List Menu:");
            System.out.println("1. Add Task");
            System.out.println("2. View Tasks");
            System.out.println("3. Mark Task as Completed");
            System.out.println("4. Exit");
            System.out.print("Enter your choice: ");

            choice = scanner.nextInt();
            scanner.nextLine();

            switch (choice)
            {
                case 1:
                    // Add Task
                    System.out.print("Enter task description: ");
                    String task = scanner.nextLine();
                    toDoList.add(task);
                    System.out.println("Task added successfully!\n");
                    break;
                case 2:
                    // View Tasks
                    System.out.println("ToDo List:");
                    for (int i = 0; i < toDoList.size(); i++)
                    {
             System.out.println((i + 1) + ". " + toDoList.get(i));
                    }
                    System.out.println();
                    break;
                case 3:
                    // Mark Task as Completed
                    System.out.print("Enter task number to mark as completed: ");
                    int taskNumber = scanner.nextInt();
                    if (taskNumber >= 1 && taskNumber <= toDoList.size())
                    {
                        String completedTask = toDoList.remove(taskNumber - 1);
                        System.out.println("Task marked as completed: " + completedTask + "\n");
                    } else {
                        System.out.println("Invalid task number!\n");
                    }
                    break;
                case 4:
                    System.out.println("Exiting ToDo List application. Goodbye!");
                    break;
```

default:
```java
                    System.out.println("Invalid choice. Please enter a valid option.\n");
            }

        } while (choice != 4);


        scanner.close();
    }
}
```

```java
package com.ravi.vector;
//Array To Collection
import java.util.*;
public class VectorDemo5
{
	public static void main(String args[])
	{
		Vector<Integer> v = new Vector<>();

		int x[]={22,20,10,40,15,58};

        //Adding array values to Vector
		for(int i=0; i<x.length; i++)
		{
			v.add(x[i]);
		}
		Collections.sort(v);
		System.out.println("Maximum element is :"+Collections.max(v));
		System.out.println("Minimum element is :"+Collections.min(v));
		System.out.println("Vector Elements :");
		v.forEach(y -> System.out.println(y));
		System.out.println(".....................");
		Collections.reverse(v);
		v.forEach(y -> System.out.println(y));
	}
}
```

```java
package com.ravi.vector;

import java.util.Vector;

public class VectorDemo6 {

	public static void main(String[] args)
	{
		Vector<String> listOfCity = new Vector<>();
		listOfCity.add("Surat");
		listOfCity.add("Pune");
		listOfCity.add("Ahmadabad");
		listOfCity.add("Vanaras");

		//List interface sort(Comparator cmp) method
		listOfCity.sort(String::compareTo);

		//Converting Collection to array
		Object[] array = listOfCity.toArray();

		for(Object obj : array)
		{
			System.out.println(obj);
		}

	}

}
```

Stack<E>
```java
public class Stack<E> extends Vector<E>

```

It is a predefined class available in java.util package. It is the sub class of Vector class introduced from JDK 1.0 so, It is also a legacy class.

It is a linear data structure that is used to store the Objects in LIFO (Last In first out) order.

Inserting an element into a Stack is known as push operation  where as extracting an element from the top of the stack is known as pop operation.

It throws an exception called java.util.EmptyStackException, if Stack is empty and we want to fetch the element.

It has only one constructor as shown below

```java
Stack s = new Stack();

```


### Methods

E push(Object o) :- To insert an element in the bottom of the Stack.

E pop() :- To remove and return the element from the top of the Stack.

E peek() :- Will fetch the element from top of the Stack without removing.

```java
boolean empty() :- Verifies whether the stack is empty or not (return type is boolean)

int search(Object o) :- It will search a particular element in the Stack and it returns OffSet position (int value). If the element is not present in the Stack it will return -1
```

```java
//Program to insert and fetch the elements from stack
package com.ravi.stack;
import java.util.*;
public class Stack1
{
      public static void main(String args[])
      {
            Stack<Integer> s = new Stack<>();
```

try
```java
               {
                  s.push(12);
                  s.push(15);
				  s.push(22);
				  s.push(33);
				  s.push(49);
				  System.out.println("After insertion elements are :"+s);

                  System.out.println("Fetching the elements using pop method");
                  System.out.println(s.pop());
                  System.out.println(s.pop());
                  System.out.println(s.pop());
                  System.out.println(s.pop());
                  System.out.println(s.pop());



				  System.out.println("After deletion elements are :"+s);

				  System.out.println("Is the Stack empty ? :"+s.empty());
              }
			catch(EmptyStackException e)
			{
			   e.printStackTrace();
			}
      }
}
```

```java
//add(Object obj) is the method of Collection
package com.ravi.stack;
import java.util.*;
public class Stack2
{
      public static void main(String args[])
      {
            Stack<Integer> st1 = new Stack<>();
            st1.add(10);
            st1.add(20);
            st1.forEach(x -> System.out.println(x));

            Stack<String> st2 = new Stack<>();
            st2.add("Java");
            st2.add("is");
            st2.add("programming");
            st2.add("language");
            st2.forEach(x -> System.out.println(x));

            Stack<Character> st3 = new Stack<>();
            st3.add('A');
            st3.add('B');
            st3.forEach(x -> System.out.println(x));

            Stack<Double> st4 = new Stack<>();
            st4.add(10.5);
            st4.add(20.5);
            st4.forEach(x -> System.out.println(x));
      }
}
```

```java
package com.ravi.stack;
import java.util.Stack;

public class Stack3
{
	public static void main(String[] args)
		{
			Stack<String> stk= new Stack<>();
			stk.push("Apple");
			stk.push("Grapes");
			stk.push("Mango");
			stk.push("Orange");
			System.out.println("Stack: " + stk);

			String fruit = stk.peek();
			System.out.println("Element at top: " + fruit);
			System.out.println("Stack elements are : " + stk);
		}
}
```

```java
//Searching an element in the Stack
package com.ravi.stack;
import java.util.Stack;
public class Stack4
{
	public static void main(String[] args)
		{
			Stack<String> stk= new Stack<>();
			stk.push("Apple");
			stk.push("Grapes");
			stk.push("Mango");
			System.out.println("Offset Position is : " + stk.search("Mango")); //1
			System.out.println("Offser Position is : " + stk.search("Banana")); //-1
		    System.out.println("Is stack empty ? "+stk.empty());	//false

			System.out.println("Index Position is : " + stk.indexOf("Mango")); //2
		}
}
```


## 26-07-2024


## ArrayList<E>

```java
public class ArrayList<E>  extends AbstractList<E> implements List<E>, Serializable, Clonable, RandomAccess

```

It is a predefined class available in java.util package under List interface from java 1.2v.

It accepts duplicate elements and null values.

It is dynamically growable array.

It stores the elements on index basis so it is simillar to dynamic array.

Initial capacity of ArrayList is 10. The new capacity of Arraylist can be calculated by using the  formula
```java
new capacity = (current capacity * 3)/2 + 1  [Almost 50% increment]

```

*All the methods declared inside an ArrayList is not synchronized so multiple thread can access the method of ArrayList.

*It is highly suitable for fetching or retriving operation when duplicates are allowed and Thread-safety is not required.

It implements List,Serializable, Clonable, RandomAccess interfcaes

Constructor of ArrayList :

### In ArrayList we have 3 types of Constructor

Constructor of ArrayList :
We have 3 types of Constructor in ArrayList

```java
1) ArrayList al1 = new ArrayList();
```

Will create ArrayList object with default capacity 10.

```java
2) ArrayList al2 = new ArrayList(int initialCapacity);
```

Will create an ArrayList object with user specified Capacity

3) ArrayList al3 = new ArrayList(Collection c)
We can copy any Collection interface implemented class data to the current object   reference (Coping one Collection data to another)
```java
 package com.ravi.arraylist;

import java.util.*;
public class ArrayListDemo
{
	public static void main(String... a)
	{
```


## ArrayList<String> arl = new ArrayList<>();//Generic type

```java
		arl.add("Apple");
		arl.add("Orange");
		arl.add("Grapes");
		arl.add("Mango");
		arl.add("Guava");
		arl.add("Mango");
		arl.sort(String::compareTo);


		System.out.println("In Ascending Order");
		arl.forEach(System.out::println);

		Collections.reverse(arl);
		System.out.println("In reverse Order");
		arl.forEach(System.out::println);


	}
}
```


### Working with Custom Object

```java
package com.ravi.arraylist;

import java.util.ArrayList;

```

record Customer(Integer customerId, String customerName, Double custBill)
```java
{

}


public class ArrayListDemo1
{
	public static void main(String[] args)
	{
```


## ArrayList<Customer> al = new ArrayList<>();

```java
	   al.add(new Customer(333, "Rohan",  29789.90));
	   al.add(new Customer(111, "Satish", 23789.90));
	   al.add(new Customer(222, "Aryan",  25789.90));
	   al.add(new Customer(444, "Zuber",  27789.90));

	   al.forEach(System.out::println);


	}
}
```

```java
package com.ravi.arraylist;

//Program to merge and retain of two collection
import java.util.*;
public class ArrayListDemo2
	{
		public static void main(String args[])
		{
```


## ArrayList<String> al1=new ArrayList<>();

```java
		  al1.add("Ravi");
		  al1.add("Rahul");
		  al1.add("Rohit");

```


## ArrayList<String> al2=new ArrayList<>();

```java
		  al2.add("Pallavi");
		  al2.add("Sweta");
		  al2.add("Puja");

		  al1.addAll(al2);

        al1.forEach(x -> System.out.println(x.toUpperCase()));

        System.out.println(".................................");

```


## ArrayList<String> al3=new ArrayList<>();

```java
		  al3.add("Ravi");
		  al3.add("Rahul");
		  al3.add("Rohit");

```


## ArrayList<String> al4=new ArrayList<>();

```java
		  al4.add("Pallavi");
		  al4.add("Rahul");
		  al4.add("Raj");

		  al3.retainAll(al4);

        al3.forEach(x -> System.out.println(x));
   }
}
```


### How to create immutable List in Collection


### We can create immutable list in java by using following two ways


1) Arrays.asList(T... x) : Here asList(T... x) method will create a
fixed length array so we can't add more elements the the existing
list otherwise we will get java.lang.UnsupportedOperationException, But we can replace the
existing element with new element as shown in the program

```java
    package com.ravi.arraylist;

import java.util.Arrays;
import java.util.List;

public class ImmutableList {

	public static void main(String[] args)
	{
		List<Integer> listOfNumbers = Arrays.asList(1,2,3,4,5,6,7);
```

listOfNumbers.set(0,100); //Valid
listOfNumbers.add(8); //java.lang.UnsupportedOperationException
```java
		System.out.println(listOfNumbers);



	}

}

```

2) From java 9v List interface has provided a predefined static method of(T... x) through which we can create an immutable list
so further addition or modification in the exitsing list is not possible otherwise we will get java.lang.UnsupportedOperationException

```java
   package com.ravi.arraylist;

import java.util.List;

public class ImmutableList1 {

	public static void main(String[] args)
	{
		List<String> listOfString = List.of("A","B","C");
		System.out.println(listOfString);
```

listOfString.set(0,"D"); //Invalid
listOfString.add("D"); //Invalid
```java
	}

}
```

```java
//Program to fetch the elements in forward and backward
//direction using ListIterator interface

package com.ravi.arraylist;

import java.util.Arrays;
import java.util.Collections;
import java.util.List;
import java.util.ListIterator;

public class ArrayListDemo3
{
public static void main(String args[])
  {
```

List<String> listOfName = Arrays.asList("Rohit","Akshar","Pallavi","Sweta"); //Length is fixed

```java
	  listOfName.sort(String::compareTo);

	 //Fetching the data in both the direction
	 ListIterator<String> lst = listOfName.listIterator();

	 System.out.println("In Forward Direction..");
	 while(lst.hasNext())
	 {
		System.out.println(lst.next());
	 }
	 System.out.println("In Backward Direction..");
	 while(lst.hasPrevious())
	 {
		System.out.println(lst.previous());
	 }

  }
}
```

```java
//Serialization and De-serialization on ArrayList Object
package com.ravi.arraylist;

import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;
import java.io.ObjectInputStream;
import java.io.ObjectOutputStream;
import java.util.ArrayList;

public class ArrayListDemo4
{
  public static void main(String[] args) throws IOException
  {
```


## ArrayList<String> cityName = new ArrayList<>();

```java
	cityName.add("Hyderabad");
	cityName.add("Pune");
	cityName.add("Banglore");
	cityName.add("Chennai");

	//Serialization
	var fos = new FileOutputStream("C:\\new\\CityName.txt");
	var oos = new ObjectOutputStream(fos);

	try(fos; oos)
	{
		oos.writeObject(cityName);
		System.out.println("Object stored successfully in the file");
	}
	catch(Exception e)
	{
		e.printStackTrace();
	}

	//De-Serialization

	var fin = new FileInputStream("C:\\new\\CityName.txt");
	var ois = new ObjectInputStream(fin);

	try(fin ; ois)
	{
		System.out.println("Reading the Object Data");
```


## ArrayList<String> list = (ArrayList<String>) ois.readObject();

```java
		System.out.println(list);
	}
	catch(Exception e)
	{

	}
  }
}
```


### Assignment

Take a record class called Product which contains 3 components productId, productName and productPrice

Take an ArrayList class which hold the custom object Product, now this
perform Serialization and De-Serialization on ArrayList object.
```java
public void ensureCapacity(int minimumCapacity) :
```

As we know we don't have capaity() method with ArrayList class.

In ArrayList, once we create the object then the default capacity is 10. After object creation, if we want to resize our arraylist capacity then we can use ensureCapacity(int minimumCapacity) method of ArrayList class.

This method will ensure that the ArrayList must hold the minimum capacity elememt which is specified as a parameter to ensureCapacity()

Even after resizing, It is dynamically Growable.
```java
package com.ravi.arraylist;

import java.util.ArrayList;
import java.util.LinkedList;

public class ArrayListDemo5
{
	public static void main(String[] args)
	{
```


## ArrayList<String> city= new ArrayList<>();



city.ensureCapacity(3); //resize the capacity of Arraylist
```java
		city.add("Hyderabad");
		city.add("Mumbai");
		city.add("Delhi");


		city.add("Kolkata");
		System.out.println("ArrayList: " + city);
	 }
}
```

```java
package com.ravi.arraylist;

//Program on ArrayList that contains null values as well as we can pass the element based on the index position
import java.util.ArrayList;
import java.util.LinkedList;
public class ArrayListDemo6
{
	public static void main(String[] args)
	{
```


## ArrayList<Object> al = new ArrayList<>(); //Generic type

```java
		al.add(12);
		al.add("Ravi");
		al.add(12);
```

al.add(3,"Hyderabad"); //add(int index, Object o)method of List interface
```java
		al.add(1,"Naresh");
		al.add(null);
		al.add(11);
		System.out.println(al);  //12 Naresh Ravi  12  Hyderabad null 11
	}
}
```

```java
package com.ravi.arraylist;

import java.util.ArrayList;
import java.util.LinkedList;
import java.util.List;

```

record Professor(String name, String specialization)
```java
{
}

class Department
{
    private String name;
    private final List<Professor> professors; // Department "HAS-A" relationship with Professor

    public Department(String name)
    {
        this.name = name;
        this.professors = new ArrayList<>();
    }

    public void addProfessor(Professor prof)
    {
        professors.add(prof);
    }

    public String getName()
    {
        return this.name;
    }

    public List<Professor> getProfessors()
    {
        return professors;
    }
}

public class ArrayListDemo7
{
    public static void main(String[] args)
    {

        Professor prof1 = new Professor("Scott", "Java");
        Professor prof2 = new Professor("Rahul", "Python");
        Professor prof3 = new Professor("Samir", ".Net");

        Department csd = new Department("Computer Science");
        csd.addProfessor(prof1);
        csd.addProfessor(prof2);
        csd.addProfessor(prof3);

        // Accessing properties through the "HAS-A" relationship
        System.out.println("Department Name: " + csd.getName());

        System.out.println("Professors in " + csd.getName() + ":");

        List<Professor> professors = csd.getProfessors();
        professors.forEach(System.out::println);


    }
}
```


### Limitation of ArrayList


### Time Complexcity of ArrayList

The time complexcity of ArrayList to insert and delete an element from the middle would be O(n) [Big O of n] because 'n' number of elements will be re-located so it is not a good choice to perform insertion and deletion operation in the middle of the List.

On the other hand time complexcity of ArrayList to retrieve an element from the List would be O(1) because by using get(int index) method we can retrieve the element randomly from the list. ArrayList class
```java
implements RandomAccess marker interface which provides the facility
```

to fetch the elements Randomly. [26-JULY]

```java
class Concurrent extends Thread
{
```


## ArrayList<String> arl = null;


```java
	public Concurrent(ArrayList<String> arl)
	{
		super();
		this.arl = arl;
	}
	@Override
	public void run()
	{
```

try
```java
		{
```


## Thread.sleep(2000);

```java
		}
		catch(InterruptedException e)
		{
			e.printStackTrace();
		}
		arl.add("Goa");
	}
}


public class ConcurrentModificationException
{
	public static void main(String[] args) throws InterruptedException
	{
```


## ArrayList<String> listOfCity = new ArrayList<>();

```java
		listOfCity.add("Hyderabad");
		listOfCity.add("Kolkata");
		listOfCity.add("Bhubneswar");
		listOfCity.add("Indore");
		listOfCity.add("Mumbai");

        Concurrent cc = new Concurrent(listOfCity);
        cc.start();

```


## Iterator<String> itr = listOfCity.iterator();


```java
        while(itr.hasNext())
        {
        	System.out.println(itr.next());
```


## Thread.sleep(500);

```java
        }


	}

}
```


### LinkedList<E>


### LinkedList

```java
public class LinkedList<E> extends AbstractSequentialList<E> implements List<E>, Deque<E>, Cloneable, Serializable

```

It is a predefined class available in java.util package under List interface fron JDK 1.2v.

It is ordered by index position like ArrayList except the elements (nodes) are doubly linked to one another. This linkage provide us new method for adding and removing the elements from the middle of LinkedList.

*The important thing is, LikedList may iterate more slowely than ArrayList but LinkedList is a good choice when we want to insert or delete the elements frequently in the list.

From jdk 1.6 onwards LinkedList class has been enhanced to support basic queue operation by implementing Deque<E> interface.

LinkedList methods are not synchronized.

It inserts the elements by using Doubly linked List so insertion and deleteion is very easy.



## ArrayList is using Dynamic array data structure but LinkedList class is using LinkedList (Doubly LinkedList) data structure.


Constructor:
It has 2 constructors

```java
1) LinkedList list1 = new LinkedList();
```

It will create a LinkedList object with 0 capacity.

```java
2) LinkedList list2 = new LinkedList(Collection c);
```

Interconversion between the collection

Methods of LinkedList class:
1) void addFirst(Object o)
2) void addLast(Object o)

3) Object getFirst()
4) Object getLast()

5) Object removeFirst()
6) Object removeLast()


> **Note :- It stores the elements in non-contiguous memory location.**


The time complexcity for insertion and deletion is  O(1)

The time complexcity for seraching O(n) becuaee it serach the elemnts using node reference.
```java
package com.ravi.linked_list;

import java.util.Iterator;
import java.util.LinkedList;
import java.util.List;
public class LinkedListDemo
{
 public static void main(String args[])
 {
      List<Object> list=new LinkedList<>();
	  list.add("Ravi");
	  list.add("Vijay");
	  list.add("Ravi");
	  list.add(null);
	  list.add(42);

	  System.out.println("1st Position Element is :"+list.get(1));

	  //Iterator interface

```


## Iterator<Object> itr = list.iterator();

itr.forEachRemaining(System.out::println); //JDK 1.8



```java
  }
}
```

```java
package com.ravi.linked_list;

import java.util.*;
public class LinkedListDemo1
{
      public static void main(String args[])
      {
```

LinkedList<String> list= new LinkedList<>(); //generic
list.add("Item 2");//2
list.add("Item 3");//3
list.add("Item 4");//4
list.add("Item 5");//5
list.add("Item 6");//6
list.add("Item 7");//7

list.add("Item 9"); //10

list.add(0,"Item 0");//0
list.add(1,"Item 1"); //1

list.add(8,"Item 8");//8
list.add(9,"Item 10");//9
```java
            System.out.println(list);

			 list.remove("Item 5");

			  System.out.println(list);

			    list.removeLast();
			    System.out.println(list);

			     list.removeFirst();
			    System.out.println(list);

```

list.set(0,"Ajay"); //set() will replace the existing value
```java
			  list.set(1,"Vijay");
			  list.set(2,"Anand");
			  list.set(3,"Aman");
			  list.set(4,"Suresh");
			  list.set(5,"Ganesh");
			  list.set(6,"Ramesh");
			  list.forEach(x -> System.out.println(x));


      }
}
```

```java
package com.ravi.linked_list;

//Methods of LinkedList class
import java.util.LinkedList;
public class LinkedListDemo2
{
    public static void main(String[] argv)
    {
          LinkedList<String> list = new LinkedList<>();

          list.addFirst("Ravi");
          list.add("Rahul");
          list.addLast("Anand");

          System.out.println(list.getFirst());
          System.out.println(list.getLast());

          list.removeFirst();
          list.removeLast();

          System.out.println(list);
    }
}
```


```java
package com.ravi.linked_list;
//ListIterator methods
import java.util.*;
public class LinkedListDemo3
{
	public static void main(String[] args)
	{
		LinkedList<String> city = new LinkedList<> ();
         city.add("Kolkata");
		 city.add("Bangalore");
		 city.add("Hyderabad");
		 city.add("Pune");
		 System.out.println(city);

		ListIterator<String> lt = city.listIterator();

       while(lt.hasNext())
		  {
			String cityName =  lt.next();

			if(cityName.equals("Kolkata"))
			{
                 lt.remove();
			}
			else if(cityName.equals("Hyderabad"))
			{
                 lt.add("Ameerpet");
			}
			else if(cityName.equals("Pune"))
			{
                 lt.set("Mumbai");
			}
		}
		city.forEach(System.out::println);
	}
}

```

Here we are modifying the List structure by using LinkedList class own method so, ConcurrentModificationException will not be generated.

## 29-07-2024

```java
package com.ravi.linked_list;

//Insertion, deletion, displaying and exit

import java.util.LinkedList;
import java.util.List;
import java.util.Scanner;

public class LinkedListDemo4
{
 public static void main(String[] args)
	{
      List<Integer> linkedList = new LinkedList<>();
      Scanner scanner = new Scanner(System.in);

        while (true)
		{
          System.out.println("Linked List: " + linkedList); //[]
          System.out.println("1. Insert Element");
          System.out.println("2. Delete Element");
		  System.out.println("3. Display Element");
          System.out.println("4. Exit");
          System.out.print("Enter your choice: ");

          int choice = scanner.nextInt();
          switch (choice)
			{
              case 1:
                  System.out.print("Enter the element to insert: ");
                  int elementToAdd = scanner.nextInt();
                  linkedList.add(elementToAdd);
                  break;
              case 2:
                  if (linkedList.isEmpty())
					{
                      System.out.println("Linked list is empty. Nothing to delete.");
                  }
					else
					{
                      System.out.print("Enter the element to delete: ");
                      int elemenetToDelete = scanner.nextInt();
                      boolean remove = linkedList.remove(Integer.valueOf(elemenetToDelete));

                       if(remove)
                       {
                    	   System.out.println("Element "+elemenetToDelete+ " is deleted Successfully" );
                       }
                       else
                       {
                    	   System.out.println(elemenetToDelete+" not available is the LinkedList");
                       }

                  }
                  break;
				case 3:
					System.out.println("Elements in the linked list.");
                    linkedList.forEach(System.out::println);
				     break;
              case 4:
                  System.out.println("Exiting the program.");
                  scanner.close();
                  System.exit(0);
```

default:
```java
                  System.out.println("Invalid choice. Please try again.");
          }
      }
  }
}
```

```java
package com.ravi.linked_list;

import java.util.Arrays;
import java.util.HashSet;
import java.util.LinkedList;
import java.util.List;
import java.util.Optional;
import java.util.stream.Stream;

public class LinkedListDemo5 {

	public static void main(String[] args)
	{


		List<String> listOfName = Arrays.asList("Ravi","Rahul","Ankit", "Rahul");

		LinkedList<String> list = new LinkedList<>(listOfName);
		list.forEach(System.out::println);


	}

}
```

```java
import java.util.LinkedList;
import java.util.Iterator;
import java.util.List;

```

record Dog(String name)
```java
{
}

public class LinkedListDemo5
{
       public static void main(String[] args)
       {
             List<Dog> d = new LinkedList<>();
             Dog dog = new Dog("Tiger");
             d.add(dog);
             d.add(new Dog("Tommy"));
             d.add(new Dog("Rocky"));

```


## Iterator<Dog> i3 = d.iterator();

i3.forEachRemaining(x -> System.out.println(x.name().toUpperCase())); //java 8


```java
             System.out.println("size " + d.size());
             System.out.println("Get 1st Position Object " + d.get(1).name());


        }
}
```

```java
import java.util.Deque;
import java.util.LinkedList;

public class LinkedListDemo6
{
    public static void main(String[] args)
		{
        // Create a LinkedList and treat it as a Deque
        Deque<String> deque = new LinkedList<>();


```

deque.addFirst("Ravi");  // Ravi Pallavi
```java
        deque.addFirst("Raj");


        deque.addLast("Pallavi");
        deque.addLast("Sweta");


        System.out.println("Deque: " + deque);


        String first = deque.removeFirst();
        String last = deque.removeLast();


        System.out.println("Removed first element: " + first);
        System.out.println("Removed last element: " + last);
        System.out.println("Updated Deque: " + deque);
    }
}
```


### Set interface

It is the sub interface of Collection interface available from JDK 1.2

It does not store the element on the basis of index.

It does not accept duplicate element here intrenally equals(Object obj) method verifies the objects, If two objects are identical then it will accept only one object.

ListIterartor interface does not work with Set interface.

It supports all the methods of Collection interface, some methods are added from java 9v.

### Set interface Hierarchy

Hierarchy is available in the paint diagram [29th July]

## What is hashing algorithm ?

Hashing algorithm is a technique through which we can search, insert and delete an element in more efficient way in comparison to our classical indexing approach.

Hashing algorithm, internally uses Hashtable data structute, Hashtable data structure internally uses Bucket data structure.

Here elements are inserted by using hashing algorithm so the time complaxcity to insert, delete and search an element would be O(1)
```java
HashSet (UNSORTED, UNORDERED , NO DUPLICATES)
```

```java
public class HashSet<E> extends AbstractSet<E> implements Set<E>, Clonabale, Serializable

```

It is a predefined class available in java.util package under Set interface and introduced from JDK 1.2V.

It is an unsorted and unordered set.

It accepts hetrogeneous kind of data.

*It uses the hashcode of the object being inserted into the Collection. Using this hashcode it finds the bucket location.

It doesn't contain any duplicate elements as well as It does not maintain any order while iterating the elements from the collection.

It can accept one null value.

HashSet methods are not synchronized.

HashSet is used for fast searching operation.

It contains 4 types of constructors
```java
1) HashSet hs1 = new HashSet();
```

It will create the HashSet Object with default capacity is 16. The default load fator or Fill Ratio is 0.75   (75% of HashSet is filled up then new HashSet Object will be created having double capacity)

```java
2) HashSet hs2 = new HashSet(int initialCapacity);
```

will create the HashSet object with user specified capacity


```java
3) HashSet hs3 = new HashSet(int initialCapacity, float loadFactor);
```

we can specify our own initialCapacity and loadFactor(by default load factor is 0.75)

```java
4) HashSet hs = new HashSet(Collection c);
```

Interconversion of Collection.
```java
//Unsorted, Unordered and no duplicates
import java.util.*;
public class HashSetDemo
{
 public static void main(String args[])
 {
	    HashSet<Integer> hs = new HashSet<>();
		hs.add(67);
		hs.add(89);
		hs.add(33);
		hs.add(45);
		hs.add(12);
		hs.add(35);

		hs.forEach(str-> System.out.println(str));
	}
}
```


## 30-07-2024

```java
import java.util.*;
public class HashSetDemo1
{
      public static void main(String[] argv)
      {
      HashSet<String> hs=new HashSet<>();
	  hs.add("Ravi");
	  hs.add("Vijay");
	  hs.add("Ravi");
	  hs.add("Ajay");
	  hs.add("Palavi");
	  hs.add("Sweta");
	  hs.add(null);
	  hs.add(null);
	  hs.forEach(str -> System.out.println(str));

      }
}
```

```java
package com.ravi.collection;

import java.util.Arrays;
import java.util.HashSet;

public class HashSetDemo2 {

	public static void main(String[] args)
	{
		Boolean b[] = new Boolean[5];

		HashSet<Object> hs = new HashSet<>();
		b[0] = hs.add(12);
		b[1] = hs.add(15);
		b[2] = hs.add(12);
		b[3] = hs.add("NIT");
		b[4] = hs.add(new String("NIT"));

		System.out.println(Arrays.toString(b));

		if(hs.contains("NIT"))
		{
			System.out.println("NIT is available");
		}
		else
		{
			System.out.println("NIT is not available");
		}

		hs.forEach(System.out::println);

	}

}

```

Note : From above program it is clear that add(Object obj) method return type is boolean.
```java
//add, delete, display and exit
import java.util.HashSet;
import java.util.Scanner;

public class HashSetDemo3
{
    public static void main(String[] args)
		{
        HashSet<String> hashSet = new HashSet<>();
        Scanner scanner = new Scanner(System.in);

        while (true)
		{
            System.out.println("Options:");
            System.out.println("1. Add element");
            System.out.println("2. Delete element");
            System.out.println("3. Display HashSet");
            System.out.println("4. Exit");

            System.out.print("Enter your choice (1/2/3/4): ");
            int choice = scanner.nextInt();

            switch (choice)
			{
                case 1:
                    System.out.print("Enter the element to add: ");
                    String elementToAdd = scanner.next();
                    if (hashSet.add(elementToAdd))
					{
                        System.out.println("Element added successfully.");
                    }
					else
					{
                        System.out.println("Element already exists in the HashSet.");
                    }
                    break;
                    case 2:
                    System.out.print("Enter the element to delete: ");
                    String elementToDelete = scanner.next();
                    if (hashSet.remove(elementToDelete))
					{
                        System.out.println("Element deleted successfully.");
                    }
					else
					{
                        System.out.println("Element not found in the HashSet.");
                    }
                    break;
                    case 3:
                    System.out.println("Elements in the HashSet:");
                    hashSet.forEach(System.out::println);
                    break;
                    case 4:
                    System.out.println("Exiting the program.");
                    scanner.close();
                    System.exit(0);
```

default:
```java
                    System.out.println("Invalid choice. Please try again.");
            }

            System.out.println();
        }
    }
}
```

LinkedHashSet<E>
```java
public class LinkedHashSet extends HashSet implements Set, Clonable, Serializable

```

It is a predefined class in java.util package under Set interface and introduced from java 1.4v.

It is the sub class of HashSet class.

It is an orderd version of HashSet that maintains a doubly linked list across all the elements.

It internally uses Hashtable and LinkedList data structures.

We should use LinkedHashSet class when we want to maintain an order.

When we iterate the elements through HashSet the order will be unpredictable, while when we iterate the elments through LinkedHashSet then the order will be same as they were inserted in the collection.

It accepts hetrogeneous and null value is allowed.

It has same constructor as HashSet class.

```java
import java.util.*;
public class LinkedHashSetDemo
{
 public static void main(String args[])
	{
		  LinkedHashSet<String> lhs=new LinkedHashSet<>();
		  lhs.add("Ravi");
		  lhs.add("Vijay");
		  lhs.add("Ravi");
		  lhs.add("Ajay");
		  lhs.add("Pawan");
		  lhs.add("Shiva");
		  lhs.add(null);
		  lhs.add("Ganesh");
		  lhs.forEach(str -> System.out.println(str));
	}
}
```

```java
import java.util.*;

public class LinkedHashSetDemo1
{
    public static void main(String[] args)
	{
       LinkedHashSet<Integer> linkedHashSet = new LinkedHashSet<>();

        linkedHashSet.add(10);
        linkedHashSet.add(5);
        linkedHashSet.add(15);
        linkedHashSet.add(20);
        linkedHashSet.add(5);


        System.out.println("LinkedHashSet elements: " + linkedHashSet);

        System.out.println("LinkedHashSet size: " + linkedHashSet.size());

        int elementToCheck = 15;
        if (linkedHashSet.contains(elementToCheck))
		{
            System.out.println(elementToCheck + " is present in the LinkedHashSet.");
        }
		else
		{
            System.out.println(elementToCheck + " is not present in the LinkedHashSet.");
        }

        int elementToRemove = 10;
        linkedHashSet.remove(elementToRemove);
        System.out.println("After removing " + elementToRemove + ", LinkedHashSet elements: " + linkedHashSet);

              linkedHashSet.clear();
        System.out.println("After clearing, LinkedHashSet elements: " + linkedHashSet); //[]
    }
}
```


### SortedSet interface

As we know Collections.sort(List list) method accept list as a parameter so, we can't perform sorting operation by using sort() method on HashSet and LinkedHashSet.

In order to provide automatic sorting facility, Set interface has provided one more interface i.e SortedSet interface available from JDK 1.2.

SortedSet interface provided default natural sorting order, default natural sorting order means, if it is number then ascending order but if it is String then alphabetical /dictionary order.

In order to sort the element either in default natural sorting order or user-defined sorting order we are using Comparable or Comparator
interfaces.
----------------------------------------------------------------------*** What is the difference between Comparable and Comparator :
Difference is available in paint diagram 30-JULY-24

### Program on Comparable<T> interface


### 2 files

Employee.java(R)
```java
package com.ravi.comparable_demo;

public record Employee(Integer employeeId, String employeeName) implements Comparable<Employee>
{
	//Sorting based on the Employee Id
	@Override
	public int compareTo(Employee e2)
	{
		return this.employeeId().compareTo(e2.employeeId());
	}


}

```

EmployeeComparable.java(C)
```java
package com.ravi.comparable_demo;

import java.util.ArrayList;
import java.util.Collections;

public class EmployeeComparable
{
	public static void main(String[] args)
	{
```


## ArrayList<Employee> listOfEmployee = new ArrayList<>();

```java
	  listOfEmployee.add(new Employee(333,"Scott"));
	  listOfEmployee.add(new Employee(222,"Amit"));
	  listOfEmployee.add(new Employee(111,"Zuber"));

	  Collections.sort(listOfEmployee);

	  listOfEmployee.forEach(System.out::println);

	}

}
```


### Limitation of Comparable interface

1) We can write only one sorting logic using comparable (We can sort based on ID or based on name but not both)

2) If the BLC class is given by some 3rd party in .class format
then we can't modify the source code hence Comparable will not work
here.

To avoid the above said problems we introduced Comparator interface :

Program on Comparator interface :

### 2 files

Product.java(R)
```java
package com.ravi.comparator;

public record Product(Integer productId, String productName)
{

}


```

ProductComparator.java(C)
```java
package com.ravi.comparator;

import java.util.ArrayList;
import java.util.Collections;
import java.util.Comparator;

public class ProductComparator
{
	public static void main(String[] args)
	{
```


## ArrayList<Product> listOfProduct = new ArrayList<>();

```java
		listOfProduct.add(new Product(333, "Camera"));
		listOfProduct.add(new Product(111, "Mobile"));
		listOfProduct.add(new Product(222, "Laptop"));


```


## Comparator<Product> comId =  new Comparator<Product>()

```java
		{
			@Override
			public int compare(Product p1, Product p2)
			{
				return p1.productId().compareTo(p2.productId());
			}
		};

		Collections.sort(listOfProduct, comId);
		System.out.println("Sorting based on the product Id");
		listOfProduct.forEach(System.out::println);

		System.out.println(".....................");

```


## Comparator<Product> cmpName = (p1,p2) -> p1.productName().compareTo(p2.productName());

```java
		Collections.sort(listOfProduct, cmpName);
		System.out.println("Sorting based on the product Name");
		listOfProduct.forEach(System.out::println);
	}

}
```


## Comparable is not a Functional interface because due to current object support(this keyword) we need to write the sorting logic in the BLC class only so BLC class must implements Comparable interface.

[We can say Comparable as a Functional interafce because it contains exactly one abastract method but we can't uas as Lambda]
We can't write the logic of compareTo(T x) method in another class because It accept only one parameter for second parameter we need to depend upon the Current Object.

### Program to sort the Integer object in descending order

```java
package com.ravi.comparator;

import java.util.ArrayList;
import java.util.Collections;

public class IntegerDescending
{
	public static void main(String[] args)
	{
```


## ArrayList<Integer> al = new ArrayList<>();

```java
		al.add(89);
		al.add(15);
		al.add(12);
		al.add(9);

		Collections.sort(al,(i1,i2)-> i2.compareTo(i1));

		System.out.println(al);

	}
}
```

TreeSet<E>

### TreeSet<E>

```java
public class TreeSet<E> extends AbstractSet<E> implements NavigableSet<E>, Clonable, Serializable

```

It is a predefined class available in java.util package under Set interface available from JDK 1.2v.

TreeSet, TreeMap  and PriorityQueue are the three sorted collection in the entire Collection Framework so these classes never accepting non comparable objects.

It will sort the elements in natural sorting order i.e ascending order in case of number , and alphabetical order or Dictionary order in the case of String. In order to sort the elements according to user choice, It uses Comparable/Comparator  interface.

It does not accept duplicate and null value (java.lang.NullPointerException)

It does not accept non comparable type of data if we try to insert it will throw a runtime exception i.e java.lang.ClassCastException

TreeSet implements NavigableSet.

NavigableSet extends SortedSet.

It contains 4 types of constructors :
```java
1) TreeSet t1 = new TreeSet();
```

create an empty TreeSet object, elements will be inserted in using Comparable/Comparator

```java
2) TreeSet t2 = new TreeSet(Comparator c);
```

Customized sorting order

```java
3)  TreeSet t3 = new TreeSet(Collection c);
```

loose coupling

```java
4) TreeSet t4 = new TreeSet(SortedSet s);
```

Another implemented class of SortedSet we can pass as a parameter.
```java
//program that describes TreeSet provides default natural sorting order
import java.util.*;
public class TreeSetDemo
{
	public static void main(String[] args)
	{
		SortedSet<Integer> t1 = new TreeSet<>();
		t1.add(4);
		t1.add(7);
		t1.add(2);
		t1.add(1);
		t1.add(9);
		System.out.println(t1);

		NavigableSet<String> t2 = new TreeSet<>();
		t2.add("Orange");
		t2.add("Mango");
		t2.add("Banana");
		t2.add("Grapes");
		t2.add("Apple");
		System.out.println(t2);
	}
}

```

Here Elements will be sorted in a default natural sorting order because
Integer and String both the classes are implementing Comparable interface.
```java
package com.ravi.treeset_ex;

import java.util.TreeSet;

```

record Product(Integer productId)
```java
{

}


public class TreeSetDemo1 {

	public static void main(String[] args)
	{
		TreeSet<Product> ts1 = new TreeSet<>();
		ts1.add(new Product(111));
		System.out.println(ts1);
	}

}

```

Here we will get java.lang.ClassCastException because Product class is not implemented by Comparable interface as well as we are not providing the support of Comparator at the time TreeSet class Object creation.
```java
package com.ravi.treeset_ex;

import java.util.TreeSet;

```

record Product(Integer productId) implements Comparable<Product>
```java
{
	@Override
	public int compareTo(Product p2)
	{
		return this.productId().compareTo(p2.productId);
	}

}


public class TreeSetDemo1 {

	public static void main(String[] args)
	{
		TreeSet<Product> ts1 = new TreeSet<>();
		ts1.add(new Product(333));
		ts1.add(new Product(222));
		ts1.add(new Product(111));
		System.out.println(ts1);
	}

}
```

Here We are using Comparable to sort the product data
```java
package com.ravi.treeset_ex;

import java.util.TreeSet;

```

record Employee(String employeeName)
```java
{




}

public class TreeSetDemo2 {

	public static void main(String[] args)
	{
		TreeSet<Employee> ts1 = new TreeSet<Employee>((e1,e2)-> e1.employeeName().compareTo(e2.employeeName()));
		ts1.add(new Employee("Scott"));
		ts1.add(new Employee("Aryan"));

		System.out.println();

	}

}
```

```java
import java.util.*;
public class TreeSetDemo1
{
	public static void main(String[] args)
	{
		TreeSet<String> t1 = new TreeSet<>();
		t1.add("Orange");
		t1.add("Mango");
		t1.add("Pear");
		t1.add("Banana");
		t1.add("Apple");
		System.out.println("In Ascending order");
		t1.forEach(i -> System.out.println(i));

		TreeSet<String> t2 = new TreeSet<>();
		t2.add("Orange");
		t2.add("Mango");
		t2.add("Pear");
		t2.add("Banana");
		t2.add("Apple");

        System.out.println("In Descending order");
```


## Iterator<String> itr2 = t2.descendingIterator();  //for descending order


```java
         itr2.forEachRemaining(x -> System.out.println(x));
	}
}

```


> **Note :- descendingIterator() is a predefined method of TreeSet class which will traverse in the descending order and return type of this method is Iterator interface.**


```java
public Iterator descendingIterator()
```

```java
import java.util.*;
public class TreeSetDemo2
{
	public static void main(String[] args)
	{
		Set<String> t = new TreeSet<>((s1,s2)-> s2.compareTo(s1));
		t.add("6");
		t.add("5");
		t.add("4");
		t.add("2");
		t.add("9");
```


## Iterator<String> iterator = t.iterator();


## iterator.forEachRemaining(x -> System.out.println(x));


```java
		//From 1.8 to replace hasNext() and next() method
	}
}
```

```java
import java.util.*;

public class TreeSetDemo3
	{
	public static void main(String[] args)
	{
		Set<Character> t = new TreeSet<>();
		t.add('A');
		t.add('C');
		t.add('B');
		t.add('E');
		t.add('D');
```


## Iterator<Character> iterator = t.iterator();


## iterator.forEachRemaining(x -> System.out.println(x));

```java
	}
}

```

Note : All the Wrapper classes as well as String class implements Comparable interface.
```java
//How to work with Custom Object
```

```java
package com.ravi.treeset_ex;

import java.util.TreeSet;

```

record Customer(Integer custId, String custName, Double custBill)
```java
{

}


public class TreeSetDemo4 {

	public static void main(String[] args)
	{
		TreeSet<Customer> ts1 = new TreeSet<>((c1,c2)->c1.custId().compareTo(c2.custId()));

		ts1.add(new Customer(333, "Aryan", 15000D));
		ts1.add(new Customer(111, "Raj", 15000D));
		ts1.add(new Customer(222, "Zuber", 15000D));
		System.out.println("Sorted based on the Customer Id :");
		ts1.forEach(System.out::println);

TreeSet<Customer> ts2 = new TreeSet<>((c1,c2)->c1.custName().compareTo(c2.custName()));

		ts2.add(new Customer(333, "Aryan", 15000D));
		ts2.add(new Customer(111, "Raj", 15000D));
		ts2.add(new Customer(222, "Zuber", 15000D));
		System.out.println("Sorted based on the Customer Name :");
		ts2.forEach(System.out::println);

	}

}
```

```java
package com.ravi.treeset_ex;

import java.util.ArrayList;
import java.util.SortedSet;
import java.util.TreeSet;

public class TreeSetDemo5 {

	public static void main(String[] args)
	{
		SortedSet<String> cityName = new TreeSet<>();
		cityName.add("Hyderabad");
		cityName.add("Mumbai");
		cityName.add("Pune");
		cityName.add("Ameerpet");

		TreeSet<String> nameOfCity = new TreeSet<>(cityName);
		System.out.println(nameOfCity);

		System.out.println(".............");

```


## ArrayList<String> listOfCity = new ArrayList<>(cityName);

```java
		System.out.println(listOfCity);
	}

}
```


### Methods of SortedSet interface

```java
public E first() :- Will fetch first element

public E last() :- Will fetch last element

public SortedSet headSet(int range) :- Will fetch the values which are less than specified range

public SortedSet tailSet(int range) :- Will fetch the values which are equal and greater than the specified range.

public SortedSet subSet(int startRange, int endRange) :- Will fetch the range of values where startRange is inclusive and endRange is exclusive.

```


> **Note :- headSet(), tailSet() and subSet(), return type is SortedSet.**

```java
import java.util.*;
public class SortedSetMethodDemo
{
       public static void main(String[] args)
       {
            TreeSet<Integer> times = new TreeSet<>();
            times.add(1205);
            times.add(1505);
            times.add(1545);
			times.add(1600);
            times.add(1830);
            times.add(2010);
            times.add(2100);

            SortedSet<Integer> sub = new TreeSet<>();

			sub =   times.subSet(1545,2100);
            System.out.println("Using subSet() :-"+sub);//[1545, 1600,1830,2010]
            System.out.println(sub.first());
            System.out.println(sub.last());

		    sub = times.headSet(1545);
			System.out.println("Using headSet() :-"+sub); //[1205, 1505]

		     sub =  times.tailSet(1545);
			 System.out.println("Using tailSet() :-"+sub); //[1545 to 2100]
       }
}
```

While working with methods of SortedSet interface we are getting elements based on the range of values but the navigation among the element is not possible by using SortedSet.

NavigableSet :
In order to provide navigation among the elements they introduced a new interface called NaviagableSet available from JDK 1.6.

NavigablSet provides various method to navigate among the elements frequently.
```java
import java.util.*;

public class NavigableSetDemo
{
    public static void main(String[] args)
    {
        NavigableSet<Integer> ns = new TreeSet<>();
        ns.add(1);
        ns.add(2);
        ns.add(3);
        ns.add(4);
        ns.add(5);
        ns.add(6);

		System.out.println("lower(3): " + ns.lower(3));//Just below than the specified element or null

       System.out.println("floor(3): " + ns.floor(3)); //Equal  less or null

       System.out.println("higher(3): " + ns.higher(3));//Just greater than specified element or null

       System.out.println("ceiling(3): " + ns.ceiling(3));//Equal or greater or null


    }
}
```


### Map interface Hierarchy

The hierarchy is available in paint diagram 31-JULY

### Map interface

```java
As we know Collection interface is used to hold single Or individual object but Map interface will hold group of objects in the form key and value pair. {key = value}

```

Map interface is not the part the Collection.

Before Map interface We had Dictionary(abstract class) class and it is extended by Hashtable class in JDK 1.0V

Map interface works with key and value pair introduced from 1.2V.

Here key and value both are objects.

Here key must be unique and value may be duplicate.

Each key and value pair is creating one Entry.(Entry is nothing but the combination of key and value pair)

```java
interface Map<K,V>
{
     interface Entry<K,V>
      {
         //key and value
      }
}

```

How to represent this entry interface (Map.Entry in .java) [Map$Entry in .class]

In Map interface whenever we have a duplicate key then the old key value will be replaced by new key(duplicate key) value.

```java
forEach(BiConsumer cons) method is available in Map interface.

```


## Iterator and ListIterator we can't use directly using Map.


### Methods of Map interface

1) Object put(Object key, Object value) :- To insert one entry in the Map collection. It will return the old object key value if the key is already available(Duplicate key), If key is not available then it will return null.

2) putIfAbsent(Object key, Object value) :- It will insert an entry if and only if key is not present , if the key is already available then it will not insert the Entry to the Map Collection


3) Object get(Object key) :- It will return  corresponding value of key, if the key is not present then it will return null.

4) Object getOrDefault(Object key, Object defaultValue) :- To avoid null value this method has been introduced, here we can pass some defaultValue to avoid the null value.

5) boolean containsKey(Object key) :- To Search a particular key

6) boolean containsValue(Object value) :- To Search a particular value

7) int size() :- To count the number of Entries.

8) remove(Object key) :- One complete entry will be removed.

9) void clear() :- Used to clear the Map

10) boolean isEmpty() :- To verify Map is empty or not?

11) void putAll(Map m) :- Merging of two Map collection
Map interface has provided few methods to convert the map into collection which are known as Collection Views method.

Methods of map interface to convert the map into Collection :
We have map interafce methods through which we can convert map interface into collection interface which is known as collection views
method.

1) public Set<Object> keySet() : It will retrieve all the keys.

2) public Collection values() : It will retrieve all the values.

3) public Set<Map.Entry> entrySet() : It will retrieve key and value
both in a single object.
How to generate Custom HashCode for String

```java
package com.ravi.map;


public class CustomStringHashCode
{
    public static int customHashCode(String str)
    {
        if (str == null)
        {
            return 0; // defualt value for null is 0
        }

        int hashCode = 0;

        for (int i = 0; i < str.length(); i++)
        {
            char charValue = str.charAt(i);
            hashCode = 31 * hashCode + charValue;
        }

        return hashCode;
    }

    public static void main(String[] args)
    {
    	String exampleString = "SURAJ";

        // Using the built-in hashCode method
        int hashCodeBuiltIn = exampleString.hashCode();
        System.out.println("Built-in hashCode: " + hashCodeBuiltIn);

        // Using the customHashCode method
        int customHashCode = customHashCode(exampleString);
        System.out.println("Custom hashCode: " + customHashCode);
    }
}
```


## 02-08-2024

**** How HashMap works internally ?
a) While working with HashSet or HashMap every object must be compared because duplicate objects are not allowed.

b) Whenever we add any new key to verify whether key is unique or duplicate, HashMap internally uses hashCode(), == operator and equals method.

c) While adding the key object in the HashMap, first of all it will invoke the hashCode() method to retrieve the corresponding key hashcode value.
```java
    Example :- hm.put(key,value);
               then internally key.hashCode();

```

d) If the newly added key and existing key hashCode value both are same (Hash collision), then only == operator is used for comparing those keys by using reference or memory address, if both keys references are same then existing key value will be replaced with new key value.

If the reference of both keys are different then equals(Object obj) method is invoked to compare those keys by using state(data). [content comparison]

If the equals(Object obj) method returns true (content wise both keys are same), this new key is duplicate then existing key value will be replaced by new key value.

If equals(Object obj) method returns false, this new key is unique, new entry (key-value) will be inserted in the same
Bucket.


> **Note :- equals(Object obj) method is invoked only when two keys are having same hashcode as well as their references are different.**


e) Actually by calling hashcode method we are not comparing the objects, we are just storing the objects in a group so the currently adding key object will be compared with its SAME HASHCODE GROUP objects, but not with all the keys which are available in the Map.

f) The main purpose of storing objects into the corresponding group to decrease the number of comparison so the efficiency of the program will increase.

g) To insert an entry in the HashMap, HashMap internally uses Hashtable data structure.

h) Now, for storing same hashcode object into a single group, hash table data structure internally uses one more data structure called Bucket.

i) The Hashtable data structure internally uses Node class array object.

j) The bucket data structure internally uses LinkedList data structure, It is a single linked list again implemented by Node class only.

*k) A bucket is group of entries of same hash code keys.

l) Performance wise LinkedList is not good to serach, so from java 8 onwards LinkedList is changed to Binary tree to decrease the number of comparison within the same bucket hashcode if the number of entries are greater than 8.
* equals() and hashCode() method contract :
Both the methods are working together to find out the duplicate objects in the Map.

*If equals() method invoked on two objects and it returns true then hashcode of both the objects must be same.

Note : IF TWO OBJECTS ARE HAVING SAME HASH CODE THEN IT MAY BE SAME OR DIFFERENT BUT IF EQUALS(OBJECT OBJ) METHOD RETURN TRUE THEN BOTH OBJECTS MUST RETURN SAME HASHCODE.

### What will happen if we don't follow the contract ?


### Case 1

If we override only equals(Object obj)
If we override only equals(Object obj) method for content comparison
then same object will have different hashcode (due to new keyword) hence same object (content wise) will move into two different
buckets [Duplication].

Case 2 :
If we override only hashCode() method
If we overrdie only hashCode() method then two object which are having same hashcode (due to overriding) will go to same bucket but == operator and equals(Object obj) method of Object class, both will return false hence duplicate object will be inserted into same bucket.


So, the conclusion is compulsory we need to override both the methods for removing duplicate elements.
```java
package com.nit.hashmap_internal;

import java.util.HashMap;

public class HashMapInternalDemo1
{
	public static void main(String[] args)
	{

		HashMap<String,Integer> hm1 = new HashMap<>();
		hm1.put("A", 1);
		hm1.put("A", 2);
		hm1.put(new String("A"), 3);
		System.out.println("Size is :"+hm1.size());
		System.out.println(hm1);

		System.out.println("....................");

		HashMap<Integer,Integer> hm2 = new HashMap<>();
		hm2.put(128, 1);
		hm2.put(128, 2);
		System.out.println("Size is :"+hm2.size());
		System.out.println(hm2);
		System.out.println("....................");


		HashMap hm3 = new HashMap();
		hm3.put("A", 1);
		hm3.put("A", 2);
		hm3.put(new String("A"), 3);
		hm3.put(65, 4);
		System.out.println("Size is :"+hm3.size());
		System.out.println(hm3);
	}
}
```

```java
package com.nit.hashmap_internal;

import java.util.HashMap;
import java.util.Objects;

class Customer
{
	private int customerId;
	private String customerName;

	public Customer(int customerId, String customerName) {
		super();
		this.customerId = customerId;
		this.customerName = customerName;
	}

	@Override
	public int hashCode()
	{
		return Objects.hash(customerId, customerName);
	}

	@Override
	public boolean equals(Object obj) {
		if (this == obj)
			return true;
		if (obj == null)
			return false;
		if (getClass() != obj.getClass())
			return false;
		Customer other = (Customer) obj;
		return customerId == other.customerId && Objects.equals(customerName, other.customerName);
	}




}
public class HashMapInternalDemo2
{

	public static void main(String[] args)
	{
	   Customer c1 = new Customer(111, "Scott");
	   Customer c2 = new Customer(111, "Scott");

	   //System.out.println(c1.hashCode()+" : "+c2.hashCode());

	   HashMap<Customer,String> map = new HashMap<>();
	   map.put(c1, "A");
	   map.put(c2, "B");

	   System.out.println(map.size());
	}

}

```

Customer class we are using as a HashMap key so it must override
```java
hashCode() and equals(Object obj) as well as at advanced level, It must be immutable class.

```

All the Wrapper classes and String class are immutable as well as
hashCode() and equals(Object obj) methods are overridden in these classes so perfectly suitable to becoming HashMap key.
```java
package com.nit.hashmap_internal;

import java.util.HashMap;

```

record Customer(Integer employeeId, String employeeName)
```java
{

}

public class HashMapInternalDemo2
{

	public static void main(String[] args)
	{
	   Customer c1 = new Customer(111, "Scott");
	   Customer c2 = new Customer(111, "Scott");

	   System.out.println(c1.hashCode()+" : "+c2.hashCode());

	   HashMap<Customer,String> map = new HashMap<>();
	   map.put(c1, "A");
	   map.put(c2, "B");

	   System.out.println(map.size());
	}

}
```

Instead of BLC classes we can migrate to record classes which is suitable for becoming HashMap key.

## 03-08-2024

HashMap<K,V> :-  [Unsorted, Unordered, No Duplicate keys]
```java
public class HashMap<K,V> extends AbstractMap<K,V> implements Map<K,V>, Serializable, Clonable

```

It is a predefined class available in java.util package under Map interface available from JDK 1.2v.

It gives us unsorted and Unordered map. when we need a map and we don't care about the order while iterating the elements through it then we should use HashMap.

It inserts the element based on the hashCode of the Object key using hashing technique [hasing alogorithhm]

It does not accept duplicate keys but value may be duplicate.

It accepts only one null key(because duplicate keys are not allowed) but multiple null values are allowed.

HashMap is not synchronized.

Time complexcity of search, insert and delete will be O(1)

We should use HashMap to perform fast searching opeartion.

For eliminating duplicate keys in hashMap object we should compulsory follow the contract between hashcode and equals(Object obj)

It contains 4 types of constructor

```java
1) HashMap hm1 = new HashMap();
```

It will create the HashMap Object with default capacity is 16. The default load fator or Fill Ratio is 0.75   (75% of HashMap is filled up then new HashMap Object will be created having double capacity)

```java
2) HashMap hm2 = new HashMap(int initialCapacity);
```

will create the HashMap object with user specified capacity


```java
3) HashMap hm3 = new HashMap(int initialCapacity, float loadFactor);
```

we can specify our own initialCapacity and loadFactor(by default load factor is 0.75)

```java
4)HashMap hm4 = new HashMap(Map m);
```

Interconversion of Map Collection
```java
//Program that shows HashMap is unordered
import java.util.*;
public class HashMapDemo
{
      public static void main(String[] a)
      {
           Map<String,String> map = new HashMap<>();
		   map.put("Ravi", "12345");
		   map.put("Rahul", "12345");
		   map.put("Aswin", "5678");
		   map.put(null, "6390");
		   map.put("Ravi","1529");
		   map.put("Aamir","890");

		   System.out.println(map); //{key = value}

		   map.forEach((k,v)-> System.out.println("Key is :"+k+" value is "+v));

      }
}
```

```java
//Program to search a particular key and value in the Map collection
import java.util.*;
public class HashMapDemo1
{
	public static void main(String args[])
	{
		HashMap<Integer,String> hm = new HashMap<>();
		hm.put(1, "JSE");
		hm.put(2, "JEE");
		hm.put(3, "JME");
		hm.put(4,"JavaFX");
		hm.put(5,null);
		hm.put(6,null);

		System.out.println("Initial map elements: " + hm);
		System.out.println("key 2 is present or not :"+hm.containsKey(2));

		System.out.println("JME is present or not :"+hm.containsValue("JME"));

		System.out.println("Size of Map : " + hm.size());
		hm.clear();
		System.out.println("Map elements after clear: " + hm); //{}
	}
}
```

```java
//Collection view methods [keySet(),  values(), Set<Map.Entry> entrySet()]
import java.util.*;
public class HashMapDemo2
{
public static void main(String args[])
	{
			Map<Integer,String> map = new HashMap<>();
			map.put(1, "C");
			map.put(2, "C++");
			map.put(3, "Java");
			map.put(4, ".net");

			map.forEach((k,v)->System.out.println("Key :"+k+" Value :"+v) );

			System.out.println("Return Old Object value :"+map.put(4,"Python"));

			Set keys =  map.keySet();
			System.out.println("All keys are :"+keys); //[1,2,3,4]

			Collection values = map.values();
			System.out.println("All values are :"+values);

			for(Map.Entry m : map.entrySet())
			 {
				 System.out.println(m.getKey()+" : "+m.getValue());
			}

			System.out.println("Retrieving using Iterator :");

```


## Iterator itr=  map.entrySet().iterator();


```java
			while(itr.hasNext())
		    {
				System.out.println(itr.next());
			}
	}
}
```

```java
import java.util.*;
public class HashMapDemo3
{
public static void main(String args[])
  {
		HashMap<Integer,String> map = new HashMap<>(26,0.95f);
		map.put(1, "Java");
		map.put(2, "is");
		map.put(3, "best");
```

map.remove(3);  //will remove the complete Entry
```java
		String val=(String)map.get(3);
		System.out.println("Value for key 3 is: " + val);
		map.forEach((k,v)->System.out.println(k +" : "+v));
   }
}
```

```java
//To merge two Map Collection (putAll)
import java.util.*;
public class HashMapDemo4
{
public static void main(String args[])
	{
		HashMap<Integer,String> newmap1 = new HashMap<>();

		HashMap<Integer,String> newmap2 = new HashMap<>();

		newmap1.put(1, "OCPJP");
		newmap1.put(2, "is");
		newmap1.put(3, "best");

		System.out.println("Values in newmap1: "+ newmap1);

		newmap2.put(4, "Exam");

		newmap2.putAll(newmap1);

		newmap2.forEach((k,v)->System.out.println(k+" : "+v));
   }
}
```

```java
import java.util.*;
public class HashMapDemo5
{
     public static void main(String[] argv)
     {
          Map<String,String> map = new HashMap<>(9, 0.85f);
          map.put("key", "value");
          map.put("key2", "value2");
          map.put("key3", "value3");
		  map.put("key7","value7");


```

Set keys = map.keySet();//keySet return type is Set
```java
		   System.out.println(keys ); //[]

```

Collection val = map.values(); //values return type is collection
```java
          System.out.println(val);

		  map.forEach((k,v)-> System.out.println(k+" : "+v));


      }
}
```

```java
//getOrDefault() method
import java.util.*;
public class  HashMapDemo6
{
	public static void main(String[] args)
	{
		Map<String, String> map = new HashMap<>();
		map.put("A", "1");
		map.put("B", "2");
		map.put("C", "3");
        //if the key is not present, it will return default value .It is used to avoid null
		String value = map.getOrDefault("D","Key is not available");
		System.out.println(value);
		System.out.println(map);
	}
}
```

```java
//interconversion of two HashMap using Constructor
import java.util.*;
public class HashMapDemo7
	{
	public static void main(String args[])
	{
		HashMap<Integer, String> hm1 = new HashMap<>();

		hm1.put(1, "Ravi");
		hm1.put(2, "Rahul");
		hm1.put(3, "Rajen");

		HashMap<Integer, String> hm2	= new HashMap<>(hm1);

		System.out.println("Mapping of HashMap hm1 are : "	+ hm1);

		System.out.println("Mapping of HashMap hm2 are : " + hm2);
	}
}
```

```java
import java.util.*;
class Employee
{
	int eid;
	String ename;

	Employee(int eid, String ename)
	{
		this.eid = eid;
		this.ename = ename;
	}

     @Override
	public boolean equals(Object obj)  //obj = e2
	{
		if(obj instanceof Employee)
        {
```

Employee e2 = (Employee) obj; //downcasting

```java
			if(this.eid == e2.eid && this.ename.equals(e2.ename))
			{
				return true;
			}
			else
			{
				return false;
			}
	    }
		else
		{
			System.out.println("Comparison is not possible");
			return false;
		}
	}


	public String toString()
		{
			 return " "+eid+" "+ename;
		}
}
public class HashMapDemo8
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(101,"Aryan");
		Employee e2 = new Employee(102,"Pooja");
		Employee e3 = new Employee(101,"Aryan");
		Employee e4 = e2;


		HashMap<Employee,String> hm = new HashMap<>();
		hm.put(e1,"Ameerpet");
		hm.put(e2,"S.R Nagar");
		hm.put(e3,"Begumpet");
		hm.put(e4,"Panjagutta");

		hm.forEach((k,v)-> System.out.println(k+" : "+v));
	}
}

```

When hashcodes are different then comparison will be done by using == operator.
LinkedHashMap<K,V>
```java
public class LinkedHashMap<K,V> extends HashMap<K,V> implements Map<K,V>

```

It is a predefined class available in java.util package under Map interface available from 1.4.

It is the sub class of HashMap class.

It maintains insertion order. It contains a doubly linked with the elements or nodes so It will iterate more slowly in comparison to HashMap.

It uses Hashtable and LinkedList data structure.

If We want to fetch the elements in the same order as they were inserted then we should go with LinkedHashMap.

It accepts one null key and multiple null values.

It is not synchronized.

It has also 4 constructors same as HashMap

```java
1) LinkedHashMap hm1 = new LinkedHashMap();
```

will create a  LinkedHashMap with default capacity 16 and load factor 0.75

```java
2) LinkedHashMap hm1 = new LinkedHashMap(iny initialCapacity);

3) LinkedHashMap hm1 = new LinkedHashMap(iny initialCapacity, float loadFactor);


4) LinkedHashMap hm1 = new LinkedHashMap(Map m);
```

```java
import java.util.*;
public class LinkedHashMapDemo
{
	public static void main(String[] args)
	{
		LinkedHashMap<Integer,String> l = new LinkedHashMap<>();
		l.put(1,"abc");
		l.put(3,"xyz");
		l.put(2,"pqr");
		l.put(4,"def");
		l.put(null,"ghi");
		System.out.println(l);
	}
}
```

```java
import java.util.*;

public class LinkedHashMapDemo1
{
      public static void main(String[] a)
      {
           Map<String,String> map = new LinkedHashMap<>();
           map.put("Ravi", "1234");
		   map.put("Rahul", "1234");
		   map.put("Aswin", "1456");
		   map.put("Samir", "1239");

		   map.forEach((k,v)->System.out.println(k+" : "+v));
      }
}
```

Hashtable<K,V>
```java
public class Hashtable<K,V> extends Dictionary<K,V> implements Map<K,V>, Clonable, Serializable

```

It is predefined class available in java.util package under Map interface from JDK 1.0.

Like Vector, Hashtable is also form the birth of java so called legacy class.

It is the sub class of Dictionary class which is an abstract class.

*The major difference between HashMap and Hashtable is, HashMap methods are not synchronized where as Hastable methods are synchronized.

HashMap can accept one null key and multiple null values where as Hashtable does not contain anything as a null(key and value both). if we try to add null then JVM will throw an exception i.e NullPointerException.

The initial default capacity of Hashtable class is 11 where as loadFactor is 0.75.


It has also same constructor as we have in HashMap.(4 constructors)

```java
1) Hashtable hs1 = new Hashtable();
```

It will create the Hashtable Object with default capacity as 11 as well as load factor is 0.75

```java
2) Hashtable hs2 = new Hashtable(int initialCapacity);
```

will create the Hashtable  object with specified capacity


```java
3) Hashtable hs3 = new Hashtable(int initialCapacity, float loadFactor);
```

we can specify our own initialCapacity and loadFactor

```java
4) Hashtable hs = new Hashtable(Map c);
```

Interconversion of Map Collection
```java
import java.util.*;
public class HashtableDemo
	{
	 public static void main(String args[])
		{
		  Hashtable<Integer,String> map=new Hashtable<>();
		  map.put(1, "Java");
		  map.put(2, "is");
		  map.put(3, "best");
		  map.put(4,"language");

		  //map.put(5,null);

		  System.out.println(map);

		  System.out.println(".......................");

		    for(Map.Entry m : map.entrySet())
			 {
				 System.out.println(m.getKey()+" = "+m.getValue());
			}
        }
}
```

```java
import java.util.*;
public class HashtableDemo1
{
   public static void main(String args[])
	{
    Hashtable<Integer,String> map=new Hashtable<>();
     map.put(1,"Priyanka");
     map.put(2,"Ruby");
     map.put(3,"Vibha");
     map.put(4,"Kanchan");

	 map.putIfAbsent(5,"Bina");
	 map.putIfAbsent(24,"Pooja");
	 map.putIfAbsent(26,"Ankita");

     map.putIfAbsent(1,"Sneha");
     System.out.println("Updated Map: "+map);
 }
}
```


### WeakHashMap<K,V>

```java
public class WeakHashMap<K,V> extends AbstractMap<K,V> implements Map<K,V>

```

It is a predefined class in java.util package under Map interface.It was introduced from JDK 1.2v onwards.

While working with HashMap, keys of HashMap are of strong reference type. This means the entry of  map will not be deleted by the garbage collector even though the key is set to be null and  still it is not eligible for Garbage Collector.

On the other hand while working with WeakHashMap, keys of WeakHashMap are of weak reference type. This means the entry and corresponding object of a map is deleted by the garbage collector if the key value is set to be null because it is of weak type.

So, HashMap dominates over Garbage Collector where as Garbage Collector dominates over WeakHashMap.

It contains 4 types of Constructor :
```java
1) WeakHashMap wm1 = new WeakHashMap();

```

Creates an empty WeakHashMap object with default capacity is 16 and load fator 0.75


```java
2) WeakHashMap wm2 = new WeakHashMap(int initialCapacity);

3) WeakHashMap wm3 = new WeakHashMap(int initialCapacity, float loadFactor);

    Eg:- WeakHashMap wm = new WeakHashMap(10,0.9);

```

capacity - The capacity of this map is 10. Meaning, it can store 10 entries.

loadFactor - The load factor of this map is 0.9. This means whenever our hashtable is filled up by 90%, the entries are moved to a new hashtable of double the size of the original hashtable.

```java
4) WeakHashMap wm4 = new WeakHashMap(Map m);
```

```java
package com.ravi.map_demo;

import java.util.WeakHashMap;

```

record Product(Integer productId, String productName, Double productPrice)
```java
{
	@Override
	public void finalize()
	{
		System.out.println("Product object is eligible for GC");
	}
}


public class WeakHashMapDemo
{
	public static void main(String[] args) throws Exception
	{
		Product p1 = new Product(111, "Camera", 43000D);

		WeakHashMap<Product,String> hm = new WeakHashMap<>();
		hm.put(p1, "Hyderabad");
		System.out.println(hm);

		p1 = null;

		System.gc();

```


## Thread.sleep(5000);


```java
		System.out.println(hm); //{}

	}

}

```

Note : Here finalize method will be invoked because Product object is
eligible for GC as well as entry of WeakHashMap will be deleted.

## 05-08-2024


### How to generate System hashcode

As we know we have predefined method called hashCode() available in
java.lang.Object class which is used to find the bucket location in the Hashtable.
If we want to generate System hashcode then we can use the following static method of System class.
```java
System.identityHashCode(Object obj);
```

```java
package com.ravi.identity_hash_code;

public class SystemHashCode
{
	public static void main(String[] args)
	{
		String str = "india";
		System.out.println("String class hashcode :"+str.hashCode());
		System.out.println("System generated hashcode :"+System.identityHashCode(str));
	}

}
```


IdentityHashMap<K,V> : [Comparing keys based on the Memory reference]
```java
public class IdentityHashMap<K,V> extends AbstractMap<K,V> implements Map<K,V>, Clonable, Serializable.

```

It was introduced from JDK 1.4 onwards.

The IdentityHashMap uses == operator to compare keys.

As we know HashMap uses equals() and hashCode() method for comparing the keys based on the hashcode of the object it will serach the bucket location and insert the entry their only.

So We should use IdentityHashMap where we need to check the reference or memory address instead of logical equality.

HashMap uses hashCode of the "Object key" to find out the bucket loaction in Hashtable, on the other hand IdentityHashMap does not use hashCode() method actually It uses System.identityHashCode(Object o)

IdentityHashMap is more faster than HashMap in case of key Comparison.

The default capacity is 32.

It has three constrcutors, It does not contain loadFactor specific constructor.
```java
package com.ravi.identity_hash_code;

import java.util.HashMap;
import java.util.IdentityHashMap;

public class IdentityHashCodeDemo {

	public static void main(String[] args)
	{
		HashMap<String,String> hm = new HashMap<>();
		hm.put("A", "1");
		hm.put(new String("A"), "2");
		System.out.println("HashMap size :"+hm.size());

		IdentityHashMap<String,String> ihm = new IdentityHashMap<>();
		ihm.put("A", "1");
		ihm.put(new String("A"), "2");
		System.out.println("IdentityHashMap size :"+ihm.size());
	}

}
```

SortedMap<K,V>
It is a predefined interface available in java.util package under Map interface.

We should use SortedMap interface when we want to insert the key element based on some sorting order i.e the default natural sorting order.
TreeMap<K,V>
```java
public class TreeMap<K,V> extends AbstractMap<K,V> implements NavigableMap<K,V> , Clonable, Serializable

```

It is a predefined class avaialble in java.util package under Map interface available for 1.2V.

It is a sorted map that means it will sort the elements by natural sorting order based on the key or by using Comparator interface as a constructor parameter.

It does not allow non comparable keys.

It does not accept null key but null value allowed.

TreeMap implements NavigableMap and NavigableMap extends SortedMap. SortedMap extends Map interface.

TreeMap contains 4 types of Constructors :

1) TreeMap tm1 = new TreeMap(); //creates an empty TreeMap

2)  TreeMap tm2 = new TreeMap(Comparator cmp); //user defined soting logic

```java
3)  TreeMap tm3 = new TreeMap(Map m);

4)  TreeMap tm4 = new TreeMap(SortedMap m);
```

```java
import java.util.*;
public class TreeMapDemo
{
	public static void main(String[] args)
	{
		TreeMap<Object,String> t = new TreeMap<>();
		t.put(4,"Ravi");
		t.put(7,"Aswin");
		t.put(2,"Ananya");
		t.put(1,"Dinesh");
		t.put(9,"Ravi");
		t.put(3,"Ankita");
		t.put(5,null);


		System.out.println(t);
	}
}
```

```java
import java.util.*;
public class TreeMapDemo1
{
      public static void main(String args[])
      {
            TreeMap map = new TreeMap();
            map.put("one","1");
            map.put("two",null);
            map.put("three","3");
			map.put("four",4);

            displayMap(map);

	map.forEach((k, v) -> System.out.println("Key = " + k + ", Value = " + v));

      }
      static void displayMap(TreeMap map)
      {
```

Collection c = map.entrySet();   //Set<Map.Entry>


## Iterator i = c.iterator();

```java
           i.forEachRemaining(x -> System.out.println(x));
      }
}
```

```java
//firstKey()  lastKey()  headMap()  tailMap()  subMap()      SortedMap
// first()     last()     headSet()  tailSet()  subSet()     SortedSet

import java.util.*;
public class TreeMapDemo2
{
    public static void main(String[] argv)
    {
        Map map = new TreeMap();
        map.put("key2", "value2");
        map.put("key3", "value3");
        map.put("key1", "value1");

        System.out.println(map); //{}

        SortedMap x = (SortedMap) map;
        System.out.println("First key is :"+x.firstKey());
        System.out.println("Last Key is :"+x.lastKey());
     }
}
```

```java
package com.ravi.treemap;

import java.util.TreeMap;

```

record Student(Integer studentId, String studentName) implements Comparable<Student>
```java
{
	@Override
	public int compareTo(Student s2)
	{
		return this.studentId.compareTo(s2.studentId);
	}


}


public class TreeMapDemo3
{
	public static void main(String[] args)
	{
		TreeMap<Student, String> tm = new TreeMap<>();
		tm.put(new Student(2, "Sailesh"), "Hyderabad");
		tm.put(new Student(1, "Zuber"), "BBSR");

		tm.forEach((k,v)-> System.out.println("Key is :"+k+" and Address is :"+v));
	}

}

```

Here, Keys are sorted based on the Comparable i.e acsending order of studentid
```java
package com.ravi.treemap;

import java.util.TreeMap;

```

record Employee(Integer employeeId, String employeeName)
```java
{

}

public class TreeMapDemo4 {

	public static void main(String[] args)
	{
		TreeMap<Employee,String> tm1 = new TreeMap<>((e1,e2)-> e2.employeeName().compareTo(e1.employeeName()));



		tm1.put(new Employee(333, "Raj"),"TCS");
		tm1.put(new Employee(111, "Dinesh"),"WIPRO");
		tm1.put(new Employee(222, "Aryan"),"NIT");

		tm1.forEach((k,v)-> System.out.println("Key is :"+k+" value is :"+v));


	}

}
```

```java
package com.ravi.treemap;

import java.util.TreeMap;

public class TreeMapDemo5 {

	public static void main(String[] args)
	{
		TreeMap<String,Integer> map = new TreeMap<>(String::compareTo);
		map.put("raj", 1);
		map.put("ravi", 2);
		map.put("rahul",3);

		System.out.println(map);

	}

}
```


### Methods of SortedMap interface

1) firstKey()  //first key

2) lastKey()  //last key

3) headMap(int keyRange) //less than the specified range

4) tailMap(int keyRange)  //equal or greater than the specified range

5) subMap(int startKeyRange, int endKeyRange) //the range of key where startKey will be inclusive and endKey will be exclusive.

```java
return type of headMap(), tailMap() and subMap() return type would be SortedMap(I)
```

```java
import java.util.*;
public class SortedMapMethodDemo
	{
 public static void main(String args[])
	 {
		SortedMap<Integer,String> map=new TreeMap<>();
		  map.put(100,"Amit");
		  map.put(101,"Ravi");

		  map.put(102,"Vijay");
		  map.put(103,"Rahul");

		  System.out.println("First Key: "+map.firstKey());  //100
		   System.out.println("Last Key "+map.lastKey());   //103
		   System.out.println("headMap: "+map.headMap(102));  //100 101
		   System.out.println("tailMap: "+map.tailMap(102));  //102 103
		   System.out.println("subMap: "+map.subMap(100, 102)); //100 101

	 }
 }
```


### Assignment for NavigableMap Method


### Properties

```java
public class Properties extends Hashtable<K,V>

```

Properties class is used to maintain the data in the key-value form. It takes both key and value as a string.

Properties class is a subclass of Hashtable.

It provides the methods to store properties in a properties file (load method).

Properties class has provided a non static method load(InputStream reader) through which we can load the properties fire.


It has also provided non static method getProperty(String key) to get the value based on the specified key.

System class has provided a predefined static method properties() through which we can get the complete properties of a System/laptop.

### Program 1


### Create a file with any name having extension .properties


db.properties :
```java
 driver = oracle.jdbc.driver.OracleDriver
 user = system
 password = manager


```

PropertiesExample1.java
```java
import java.util.*;
import java.io.*;
public class PropertiesExample1
{
public static void main(String[] args)throws Exception
 {
    FileReader reader=new FileReader("db.properties");

    Properties p=new Properties();
    p.load(reader);

    String driver = p.getProperty("driver");
	System.out.println(driver);

	String user = p.getProperty("user");
	System.out.println(user);

	String pwd = p.getProperty("password");
	System.out.println(pwd);

    }
}

```

If we make changes in the properties file then directly (without compilation) we can take the the value in our java file so after any modification in the properties file we need not to re-compile/re-deploy the file.
```java
import java.util.*;
import java.io.*;
public class PropertiesExample2
{
public static void main(String[] args)throws Exception
{
	Properties p=System.getProperties();
	Set set=p.entrySet();

```


## Iterator itr=set.iterator();

```java
	while(itr.hasNext())
    {
		Map.Entry entry=(Map.Entry)itr.next();
		System.out.println(entry.getKey()+" = "+entry.getValue());
	}

}  }

```

It will provide complete System properties.

## 06-08-2024


### Queue interface

1) It is sub interface of Collection(I) available from JDK 1.5V

2) It works in FIFO(First In first out)

3) It is an ordered collection.

4) In a queue, insertion is possible from last is called REAR where as deletion is possible from the starting is called FRONT of the queue.

5) From jdk 1.5 onwards LinkedList class implments Queue interface to handle the basic queue operations.

PriorityQueue :
```java
public class PriorityQueue extends AbstractQueue implements Serializable

```

It is a predefined class in java.util package, available from Jdk 1.5 onwards.

It stores the elements using min-heap tree, meaning the smallest element is at the head of the queue.

The elements of the priority queue are ordered according to their natural ordering (min heap tree), or by using Comparator provided at queue construction time, depending on which constructor is used.

A priority queue does not permit null elements.

It provides natural sorting order so we can't take non-comparable objects(hetrogeneous types of Object)

The initial capacity of PriorityQueue is 11.

Constructor :
```java
1) PriorityQueue pq1 = new PriorityQueue();

2) PriorityQueue pq2 = new PriorityQueue(int initialCapacity);

3) PriorityQueue pq3 = new PriorityQueue(int initialCapacity, Comparator cmp);

4) PriorityQueue pq3 = new PriorityQueue(Comparator cmp);


5) PriorityQueue pq4 = new PriorityQueue(Collection c);

```



### Methods

```java
add() / offer() :- Used to add an element in the Queue

poll() :- It is used to fetch the elements from head of the queue, after fetching it will delete the element.


```

peek() :- It is also used to fetch the elements from head of the queue, Unlike poll it will only fetch but not delete the element.

```java
boolean remove(Object element) :- It is used to remove an element. The return  type is boolean.
```

```java
import java.util.PriorityQueue;

public class PriorityQueueDemo
{
      public static void main(String[] argv)
      {
            PriorityQueue<String> pq = new PriorityQueue<>();
            pq.add("Orange");
			pq.add("Apple");
			pq.add("Mango");
			pq.add("Guava");
			pq.add("Grapes");


			System.out.println(pq);

      }
}
```

```java
import java.util.PriorityQueue;
public class PriorityQueueDemo1
{
      public static void main(String[] argv)
      {
            PriorityQueue<Integer> pq = new PriorityQueue<>();
	    pq.add(11);
            pq.add(2);
            pq.add(4);
	    pq.add(6);
           System.out.println(pq);
	  }
}
-----------------------------------------------------------------------    import java.util.PriorityQueue;
public class PriorityQueueDemo2
{
      public static void main(String[] argv)
      {
            PriorityQueue<String> pq = new PriorityQueue<>();
            pq.add("2");
            pq.add("4");
			pq.add("6");
            System.out.print(pq.peek() + " "); //2 2 3 4 4
            pq.offer("1");
			pq.offer("9");
```

pq.add("3");   //

```java
            pq.remove("1");
            System.out.print(pq.poll() + " ");
            if (pq.remove("2"))
                System.out.print(pq.poll() + " ");
            System.out.println(pq.poll() + " " + pq.peek()+"  "+pq.poll());
	  }
}
```

```java
import java.util.*;

```

record Task(String name, int priority)
```java
{
}


public class PriorityQueueDemo3 {
    public static void main(String[] args)
    {
```

PriorityQueue<Task> taskQueue = new PriorityQueue<>(new Comparator<Task>()
```java
		{
            @Override
            public int compare(Task t1, Task t2)
            {
                return Integer.compare(t1.priority(), t2.priority());
            }
        });

        taskQueue.add(new Task("Submit report", 4));
        taskQueue.add(new Task("Find Bug", 2));
        taskQueue.add(new Task("Write Program", 1));
        taskQueue.add(new Task("Execute Program", 3));

        while (!taskQueue.isEmpty())
        {
            System.out.println("Executing: " + taskQueue.poll());
        }
    }
}

```

Apart fron all these PriorityQueue also inserts the elemnts based on "Priority In and Priority Out"

## Generics


### Why generic came into picture

As we know our compiler is known for Strict type checking because java is a statically typed checked language.

The basic problem with collection is It can hold any kind of Object.


## ArrayList al = new ArrayList();

```java
al.add("Ravi");
al.add("Aswin");
al.add("Rahul");
al.add("Raj");
al.add("Samir");

for(int i =0; i<al.size(); i++)
{
   String s = (String) al.get(i);
   System.out.println(s);
}

```

By looking the above code it is clear that Collection stores everything in the form of Object so here even after adding String type only we need to provide casting as shown below.
```java
import java.util.*;
class Test1
{
	public static void main(String[] args)
	{
```


## ArrayList al = new ArrayList(); //raw type

```java
		al.add("Ravi");
		al.add("Ajay");
		al.add("Vijay");

		for(int i=0; i<al.size(); i++)
		{
		String name =  (String) al.get(i); //type casting is required
		System.out.println(name.toUpperCase());
		}

	}
}
```

Even after type casting there is no guarantee that the things which are coming from ArrayList Object is String only because we can add anything in the Collection as a result java.lang.ClassCastException as shown in the program below.

```java
import java.util.*;
class Test2
{
	public static void main(String[] args)
	{
```


## ArrayList t = new ArrayList(); //raw type

```java
		t.add("alpha");
		t.add("beta");
		for (int i = 0; i < t.size(); i++)
		{
		  String str =(String) t.get(i);
		  System.out.println(str);
		}

		 t.add(1234);
		 t.add(1256);
		  for (int i = 0; i < t.size(); ++i)
	       {
			 String obj= (String)t.get(i); //we can't perform type casting here
			 System.out.println(obj);
		  }
	}
}
```

To avoid all the above said problem Generics came into picture from JDK 1.5 onwards

-> It deals with type safe Object so there is a guarantee of both the end i.e putting inside and getting outside.

Example:-

## ArrayList<String > al = new ArrayList<>();


Now here we have a guarantee that only String can be inserted as well as only String will come out from the Collection so we can perform String related operation.

Advantages of Generics :
1) Type Safe Object (No Compilation warning)
2) No need of type casting
3) Strict compile time checking. (*Type Erasure)
```java
 import java.util.*;
public class Test3
{
public static void main(String[] args)
{
```


## ArrayList<String> al = new ArrayList<>();  //Generic type

```java
		al.add("Ravi");
		al.add("Ajay");
		al.add("Vijay");

        for(int i=0; i<al.size(); i++)
		{
		String name = al.get(i); //no type casting is required
		System.out.println(name.toUpperCase());
		}
   }
}
```

```java
//Program that describes the return type of any method can be type safe
//[We can apply generics on method return type]

import java.util.*;
public class Test4
{
	public static void main(String [] args)
	{
		Dog d1 = new Dog();
		Dog d2 = d1.getDogList().get(0);
		System.out.println(d2);
	}
}
class Dog
{
	public List<Dog> getDogList()
	{
```


## ArrayList<Dog> d = new ArrayList<>();

```java
        d.add(new Dog());
		d.add(new Dog());
		d.add(new Dog());
		return d;
	}
}
```


> **Note :- In the above program the compiler will stop us from returning anything which is not compaitable List<Dog> and there is a guarantee that only "type safe list of Dog object" will be returned so we need not to provide type casting as shown below**

Dog d2 = (Dog) d1.getDogList().get(0);  //before generic.
```java
//Mixing generic with non-generic
import java.util.*;

class Car
{
}
public class Test5
{
	public static void main(String [] args)
	{
```


## ArrayList<Car> a = new ArrayList<>();

```java
	a.add(new Car());
	a.add(new Car());
    a.add(new Car());

```


## ArrayList b = a;  //assigning Generic to raw type



```java
    System.out.println(b);
	}
}
```

```java
//Mixing generic to non-generic
import java.util.*;
public class Test6
{
	public static void main(String[] args)
	{
		List<Integer> myList = new ArrayList<>();
		myList.add(4);
		myList.add(6);
		myList.add(5);

		UnknownClass u = new UnknownClass();
		int total = u.addValues(myList);
		System.out.println("The sum of Integer Object is :"+total);
	}
}
class UnknownClass
{
	public int addValues(List list)  //generic to raw type OR
	{
```


## Iterator it = list.iterator();

```java
	int total = 0;
	while (it.hasNext())
	{
		int i = ((Integer)it.next());
```

total += i;                           //total =  15
```java
	}
	return total;
	}
}

```


> **Note :-**

In the above program the compiler will not generate any warning message because even though we are assigning type safe Integer Object to unsafe or raw type List Object but this List Object is not inserting anything new in the collection so there is no risk to the caller.
```java
//Mixing generic to non-generic
import java.util.*;
public class Test7
{
	public static void main(String[] args)
	{
		List<Integer> myList = new ArrayList<>();
		myList.add(4);
		myList.add(6);
		UnknownClass u = new UnknownClass();
		int total = u.addValues(myList);
		System.out.println(total);
	}
}
class UnknownClass
{
    public int addValues(List list)
	{
```

list.add(5);	//adding object to raw type

## Iterator it = list.iterator();

```java
		int total = 0;
		while (it.hasNext())
		{
		int i = ((Integer)it.next());
		total += i;
		}
		return total;
	}
}

```

Here Compiler will generate warning message because the unsafe object is inserting the value 5 to safe object.
*Type Erasure
In the above program the compiler will  generate  warning message because the unsafe List Object is inserting the Integer object 5 so the type safe Integer object is getting value 5 from unsafe type so there is a problem to the caller method.

By writing ArrayList<Integer> actually JVM does not have any idea that our ArrayList was suppose to hold only Integers.

All the type safe generics information does not exist at runtime. All our generic code is Strictly for compiler.

There is a process done by java compiler called "Type erasure" in which the java compiler converts generic version to non-generic type.

```java
List<Integer> myList = new ArrayList<Integer>();

```

At the compilation time it is fine but at runtime for JVM the code becomes

```java
List myList = new ArrayList();

```


> **Note :- GENERIC IS STRICTLY COMPILE TIME PROTECTION.**

```java
//Polymorphism with array :
```

```java
//Polymorphism with array

import java.util.*;
```


## abstract class Animal

```java
{
	public abstract void checkup();
}

class Dog extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Dog checkup");
	}
}

class Cat extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Cat checkup");
	}
}

class Bird extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Bird checkup");
	}
}

public class  Test8
{
	public void checkAnimals(Animal animals[])
	{
		for(Animal animal : animals)
		{
			animal.checkup();
		}
	}

	public static void main(String[] args)
	{
		Dog []dogs={new Dog(), new Dog()};

		Cat []cats={new Cat(), new Cat(), new Cat()};

		Bird []birds = {new Bird(), new Bird()};

		Test8 t = new Test8();

		t.checkAnimals(dogs);
		t.checkAnimals(cats);
		t.checkAnimals(birds);
	}
}

```


> **Note :-From the above program it is clear that polymorphism(Upcasting) concept works with array.**

```java
import java.util.*;
```


## abstract class Animal

```java
{
	public abstract void checkup();
}

class Dog extends Animal
{
    @Override
	public void checkup()
	{
		System.out.println("Dog checkup");
	}
}

class Cat extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Cat checkup");
	}
}
class Bird extends Animal
{
	@Override
	public void checkup()
	{
		System.out.println("Bird checkup");
	}
}
public class Test9
{
	public void checkAnimals(List<Animal> animals)
	{
		for(Animal animal : animals)
		{
             animal.checkup();
		}
	}
	public static void main(String[] args)
	{
		List<Dog> dogs = new ArrayList<>();
		dogs.add(new Dog());
		dogs.add(new Dog());

		List<Cat> cats = new ArrayList<>();
		cats.add(new Cat());
		cats.add(new Cat());

		List<Bird> birds = new ArrayList<>();
		birds.add(new Bird());

		Test9 t = new Test9();
		t.checkAnimals(dogs);
		t.checkAnimals(cats);
		t.checkAnimals(birds);

	}
}


```


> **Note :- The above program will generate compilation error.**


So from the above program it is clear that polymorphism does not work in the same way for generics as it does with arrays.

Example :

Parent [] arr = new Child[5]; //valid
Object [] arr = new String[5]; //valid

But in generics the same type is not valid

List<Object> list = new ArrayList<Integer>(); //Invalid
List<Parent> mylist = new ArrayList<Child>(); //Invalid
```java
import java.util.*;
public class Test10
{
public static void main(String [] args)
	{
	   /*ArrayList<Object> al = new ArrayList<String>(); [Compile time]
```


## ArrayList al = new ArrayList();  [Runtime, Type Erasure]

al.add("Ravi");*/


Object []obj = new String[3]; //valid with Array
```java
		obj[0] = "Ravi";
		obj[1] = "hyd";
```

obj[2] =  90; //java.lang.ArrayStoreException
```java
		System.out.println(Arrays.toString(obj));
	}
}


```


> **Note :- Program will generate java.lang.ArrayStoreException because we are trying to insert 90 (integer value) into String array.**


In Array we have an Exception called ArrayStoreException (Which protect us to assign some illegal value in the array) but the same Exception or such type of exception, is not available with Generics (due to Type Erasure) that is the reason in generics, compiler does not allow upcasting concept.
(It is a strict compile time checking)

### Wild card character(?)

<?>	-: Many possibilities

<Animal>-: Only <Animal> can assign, but not Dog or sub type of animal

<? super Dog>-: Dog, Animal, Object can assign (Compiler has                      surity) It is also called lower bound

<? extends Animal> -: Below of Animal(Child of Animal) means, sub classes of Animal (But the compiler does not have surity because you can have many sub classes of Animal in the future, so chances of wrong collections). It is also called Upper bound.
```java
import java.util.*;
class Parent
{
}
class Child extends Parent
{
}

public class Test11
{
public static void main(String [] args)
	{
```


## ArrayList<?> lp = new ArrayList<Child>(); //error



## ArrayList<Parent> lp1 = new ArrayList<Parent>();



## ArrayList<Child> lp2 = new ArrayList<>();


```java
		System.out.println("Success");
	}
}
```

```java
import java.util.*;
public class Test13
{
	public static void main(String[] args)
	{
		List<? extends Number> list1 = new ArrayList<Float>();

		List<? super String> list2 = new ArrayList<Object>();

		List<? super Gamma> list3 = new ArrayList<Alpha>();

		List list4 = new ArrayList();

		System.out.println("yes");
	}
}

class Alpha
{
}
class Beta extends Alpha
{
}
class Gamma extends Beta
{
}
```


### How to create our own functional interfaces with multiple parameters

```java
package com.ravi.functional_interface;

@FunctionalInterface
interface TriFunction<T,U,V,R>
{
	R apply(T t, U u, V v);
}


public class UserDefinedFunctionalInterface
{
	public static void main(String[] args)
	{
		TriFunction<Integer,String,Integer,String> fn = (t,u,v)-> t + u + v;
        System.out.println(fn.apply(123, " india ", 456));
	}

}
```

```java
class Test<T,U>
{
	private T r;
	public void set(U a)
	{
		r = (T) a;
	}

	public T get()
	{
		return this.r;
	}
}
public class Test14
{
   public static void main(String[] args)
   {
      Test<String,String> test = new Test();
      test.set("NIT");
      System.out.println(test.get());
   }
}
```

```java
class MyClass<T>
{
	T obj;
	public MyClass(T obj)       //Student obj
	{
		this.obj=obj;
	}

```

T getObj()
```java
	{
		return this.obj;
	}
}
public class Test15
{
	public static void main(String[] args)
	{
		Integer i=12;
		MyClass<Integer> mi = new MyClass<>(i);
		System.out.println("Integer object stored :"+mi.getObj());

		Float f=12.34f;
		MyClass<Float> mf = new MyClass<>(f);
		System.out.println("Float object stored :"+mf.getObj());

		MyClass<String> ms = new MyClass<>("Rahul");
		System.out.println("String object stored :"+ms.getObj());

		MyClass<Boolean> mb = new MyClass<>(false);
		System.out.println("Boolean object stored :"+mb.getObj());

		Double d=99.34;
		MyClass<Double> md = new MyClass<>(d);
		System.out.println("Double object stored :"+md.getObj());

		MyClass<Student> std = new MyClass<>(new Student(1,"A"));
		System.out.println("Student object stored :"+std.getObj());
	}
}

```

record Student(int id, String name)
```java
{

}
```

```java
//E stands for Element type
class Fruit
{
}
class Apple extends Fruit   //Fruit is super, Apple is sub class
{
	@Override
	public String toString()
	{
		return "Apple";
	}
}

class Basket<E>   //Element is Fruit Type
{
	private E element;
	public void setElement(E element) //Fruit element
	{
		this.element = element;
	}

	public E getElement()
	{
		return this.element;
	}
}

public class Test16
{
	public static void main(String[] args)
	{
		Basket<Fruit> b = new Basket<>();
		b.setElement(new Apple());

		Apple x = (Apple) b.getElement();
		System.out.println(x);


        Basket<Fruit> b1 = new Basket<>();
		b1.setElement(new Mango());
		Mango y = (Mango)b1.getElement();
		System.out.println(y);

	}
}
class Mango extends Fruit
{
	@Override
	public String toString()
	{
		return "Mango";
	}
}

```

Note : There is no difference between element and type parameter, only they are represented by different types

E : Element Type
T : Type Parameter
Concurrent collections in java
Concurrent Collections are introduced from JDK 1.5 onwards to enhance the performance of multithreaded application.

These are threadsafe collection and available in java.util.concurrent sub package.

Limitation of Traditional Collection :
1) In the Collection framework most of the Collection classes are not thread-safe because those are non-synchronized like ArrayList, LinkedList, HashSet, HashMap is non-synchronized in nature, So If multiple threads will perform any operation on the collection object simultaneously then we will get some wrong data this is known as Data race or Race condition.

2) Some Collection classes are synchronized like Vector, Hashtable but performance wise these classes are slow in nature.

Collections class has provided static methods to make our List, Set and Map interface classes as a synchronized.

a) public static List synchronizedList(List list)
b) public static Set synchronizedSet(Set set)
c) public static Map synchronizedMap(Map map)

3) Traditional Collection works with fail fast iterator that means while iterating the element,
```java
     if there is a change in structure then we will get java.util.ConcurrentModificationException,
```

On the other hand concurrent collection works with fail safe iterator where even though there is a change in structure but we will not get ConcurrentModificationException.
```java
import java.util.*;
public class Collection1
{
     public static void main(String args[])
     {
```


## ArrayList al = new ArrayList();

```java
          al.add(10);
          al.add(20);
          al.add(30);
          al.add(40);
          al.add(50);
		  al.add(50);
          System.out.println("Arraylist Elements : "+al);
          Set s = new HashSet(al);
          System.out.println("Set Elements are: "+s);
     }
}
```

```java
//Collections.synchronizedList(List list);
import java.util.*;
public class Collection2
{
	public static void main(String[] args)
	{
```


## ArrayList<String> arl = new ArrayList<>();

```java
		arl.add("Apple");
		arl.add("Orange");
		arl.add("Grapes");
		arl.add("Mango");
		arl.add("Guava");
		arl.add("Mango");

		List<String> syncCollection = Collections.synchronizedList(arl);

```

List<String> upperList = new ArrayList<>(); //New List

Runnable listOperations = () ->
```java
		{
			synchronized (syncCollection)
			{
               syncCollection.forEach(str -> upperList.add(str.toUpperCase()));
           }
       };

```


## Thread t1 = new Thread(listOperations);

```java
	   t1.start();

      upperList.forEach(x -> System.out.println(x));
	}
}
```

```java
//Collections.synchronizedSet(Set set);
import java.util.*;
public class Collection3
{
    public static void main(String[] args)
		{
        Set<String> set = Collections.synchronizedSet(new HashSet<>());
        set.add("Apple");
		set.add("Orange");
		set.add("Grapes");
		set.add("Mango");
		set.add("Guava");
		set.add("Mango");
        System.out.println("Set after Synchronization :");
        synchronized (set)
		{
           Spliterator<String> itr = set.spliterator();
		   itr.forEachRemaining(str -> System.out.println(str));
         }
     }
}
```

```java
//Collections.synchronizedMap(Map map);
import java.util.*;
public class Collection4
{
    public static void main(String[] args)
	{
        Map<String, String> map = new HashMap<String, String>();
        map.put("1", "Ravi");
        map.put("4", "Elina");
        map.put("3", "Aryan");
        Map<String, String> synmap = Collections.synchronizedMap(map);
        System.out.println("Synchronized map is :" + synmap);
     }
}
```

```java
package com.ravi.functional_interface;

import java.util.ArrayList;
import java.util.Iterator;

class Concurrent extends Thread
{
```


## ArrayList<String> al = null;


```java
	public Concurrent(ArrayList<String> al)
	{
	  super();
	  this.al = al;
    }

	@Override
	public void run()
	{
```

try
```java
		{
```


## Thread.sleep(1500);

```java
		}
		catch(InterruptedException e)
		{
			e.printStackTrace();
		}
		al.add("Kiwi");
	}

}

public class Collections5
{

	public static void main(String[] args) throws InterruptedException
	{
```


## ArrayList<String> listOfFruits = new ArrayList<String>();

```java
		listOfFruits.add("Pomogranate");
		listOfFruits.add("Apple");
		listOfFruits.add("Orange");
		listOfFruits.add("Grapes");
		listOfFruits.add("Mango");
		listOfFruits.add("Guava");

		Concurrent con = new Concurrent(listOfFruits);
		con.start();

```


## Iterator<String> itr = listOfFruits.iterator();


```java
		while(itr.hasNext())
		{
			System.out.println(itr.next());
```


## Thread.sleep(500);

```java
		}


	}

}

```


> **Note :- In the above program we will get java.util.ConcurrentModificationException because Iterator is fail fast iterator.**


Note : IMMUTABLE OBJECTS ARE ALWAYS THRAED SAFE.

## 08-08-2024


### CopyOnWriteArrayList in java

```java
public class CopyOnWriteArrayList implements List, Cloneable, Serializable, RanomAccess

```

A CopyOnWriteArrayList is similar to an ArrayList but it has some additional features like thread-safe. This class is existing in java.util.concurrent sub package.


## ArrayList is not thread-safe. We can�t use ArrayList in the multi-threaded environment because it creates a problem in ArrayList values  (Data inconsistency).


*The CopyOnWriteArrayList is an enhanced version of ArrayList. If we are making any modifications(add, remove, etc.)  in  CopyOnWriteArrayList then JVM creates a new copy by use of Cloning.

The CopyOnWriteArrayList is costly, if we want to perform update operations  so it is immutable object , because whenever we make any changes the JVM creates a cloned copy of the  array and add/update element to new object.

It is a thread-safe version of ArrayList as well as here Iterator is fail safe iterator.

*CopyOnWriteArrayList is the best choice if we want to perform read operation frequently in multithreaded environment.

The CopyOnWriteArrayList is a replacement of a synchronized List, because it offers better concurrency.

Constructors of CopyOnWriteArrayList in java :

### We have 3 constructors


```java
1) CopyOnWriteArrayList c = new CopyOnWriteArrayList();
```

It creates an empty list in memory. This constructor is useful when we want to create a list without any value.

```java
2) CopyOnWriteArrayList c = new CopyOnWriteArrayList(Collection c);
```

Interconversion of collections.

```java
3) CopyOnWriteArrayList c = new CopyOnWriteArrayList(Object[] obj) ;
```

It Creates a list that containing all the elements that is specified Array. This constructor is useful when we want to create a CopyOnWriteArrayList from Array.


Note : All the immutable objects are thread-safe because, On immutable objects if we perform any operation then another object will be created in a new memory location so at a time multiple threads can work.

All String Object, Wrapper classes object, Concurrent collection classes are Thread-safe.
```java
import java.util.Arrays;
import java.util.Iterator;
import java.util.List;
import java.util.concurrent.CopyOnWriteArrayList;

public class CopyOnWriteArrayListExample1
{
    public static void main(String[] args)
    {
        List<String> list = Arrays.asList("Apple", "Orange", "Mango","Kiwi", "Grapes");


        CopyOnWriteArrayList<String> copyOnWriteList = new CopyOnWriteArrayList<String>(list);

        System.out.println("Without modification = "+copyOnWriteList);

		 //Iterator1
```


## Iterator<String> iterator1 = copyOnWriteList.iterator();


```java
        //Add one element and verify list is updated
        copyOnWriteList.add("Guava");

        System.out.println("After modification = "+copyOnWriteList);

        //Iterator2
```


## Iterator<String> iterator2 = copyOnWriteList.iterator();


```java
        System.out.println("Element from first Iterator:");
```


## iterator1.forEachRemaining(System.out::println);


```java
        System.out.println("Element from Second Iterator:");
```


## iterator2.forEachRemaining(System.out::println);

```java
    }
}
```

```java
import java.util.*;
import java.util.concurrent.*;
class ConcurrentModification extends Thread
{
	CopyOnWriteArrayList<String> al = null;
	public ConcurrentModification(CopyOnWriteArrayList<String> al)
	{
		this.al = al;
	}
	@Override
	public void run()
	{
```

try
```java
		{
```


## Thread.sleep(1000);

```java
		}
		catch (InterruptedException e)
		{
		}
	    al.add("KIWI");
	}
}
public class CopyOnWriteArrayListExample2
{
	public static void main(String[] args) throws InterruptedException
	{
		CopyOnWriteArrayList<String> arl = new CopyOnWriteArrayList<>();
		arl.add("Apple");
		arl.add("Orange");
		arl.add("Grapes");
		arl.add("Mango");
		arl.add("Guava");
		ConcurrentModification cm = new ConcurrentModification(arl);
		cm.start();

```


## Iterator<String> itr = arl.iterator();

```java
        while(itr.hasNext())
		{
			String str = itr.next();
			System.out.println(str);
```


## Thread.sleep(500);

```java
		}

	    System.out.println("............");

		Spliterator<String> spl =  arl.spliterator();
		spl.forEachRemaining(x -> System.out.println(x));
	}
}
```


### CopyOnWriteArraySet

```java
public class CopyOnWriteArraySet extends AbstractSet implements Serializable

```

A CopyOnWriteArraySet is a thread-safe version of HashSet in Java and it works like CopyOnWriteArrayList in java.

The CopyOnWriteArraySet internally used CopyOnWriteArrayList to perform all type of operation.It means the CopyOnWriteArraySet internally creates an object of CopyOnWriteArrayList and perform operation on it.

Whenever we perform add, set, and remove operation on CopyOnWriteArraySet, it internally creates a new object of CopyOnWriteArrayList and copies all the data to the new object by eliminating duplicates so, when it is used in by multiple threads, it doesn�t create a problem, but it is well suited if we have small size collection and want to perform only read operation by multiple threads.

The CopyOnWriteArraySet is the replacement of synchronizedSet and offers better concurrency.

It creates a new copy of the array every time iterator is created, so performance is slower than HashSet.

Constructors :
It has two constructors

```java
1) CopyOnWriteArraySet set1 = new CopyOnWriteArraySet();
```

It will create an empty Set


2) CopyOnWriteArraySet set1 = new CopyOnWriteArraySet(Collection c); Interconversion of collection.
```java
import java.util.*;
import java.util.concurrent.CopyOnWriteArraySet;
import java.util.concurrent.CopyOnWriteArraySet;

public class CopyOnWriteArraySetExample1
{
  public static void main(String[] args)
   {
        CopyOnWriteArraySet<String> set = new CopyOnWriteArraySet<>();

        set.add("Java");
        set.add("Python");
        set.add("C++");
		set.add("Java");

```


## Iterator itr = set.iterator();

```java
		while(itr.hasNext())
	    {
			System.out.println(itr.next());
	    }

        // Adding a new element
        set.add("JavaScript");
        System.out.println("............");
        for (String language : set)
		{
            System.out.println(language);
        }
    }
}
```

```java
import java.util.concurrent.CopyOnWriteArraySet;

public class CopyOnWriteArraySetExample2
{
    public static void main(String[] args)
    {
        CopyOnWriteArraySet<Integer> set = new CopyOnWriteArraySet<Integer>();
        set.add(1);
        set.add(2);
        set.add(3);
        set.add(4);
        set.add(5);

        System.out.println("Is element contains: "+set.contains(1));

        System.out.println("Is set empty: "+set.isEmpty());

        System.out.println("remove element from set: "+set.remove(3));

        System.out.println("Element from Set: "+ set);
    }
}
```

*** ConcurrentHashMap : [Bucket Level Locking]
```java
public class ConcurrentHashMap<K,V> extends AbstractMap<K,V> implements ConcurrentMap<K,V>, Serializable

```

Like HashMap, ConcurrentHashMap provides similar functionality except that it has internally maintained concurrency.

It is the concurrent version of the HashMap. It internally maintains a Hashtable that is divided into segments(Buckets).

The number of segments depends upon the level of concurrency required the Concurrent HashMap. By default, it divides into 16 segments and each Segment behaves independently. It doesn�t lock the whole HashMap as done in Hashtables/synchronizedMap, it only locks the particular segment(Bucket) of HashMap. [Bucket level locking]

ConcurrentHashMap allows multiple threads can perform read/write operation without locking the ConcurrentHashMap object.

It does not allow null as a key or evan null as a value.

[Note :- TreeSet, TreeMap, Hashtable, PriroityQueue, ConcurrentHashMap , These 5 classes never containing null key or null element)

It contains 5 types of constructor :
```java
1) ConcurrentHashMap chm1 = new ConcurrentHashMap();

2) ConcurrentHashMap chm2 = new ConcurrentHashMap(int initialCapacity);

3) ConcurrentHashMap chm3 = new ConcurrentHashMap(int initialCapacity, float loadFactor);

4) ConcurrentHashMap chm4 = new ConcurrentHashMap(int initialCapacity, float loadFactor, int concurrencyLevel);

5) ConcurrentHashMap chm5 = new ConcurrentHashMap(ConcurrentMap m);

```

Internal Working of ConcurrentHashMap :
Like HashMap and Hashtable, the ConcurrentHashMap is also used Hashtable data structure. But it is using the segment locking strategy to handle the multiple threads.

A segment(bucket) is a portion of ConcurrentHashMap and ConcurrentHashMap uses a separate lock for each thread. Unlike Hashtable or synchronized HashMap,  it doesn�t synchronize the whole HashMap or Hashtable for one thread.

As we have seen in the internal implementation of the HashMap, the default size of HashMap is 16 and it means there are 16 buckets. The ConcurrentHashMap uses the same concept is used in ConcurrentHashMap. It uses the 16 separate locks for 16 buckets by default because the default concurrency level is 16. It means a ConcurrentHashMap can be used by 16 threads at same time. If one thread is reading from one bucket(Segment), then the second bucket doesn�t affect it.

Why we need ConcurrentHashMap in java?
As we know Hashtable and HashMap works based on key-value pairs. But why we are introducing another Map? As we know HashMap is not thread safe, but we can make it thread-safe by using Collections.synchronizedMap() method and Hashtable is thread-safe by default.

But a synchronized HashMap or Hashtable is accessible only by one thread at a time because the object get the lock for the whole HashMap or Hashtable. Even multiple threads can�t perform read operations at the same time. It is the main disadvantage of Synchronized HashMap or Hashtable, which creates performance issues. So ConcurrentHashMap provides better performance than Synchronized HashMap or Hashtable.
```java
import java.util.HashMap;
import java.util.concurrent.ConcurrentHashMap;

public class ConcurrentHashMapExample1
{
   public static void main(String args[])
   {

       HashMap<Integer, String> hashMap = new HashMap<Integer, String>();
       hashMap.put(1, "Ravi");
       hashMap.put(2, "Ankit");
       hashMap.put(3, "Prashant");
	   hashMap.put(4, "Pallavi");

       ConcurrentHashMap<Integer, String> concurrentHashMap = new ConcurrentHashMap<>(hashMap);
       System.out.println("Object from ConcurrentHashMap: "+ concurrentHashMap);

   }

}
```

```java
import java.util.Iterator;
import java.util.Map;
import java.util.concurrent.ConcurrentHashMap;

public class ConcurrentHashMapExample2
{
   public static void main(String args[])
   {
       // Creating ConcurrentHashMap
       Map<String, String> cityTemperatureMap = new ConcurrentHashMap<>();

        cityTemperatureMap.put("Delhi", "30");
        cityTemperatureMap.put("Mumbai", "32");
        cityTemperatureMap.put("Chennai", "35");
        cityTemperatureMap.put("Bangalore", "22" );

```


## Iterator<String> iterator = cityTemperatureMap.keySet().iterator();


```java
        while (iterator.hasNext())
        {
          System.out.println(cityTemperatureMap.get(iterator.next()));
          // adding new value, it won't throw error
          cityTemperatureMap.put("Hyderabad", "28");
        }
   }
}
```


## 09-08-2024


### Stream API in Java


It is introduced from Java 8 onwards, the Stream API is used to process the collection objects.

It contains classes for processing sequence of elements over Collection object and array.

Stream is a predefined interface available in java.util.stream sub package.

Package Information :
java.util -> Base package
java.util.function -> Functional interfaces
java.util.concurrent -> Multithreaded support
java.util.stream -> Processing of Collection Object

Interfaces which contains forEach() method in java :
The Java forEach() method is a  technique to iterate over a collection such as (list, set or map) and stream. It  is used to perform a given action on each of the element of the collection.

The forEach() method has been added in following places:

Iterable interface � This makes Iterable.forEach() method available to all collection classes. Iterable interface is the super interface of Collection interface

Map interface � This makes forEach() operation available to all map classes.

Stream interface � This makes forEach() operations available to all types of stream.

### Creation of Streams to process the data


### We can create Stream from  collection or array with the help of stream() and Stream.of(T ...values) methods


A stream()  method is added to the Collection interface and allows creating a Stream<T> using any collection object as a source

```java
public java.util.stream.Stream<E> stream();

```

The return type of this method is Stream interafce available in java.util.stream sub package.

Eg:-
```java
List<String> items = new ArrayList<String>();
		items.add("Apple");
		items.add("Orange");
		items.add("Mango");
		//Collection to stream
		Stream<String> stream = items.stream();
```

```java
package com.ravi.basic;
import java.util.*;  //Base package
import java.util.stream.*; //Sub package
public class StreamDemo1
{
	public static void main(String[] args)
	{
		List<String> items = new ArrayList<>();

		items.add("Apple");
		items.add("Orange");
		items.add("Mango");

        //Collections Object to Stream
		Stream<String> strm = items.stream();
		strm.forEach(p -> System.out.println(p));
	}
}
```

```java
public static java.util.stream.Stream  of(T ...x)
```

It is a static method of Stream interface through which we can create Stream of arrays and Stream of Collection. The return type of this method is Stream interface


```java
//Stream.of()
package com.ravi.basic;
import java.util.stream.*;
public class StreamDemo2
{
	public static void main(String[] args)
	{
		//Stream of numbers
		Stream<Integer> stream = Stream.of(1,2,3,4,5,6,7,8,9);
		stream.forEach(p -> System.out.println(p));

		System.out.println("...............................");

         //Anonymous Array Object (Stream of Arrays)

		Stream<Integer> strm = Stream.of( new Integer[]{15,29,45,8,16} );
		strm.forEach(p -> System.out.println(p));
	}
}
```



### Intermediate Operations

The following methods are available to perform intermediate operation.

filter(Predicate<T> predicate): Returns a new stream which contains filtered elements based on the boolean expression using Predicate.

```java
map(Function<T, R> mapper): Transforms elements in the stream using the provided mapping function.

flatMap(Function<T, Stream<R>> mapper): Flattens a stream of streams into a single stream.

distinct(): Returns a stream with distinct elements (based on their equals method).

sorted(): Returns a stream with elements sorted in their natural order.

sorted(Comparator<T> comparator): Returns a stream with elements sorted using the specified comparator.

peek(Consumer<T> action): Allows us to perform an action on each element in the stream without modifying the stream.

limit(long maxSize): Limits the number of elements in the stream to a specified maximum size.

skip(long n): Skips the first n elements in the stream.

```

takeWhile(Predicate<T> predicate): Returns a stream of elements from the beginning until the first element that does not satisfy the predicate.

dropWhile(Predicate<T> predicate): Returns a stream of elements after skipping elements at the beginning that satisfy the predicate.
```java
public abstract Stream<T> filter(Predicate<T> p) :
```

It is a predfined method of Stream interface. It is used to select/filter elements as per the Predicate passed as an argument. It is basically used to filter the elements based on boolean condition.

```java
public abstract <T>  collect(java.util.stream.Collectors c)
```

It is a predfined method of Stream interface. It is used to return the result of the intermediate operations performed on the stream.

It is a terminal operation. It is used to collect the data after filteration and convert the data to the Collection(List/Set/Map).

Collectors is a predfined final class available in java.util.stream sub package which conatins  static method toList(),toSet(), toMap() to convert the data as a List/Set i.e Collection object. The return type of this method is List/Set/Map interface.

```java
//Filter all the even numbers from Collection
package com.ravi.basic;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;
import java.util.Set;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class StreamDemo3
{
	public static void main(String[] args)
	{
	   //Printing even number without Stream interface
		List<Integer> listOfNumber = Arrays.asList(1,2,3,4,5,6,7,8,9,10,11,12);

		List<Integer> evenList = new ArrayList<>();

		for(Integer x : listOfNumber)
		{
			if(x%2==0)
			{
				evenList.add(x);
			}
		}
		evenList.forEach(System.out::println);
		System.out.println(".............................");
		Stream.of(1,2,3,4,5,6,7,8,9,10,11,12).filter(num -> num%2==0).forEach(System.out::println);

		System.out.println(".............................");
```


## ArrayList<Integer> al = new ArrayList<>();

```java
		al.add(11);
		al.add(12);
		al.add(13);
		al.add(14);
		al.add(15);
		al.add(16);
		al.add(17);
		al.add(18);
		al.add(19);
		al.add(20);
		al.add(20);

		Set<Integer> set = al.stream().filter(num -> num%2==0).collect(Collectors.toSet());
		set.forEach(System.out::println);
	}
}
```

```java
//Filtering the name which starts with 'R' character with Stream API
package com.ravi.basic;

import java.util.Arrays;
import java.util.Comparator;
import java.util.List;
import java.util.stream.Collector;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class StreamDemo4
{
	public static void main(String[] args)
	{
		List<String> listOfName = Arrays.asList("Raj","Rahul","Ankit","Roshan","Scott");

		listOfName.stream().filter(str -> str.startsWith("R")).forEach(System.out::println);
	}
}
```

```java
public Stream sorted() :
```

It is a predefined method of Stream interface.
It provides default natural sorting order.
The return type of this method is Stream.
It has an overloaded method which accept Comparator<T> as a parameter
through which we can provide user-defined sorting logic

```java
//Sorting the data
package com.ravi.basic;
import java.util.*;
import java.util.stream.*;
public class StreamDemo5
{
	public static void main(String[] args)
	{
	List<String> names = Arrays.asList("Zaheer","Rahul","Aryan","Sailesh","Zaheer");

```

List<String> sortedName =
```java
            names.stream().sorted().collect(Collectors.toList());

        System.out.println(sortedName);
	}
}
```

```java
package com.ravi.basic;

import java.util.ArrayList;
import java.util.List;

//Fetch all the Employees name whose salary is greater then 50k

```

record Employee(Integer employeeId, String employeeName, Double employeeSalary)
```java
{

}

public class StreamDemo6
{
	public static void main(String[] args)
	{
	  List<Employee> listOfEmployee = new ArrayList<>();
	  listOfEmployee.add(new Employee(111, "Scott", 75000D));
	  listOfEmployee.add(new Employee(222, "John", 45000D));
	  listOfEmployee.add(new Employee(333, "Martin", 55000D));
	  listOfEmployee.add(new Employee(444, "Smith", 65000D));
	  listOfEmployee.add(new Employee(555, "Virat", 95000D));

	  System.out.println("Name of the employee salary is greater than 50K");
	  listOfEmployee.stream().filter(emp -> emp.employeeSalary()>50000).forEach(employee -> System.out.println(employee.employeeName()));


	}
}
```


## 10-08-2024

```java
public Stream map(Function<? super T,? extends R> mapper) :
```

It is a predefined method of Stream interface.

It takes Function (Predefined functional interafce ) as a parameter.

It performs intermediate operation and consumes single element from input Stream and produces single element to output Stream. (1:1 transformation)

Here mapper function is functional interface which takes one input and provides one output.

```java
package com.ravi.basic;
import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class StreamDemo7
{
    public static void main(String[] args)
    {
      //add value 10 to each and every number
      List<Integer> listOfNumbers =             Arrays.asList(11,12,13,14,15,16,17,18,19,20);

      listOfNumbers.stream().map(num -> num + 10).forEach(System.out::println);

    	System.out.println("............................");

    	//Find even numbers in stream and collect the cubes
    List<Integer> numbers = List.of(1,2,3,4,5,6,7,8,9,10,11,12);
                  List<Integer> evenCubes = numbers.stream().filter(num -> num%2==0).map(n -> n*n*n).collect(Collectors.toList());
                  System.out.println(evenCubes);


    	System.out.println("...................");

    	//Find the length of the name
    	Stream.of("Raj","Scott","subramanyam","Rahul").map(str-> str.length()).forEach(System.out::println);

    	//retrieve first character of all the given name

    	List<Character> firstChar = Stream.of("Jyoti","Aman","Viraj","Ankit").map(str -> str.charAt(0)).collect(Collectors.toList());
    	System.out.println(firstChar);

    }
}
```

```java
//Program on map(Function<T,R> mapped)
package com.ravi.basic;

import java.util.ArrayList;
import java.util.List;
import java.util.Set;
import java.util.stream.Collectors;

public class StreamDemo8
{
	public static void main(String args[])
	{
		//Get the name of the Player from Player Object
		List<Player> listOfPlayers = createPlayerList();
		Set<String> playerNames = listOfPlayers.stream().map(player -> player.name()).collect(Collectors.toSet());
		System.out.println(playerNames);

	}

	public static List<Player> createPlayerList()
	{
		List<Player> al = new ArrayList<>();
		al.add(new Player(18, "Virat"));
		al.add(new Player(45, "Rohit"));
		al.add(new Player(7, "Dhoni"));
		al.add(new Player(18, "Virat"));
		al.add(new Player(90, "Bumrah"));
		al.add(new Player(67, "Hardik"));

		return al;
	}
}


```

record Player(Integer playerId, String name)
```java
{

}
```

```java
public Stream flatMap(Function<? super T,? extends Stream<? extends R>> mapper)
```

It is a predefined method of Stream interface.

The map() method produces one output value for each input value in the stream So if there are n elements in the stream, map() operation will produce a stream of n output elements.

flatMap() is two step process i.e. map() + Flattening. It helps in converting Collection<Collection<T>> into Collection<T> [to make flat i.e converting Collections of collection into single collection or merging of all the collection]
```java
package com.nit.record;

import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

public class FlatMapDemo1
{
	public static void main(String[] args)
	{
		List<Integer> list1 = Arrays.asList(1,2,3,4,5);
		List<Integer> list2 = Arrays.asList(11,21,31,41,51);
		List<Integer> list3 = Arrays.asList(31,32,33,34,35);

		List<List<Integer>> nestedList = Arrays.asList(list1, list2, list3);
        System.out.println(nestedList);

        List<Integer> collect = nestedList.stream().flatMap(list -> list.stream()).collect(Collectors.toList());
        System.out.println(collect);
	}

}
```

```java
//flatMap()
//map + Flattening [Converting Collections of collection into single collection]
package com.ravi.basic;

import java.util.Arrays;
import java.util.List;
import java.util.stream.Collector;
import java.util.stream.Collectors;

public class StreamDemo9
{
	public static void main(String[] args)
	{
		List<String> list1 = Arrays.asList("A","B","C");
		List<String> list2 = Arrays.asList("D","E","F");
		List<String> list3 = Arrays.asList("G","H","I");

		List<List<String>> nestedColl = Arrays.asList(list1, list2, list3);
		System.out.println(nestedColl);

		List<String> flatColl = nestedColl.stream().flatMap(list -> list.stream()).collect(Collectors.toList());
		System.out.println(flatColl);

	}
}
```

```java
//Flattening of prime, even and odd number
package com.ravi.basic.flat_map;

import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class FlatMapDemo1
{
	public static void main(String[] args)
	{
      List<Integer> primeNumbers = Arrays.asList(5,7,11);
      List<Integer> evenNumbers = Arrays.asList(2,4,6);
      List<Integer> oddNumbers = Arrays.asList(1,3,5);

      List<List<Integer>> nestedColl = List.of(primeNumbers,evenNumbers,oddNumbers);
      System.out.println(nestedColl);

     List<Integer> flatteningNumbers = nestedColl.stream().flatMap(list -> list.stream()).collect(Collectors.toList());

     System.out.println(flatteningNumbers);


	}

}
```

```java
//Fetching first character using flatMap()
package com.ravi.basic.flat_map;

import java.util.List;
import java.util.Set;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class FlatMapDemo2
{
	public static void main(String[] args)
	{
	    List<String> listOfNames = List.of("Aman","Venkatesh","Raj","Scott","Smith");

	   List<Character> firstChar = listOfNames.stream().flatMap(str -> Stream.of(str.charAt(0))).collect(Collectors.toList());

	   System.out.println(firstChar);

	}

}
```

```java
package com.ravi.basic.flat_map;

import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

class Product
{
	private Integer productId;
	private List<String> listOfProducts;

	public Product(Integer productId, List<String> listOfProducts)
	{
		super();
		this.productId = productId;
		this.listOfProducts = listOfProducts;

	}

	public Integer getProductId() {
		return productId;
	}

	public List<String> getListOfProducts() {
		return listOfProducts;
	}
}

public class FlatMapDemo3
{
	public static void main(String[] args)
	{
```

List<Product> listOfProduct = Arrays.asList(
```java
	new Product(1, Arrays.asList("Camera", "Mobile", "Laptop")),
	new Product(2, Arrays.asList("Bat", "Ball", "Wicket")),
	new Product(3, Arrays.asList("Chair", "Table", "Lamp")),
	new Product(4, Arrays.asList("Cycle", "Bike", "Car"))

		);

		List<String> collect = listOfProduct.stream().flatMap(product -> product.getListOfProducts().stream()).collect(Collectors.toList());

		System.out.println(collect);
	}

}
```


### Working with Primitive Streams

Streams works with collections of objects and not primitive types.

Now, to provide a way to work with the three most used primitive types � int, long and double, Java provides three primitive specialized implementations of Stream.

```java
IntStream (represents sequence of primitive int elements)
LongStream (represents sequence of primitive long elements)
DoubleStream (represents sequence of primitive double elements)
```

```java
package com.ravi.basic.map;

import java.util.Arrays;
import java.util.stream.DoubleStream;
import java.util.stream.IntStream;
import java.util.stream.LongStream;

public class PrimitiveToStreamDemo1 {

	public static void main(String[] args)
	{
		IntStream intStream = IntStream.of(1,2,3,4,5,6,7,8);
		LongStream longStream = LongStream.of(1L,2L,3L,4L,5L);
		DoubleStream doubleStream = DoubleStream.of(1.1,1.2,1.3,1.4,1.5);
		intStream.forEach(System.out::print );
		System.out.println();
		longStream.forEach(System.out::print);
		System.out.println();
		doubleStream.forEach(System.out::print);

		System.out.println();
		System.out.println("..........................");

		int a[] = {1,2,3,4,5};
		IntStream intStream2 = Arrays.stream(a);

		long l[] = {1L, 2L, 3L, 4L};
		LongStream longStream2 = Arrays.stream(l);

		double d[] = {1.2, 2.6, 3.9, 8.9};
		DoubleStream doubleStream2 = Arrays.stream(d);

		intStream2.forEach(System.out::print );
		System.out.println();
		longStream2.forEach(System.out::print);
		System.out.println();
		doubleStream2.forEach(System.out::print);


	}

}
```

IntStream flatMapToInt(Function<? super T, ? extends IntStream> mapper)
It is a predefined method of Stream interface which comes under flattening.

It allows us to transform each element of the stream into an IntStream (a stream of primitive int values) and then flattens these resulting streams into a single IntStream.

Note : IntStream is a specialized stream for working with int values avilable in java.util.stream sub package.
```java
package com.ravi.basic.flat_map;

import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;
import java.util.stream.IntStream;

public class FlatMapToIntDemo1 {

	public static void main(String[] args)
	{
		int []a1 = new int[] {1,2,3};
		int []a2 = new int[] {4,5,6};
		int []a3 = new int[] {7,8,9};

		List<int[]> listofArrays = Arrays.asList(a1,a2,a3);

		IntStream intStream = listofArrays.stream().flatMapToInt(array-> IntStream.of(array));

		intStream.forEach(System.out::println);




	}

}
```


### LongStream flatMapToLong(Function<? super T, ? extends LongStream> mapper)


It is a predefined method of Stream interface which comes under flattening.

It allows us to transform each element of the stream into a LongStream (a stream of primitive long values) and then flattens these resulting streams into a single LongStream.

Note : LongStream is a specialized stream for working with long values avilable in java.util.stream sub package.

```java
package com.ravi.basic.flat_map;

import java.util.Arrays;
import java.util.List;
import java.util.stream.LongStream;

public class FlatMapToLongDemo1 {

	public static void main(String[] args)
	{
		long []arr1 = new long[] {23,33,43};
		long []arr2 = new long[] {53,63,73};
		long []arr3 = new long[] {83,93,103};

		List<long[]> longArray = Arrays.asList(arr1, arr2,arr3);
		LongStream flatMapToLong = longArray.stream().flatMapToLong(array -> Arrays.stream(array));

		flatMapToLong.forEach(System.out::println);
	}

}
```

DoubleStream flatMapToDouble(Function<? super T, ? extends DoubleStream> mapper)

It is a predefined method of Stream interface which comes under flattening.

It allows us to transform each element of the stream into an DoubleStream (a stream of primitive double values) and then flattens these resulting streams into a single DoubleStream.

Note : DoubleStream is a specialized stream for working with double values avilable in java.util.stream sub package.
```java
package com.ravi.basic.flat_map;

import java.util.Arrays;
import java.util.List;
import java.util.stream.DoubleStream;

public class FlatMapToDoubleDemo1
{
    public static void main(String[] args)
    {
    	double d1[] = new double[]{1.1, 1.2, 1.3};
    	double d2[] = new double[]{2.1, 2.2, 2.3};
    	double d3[] = new double[]{3.1, 3.2, 3.3};

    	List<double[]> listOfDoubleArrays = Arrays.asList(d1,d2,d3);

```

DoubleStream doubleStream = listOfDoubleArrays.stream()
```java
                .flatMapToDouble(array -> DoubleStream.of(array));

            // Print each double value in the flattened stream
            doubleStream.forEach(System.out::println);
        }
}
```

**Difference between map() and flatMap()
```java
map() method transforms each element into another single element.

flatMap() transforms each element into a stream of elements and then flattens those streams into a single stream.

```

We should use map() when you want a one-to-one transformation, and  we should use flatMap() when dealing with nested structures or when you need to produce multiple output elements for each input element.

## 12-08-2024

```java
public Stream sorted() :
```

It is a predefined method of Stream interface.
It provides default natural sorting order.
The return type of this method is Stream.
It has an overloaded method which accept Comparator<T> as a parameter
through which we can provide user-defined sorting logic

```java
public Stream distinct() :
```

It is a predefined method of Stream interface.

If we want to return stream from another stream by removing all the duplicates then we should use distinct() method.


```java
package com.ravi.basic;

import java.util.List;
import java.util.stream.Stream;

public class StreamDemo10
{
	public static void main(String[] args)
	{
		 //Print the numbers in ascending order
		 List<Integer> listOfNum = List.of(89,67,56,45,23,15);
		 listOfNum.stream().sorted(Integer::compareTo).forEach(System.out::println);
		 System.out.println("===============================");

		//Print the numbers in descending order
		 List<Integer> listOfNumber = List.of(89,67,56,45,23,15);
		 listOfNumber.stream().sorted((i1,i2)-> i2.compareTo(i1)).forEach(System.out::println);
		 System.out.println("===============================");

		 //Print the names in Ascending order
		 Stream<String> strOfName = Stream.of("Ankit","Scott","Smith","James");
		 strOfName.sorted(String::compareTo).forEach(System.out::println);

		 System.out.println("===============================");

		 //Print the names in Descending order
		 Stream<String> strmOfName = Stream.of("Ankit","Scott","Smith","James");
		 strmOfName.sorted((s1,s2)-> s2.compareTo(s1)).forEach(System.out::println);

		 System.out.println("......................");
		 Stream<String> s = Stream.of("Virat", "Rohit", "Dhoni", "Virat", "Rohit","Aswin","Bumrah");
			s.distinct().sorted((s1,s2)-> s2.compareTo(s1)).forEach(System.out::println);

	}

}
```

```java
package com.ravi.basic;
import java.util.stream.Stream;
public class StreamDemo11
{
	public static void main(String[] args)
	{
		Stream<Integer> numbers = Stream.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 3, 4, 5);

		numbers.distinct().forEach(System.out::println);


	}
}



```

```java
public Stream<T> limit(long maxSize) :
```

It is a predefined method of Stream interface to work with sequence of elements.

The limit() method is used to limit the number of elements in a stream by providing maximum size.

It creates a new Stream by taking the data from original Stream.

Elements which are not in the range or beyond the range of specified limit will be ignored.
```java
public Stream<T> skip(long n) :
```

It is a predefined method of Stream interface which is used to skip the elements from begning of the Stream.

It returns a new stream that contains the remaining elements after skipping the specified number of elements which is passed as a parameter.
```java
package com.ravi.basic;
import java.util.stream.Stream;
public class StreamDemo12
{
	public static void main(String[] args)
	{
		Stream<String> s = Stream.of("Virat", "Rohit", "Dhoni", "Zaheer", "Raina","Sahwag","Sachin","Bumrah");
		s.skip(2).limit(5).forEach(System.out::println);
	}
}
```

```java
public Stream<T> peek(Consumer<? super T> action) :
```

It is a predefined method of Stream interface which is used to perform a side-effect operation on each element in the stream while the stream remains unchanged.

It is an intermediate operation that allows us to perform operation on each element of Stream without modifying original.

The peek() method takes a Consumer as an argument, and this function is applied to each element in the stream. The method returns a new stream with the same elements as the original stream.
```java
package com.ravi.basic;

import java.util.List;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class StreamDemo13
{
	public static void main(String[] args)
	{
		Stream<String> listOfFruits = Stream.of("Apple","Mango","Grapes","Kiwi","pomogranate");

```

List<Integer> doubledNumbers = listOfFruits
.peek(str -> System.out.println("Peeking from Original: " + str.toUpperCase()))
.map(fruit -> fruit.length())
```java
		    .collect(Collectors.toList());
		System.out.println("-----------------");
		System.out.println(doubledNumbers);

	}

}

```


> **Note :- peek(Consumer<T> cons) will not modify the Original Source.**

```java
public Stream<T> takeWhile(Predicate<T> predicate) :
```

It is a predefined method of Stream interface introduced from java 9 which is used to perform a side-effect operation on each element in the stream while the stream remains unchanged.

*It is used to create a new stream that includes elements from the original stream only as long as they satisfy a given predicate.

```java
package com.ravi.basic;

import java.util.stream.Stream;

public class StreamDemo14
{
 public static void main(String[] args)
 {
	 Stream<Integer> numbers = Stream.of(10,11,9,13,2,1,100);

     numbers.takeWhile(n -> n > 9).forEach(System.out::println);

     System.out.println(".......................");

     numbers = Stream.of(12,2,10,3,4,5,6,7,8,9);

     numbers.takeWhile(n -> n%2==0).forEach(System.out::println);


     System.out.println(".......................");

     numbers = Stream.of(1,2,3,4,5,6,7,8,9);

     numbers.takeWhile(n -> n < 9).forEach(System.out::println);

     System.out.println(".......................");

     numbers = Stream.of(11,2,3,4,5,6,7,8,9);

     numbers.takeWhile(n -> n > 9).forEach(System.out::println);

     System.out.println(".............................");

     Stream<String> stream = Stream.of("Ravi", "Ankit", "Rohan", "Aman", "Ravish");

     stream.takeWhile(str -> str.charAt(0)=='R').forEach(System.out::println);
     }
}
```

```java
public Stream<T> dropWhile(Predicate<T> predicate) :
```

It is a predefined method of Stream interface introduced from java 9 which is used to create a new stream by excluding elements from the original stream as long as they satisfy a given predicate.

```java
package com.ravi.basic;

import java.util.stream.Stream;

public class StreamDemo15 {

	public static void main(String[] args)
	{
		Stream<Integer> numbers = Stream.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

		numbers.dropWhile(num -> num < 7).forEach(System.out::println);

		System.out.println("..................................");

		numbers = Stream.of(15, 8, 7, 9, 5, 6, 7, 8, 9, 10);

		numbers.dropWhile(num -> num > 5).forEach(System.out::println);
	}

}
```


### Optional<T> class in Java

It is a predefined final and immutable class available in java.util package from java 1.8v.

It is a container object which is used to represent an object (Optional object) that may or may not contain a non-null value.

If the value is available in the container, isPresent() method will return true and get() method will return the actual value.

It is very useful in industry to avoid NullPointerException.

Methods of Optional<T> class :

### 1) public static Optional<T> ofNullable(T x)

It will return the object of Optional class with specified value. If the specified value is null then this method will return an empty object of the optional class.

2) public boolean isPresent() :
It will return true, if the value is available in the container otherwise it will return false.

3) public T get() :
It will get/fetch the value from the container, if the value is not available then it will throw java.util.NoSuchElementException.

4) public T orElse(T defaultValue) :
It will return the value, if available  otherwise it will return the specified default value.

5) public static Optional<T> of (T value) :
It will return the optional object with the specified value that is non- null value.

6) public static Optional<T> empty() :
It will return an empty Optional Object.


7) public java.util.stream.Stream  stream()
It will Convert optional to Stream.

8) public void ifPresent(Consumer<T> cons) :
It Used to consume/accept the value from optional container if the value is not null.
```java
//Program to verify whether the container has value or not
package com.ravi.optional_class_demo;

import java.util.Optional;

public class OptionalDemo1
{
	public static void main(String[] args)
	{
		String str = null;

		Optional<String> optional = Optional.ofNullable(str);

		String orElse = optional.orElse("No value in container");
		System.out.println("Value by orElse :"+orElse);


		//Optional is containing value or not?
		if(optional.isPresent())
		{
			System.out.println("Value by get :"+optional.get());
		}
		else
		{
			System.err.println("No value is available in the container");
		}


	}

}
```

```java
//Writing different style of getter
package com.ravi.optional_class_demo;
import java.util.Optional;
class Employee
{
	private Integer empId;
	private String empName;

	public Employee() {}

	public Employee(Integer empId, String empName)
	{
		super();
		this.empId = empId;
		this.empName = empName;
	}

	//Changing the style of writing getter method
	public Optional<Integer> getEmpId()
	{
		return Optional.ofNullable(empId);
	}

	public Optional<String> getEmpName()
	{
		return Optional.ofNullable(empName);
	}
}

public class OptionalDemo2
{
	public static void main(String[] args)
	{
		Employee emp = new Employee(111,"Ravi");
		//Employee emp = new Employee();

		Optional<Integer> empId = emp.getEmpId();
		if(empId.isPresent())
		{
			System.out.println(empId.get());
		}
		else
		{
			System.err.println("No id value ");
		}

		Optional<String> empName = emp.getEmpName();
		String name = empName.orElse("name is not available");
		System.out.println(name);

	}
}
```

```java
//Program to verify value is available or not
package com.ravi.optional_class_demo;

import java.util.ArrayList;
import java.util.List;
import java.util.Optional;

public class OptionalDemo3
{
    public static void main(String[] args)
    {
        List<Optional<String>> optionalList = new ArrayList<>();
        optionalList.add(Optional.of("BCA"));
        optionalList.add(Optional.of("MCA"));
        optionalList.add(Optional.of("B.TECH"));
        optionalList.add(Optional.of("M.Tech"));
        optionalList.add(Optional.of("BA"));
        optionalList.add(Optional.empty());

        for(Optional<String> optional : optionalList)
        {

        	if(optional.isPresent())
        	{
        		System.out.println(optional.get());
        	}
        	else
        	{
        		System.err.println("No Value is available");
        	}
        }


    }
}

```

Note : If we take null then we will get NPE so instead of null we should use Optional.empty() to represent an empty optional.

## 13-08-2024

Program that Describes Optional<T> is an immutable class.

```java
//Immutability of Optional class

package com.ravi.optional_class_demo;

import java.util.Optional;
public class OptionalDemo4
{
    public static void main(String[] args)
    {

        Optional<String> optl = Optional.of("India");
        System.out.println(optl.hashCode());

        Optional<String> newOptnl = modifyOptional(optl);
        System.out.println(newOptnl.hashCode());

        // Check if the original Optional is still the same
        System.out.println("Address is :" + (optl == newOptnl));

    }

    public static Optional<String> modifyOptional(Optional<String> optional)
    {

        if (optional.isPresent())
        {
            return Optional.of("Modified: " + optional.get());
        }
        else
        {
            return Optional.empty();
        }
    }
}

```

Note : Here We have differenr hashcode and == operator will return false.

### New Date and Time API


### LocalDate

It is a predefined final class which represents only Date. The java.util.Date class is providing Date and Time both so, only to get the Date we need to use LocalDate class available in java.time package.

```java
         LocalDate d = LocalDate.now();

```

Here now is a static method of LocalDate class and its return type is LocalDate class. (Factory Method)

LocalTime :
It is also a final class which will provide only time.
```java
            LocalTime d = LocalTime.now();

```

Here now is a static method of LocalTime class and its return type is LocalTime (Factory Method).

LocalDateTime :
It is also a final class which will provide Date and Time both without a time zone. It is a combination of LocalDate and LocalTime class.
```java
             LocalDateTime d = LocalDateTime.now();
```

```java
package com.ravi.new_date_time;

import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;
import java.time.ZoneId;
import java.time.ZonedDateTime;

public class Demo1
{
	public static void main(String[] args)
	{
	   LocalDate d = LocalDate.now();
	   System.out.println(d);

	   LocalTime t = LocalTime.now();
	   System.out.println(t);

	    LocalDateTime dt = LocalDateTime.now();
	    System.out.println(dt);


	}
}
```

Now, based on our application requirement we can take only date OR only time ot Date and time both

ZonedDateTime : (Date and time + Time zone)
It is a final class available in java.time package.

It is also provides date and time along with time zone so, by using this class we can work with different time zone in a global way.

```java
ZonedDateTime x = ZonedDateTime.now();
ZoneId zone = x.getZone();

```

getZone() is a predefined non static method of ZonedDateTime class which returns ZoneId class, this ZoneId class provides the different zones, by using getAvailableZoneIds() static method we can find out the total zone available using this ZoneId class.
```java
package com.ravi.new_date_time;

import java.time.ZoneId;
import java.time.ZonedDateTime;

public class Demo2
{
	public static void main(String[] args)
	{
		ZonedDateTime z = ZonedDateTime.now();
		System.out.println(z);

	    ZoneId zone = z.getZone();
	    System.out.println(zone);

	    System.out.println(ZoneId.getAvailableZoneIds());


	}

}
```

Different of() static method :
```java
List.of();
Set.of();
Map.of();
Stream.of();
Optional.of();
ZoneId.of();
```

```java
package com.ravi.new_date_time;

import java.time.ZoneId;
import java.time.ZonedDateTime;

public class Demo3
{
    public static void main(String[] args)
    {
        ZoneId AusTimeZone = ZoneId.of("Australia/Hobart");
        ZonedDateTime aus = ZonedDateTime.now(AusTimeZone);
        System.out.println("Current Date and Time in Australia Time Zone: " + aus);

        ZoneId londonTimeZone = ZoneId.of("Europe/London");
        ZonedDateTime lon = ZonedDateTime.now(londonTimeZone);
        System.out.println("Current Date and Time in London Time Zone: " + lon);




    }
}
```


> **Note :- of(String zoneId) is a static method of ZoneId abstract class it will provide the zoneId of specified zone as a parameter.**

Now with ZonedDateTime we can find out the specified zoned time.

### DateTimeFormatter

It is a predefined final class available in java.time.format sub package.

It is mainly used to formatting and parsing date and time objects according to Java Date and Time API.

Method :
```java
public static DateTimeFormatter ofPattern(String pattern) :

```

It is a static method of DateTimeFormatter class, It creates a
formatter using user specified String pattern ("dd-MM-yyyy HH:mm:ss")
and LocalDateTime class contains format method which takes
DateTimeFormatter as a parameter and returns the String value.

```java
package com.ravi.new_date_time;

import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;

public  class Demo4
{
  public static void main(String[] args)
  {
	LocalDateTime now = LocalDateTime.now();
	System.out.println(now);

	DateTimeFormatter formatter = DateTimeFormatter.ofPattern("dd-MM-YYYY");

	String formattedDateTime = now.format(formatter);
	System.out.println("Formatted DateTime: " + formattedDateTime);
  }
}
```


### Terminal Operation in Stream in java

In Java's Stream API, a terminal operation is an operation that produces a result or a side-effect operation.

Unlike intermediate operations, which returns a new stream, terminal operation consumes the elements of the stream.

Once a terminal operation is applied to a stream, the stream is considered consumed and cannot be reused.

It is a final operation.

Methods of Terminal Operation :
1) public long count()

2) public Optional<T> min(Comparator<? super T> comparator)

3) public Optional<T> max(Comparator<? super T> comparator)

4) public Optional<T> findAny()

5) public Optional<T> findFirst()

6) public boolean allMatch(Predicate<? super T> predicate)

7) public boolean anyMatch(Predicate<? super T> predicate)

8) public boolean noneMatch(Predicate<? super T> predicate)

9) public void forEach(Consumer<T> cons)

10) public R reduce(BinaryOperator<Integer> accumulator)

11) public Optional<T> collect(Collector<? super Integer,A,R> collect)
```java
public long count() :
```

The count operation returns the number of elements available in the stream. It is a terminal operation that terminates the stream after its execution.
Basically it used to count the number of elements after filter() method.
```java
package com.ravi.advanced.count_demo;

import java.util.stream.Stream;

public class CountDemo1
{
	public static void main(String[] args)
	{
		long count = Stream.of("Ravi","Raj","Elina","Aryan").count();
		System.out.println(count);

	}

}
```

```java
package com.ravi.advanced.count_demo;

//Count the name whose length is greater than 3

import java.util.List;

public class CountDemo2
{
    public static void main(String[] args) {
        List<String> listOfName = List.of("Raj","Ravi","Virat","Rohit","Ram","Bumrah","Sachin");

        long names = listOfName.stream().filter(name -> name.length()>3).count();
        System.out.println("Names whose length is > 3 are :"+names);
    }
}
```

```java
package com.ravi.advanced.count_demo;

//Count Unique elements by using Stream API
import java.util.List;

public class CountDemo3
{
    public static void main(String[] args) {
    	List<String> listOfName = List.of("Raj","Ravi","Virat","Raj");

```

long count = listOfName.stream()
.distinct()
```java
                         .count();

        System.out.println("Count of unique elements: " + count);
    }
}
```

```java
package com.ravi.advanced.count_demo;

//Count the names which are containing the character A
import java.util.Arrays;
import java.util.List;

public class CountDemo4
{
    public static void main(String[] args) {
        List<String> list = Arrays.asList("Raj","Ravi","Rohit","Virat","Raj");

```

long count = list.stream()
.map(String::toUpperCase)
.filter(s -> s.contains("A"))
.distinct()
```java
                         .count();

        System.out.println("Count of distinct strings containing 'A': " + count);
    }
}
```


### Working with Predefined functional interfaces


### UnaryOperator<T> functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents an operation on a single operand that produces a result of the same type as its operand. This is a specialization of Function for the case where the operand and result are of the same type.

It has a single type parameter, T, which represents both the operand type and the result type.

```java
@FunctionalInterface
public interface UnaryOperator<T> extends Function<T,R>
{
  public abstract T apply(T x);
}
```

```java
import java.util.function.*;
public class UnaryOperatorDemo
{
	public static void main(String[] args)
	{
		UnaryOperator<Integer> square = x -> x * x;
        System.out.println(square.apply(5));

		UnaryOperator<String> concat = str -> str.concat("base");
		 System.out.println(concat.apply("Data"));
	}
}
```


### BinaryOperator<T> Functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents an operation upon two operands of the same type, producing a result of the same type as the operands.

This is a specialization of BiFunction for the case where the operands and the result are all of the same type.

It has two parameters of same type, T, which represents both the operand types and the result type.

```java
@FunctionalInterface
public interface BinaryOperator<T> extends BiFunction<T,U,R>
{
  public abstract T apply(T x, T y);
}
```

```java
import java.util.function.*;
public class Lambda16
{
	public static void main(String[] args)
	{
		BinaryOperator<Integer> add = (a, b) -> a + b;
        System.out.println(add.apply(3, 5));
	}
}
```


### ToIntFunction<T> functional interface

It is a predefined functional interface available in java.util.function sub package.

It is a functional interface in Java that represents a function that takes an argument of type T and returns an int. This is typically used in streams when you need to perform operations that result in primitive int value.

```java
@FunctionalInterface
public interface ToIntFunction<T>
{
    int applyAsInt(T value);
}
```

```java
import java.util.*;
import java.util.function.*;
import java.util.stream.*;

```

record Employee(String name, int experience)
```java
{

}

public class Lambda17
{
   public static void main(String[] args)
   {
```


## ArrayList<Employee> listOfEmployee = new ArrayList<>();

```java
	  listOfEmployee.add(new Employee("Virat",12));
	  listOfEmployee.add(new Employee("Rohit",12));
	  listOfEmployee.add(new Employee("Bumrah",6));
	  listOfEmployee.add(new Employee("Akshar",5));

      ToIntFunction<Employee> experienceFunction = employee -> employee.experience();

      int totalYearsOfExperience = listOfEmployee.stream()
```

.mapToInt(experienceFunction)
```java
                                              .sum();

       System.out.println("Total years of experience: " + totalYearsOfExperience);


   }
}
```


### Predefined Functional interface

1) Predicate<T>         boolean test(T x)
2) Consumer<T>          void accept(T x)
3) Function<T,R>        R apply(T x)
4) Supplier<T>          T get()
5) BiPredicate<T,U>     boolean test(T x, U u)
6) BiConsumer<T,U>      void accept(T x, U u)
7) BiFunction<T,U,R>    R apply(T x, U u)
8) UnaryOpartor<T>      T apply(T x)
```java
9) BinaryOperator<T,T>  T apply(T x, T y);
```

10) ToIntFunction<T>    int applyAsInt(T x)

## 14-08-2024

```java
public Optional<T> min(Comparator<? super T> comparator)
```

It is a predefined method of Stream interface ,It is used to find the minimum element of the stream according to the provided Comparator.

This method is useful when we need to find out the smallest element in a stream, based on a specific comparison criteria using Comparator.
```java
package com.ravi.advanced.min_demo;

import java.util.Arrays;
import java.util.List;
import java.util.Optional;

public class MinDemo1
{
    public static void main(String[] args)
    {
        List<Integer> listOfNumbers = Arrays.asList(10, 20, 5, 40, 25, 2,1);

        Optional<Integer> min = listOfNumbers.stream().min(Integer::compareTo);

        min.ifPresent(System.out::println);


    }
}
```

```java
package com.ravi.advanced.min_demo;

import java.util.Comparator;
import java.util.Optional;
import java.util.stream.Stream;

//Finding the minimum age of Employee

```

record Employee(Integer age, String name)
```java
{

}


public class MinDemo2
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(23, "Scott");
		Employee e2 = new Employee(29, "Smith");
		Employee e3 = new Employee(21, "John");

		Stream<Employee> streamOfEmployee = Stream.of(e1,e2,e3);

		Optional<Employee> minAge = streamOfEmployee.min(Comparator.comparingInt(Employee::age));

		if(minAge.isPresent())
		{
			System.out.println("Minimum Age of Employee is :"+minAge.get());
		}
		else
		{
			System.err.println("No record available");
		}


	}

}

```

Note : Comparator interface has provided a static method comparingInt(ToIntFunction<T> x) which will accept ToIntFunction as a parameter (which is basically any type of Input <T>) but return value must be interger.
```java
package com.ravi.advanced.min_demo;

import java.util.Comparator;
import java.util.List;
import java.util.Optional;

//Finding the Cheapest Product

```

record Product(Integer productId, String productName, Double productPrice)
```java
{

}


public class MinDemo3 {

	public static void main(String[] args)
	{
		var p1 = new Product(111, "Camera", 45000D);
		var p2 = new Product(222, "Watch", 23000D);
		var p3 = new Product(333, "HeadPhone", 2000D);

		List<Product> listOfProduct = List.of(p1,p2,p3);

		Optional<Product> min = listOfProduct.stream().min(Comparator.comparingDouble(Product::productPrice));

		if (min.isPresent())
		{
            System.out.println("The cheapest product is: " + min.get());
        }
		else
        {
            System.out.println("No products found.");
        }

	}

}

```

Note : Comparator interface has provided a static method comparingDouble(ToDoubleFunction<T> x) which will accept ToDoubleFunction as a parameter (which is basically any type of Input <T>) but return value must be double.
```java
public Optional<T> max(Comparator<? super T> comparator)
```

It is a predefined method of Stream interface ,It is used to find the maximum element of the stream according to the provided Comparator.

This method is useful when we need to find out the largest element in a stream, based on a specific comparison criteria using Comparator.

```java
package com.ravi.advanced.max_demo;

import java.util.Comparator;
import java.util.List;
import java.util.Optional;

public class MaxDemo1 {

	public static void main(String[] args)
	{
		List<String> listOfFruits = List.of("Apple","Orange","Mango","Grapes","Pomogranate");

		Optional<String> max = listOfFruits.stream().max(Comparator.comparingInt(String::length));

		max.ifPresent(System.out::println);

	}

}
```

```java
package com.ravi.advanced.max_demo;

import java.util.Comparator;
import java.util.Optional;
import java.util.stream.Stream;

//Finding the Employee with the Highest Salary

```

record Employee(Integer employeeId, String employeeName, Double employeeSalary)
```java
{
}

public class MaxDemo2
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(111, "Aman", 23000D);
		Employee e2 = new Employee(222, "Ramesh", 24000D);
		Employee e3 = new Employee(333, "Suraj", 25000D);
		Employee e4 = new Employee(444, "Raj", 26000D);
		Employee e5 = new Employee(555, "Scott", 46000D);

		Stream<Employee> streamOfEmployees = Stream.of(e1,e2,e3,e4,e5);

		Optional<Employee> max = streamOfEmployees.max(Comparator.comparingDouble(Employee::employeeSalary));

		if(max.isPresent())
		{
			System.out.println("Employee Having Maximum Salary is :"+max.get());
		}
		else
		{
			System.out.println("No record Available");
		}

	}

}
```

```java
public Optional<T> findAny() :
```

It is a predefined method of Stream interface ,It is used  to return an Optional which describes some element of the stream, or an empty Optional if the stream is empty.

It's useful when we need any element from the stream but don't care which one.

```java
package com.ravi.advanced.find_any;

import java.util.List;
import java.util.Optional;

public class FindAnyDemo1
{
	public static void main(String[] args)
	{
		List<String> listOfNames = List.of("Raj", "Rahul", "Ankit");

		Optional<String> findAny = listOfNames.parallelStream().findAny();

		findAny.ifPresent(System.out::println);

	}

}
```

```java
package com.ravi.advanced.find_any;

import java.util.List;
import java.util.Optional;

public class FindAnyDemo2 {

	public static void main(String[] args)
	{
        List<String> listOfName = List.of("Sachin", "Ankit", "Aman", "Rahul", "Ravi");

        Optional<String> anyElement = listOfName.parallelStream().filter(s -> s.startsWith("R")).findAny();

        anyElement.ifPresent(System.out::println);
    }

}

```

Note : findAny() will select any random element but if we use parallelStream() then we will get the effect.
```java
public Optional<T> findFirst()
```

It is a predefined method of Stream interface ,It is used to return
an Optional which describes the first element of the stream, or an empty Optional if the stream is empty.

```java
package com.ravi.advanced.find_first;

import java.util.stream.Stream;

public class FindFirstDemo1
{
   public static void main(String[] args)
   {
	   Stream<String> fruitsStream = Stream.of("Virat", "Rohit", "Raj", "Bumrah", "Arshdeep");


       fruitsStream.findFirst().ifPresent(System.out::println);
   }
}
```

Differences between findAny() and findFirst()
```java
findFirst(): Always returns the first element of the stream, which is particularly useful for ordered streams.

```

findAny(): Returns any element from the stream, and is typically used in unordered streams where the order is not required. It may return elements faster because it does not have to maintain the order.

Note : Collection interface has provided parallelStream() method for
fast execution [It uses multiple threads]
```java
public boolean allMatch(Predicate<? super T> predicate)
```

It is a predefined method of Stream interface , It is used to check if all elements of the stream match a given predicate. This method is useful when we need to verify that every element in a stream satisfies a specific condition by using Predicate.

```java
package com.ravi.advanced.match;

import java.util.Arrays;
import java.util.List;
import java.util.function.Predicate;
import java.util.stream.Stream;

public class AllMatchDemo1 {

	public static void main(String[] args)
	{
		Stream<Integer> stream = Stream.of(1, 2, 3, 4, 5);
        boolean allPositive = stream.allMatch(n -> n > 0);
        System.out.println("All elements are positive: " + allPositive);

        System.out.println("...........................");

        List<Integer> numbers = Arrays.asList(2, 4, 6, 8, 10, 11);

        Predicate<Integer> isEven = number -> number % 2 == 0;

        boolean allEven = numbers.stream().allMatch(isEven);

        if (allEven)
        {
            System.out.println("All numbers are even.");
        }
        else
        {
            System.out.println("Not all numbers are even.");
        }
	}

}
```

```java
public boolean anyMatch(Predicate<? super T> predicate)
```

It is a predefined method of Stream interface, It returns a boolean indicating whether any elements of the stream match the given predicate. It is useful when we need to verify if there exists at least one element in the stream that satisfies the provided condition.

```java
package com.ravi.advanced.match;

import java.util.Arrays;
import java.util.List;
import java.util.function.Predicate;

public class AnyMatchDemo1
{
	 public static void main(String[] args)
	 {
	        List<String> listOfName = List.of("Virat","Rohit","Bumrah","Surya");

            boolean startsWithA = listOfName.stream().anyMatch(name -> name.startsWith("A"));

	        System.out.println("Any name starts with letter 'A' : " + startsWithA);

	        System.out.println("================================");

	        List<Integer> numbers = Arrays.asList(2, 1, 3, 5, 7);

	        Predicate<Integer> isEven = number -> number % 2 == 0;

	        boolean anyEven = numbers.stream().anyMatch(isEven);

	        if (anyEven)
	        {
	            System.out.println("There is at least one even number.");
	        }
	        else
	        {
	            System.out.println("There are no even numbers.");
	        }
	    }
}
```

```java
public boolean noneMatch(Predicate<? super T> predicate)
```

It is a predefined method of Stream interface, It is used to check if no elements of the stream match a given predicate. It returns a boolean value true if no elements match the predicate, and false if at least one element matches the predicate or if the stream is empty.

```java
package com.ravi.advanced.match;

import java.util.Arrays;
import java.util.List;
import java.util.function.Predicate;

public class NoneMatchDemo1
{
  public static void main(String[] args)
  {
	  List<Integer> numbers = Arrays.asList(1, 3, 5, 7, 9, 2, 8);

      Predicate<Integer> isEven = number -> number % 2 == 0;


      boolean noneEven = numbers.stream().noneMatch(isEven);


      if (noneEven)
      {
          System.out.println("There are no even numbers.");
      }
      else
      {
          System.out.println("There is at least one even number.");
      }
}
}
```

```java
R collect(Collector<? super T, A, R> collector);
```

It is a predefined method of Stream interface.It is used to transform the elements of a stream into a different form like collection i.e. List, Set, or Map.

The collect() method takes an argument of type Collector, which is a functional interface that specifies how to perform the collection operation. The Collectors class has provided follwing static methods

a) toList(): Collects the elements of the stream into a List.
b) toSet(): Collects the elements of the stream into a Set.
c) toMap(): Collects the elements of the stream into a Map.
d) joining(): Concatenates the elements of the stream into a String.
e) groupingBy(): Groups the elements of the stream by a classifier        function.
f) partitioningBy(): Partitions the elements of the stream into two       groups based on a predicate.

```java
package com.ravi.advanced.collect;

//Join the elements by using joining() methods of Collectors class
import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

public class CollectDemo1
{
    public static void main(String[] args)
    {
        List<String> list = Arrays.asList("a", "b", "c", "d");
        String result = list.stream().collect(Collectors.joining("-"));
        System.out.println(result);
    }
}
```

```java
package com.ravi.advanced.collect;

//Group the city name according to length of the city name
import java.util.*;
import java.util.stream.Collectors;

public class CollectDemo2
{
    public static void main(String[] args)
    {
        List<String> items = Arrays.asList("Delhi", "Indore", "Kolkata", "Pune", "Hyderabad","Mumbai","Chennai");

            Map<Integer, List<String>> groupedByLength = items.stream().collect(Collectors.groupingBy(String::length));

```

groupedByLength.forEach((length, cities) ->
```java
        {
            System.out.println("Length " + length + ": " + cities);
        });
    }
}

```

Note : groupingBy() method will group the element based on the classifier and return type is Map<Classifier, List<E>>
```java
package com.ravi.advanced.collect;

//Print the length of the country
import java.util.*;
import java.util.stream.Collectors;

public class CollectDemo3
{
    public static void main(String[] args)
    {
       List<String> listOfCountry = List.of("India","Australia","USA","China","Japan");

```

Map<String, Integer> map = listOfCountry.stream()
.collect(Collectors.toMap(
countryName -> countryName,
countryName -> countryName.length()
```java
                ));

```

map.forEach((key, value) ->
```java
        {
            System.out.println(key + ": " + value);
        });
    }
}

```

Here toMap(Function<T,R>, Function<T,R>) as a parameter.

### How to convert a Map into Stream for data proessing?

```java
 package maptostream;

import java.util.HashMap;
import java.util.Map;
import java.util.stream.Collectors;

//Fetch all the product details whose price  is more than 40K

public class MapToStream
{

	public static void main(String[] args)
	{
		Map<String,Double> map = new HashMap<>();
		map.put("Camera", 45890.90);
		map.put("Laptop", 85890.90);
		map.put("Mobile", 35890.90);
		map.put("Watch",  25890.90);

		Map<String, Double> filteredProdMap = map.entrySet().stream().filter(entry -> entry.getValue()>40000).collect(Collectors.toMap(Map.Entry::getKey, Map.Entry::getValue));

		System.out.println(filteredProdMap); //

		//Total sum of all the filtered products
		 double sumOfProd = filteredProdMap.values().stream().mapToDouble(Double::doubleValue).sum();
		System.out.println("Total price :"+sumOfProd);

	}

}
```


## 16-08-2024

```java
//Based on the department, group all the employee

package com.ravi.advanced.collect;

import java.util.HashMap;
import java.util.List;
import java.util.Map;
import java.util.stream.Collectors;

```

record Employee(Integer empId, String empName, double salary, Department dept)
```java
{
	//111 , "A", 23890.89, new Department(1,"IT");
}

```

record Department(Integer deptId, String deptName)
```java
{
}

public class CollectDemo4
{
	public static void main(String[] args)
	{
		Employee e1 = new Employee(111, "Raj", 23789.89, new Department(1, "IT"));
		Employee e2 = new Employee(222, "Rahul", 23789.89, new Department(1, "IT"));
		Employee e3 = new Employee(333, "Scott", 23789.89, new Department(2, "Sales"));
		Employee e4 = new Employee(444, "Smith", 23789.89, new Department(2, "Sales"));
		Employee e5 = new Employee(333, "Virat", 23789.89, new Department(3, "HR"));
		Employee e6 = new Employee(444, "Rohit", 23789.89, new Department(3, "HR"));



		List<Employee> list = List.of(e1,e2,e3,e4,e5,e6);


     	Map<Department, List<Employee>> collect = list.stream().collect(Collectors.groupingBy(Employee::dept));

```

collect.forEach((key, value) ->
```java
        {
            System.out.println(key + ": " + value);
        });
	}

}
```

Map<Boolean, List<T>> Collectors.partitioningBy(Predicate<T> p)
It is a predefined static method of Collectors class.

It is used to partition the elements of a stream into two groups based on a given predicate.

The result is a Map with Boolean keys, where the true key corresponds to elements that satisfy the predicate, and the false key corresponds to elements that do not satisfy the predicate.
```java
package com.ravi.advanced.collect;

//Partition the given number based on the Predicate

import java.util.List;
import java.util.Map;
import java.util.stream.Collectors;

public class CollectDemo5
{
    public static void main(String[] args)
    {
        List<Integer> numbers = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

```

Map<Boolean, List<Integer>> partitioned = numbers.stream()
```java
            .collect(Collectors.partitioningBy(n -> n % 2 == 1));

        System.out.println(partitioned);
     }
}
```

```java
package com.ravi.advanced.collect;

//Partition the given number based on the Predicate and convert to Set

import java.util.List;
import java.util.Map;
import java.util.Set;
import java.util.stream.Collectors;

public class CollectDemo6
{
    public static void main(String[] args)
    {
        List<Integer> numbers = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 1, 3);

```

Map<Boolean, Set<Integer>> partitioned = numbers.stream()
.collect(Collectors.partitioningBy(
n -> n % 2 == 1,
```java
                Collectors.toSet()));

        System.out.println(partitioned);

    }
}

```

Collectors.partitioningBy() is accepting two parameters , Predicate, Collector so by uisng 2nd parameter we can convert to Set so, duplicates are not allowed.
```java
package com.ravi.advanced.collect;

//Count how many elements are partition based on given predicate

import java.util.List;
import java.util.Map;
import java.util.stream.Collectors;

public class CollectDemo7
{
    public static void main(String[] args) {
        List<Integer> numbers = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11);

```

Map<Boolean, Long> partitioned = numbers.stream()
.collect(Collectors.partitioningBy
(
n -> n % 2 == 1,
```java
                Collectors.counting()));

        System.out.println(partitioned);

    }
}

```

Collectors.counting() to count the numbers.
Optional<T> reduce(BinaryOperator<T> accumulator)
It is a predefined method of Stream interface.

This method is useful for combining stream elements into a single result because it accept BinaryOperator<T> as a parameter, such as computing the sum, product, or concatenation of elements.

It performs a reduction on the elements of the stream, using an associative accumulation function, and returns an Optional.

```java
package com.ravi.advanced.reduce;

import java.util.Optional;
import java.util.stream.Stream;

public class ReduceDemo1
{
    public static void main(String[] args)
    {

        Stream<Integer> integerStream = Stream.of(1, 2, 3, 4, 5);
        Optional<Integer> reduce = integerStream.reduce(Integer::sum);

        reduce.ifPresent(System.out::println);

        System.out.println("==========================================");

        integerStream = Stream.of(1, 2, 3, 4, 5);
        Integer sumWithIdentity = integerStream.reduce(2, Integer::sum);
        System.out.println(sumWithIdentity);



    }
}
```

```java
package com.ravi.advanced.reduce;

//Finding the maximum number

import java.util.Arrays;
import java.util.List;
import java.util.Optional;

public class ReduceDemo2
{
    public static void main(String[] args) {
        List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);

```

Optional<Integer> max = numbers.stream()
```java
                                       .reduce(Integer::max);

        max.ifPresent(System.out::println);
    }
}
```

```java
package com.ravi.advanced.reduce;

//Finding the multiplication of all numbers

import java.util.Arrays;
import java.util.List;
import java.util.Optional;

public class ReduceDemo3
{
    public static void main(String[] args) {
        List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);

```

Optional<Integer> product = numbers.stream()
```java
                                           .reduce((a, b) -> a * b);

        product.ifPresent(System.out::println);

        System.out.println("==========================");
        Integer reduce = numbers.stream().reduce(1,(a,b)-> a*b);
        System.out.println(reduce);

    }
}
```

```java
package com.ravi.advanced.reduce;
import java.util.Arrays;
import java.util.List;
import java.util.Optional;

public class ReduceDemo4
{
    public static void main(String[] args) {
        List<String> words = Arrays.asList("Java", "is", "Best");

```

Optional<String> concatenated = words.stream()
```java
                                             .reduce((a, b) -> a + " " + b);

        concatenated.ifPresent(System.out::println);
      }
}
```

```java
package com.ravi.advanced.reduce;

//Finding the total sale amount

import java.util.stream.Stream;

```

record Sale(String item, Double amount)
```java
{

}

public class ReduceDemo5
{
	public static void main(String[] args)
	{
```

Stream<Sale> sales = Stream.of(
```java
	            new Sale("Camera", 10000.0),
	            new Sale("Mobile", 50000.0),
	            new Sale("Laptop", 80000.0),
	            new Sale("LED", 20000.0)
	        );

		Double totalSale = sales.reduce(0.0, (sum , sale)-> sum + sale.amount(),Double::sum);

		System.out.println("Total Sale for today is :"+totalSale);

	}

}
```

84 Stream API Question

```java
public class Tester {
	private static final String RED = "\033[1;31m"; // RED
	private static final String RESET = "\033[0m"; // Text Reset
	public static void main(String[] args)
	{
		List<Employee> list = EmployeeAdder.addDetails();
		Set<Integer> set = new HashSet<>();
		Set<String> set2 = new HashSet<>();
//		 1. Filter Employees by Gender:
//		 - Retrieve a list of all female employees.
		System.out.println(RED+"*****Retrieve a list of all female employees********"+RESET);
```

list.stream()
.filter(t -> t.getGender().equals("Female"))
```java
		.forEach(System.out::println);
		System.out.println(RED+"*****Get a list of employees older than 30 years.********"+RESET);
//		2. Filter Employees by Age:
//			   - Get a list of employees older than 30 years.
```

list.stream()
.filter(employee->employee.getAge()>30)
```java
		.forEach(System.out::println);
		System.out.println(RED+"*****Find employees with a salary greater than $50,000.********"+RESET);
//		3. Filter Employees by Salary:
//			   - Find employees with a salary greater than $50,000.
```

list.stream()
.filter(employee->employee.getSalary()>50000)
```java
		.forEach(System.out::println);

//		4. Map Employee Names:
//		   - Create a list of employee names (Strings).
		System.out.println(RED+"*************Create a list of employee names (Strings)*************"+RESET);
```

list.stream()
.map(employee->employee.getName())
```java
		.forEach(System.out::println);

//		5. Calculate Average Salary:
//			   - Calculate the average salary of all employees.
		System.out.println(RED+"*********Calculate the average salary of all employees.*******"+RESET);
		double orElseThrow = list.stream()
```

.mapToDouble(Employee::getSalary)
.average()
```java
				.orElseThrow();
		System.out.println("Average : "+orElseThrow);

//		6. Find Maximum Salary:
//			   - Find the employee with the highest salary.
		System.out.println(RED+"*********Find the employee with the highest salary.********"+RESET);
		double max = list.stream()
```

.mapToDouble(Employee::getSalary)
.max()
```java
				.orElseThrow();
		System.out.println("Max Salary : "+max);

//		7.Group Employees by Gender:
//			   - Group employees by gender and return
//			   a map with gender as the key and a list of employees as the value.
		System.out.println(RED+"******Group employees by gender and return a map******"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getGender))
```java
		.forEach((key,value)->System.out.println(key+" - "+value));

//		8. Count Male Employees:
//			   - Count the number of male employees.
		System.out.println(RED+"**********Count the number of male employees.*********"+RESET);
```

long count = list.stream()
.filter(employee -> employee.getGender().equals("Male"))
```java
				.count();
		System.out.println("Count : "+count);

//		9. Sum of All Salaries:
//			   - Calculate the total sum of salaries for all employees.
		System.out.println(RED+"*********Calculate the total sum of salaries for all employees.**********"+RESET);
		double sum = list.stream()
```

.mapToDouble(employee->employee.getSalary())
```java
				.sum();
		System.out.println("Sum : "+sum);

//		10. Sort Employees by Name:
//		    - Sort the employees by their names in alphabetical order.
		System.out.println(RED+"*******Sort the employees by their names in alphabetical order.*****"+RESET);
```

list.stream().sorted(Comparator.comparing(Employee::getName))
```java
		.forEach(System.out::println);

//		11. Sort Employees by Age:
//		    - Sort the employees by age in ascending order.
		System.out.println(RED+"**********Sort the employees by age in ascending order.********"+RESET);
```

list.stream()
.sorted(Comparator.comparing(Employee::getAge))
```java
		.forEach(System.out::println);

//		12. Sort Employees by Salary:
//		    - Sort the employees by salary in descending order.
		System.out.println(RED+"*********Sort the employees by salary in descending order.******"+RESET);
```

list.stream()
.sorted(Comparator.comparing(Employee::getAge).reversed())
```java
		.forEach(System.out::println);

//		13. Find Oldest Employee:
//		    - Find the oldest employee.
		System.out.println(RED+"*********Find the oldest employee.*********"+RESET);
//		int orElseThrow2 = list.stream().mapToInt(Employee::getAge).max().orElseThrow();
```

Employee employee = list.stream()
.max((e1,e2)->(e1.getAge()-e2.getAge()))
```java
				.get();
		System.out.println(employee);
//		System.out.println("Max Age : "+orElseThrow2);

//		14. Group Employees by Age:
//		    - Group employees into age groups (e.g., 20-30, 31-40, etc.)
//		    and return a map with age group as the key and a list of employees as the value.
		System.out.println(RED+"****Group employees into age groups (e.g., 20-30, 31-40, etc.)*****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy((t) ->
```java
						{int age = t.getAge();
							if(age>=20 && age<=30)
								return "20-30";
							else if (age>=31 && age<=40)
								return "31-40";
							else
								return "40+";
						})).forEach((key,value)->System.out.println(key+ " - "+value ));
//		15. Find Employees with a Specific Age:
//		    - Find all employees who are exactly 35 years old.
		System.out.println(RED+"************ Find all employees who are exactly 35 years old.***********"+RESET);
		list.stream().filter(k->k.getAge()==35).forEach(System.out::println);

//		16. Calculate the Sum of Salaries by Gender:
//		    - Calculate the sum of salaries for each gender (i.e., male and female)
//		    and return a map with gender as the key and the sum of salaries as the value.
		System.out.println(RED+"********* Calculate the sum of salaries for each gender**********"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getGender ,
Collectors.summingDouble(Employee::getSalary)))
```java
		.forEach((key,value)->System.out.println(key +" - "+value));


//		17. Find Employees with Names Starting with "J":
//		    - Find all employees whose names start with the letter "E."
		System.out.println(RED+"*********Find all employees whose names start with the letter J******"+RESET);
		list.stream().filter(k->k.getName().startsWith("E")).forEach(System.out::println);

//		18. Calculate the Average Salary for Male and Female Employees:
//		    - Calculate the average salary separately for male
//		    and female employees and return a map with gender
//		    		as the key and the average salary as the value.
		System.out.println(RED+"**********Calculate the average salary separately for male and female*********"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getGender,
Collectors.averagingDouble(Employee::getSalary)))
```java
		.forEach((key,value)->System.out.println(key+" - "+value));

//		19. Find the Top N Highest Paid Employees:
//		    - Find the top N employees with the highest salaries.

		System.out.println(RED+"*******Find the top N employees with the highest salaries.********"+RESET);
```

list.stream().sorted((o1, o2) -> -(int)(o1.getSalary()-o2.getSalary()))
```java
		.limit(5).forEach(System.out::println);

```

list.stream()
.sorted(Comparator.comparingDouble(Employee::getSalary).reversed())
.limit(3)
```java
		.forEach(System.out::println);

//		20. Retrieve Distinct Age Values:
//		    - Get a list of distinct ages of all employees.
		System.out.println(RED+"*********Get a list of distinct ages of all employees.*********"+RESET);

		list.stream().filter(k->!set.add(k.getAge())).forEach(System.out::println);

//		21. Find the Three Lowest-Paid Employees:
//			   - Find and display the names of the three employees with the lowest salaries.
		System.out.println(RED+"*******Find and display the names of the three employees with the lowest salaries.********"+RESET);
```

list.stream()
.sorted((o1,o2)->(int)(o1.getSalary()-o2.getSalary()))
.map(k->k.getName())
.limit(3)
```java
		.forEach(System.out::println);

//		22. Sort Employees by Name Length:
//			   - Sort employees by the length of their names (shortest to longest).
		System.out.println(RED+"***********Sort employees by the length of their names (shortest to longest).*******"+RESET);
```

list.stream()
.sorted((o1, o2) ->(o1.getName().length()-o2.getName().length()))
```java
		.forEach(System.out::println);

//		23. Group Employees by Age Range:
//			   - Group employees into custom
//			   age ranges (e.g., 20-29, 30-39, etc.) and
//			   return a map with the age range as the key and a list of employees as the value.
		System.out.println(RED+"*********Group employees into custom age ranges (e.g., 20-29, 30-39, etc.)*********"+RESET);
```

list.stream()
.collect(Collectors.groupingBy((t)->
```java
		{
			int age = (t).getAge();
			if(age>=20 && age<=29)
				return "20-29";
			else if(age>=30 && age <= 39)
				return "30-39";
			else
				return "40+";
		}))
		.forEach((key,value)->System.out.println(key+" - "+value));

//		24. Find the Average Salary of Employees Aged 30 or Younger:
//			   - Calculate the average salary of employees aged 30 or younger.

		System.out.println(RED+"********Calculate the average salary of employees aged 30 or younger.******"+RESET);
		double orElseThrow2 = list.stream()
		.filter(emp->emp.getAge()<=30).mapToDouble(k->k.getSalary()).average().orElseThrow();
		System.out.println(orElseThrow2);

//		25. Find the Names of Male Employees with Salaries Over $60,000:
//			   - Retrieve the names of male employees with salaries over $60,000.
		System.out.println(RED+"**********Retrieve the names of male employees with salaries over $53,000.***********"+RESET);
```

list.stream()
.filter(e->e.getSalary()>=53000 && e.getGender().equals("Male"))
.map(k->k.getName())
```java
		.forEach(System.out::println);

//		26. Find the Youngest Female Employee:
//			   - Find the youngest female employee.
		System.out.println(RED+"**********Find the youngest female employee.**********"+RESET);
```

Employee employee2 = list.stream()
.filter(k->k.getGender().equals("Female"))
```java
		.collect(Collectors.minBy((o1, o2) -> o1.getAge()-o2.getAge())).get();
		System.out.println(employee2);

//		27. Retrieve the Names of Employees in Reverse Order:
//			   - Get a list of employee names in reverse order (from the last employee to the first).
		System.out.println(RED+"******Get a list of employee names in reverse order*******"+RESET);
		List<String> collect = list.stream().map(k->k.getName()).collect(Collectors.toList());
		Collections.reverse(collect);
		System.out.println(collect);

//		28. Find the Highest Salary Among Female Employees:
//			   - Find the highest salary among female employees.
		System.out.println(RED+"******Find the highest salary among female employees."+RESET);
```

Employee employee3 = list.stream()
.filter(k->k.getGender().equals("Female"))
```java
		.collect(Collectors.maxBy((o1, o2) -> (int)(o1.getSalary()-o2.getSalary()))).get();
		System.out.println(employee3);

//		29. Group Employees by Age and Gender:
//			   - Group employees by both age and gender and return a multi-level map.
		System.out.println(RED+"********Group employees by both age and gender and return a multi-level map.*****"+RESET);
```

Map<String, Map<Integer, List<Employee>>> collect2 = list.stream()
```java
		.collect(Collectors.groupingBy(Employee::getGender,Collectors.groupingBy(Employee::getAge)));

```

collect2.forEach((key,value)->
```java
		{
			value.forEach((k,v)->System.out.println(k+"-"+v));
			System.out.println(key+"-"+value);
		});

//		30. Find the Sum of Salaries for Employees with Names Containing "Smith":
//			   - Calculate the sum of salaries for employees whose names contain the substring "Smith."
		System.out.println(RED+"******* Calculate the sum of salaries for employees whose names contain the substring Smith***"+RESET);
		double sum2 = list.stream().filter(k->k.getName().contains("Smith")).mapToDouble(k->k.getSalary()).sum();
		System.out.println(sum2);

//		31. Find the Names of Employees Aged 30-40 with Salaries Between $50,000 and $60,000:
//			   - Retrieve the names of employees aged 30-40 with salaries between $50,000 and $60,000.
		System.out.println(RED+"******Retrieve the names of employees aged 30-40 with salaries between $50,000 and $60,000.*******"+RESET);
```

list.stream()
.filter(k->(k.getAge()>=30 && k.getAge()<=40)&&(k.getSalary()>=52000&&k.getSalary()<=60000))
```java
		.forEach(System.out::println);

//		32. Calculate the Total Number of Employees:
//			   - Determine the total count of employees.

		System.out.println(RED+"******** Determine the total count of employees.*******"+RESET);
		System.out.println("Total Count of employess : "+list.stream().count());

//		33. Find the Most Common Age Among Employees:
//			   - Determine the age that is most common among the employees.
		System.out.println(RED+"******Determine the age that is most common among the employees.***"+RESET);
```

Integer orElseThrow3 = list.stream()
.collect(Collectors.groupingBy(Employee::getAge,Collectors.counting())) // grouping ages and count
.entrySet() // converting to set
.stream()
.max(Map.Entry.comparingByValue()) // finding max value in map
.map(Map.Entry::getKey) // getting key of max value
.orElseThrow(); // getting the key
```java
		System.out.println(orElseThrow3);

//		34. Find the Median Salary:
//			   - Calculate the median salary of all employees.

		System.out.println(RED+"********Calculate the median salary of all employees.******"+RESET);
```

List<Employee> list2 = list.stream()
```java
		.sorted(Comparator.comparingDouble(Employee::getSalary)).toList();
		int size = list2.size();
		if(size%2==0)
		{
			double s = list2.get(size/2-1).getSalary();
			double s1 = list2.get(size/2).getSalary();
			System.out.println((s+s1)/2.0);
		}
		else {
			System.out.println(list2.get(size/2).getSalary());
		}


//		35. Group Employees by Age and Count:
//		   - Group employees by age and count the number of employees in each age group.
		System.out.println(RED+"*******Group employees by age and count******"+RESET);
```

list.stream().collect(Collectors.groupingBy(Employee::getAge,Collectors.counting()))
```java
		.forEach((key,value)->System.out.println(key+" - "+value));

//		36. Find the Employee with the Longest Name:
//			   - Find the employee with the longest name.
		System.out.println(RED+"********Find the employee with the longest name.****"+RESET);
```

Employee employee4 = list.
```java
							stream()
```

.max((o1, o2) -> o1.getName().length() - o2.getName().length())
```java
							.get();
		System.out.println(employee4);

//		37. Calculate the Sum of Salaries for Each Age:
//			   - Calculate the sum of salaries for each distinct age in a map.
		System.out.println(RED+"***********Calculate the sum of salaries for each distinct age in a map*******"+RESET);
		set.clear();
```

list.stream()
.filter(k->!set.add(k.getAge()))
.collect(Collectors.groupingBy(Employee::getAge,Collectors.summingDouble(Employee::getSalary)))
```java
		.forEach((key,value)->System.out.println(key+" - "+value));

//		38. Sort Employees by Age, Then by Salary:
//			   - Sort employees first by age in ascending order, and then by salary in descending order.
		System.out.println(RED+"**********Sort employees first by age in ascending order, and then by salary in descending order*******"+RESET);
```

list.stream()
.sorted(Comparator.comparingInt(Employee::getAge)
.thenComparing(Comparator.comparingDouble(Employee::getSalary).reversed()))
```java
		.forEach(System.out::println);

//		39. Find Employees Whose Names Contain More Than One Word:
//			   - Retrieve employees whose names consist of more than one word.
		System.out.println(RED+"***********Retrieve employees whose names consist of more than one word.*****"+RESET);
```

list.stream()
.filter(k->k.getName().length()>1)
```java
		.forEach(System.out::println);

//		40. Find the Two Highest Paid Female Employees:
//			   - Find and display the names of the two highest-paid female employees.
		System.out.println(RED+"**********Find and display the names of the two highest-paid female employees.*****"+RESET);
```

list.stream()
.filter(k->k.getGender().equals("Female"))
.sorted(Comparator.comparingDouble(Employee::getSalary).reversed())
.limit(2)
```java
		.forEach(System.out::println);

//		41. Find the Employee with the Highest Salary in Each Gender:
//			   - Find the employee with the highest salary for each gender (male and female).
		System.out.println(RED+"******Find the employee with the highest salary for each gender (male and female).*****"+RESET);
```

list.stream()
.collect(Collectors.toMap(Employee::getGender, k->k,(e1, e2) -> e1.getSalary()>=e2.getSalary()?e1:e2))
```java
		.forEach((key,value)->System.out.println(key+"-"+value));

//		42. Retrieve Employees with Unique Names:
//			   - Find employees with unique names (no duplicate names in the list).
		System.out.println(RED+"*******Find employees with unique names (no duplicate names in the list).****"+RESET);
```

list.stream().filter(k->set2.add(k.getName()))
```java
		.forEach(System.out::println);
		set2.clear();

//		43. Find the Names of Employees in Uppercase:
//			   - Get a list of employee names in uppercase.
		System.out.println(RED+"*******Get a list of employee names in uppercase.*****"+RESET);
```

list.stream()
.filter(k->k.getName().equals(k.getName().toUpperCase()))
```java
		.forEach(System.out::println);

//		44. Calculate the Salary Range (Min-Max) for Each Age Group:
//			   - Calculate the salary range (minimum and maximum) for each distinct age group.
		System.out.println(RED+"******Calculate the salary range (minimum and maximum) for each distinct age group.****"+RESET);
```

list.stream()
.collect(Collectors.
```java
				groupingBy(Employee::getAge,
```

Collectors.collectingAndThen(Collectors.toList(),
employees->
```java
						{
							double min = employees.stream()
```

.mapToDouble(Employee::getSalary)
```java
									.min().orElseThrow();
							double maxs = employees.stream()
```

.mapToDouble(Employee::getSalary)
```java
									.max().orElseThrow();
							Map<String,Double> map = new HashMap<>();
							map.put("min", min);
							map.put("max", maxs);
							return map;
						}))).
		forEach((age,salary)->
		System.out.println
		("Age : "+age+" - "+"Min Salary : "+salary.get("min")+" Max Salary : "+salary.get("max")));

//		45. Filter Employees by First Name Initial:
//			   - Retrieve employees whose first name starts with a specific initial (e.g., 'A').
		System.out.println(RED+"********Retrieve employees whose first name starts with a specific initial (e.g., 'E').******"+RESET);
```

list.stream()
.filter(k->k.getName().startsWith("E"))
```java
		.forEach(System.out::println);

//		46. Group Employees by Age and List Only Unique Salaries:
//			   - Group employees by age and display a list of unique salaries for each age group.
		System.out.println(RED+"********Group employees by age and display a list of unique salaries for each age group.*****"+RESET);
```

list.stream()
.collect(Collectors
.groupingBy(Employee::getAge,
Collectors.mapping(Employee::getSalary, Collectors.toSet())))
```java
							.forEach((key,value)->System.out.println("Age : "+key +" Salary : "+value));

//		47. Find Employees with the Same Salary:
//			   - Identify and display employees who have the same salary.
		System.out.println(RED+"*****Identify and display employees who have the same salary.****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getSalary))
.entrySet()
.stream() // k is entry
.filter(k -> k.getValue().size()>1)
.forEach(entry ->  // Map (Double , List<>)
```java
		{
			System.out.println(entry.getKey());
			entry.getValue().forEach(System.out::println);

		});


//		48. Find the Employee with the Shortest Name Among Male Employees:
//		   - Find the male employee with the shortest name.
		System.out.println(RED+"******Find the male employee with the shortest name.******"+RESET);
```

Employee employee5 = list.stream()
.filter(k->k.getGender().equals("Male"))
.min((o1, o2) -> Integer.compare(o1.getName().length(), o2.getName().length()))
```java
		.orElseThrow();
		System.out.println(employee5);

//		49. Find the Most Common Salary Value:
//			   - Determine the salary value that appears most frequently among the employees.
		System.out.println(RED+"************Determine the salary value that appears most frequently among the employees.********"+RESET);
```

Double orElseThrow4 = list.stream()
.collect(Collectors.groupingBy(Employee::getSalary , Collectors.counting()))
.entrySet()
.stream()
.max(Map.Entry.comparingByValue())
```java
		.map(Map.Entry::getKey).orElseThrow();
		System.out.println(orElseThrow4);

//		50. Find the Oldest Employee with the Lowest Salary:
//			   - Find the oldest employee with the lowest salary.
		System.out.println(RED+"*******Find the oldest employee with the lowest salary.******"+RESET);
```

Employee employee6 = list.stream()
.filter(k-> k.getAge()==list.stream().mapToInt(Employee::getAge).max().orElseThrow())
```java
		.min(Comparator.comparingDouble(Employee::getSalary)).get();
		System.out.println(employee6);

//		51. Filter Employees by Gender:
//			   - Retrieve a list of all female employees.
		System.out.println(RED+"****** Retrieve a list of all female employees.****"+RESET);
```

list
.stream()
.filter(k->k.getGender().equals("Female"))
```java
		.forEach(System.out::println);

//		52. Filter Employees by Age:
//			   - Get a list of employees older than 30 years.
		System.out.println(RED+"*************Get a list of employees older than 30 years.********"+RESET);
```

list
.stream()
.filter(k->k.getAge()>30)
```java
		.forEach(System.out::println);

//		53. Filter Employees by Salary:
//			   - Find employees with a salary greater than $50,000.
		System.out.println(RED+"******Find employees with a salary greater than $50,000.******"+RESET);
```

list.stream()
.filter(k->k.getSalary()>50000)
```java
		.forEach(System.out::println);


//		54. Map Employee Names:
//		   - Create a list of employee names (Strings).
		System.out.println(RED+"******Create a list of employee names (Strings).******"+RESET);
```

list.stream()
.map(k->k.getName())
```java
		.toList().forEach(System.out::println);


//		55. Calculate Average Salary:
//		   - Calculate the average salary of all employees.
		System.out.println(RED+"*********Calculate the average salary of all employees.****"+RESET);
```

Double collect3 = list.stream()
```java
		.collect(Collectors.averagingDouble(Employee::getSalary));
		System.out.println(collect3);

//		56. Find Maximum Salary:
//			   - Find the employee with the highest salary.
		System.out.println(RED+"********Find the employee with the highest salary.********"+RESET);
```

Employee employee7= list.stream()
```java
		.collect(Collectors.maxBy(Comparator.comparingDouble(Employee::getSalary))).get();
		System.out.println(employee7);

//		57. Group Employees by Gender:
//			   - Group employees by gender
//			   and return a map with gender as the key and a list of employees as the value.
		System.out.println(RED+"*********return a map with gender as the key and a list of employees*****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getGender))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		58. Count Male Employees:
//			   - Count the number of male an female employees.
		System.out.println(RED+"****Count the number of male and female employees.*****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getGender , Collectors.counting()))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		59. Sum of All Salaries:
//			   - Calculate the total sum of salaries for all employees.
		System.out.println(RED+"******Calculate the total sum of salaries for all employees.*****"+RESET);
```

Double collect4 = list.stream()
```java
		.collect(Collectors.summingDouble(Employee::getSalary));
		System.out.println(collect4);

//		60. Sort Employees by Name:
//			   - Sort the employees by their names in alphabetical order.
		System.out.println(RED+"****** Sort the employees by their names in alphabetical order.******"+RESET);
```

list.stream()
```java
		.sorted(Comparator.comparing(Employee::getName)).forEach(System.out::println);

//		61. Find the Employee with the Highest Salary in Each Gender:
//			   - Find the employee with the highest salary for each gender (male and female).
		System.out.println(RED+"*******Find the employee with the highest salary for each gender (male and female).*****"+RESET);
```

list.stream()
.collect(Collectors.toMap(Employee::getGender, t -> t,(t, u) -> t.getSalary()>=u.getSalary() ? t : u))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		62. Retrieve Employees with Unique Names:
//			   - Find employees with unique names (no duplicate names in the list).
		System.out.println(RED+"*******Find employees with unique names (no duplicate names in the list).******"+RESET);
```

list
.stream()
.collect(Collectors.groupingBy(Employee::getName , Collectors.counting()))
.entrySet()
.stream()
.filter(k->k.getValue()==1)
```java
		.forEach(k->System.out.println(k.getKey()));

//		63. Find the Names of Employees in Uppercase:
//			   - Get a list of employee names in uppercase.
		System.out.println(RED+"******Get a list of employee names in uppercase.******"+RESET);
```

list
.stream()
.filter(k->k.getName().equals(k.getName().toUpperCase()))
```java
		.forEach(System.out::println);

//		64. Calculate the Salary Range (Min-Max) for Each Age Group:
//			   - Calculate the salary range (minimum and maximum) for each distinct age group.
		System.out.println(RED+"*******Calculate the salary range (minimum and maximum) for each distinct age group.******"+RESET);
```

Map<Integer,Map<String,Double>> collect5 = list.stream()
.collect(Collectors.groupingBy(Employee::getAge,
Collectors.collectingAndThen(Collectors.toList(), k ->
```java
		{
			Double maxx = k.stream().mapToDouble(k2->k2.getSalary()).max().getAsDouble();
			Double min = k.stream().mapToDouble(k1->k1.getSalary()).min().getAsDouble();
			Map<String, Double> map =  new HashMap<>();
			map.put("max", maxx);
			map.put("min", min);
			return map;

		})));
```

collect5.forEach((age,map)->
```java
		{
			System.out.print("Age : "+age+" - ");
			System.out.println("Minimum : "+map.get("min")+" Maximum : "+map.get("max"));
		});

//		65. Filter Employees by First Name Initial:
//			   - Retrieve employees whose first name starts with a specific initial (e.g., 'E').
		System.out.println(RED+"**********Retrieve employees whose first name starts with a specific initial *******"+RESET);
```

list.stream()
.filter(k->k.getName().startsWith("E"))
```java
		.forEach(System.out::println);

//		66. Group Employees by Age and List Only Unique Salaries:
//			   - Group employees by age and display a list of unique salaries for each age group.
		System.out.println(RED+"*******Group employees by age and display a list of unique salaries for each age group.******"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getAge,
Collectors.mapping(Employee::getSalary, Collectors.toSet())))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		67. Find Employees with the Same Salary:
//			   - Identify and display employees who have the same salary.
		System.out.println(RED+"********Identify and display employees who have the same salary.****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(Employee::getSalary))
.entrySet()
.stream()
.filter(k->k.getValue().size()>1)
.forEach(t ->
```java
		{
			System.out.println(t.getKey() + " " + t.getValue());
		});

//		68. Find the Employee with the Shortest Name Among Male Employees:
//			   - Find the male employee with the shortest name.
		System.out.println(RED+"********Find the male employee with the shortest name.*****"+RESET);
```

Employee employee8 = list.stream().filter(k->k.getGender().equals("Male"))
```java
		.min(Comparator.comparing(Employee::getName)).get();
		System.out.println(employee8);

//		69. Find the Most Common Salary Value:
//			   - Determine the salary value that appears most frequently among the employees.
		System.out.println(RED+"*******Determine the salary value that appears most frequently among the employees.********"+RESET);
```

Double double1 = list.stream()
.collect(Collectors.groupingBy(Employee::getSalary , Collectors.counting()))
.entrySet()
.stream()
.max(Map.Entry.comparingByValue())
```java
		.map(Map.Entry::getKey).get();
		System.out.println(double1);

//		70. Find the Oldest Employee with the Lowest Salary:
//			   - Find the oldest employee with the lowest salary.
		System.out.println(RED+"*******Find the oldest employee with the lowest salary.*****"+RESET);
```

Employee employee9 = list.stream()
.filter(k->k.getAge()==list.stream().mapToInt(Employee::getAge).max().getAsInt())
```java
		.min(Comparator.comparingDouble(Employee::getSalary)).get();
		System.out.println(employee9);

//		71. Find the Most Common Age Among Employees:
//			   - Determine the age that is most common among the employees.
		System.out.println(RED+"*******Determine the age that is most common among the employees.*****"+RESET);
```

Integer integer = list.stream()
.collect(Collectors.groupingBy(Employee::getAge , Collectors.counting()))
.entrySet()
.stream()
.max(Map.Entry.comparingByValue())
.map(Map.Entry::getKey)
```java
		.get();
		System.out.println(integer);

//		72. Find the Employee with the Longest Name:
//			   - Find the employee with the longest name.
		System.out.println(RED+"******Find the employee with the longest name.****"+RESET);
```

Employee employee10 = list.stream()
```java
		.max(Comparator.comparingInt(value -> value.getName().length())).get();
		System.out.println(employee10);

//		73. Find Employees with Palindromic Names:
//			   - Retrieve employees whose names are palindromes (e.g., "Anna" or "Bob").
		System.out.println(RED+"******Retrieve employees whose names are palindromes*****"+RESET);
```

list.stream()
.filter(k->
```java
		{
			String mainString = k.getName().toLowerCase();
			StringBuffer sr = new StringBuffer(mainString);
			return mainString.contentEquals(sr.reverse());
		}).forEach(System.out::println);

//		74. Calculate the Sum of Salaries for Employees with Odd Ages:
//			   - Calculate the sum of salaries for employees with odd ages.
		System.out.println(RED+"*********the sum of salaries for employees with odd ages.******"+RESET);
		double sum3 = list.stream()
```

.filter(k->k.getAge()%2!=0)
.mapToDouble(Employee::getSalary)
```java
		.sum();
		System.out.println(sum3);

//		75. Find the Employee with the Highest Salary Whose Name Contains "Smith":
//			   - Find the employee with the highest salary whose name contains the word "Smith."
		System.out.println(RED+"******Find the employee with the highest salary whose name contains the word \"Smith.\"*******"+RESET);
```

Employee employee11 = list.stream()
.filter(k->k.getName().contains("Smith"))
```java
		.max(Comparator.comparingDouble(Employee::getSalary)).get();
		System.out.println(employee11);

//		76. Group Employees by the First Letter of Their Names:
//			   - Group employees by the first letter
//			   of their names and return a map with
//					   the letter as the key and a list of employees as the value.
		System.out.println(RED+"*****Group employees by the first letter of their names****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(t -> t.getName().charAt(0)))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		77. Find the Employee with the Shortest Name:
//			   - Find the employee with the shortest name.
		System.out.println(RED+"*******Find the employee with the shortest name.*****"+RESET);
```

Employee employee12 = list.stream()
.min(Comparator.comparingInt(value -> value.getName().length()))
```java
		.get();
		System.out.println(employee12);

//		78. Calculate the Average Salary of Employees Whose Names Start with "E":
//			   - Calculate the average salary of employees whose names start with the letter "E."
		System.out.println(RED+"******Calculate the average salary of employees whose names start with the letter \"E.\""+RESET);
```

Double collect6 = list.stream()
.filter(k->k.getName().startsWith("E"))
```java
		.collect(Collectors.averagingDouble(Employee::getSalary));
		System.out.println(collect6);

//		79. Filter Employees by Age Range:
//			   - Filter employees
//			   based on a custom age range (e.g., between 25 and 35 years old).
		System.out.println(RED+"*******based on a custom age range (e.g., between 25 and 35 years old)*****"+RESET);
```

list.stream()
.filter(k->k.getAge()>=25 && k.getAge()<=35)
```java
		.forEach(System.out::println);

//		80. Group Employees by the First Two Letters of Their Names:
//			   - Group employees by the first two letters
//			   of their names and
//			   return a map with the letters as the key and a list of employees as the value.
		System.out.println(RED+"*****Group employees by the first two letters*****"+RESET);
```

list.stream()
.collect(Collectors.groupingBy(k->k.getName().substring(0, 2)))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		81. Find the Employee with the Longest Name Whose Salary Is Below $70,000:
//			   - Find the employee with the longest name whose salary is below $70,000.
		System.out.println(RED+"*******Find the employee with the longest name whose salary is below $70,000.**"+RESET);
```

Employee employee13 = list.stream().filter(k->k.getSalary()<70000)
```java
		.max(Comparator.comparingInt(k->k.getName().length())).get();
		System.out.println(employee13);

//		82. Calculate the Average Salary of Employees Whose Names End with "son":
//			   - Calculate the average salary of employees whose names end with the suffix "son."
		System.out.println(RED+"*******Calculate the average salary of employees whose names end with the suffix \"son.\""+RESET);
```

Double collect7 = list.stream()
.filter(k->k.getName()
```java
				.endsWith("na")).collect(Collectors.averagingDouble(Employee::getSalary));
		System.out.println(collect7);

//		83. Group employees by the number of
//		words in their names (e.g., one-word names, two-word names, etc.)
//		and return a map with the count as the key and a list of employees as the value.
```

list.stream()
.collect(Collectors.groupingBy(k->k.getName().length()))
```java
		.forEach((k,v)->System.out.println(k+" - "+v));

//		84. Calculate the Average Salary of Employees Whose Names Contain Both "A" and "E":
//			   - Calculate the average salary of employees whose names contain both the letters "A" and "E."
		System.out.println(RED+"********the average salary of employees whose names contain both the letters \"A\" and \"E.\"**********"+RESET);
		double asDouble = list.stream()
```

.filter(k->k.getName().contains("A")&&k.getName().contains("E"))
```java
		.mapToDouble(Employee::getSalary).average().orElse(0.0);
		System.out.println(asDouble);
	}

}
```


### Networking in java


### IP Address

An IP address is a unique identification number allocated to each and every device connected through the network.

By using this IP address we can recognise a client in the network. IP address contains some bytes which identify the network and the actual computer inside the network.

Eg:- 192.168.100.09  (ipconfig is the command in command propmpt)

Finding the IP Address of a server :
It is possible to find out the IP address of any website on internet. In order to do the same, java.net package has provided a predefined class called InetAddress which contains a static method getByName(String host) through which we can find out the IP address of any website.

```java
Ex :- InetAddress.getByName("www.google.com");

```

Here getByName() will return the IP address of Google.com website.

The following are the important methods of InetAddress class :
1) public static InetAddress getByName(String host) throws
UnknownHostException :-

It will return the IP address of the specified host.

2) public static InetAddress getLocalHost() throws
UnknownHostException :-

It will return both the IP address and name of the local system.


3) public String getHostName() :- It will return the name of the System


4) public String getHostAddress() :-It will the return the IP Address of
the System
```java
//Program to find out the local host IP address and Name.
import java.net.*;
public class Inet
{
      public static void main(String args[]) throws UnknownHostException
      {
	       InetAddress ia = InetAddress.getLocalHost();
           System.out.println("Local Name and IP Address  : "+ia);


      }
}
```

```java
//Program to find out the name and address of local machine
import java.net.*;
public class Inet3
{
      public static void main(String args[]) throws UnknownHostException
      {
            InetAddress ia = InetAddress.getLocalHost();
            String addr = ia.getHostAddress();
            String name = ia.getHostName();
            System.out.println("My host name is :"+name+" My address is : "+addr);
      }
}
```

```java
//Name and IP address both at the same time
import java.net.*;
class LocalHost
{
	public static void main(String [] args) throws UnknownHostException
	{
		System.out.println(InetAddress.getLocalHost());
	}
}
```

```java
//program to find out the IP address of the given host
import java.net.*;
import java.io.*;
class IpAddress
{
public static void main(String[] args ) throws IOException
    {
```

BufferedReader br = new BufferedReader
```java
		(new InputStreamReader(System.in));

		System.out.print("Enter the host name: ");
                String host = br.readLine();
```

try
```java
                {
                   InetAddress ia = InetAddress.getByName(host);
                  System.out.println("IP address of "+host+" is : " + ia);
                }
		catch(UnknownHostException e )
		{
		System.err.println(e);
		}
    }
}

/*
```

.com
.in
.ac.in
.edu
.gov.in
*/

### URL class

It is a predefined class available in java.net package. It stands for Uniform Resource Locator. The URL class represents the address that we specify at browser URL to access some resource.

Example of URL:-

https ://www.gmail.com:25/index.jsp

From this above URL

1) Protocol Name :- https (getProtocol())

2) server name or host name :- www.gmail.com (getHost())

3) port number :- 25 (-1 will be the value, if not supplied by the website) (getPort())

4) File name :- index.jsp (getFile())
```java
import java.net.*;
public class URLInfo
{
public static void main(String[] args)
{
```

try
```java
	{
	URL url=new URL("https://www.gmail.com:110/index.jsp");
	System.out.println("Protocol: "+url.getProtocol());
	System.out.println("Host Name: "+url.getHost());
	System.out.println("Port Number: "+url.getPort());
	System.out.println("File Name: "+url.getFile());
	}
	catch(Exception e)
	{
	System.out.println(e);
	}
 }
}
```


### URLConnection class

It is a predefined class availavle in java.net package. This class is useful to connect to a website or a resource in the network, it will fetch all the details of the specified web page as a part of URL class.

The URL class provides a method called openConnection(), this method will establish a connection with the specified web page and returns the URLConnection object, that is nothing but the complete details of the web page.

```java
public URLConnection openConnection() throws IOException
```

```java
import java.io.*;
import java.net.*;
public class Details
{
public static void main(String[] args)
	{
```

try
```java
		{
		URL url=new URL("https://www.python.org/downloads/");

        //Eastablishing the connection from the Specified URL
		URLConnection urlcon=url.openConnection();

		InputStream stream = urlcon.getInputStream();

		while(true)
			{
			  int  i = stream.read();
				if(i==-1)
					break;
				System.out.print((char)i);

			}
		}
		catch(Exception e)
		{
		  System.out.println(e);
		}
}
}
```

25-Feb-23

### Socket

It is possible to eastblish a logical connection point between the server and the client so that communication can be done through this point is called Socket.

Now, each socket is given an identification number which is called port number. The range of port number is 0-65535.

Eastablishing a communication between the client and server using socket is called Socket Programming.

Socket programming can be connection oriented or connection less. In java Socket (for client) and ServerSocket (for server) are the predefined classes available in java.net package for connection oriented Socket Programming.

The client socket programming must have two information.
1) Ip address of the server
2) port number

The following are the importatnt methods of Socket class :
```java
1) public InputStream getInputStream();

2) public OutputStream getOutputStream();

3) public synchronized void close();


```

The following are the importatnt methods of ServerSocket class :
1) public Socket accept() :- It is used to put the server in wait mode till
a client accept or eastblish the connection

```java
2) public InputStream getInputStream();

3) public OutputStream getOutputStream();

4) public synchronized void close();
```


### Creating a server that can send some data

We can create a Socket that can be used to connect to a server and a client. Once the Socket is created, the Server can send the data to the client and client can receive the data.

All we have to do to just to send the data from server to socket. The socket will take care of whom to send the data on the network.

We should write the following java code to create a server that can send some data to the client.

1) At server side, create a server socket with some port number, This is done by using ServerSocket class

```java
		ServerSocket ss = new ServerSocket(7777);

```

2) We should make the server wait till a client accept connections. This can be done by using accept().

```java
		Socket s = ss.accept();

```

3) Now Attach some output stream to ServerSocket using getOutputStream() method. This method returns OutputStream object. This method is used to send the data from Socket to the client

```java
		OutputStream obj =  s.getOutputStream();


```

4) Take another Stream like PrintStream or DataOutputStream to send the data till the Socket.

```java
                PrintStream ps = new PrintStream(obj);

```

5) Now to print the data which we are sending from Server to the client we can use print() or println() method available in PrintStream class.

```java
		ps.println(String data);


```

6) Now close all the connections.

```java
		ss.close();
		s.close();
		ps.close();


```

Creating a client that can receive some data :-
We can write client program that receives all the String sent from server to client machine.We should write the followinng java code

1) We should create a Socket at client side by using Socket class as

```java
	Socket s = new Socket("Ip address", port number);

```


> **Note :- If the client and server both are running in a single machine then it is called "localhost",  we should write localhost instead of IP address.**



2) We should add InputStream to the Socket so that the Socket will be able to receive the data on the InputStream.

```java
		InputStream obj = s.getInputStream();


```

3) Now to read the data from Socket to the client machine we can take the help of BufferedReader as

```java
		BufferedReader br  = new BufferedReader(new InputStreamReader(obj));

```

4) Now We can read the data from the BufferedReader as

```java
		String str = br.readLine();

```

5) close the connection

```java
			br.close();
			s.close();
```

Server1.java
```java
//Program to send String to the client
import java.io.*;
import java.net.*;
class Server1
{
	public static void main(String args[]) throws IOException
	{
		ServerSocket ss = new ServerSocket(777);

		Socket s=ss.accept();

		System.out.println("Connection established...");

		OutputStream obj=s.getOutputStream();

		PrintStream ps = new PrintStream(obj);

		String str="Hello Client";
		ps.println(str);
		ps.println("Bye-Bye");
		ps.close();
		s.close();
		ss.close();
	}
}

```

Client1.java
```java
import java.io.*;
import java.net.*;
class Client1
{
	public static void main(String args[]) throws Exception
	{
      Socket s = new Socket("localhost",777);

	  InputStream obj = s.getInputStream();

	  BufferedReader br = new BufferedReader(new InputStreamReader(obj));

	  String str;

	  while((str=br.readLine()) !=null)
		{
		  System.out.println("From Server :"+str);
		}
	  br.close();
	  s.close();
	}
}
```

Chating between Client and Server
Server2.java
```java
//A server that receives and send the data
import java.io.*;
import java.net.*;
class Server2
{
	public static void main(String [] args) throws Exception
	{
		ServerSocket ss = new ServerSocket(888);
		Socket s = ss.accept();

		System.out.println("Connection Established..");

		PrintStream ps = new PrintStream(s.getOutputStream());

```

BufferedReader br = new BufferedReader
```java
			(new InputStreamReader( s.getInputStream()));

		BufferedReader kb = new BufferedReader(new InputStreamReader(System.in));

		while(true)
		{
			String recv,send;  //send is for sending and recv is for receiving the data

			while((recv=br.readLine()) !=null)
			{
				System.out.println(recv);
				send=kb.readLine();
				ps.println(send);
			}
			ps.close();
			br.close();
			kb.close();
			s.close();
			ss.close();
			System.exit(0);//Shutdown the JVM
		}
	}
}

```

Client2.java
```java
//A client that receives and send the data
import java.io.*;
import java.net.*;
class Client2
{
	public static void main(String [] args) throws Exception
	{
		Socket s = new Socket("localhost",888);

		DataOutputStream dos = new DataOutputStream(s.getOutputStream());

		BufferedReader br = new BufferedReader(new InputStreamReader(s.getInputStream()));

		BufferedReader kb = new BufferedReader(new InputStreamReader(System.in));

		String send,recv; //send is for sending and recv is for receiving the data

		while(! (send=kb.readLine()).equals("exit"))   //Hello Server
		{
			dos.writeBytes(send+"\n");
			recv=br.readLine();
			System.out.println(recv);
		}
		dos.close();
		br.close();
		kb.close();
		s.close();
	}
}
```

```java
//Program to downlaod the content of a file from the Server, if the file is available at server.

```

FileServer.java
```java
//A server that can send file content to the client
import java.io.*;
import java.net.*;
class FileServer
{
	public static void main(String [] args ) throws Exception
	{
		ServerSocket ss = new ServerSocket(8888);
		Socket s = ss.accept();

		System.out.println("Connection established...");

		BufferedReader in = new BufferedReader(new InputStreamReader(s.getInputStream()));

		DataOutputStream out = new DataOutputStream(s.getOutputStream());

		String fname = in.readLine();     //fname = abc.txt

		boolean flag;

        //File is existing or not
		File f = new File(fname);
		if(f.exists())
			flag=true;
		else
		     flag=false;

        //Sending the acknowledgement message to the client
		if(flag==true)
			out.writeBytes("yes"+"\n");
		else
			out.writeBytes("no"+"\n");


        //Reading the File content and sending it to the client
		if(flag==true)
		{
			FileReader fr=new FileReader(fname);
			BufferedReader file = new BufferedReader(fr);

			String str;
			while((str=file.readLine()) !=null)
			{
				out.writeBytes(str+"\n");
			}
			file.close();
			fr.close();
			out.close();
			in.close();
			s.close();
			ss.close();
		}
	}
}

```

FileClient.java
```java
//A Client receiving a file content
import java.io.*;
import java.net.*;
class FileClient
{
	public static void main(String [] args ) throws Exception
	{
		Socket s = new Socket("localhost",8888);

		BufferedReader kb = new BufferedReader(new InputStreamReader(System.in));

		System.out.print("Enter a file name :");

		String fname = kb.readLine();  //fname = abc.txt

		DataOutputStream out = new DataOutputStream(s.getOutputStream());

```

out.writeBytes(fname+"\n"); //first of all client is sending file name

```java
		BufferedReader in = new BufferedReader(new InputStreamReader(s.getInputStream()));

		String str = in.readLine();

		if(str.equalsIgnoreCase("yes"))
		{
			while((str=in.readLine()) !=null)
				System.out.println(str);
			kb.close();
			out.close();
			in.close();
			s.close();
		}
		else
		{
			System.out.println("File not found at Server location..");
		}
	}
}
```










































































































































































































































































































































































































































































































































































































































































































































