# EO Greet

Just an example program in [eo](https://github.com/objectionary/eo).

Compile the code (you will need [Maven 3.3+](https://maven.apache.org/)
and [Java SDK 11+](https://www.java.com/en/download/) installed):

```bash
$ mvn clean compile
```

Then run the bytecode program through JRE:

```bash
java -cp target/classes org.eolang.Main greet.app 10
```

You should see: 

```
I am 10 years old!
```

That's it.