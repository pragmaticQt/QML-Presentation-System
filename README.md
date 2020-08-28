# QML-Presentation-System

This is a slide presentation system demo.


Installing
----------

```sh
$ qmake
$ make install
```

Usage
----------
```qml
import Qt.labs.presentation 1.0
import QtQuick 2.10

Presentation
{
    id: presentation

    width: 1280
    height: 720

    SlideCounter {}
    Clock {}


    Slide {
        centeredText: "Use [space] or [keypad] to see intro"
    }
    ...
```


[![QML Presentation System by pragmaticQt](http://img.youtube.com/vi/Sw85F9Ky3iI/0.jpg)](http://www.youtube.com/watch?v=Sw85F9Ky3iI "QML Presentation System")
