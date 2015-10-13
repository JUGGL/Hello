# A Basic Maven Project

The next step is to use a build tool to simplify the management of our application and to simplify compiling code when we have a large number of source files. This example uses [Maven](http://maven.apache.org/) as the build tool and you can see the build definition in the **pom.xml** file.

## Compile
```
mvn package
```

## Run
```
java -cp target/hello-1.0-SNAPSHOT.jar us.juggl.hello.Hello
```

Next step, go to branch [Step_05](https://github.com/JUGGL/Hello/tree/Step_05)
