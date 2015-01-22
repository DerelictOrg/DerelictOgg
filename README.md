DerelictOgg
==========

A dynamic binding to [libogg][1] versions 1.3.0 and 1.3.1 for the D Programming Language.

Please see the pages [Building and Linking Derelict][2] and [Using Derelict][3], in the Derelict documentation, for information on how to build DerelictOgg and load libogg at run time. In the meantime, here's some sample code.

```D
import derelict.ogg.ogg;

void main() {
    // Load the libogg library.
    DerelictOgg.load();

    // Now libogg functions can be called.
    ...
}
```

[1]: http://xiph.org/ogg/
[2]: http://derelictorg.github.io/compiling.html
[3]: http://derelictorg.github.io/using.html
