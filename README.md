# Eclair Scala :zap:

## Run scripts from terminal

Download Scala binaries, move them somewhere like `/usr/bin/share` then add env variable to point towards this location.

- just interpret: `scala myScript.scala`
- compile and interpret: `scalac myScript.scala; scala myScript`

## Factorial example

Run `scala` interpreter and launch:

```
Welcome to Scala 2.12.1 (Java HotSpot(TM) 64-Bit Server VM, Java 1.8.0_91).
Type in expressions for evaluation. Or try :help.

scala> :load Factorial.scala
Loading Factorial.scala...
factorial: (n: Int)Int

scala> factorial(4)
res0: Int = 24
```
