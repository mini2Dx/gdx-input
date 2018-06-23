gdx-input
=============================
LibGDX Input and Controller classes extracted into a standalone library

Mechanism
---------------------------------

The gradle build will checkout a specific version of libgdx, copy the input source files into src/main/java, package renamed from _com.badlogic_ to _org.mini2Dx_ and compile the standalone jar.

Usage
---------------------------------

```gradle
compile "org.mini2Dx:gdx-input:1.9.8"
```

This project's only dependency is [gdx-collections](https://github.com/mini2Dx/gdx-collections).

Included Classes
---------------------------------

* ControlType
* Controller
* ControllerAdapter
* ControllerListener
* ControllerManager
* ControllerManagerStub
* Input
* InputAdapter
* InputEventQueue
* InputMultiplexer
* InputProcessor
* PovDirection