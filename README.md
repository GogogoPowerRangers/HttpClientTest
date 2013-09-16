### Testing Apache HttpAsyncClient 4
==============

#### Build:

```
./gradlew build
```

#### Run Test 1

```
./gradlew runFutureBoolean
```

#### Run Test 2

```
./gradlew runFutureCallback
```


### Different JDKs (on OSX)

Note how JDK 1.7.0_05 doesn't work.

##### Eclipse Execution with JDK 1.7.0_05 (hangs or very slow)

```
-------------------------------------------------------------------
java.version: 1.7.0_05
java.vendor.url: http://java.oracle.com/
java.vendor: Oracle Corporation
java.home: /Library/Java/JavaVirtualMachines/1.7.0.jdk/Contents/Home/jre
os.arch: x86_64
os.name: Mac OS X
os.version: 10.8.5
-------------------------------------------------------------------
result: true
```


##### Eclipse Execution with JDK 1.6

```
-------------------------------------------------------------------
java.version: 1.6.0_51
java.vendor.url: http://www.apple.com/
java.vendor: Apple Inc.
java.home: /System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
os.arch: x86_64
os.name: Mac OS X
os.version: 10.8.5
-------------------------------------------------------------------
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
Total time (sec):0.671
Done
```

##### Eclipse Execution with JDK 1.8

```
-------------------------------------------------------------------
java.version: 1.8.0-ea
java.vendor.url: http://java.oracle.com/
java.vendor: Oracle Corporation
java.home: /Library/Java/JavaVirtualMachines/jdk1.8.0.jdk/Contents/Home/jre
os.arch: x86_64
os.name: Mac OS X
os.version: 10.8.5
-------------------------------------------------------------------
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
Total time (sec):0.67
Done
```

##### Eclipse Execution with JDK 1.7.0_40

```
-------------------------------------------------------------------
java.version: 1.7.0_40
java.vendor.url: http://java.oracle.com/
java.vendor: Oracle Corporation
java.home: /Library/Java/JavaVirtualMachines/jdk1.7.0_40.jdk/Contents/Home/jre
os.arch: x86_64
os.name: Mac OS X
os.version: 10.8.5
-------------------------------------------------------------------
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
Total time (sec):0.662
Done
```

##### Eclipse Execution with JDK 1.7.0_13

```
-------------------------------------------------------------------
java.version: 1.7.0_13
java.vendor.url: http://java.oracle.com/
java.vendor: Oracle Corporation
java.home: /Library/Java/JavaVirtualMachines/jdk1.7.0_13.jdk/Contents/Home/jre
os.arch: x86_64
os.name: Mac OS X
os.version: 10.8.5
-------------------------------------------------------------------
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
result: true
Total time (sec):0.73
Done
```
