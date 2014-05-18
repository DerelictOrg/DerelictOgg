DerelictOgg
==========

A dynamic binding to [libogg][1] for the D Programming Language.

For information on how to build DerelictOgg and link it with your programs, please see the post [Using Derelict][2] at the The One With D.

For information on how to load the libogg library via DerelictOgg, see the page [DerelictUtil for Users][3] at the DerelictUtil Wiki. In the meantime, here's some sample code.

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
[2]: http://dblog.aldacron.net/derelict-help/using-derelict/
[3]: https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users
