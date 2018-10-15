# zinc-issues-123

### Steps:
Run `sbt clean compile` to gen an exception:
```
[error] java.lang.ArrayStoreException: sun.reflect.annotation.TypeNotPresentExceptionProxy
[error]         at sun.reflect.annotation.AnnotationParser.parseClassArray(AnnotationParser.java:724)
...
[error]         at sbt.internal.inc.ClassToAPI$.toDefinitions0(ClassToAPI.scala:128)
...
```
