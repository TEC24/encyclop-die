```
import 'dart:ui';

import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Icon(Icons.home),
          backgroundColor: Colors.orangeAccent,
        ),
        body: Container(
          padding: EdgeInsets.all(20),
          margin: EdgeInsets.all(30.0),
          color: Colors.black,
          child: Image(
            image: AssetImage('assets/pasted image 0.png'),
          ),
        ),
      ),
    );
  }
}
```
