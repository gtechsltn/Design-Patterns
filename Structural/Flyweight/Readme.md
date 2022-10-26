# Introduction
The Flyweight Design Pattern is of class *Structural* and having subclass of *Object Structural*. It helps to support large number of fined grained objects.

## Intent
Flyweight Design Pattern is used for sharing to support large number of fine grained objects, that can be used to handle creation and deletion of objects on the specified scenarios.

## Motivation
Let's say we have a Document Editor, and in that document editor most common things such as Rows, Tables and Characters are objects. So, this will cause creation of lots of objects that ca cause loading and time overhead while opening a Document in the Document Editor.
Flyweight Pattern describes how to share objects to allow their use of fine gains with any Prohibition costs.
**Flyweight** is an object which is shared and that can be used in multiple contexts simultaneously. 