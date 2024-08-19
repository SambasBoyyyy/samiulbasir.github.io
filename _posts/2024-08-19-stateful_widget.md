---
title: Understanding Flutter Stateful Widgets
date: 2024-08-19
tags: [Flutter, Widgets, State Management]
---

In Flutter, widgets are the building blocks of your app's UI. There are two types of widgets: **Stateless** and **Stateful**. While stateless widgets are immutable and cannot change their state after they are built, **stateful widgets** can change their state during their lifetime.

### What is a Stateful Widget?

A stateful widget is a widget that has mutable state. This means that the widget can rebuild itself when its state changes. A stateful widget consists of two classes:

1. **StatefulWidget**: This class is immutable and can be considered as the configuration for the widget.
2. **State**: This is where the mutable state resides. The state object persists over the lifetime of the widget and is responsible for rebuilding the widget when the state changes.

### Creating a Stateful Widget

To create a stateful widget in Flutter, you need to extend the `StatefulWidget` class and override the `createState()` method to return an instance of your `State` class.

```dart

import 'package:flutter/material.dart';

class MyStatefulWidget extends StatefulWidget {
  @override
  _MyStatefulWidgetState createState() => _MyStatefulWidgetState();
}

class _MyStatefulWidgetState extends State<MyStatefulWidget> {
  int _counter = 0;

  void _incrementCounter() {
    setState(() {
      _counter++;
    });
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Stateful Widget Example'),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: <Widget>[
            Text(
              'You have pushed the button this many times:',
            ),
            Text(
              '$_counter',
              style: Theme.of(context).textTheme.headline4,
            ),
          ],
        ),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: _incrementCounter,
        tooltip: 'Increment',
        child: Icon(Icons.add),
      ),
    );
  }
}
```