<!-- Header -->
<h1 align='center'>1.2 Data Types</h1>
<p align='center'><em>The Long and Short of Java</em></p>
<p align='center'><a href='./classes.md'><<</a> | <a href='../readme.md'>Index</a> | <a href='./variables.md'>>></a></p>

---

<!-- Content -->
<!--### Bits and Bytes

If you are interested in learning in-depth how each variable is stored in memory, please take a look at [Appendix B: Bits and Bytes](#).--> 

### Data Types

**Data Types** (sometimes represented as Datatypes or simply Types) are a key part in the state of a Class. State is storing data, and data types tell the computer and the JVM how to store that data. Java is a **Strongly Typed** language, which means that each type is distinct and requires specific steps before differing types can be operated on, and throwing exceptions if those steps are not followed. Java is also **Statically Typed**, which means that the types are linked to the storage of the data, rather than the value that is stored, and they cannot be changed.

### Primitives

Primitives are the data types that are the building blocks of more complex Classes and objects. There are two ways that these are represented: a featureful Class, and a simpler Primitive. Most of these blocks are made for representing numbers in ways that the computer can manage.

### Available Primitive Data Types

Java has primitive data types that fall into three different categories: Integral, Floating Point, and Boolean. Each one represents a different type of data, and have different options for the storage of that data. 

### Integral Data Types

**Integral** data types represent non-decimal numbers, and have a variety of sizes. **Characters** are a special case, since they store and print as unicode characters, but when combined with other Integral data types they act like numbers or the number eqivalent of the character they were storing.  

| Class     | Primitive | Size    | Min Value            | Max Value           | Default    |
|:----------|:----------|:--------|:---------------------|:--------------------|:-----------|
| Byte      | `byte`    | 1 byte  | -128                 | 127                 | 0          |
| Short     | `short`   | 2 bytes | -32768               | 32767               | 0          |
| Character | `char`    | 2 bytes | 0 or `'\u0000'`      | 65536 or `'\uFFFF'` | `'\u0000'` |
| Integer   | `int`     | 4 bytes | -2147483648          | 2147483647          | 0          |
| Long      | `long`    | 8 bytes | -9223372036854775808 | 9223372036854775807 | 0L         |

### Floating Point Data Types

**Floating Point** data types represent decimal numbers, and have two sizes available. In computing in general, floating point numbers are an approximation in order to store these numbers in an efficient manner. The approximations made are especially evident when looking at floating point math. For example, when I run `0.78f + 0.1f` in my terminal, it returns `0.8799999713897705` rather than `0.88`.

| Class  | Primitive | Size    | Min Value | Max Value              | Default |
|:-------|:----------|:--------|:----------|:-----------------------|:--------|
| Float  | `float`   | 4 bytes | 1.4E-45   | 3.4028235E38           | 0.0f    |
| Double | `double`  | 8 bytes | 4.9E-324  | 1.7976931348623157E308 | 0.0d    |

### The Boolean Data Type

The **Boolean** data type is a type of its own. It is simply one bit, a one or a zero in the computer. Another way to picture a boolean is to imagine a *light switch*. It is either on, or off, with no in between. Booleans are commonly used in a similar way to a light switch, to enable or disable features or blocks of code. The size is not defined by the Java language specification, and depends on the JVM.

| Class   | Primitive | Size      | Min Value | Max Value | Default |
|:--------|:----------|:----------|:----------|:----------|:--------|
| Boolean | `boolean` | Undefined | `false`   | `true`    | `false` |

### Review

**Data Types** tell the computer how to store data that we want to save. **Primitives** are simple data types that are built into Java and the building blocks of more complex classes and programs. There are three types of primitive. **Integral Primitives** are non-decimal numbers with a variety of ranges. **Floating-Point Primitives** are approximations of decimal numbers. **Booleans** are primitives that are either on or off. We will be using these primitive data types in the next chapter.

<!-- Footer -->

---

<p align='center'><a href='./classes.md'><<</a> | <a href='../readme.md'>Index</a> | <a href='./variables.md'>>></a></p>

<sub>© 2018 UberPilot All Rights Reserved</sub>