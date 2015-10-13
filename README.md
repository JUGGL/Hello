# A Basic Gradle Project

The next step is to use a build tool to simplify the management of our application and to simplify compiling code when we have a large number of source files. This example uses [Gradle](http://gradle.org/) as the build tool and you can see the build definition in the **build.gradle** file.

## Compile
```
gradle jar
```

## Run
```
java -cp build/libs/HelloWorld.jar us.juggl.hello.Hello
```

Next step, go to branch [Step_04](https://github.com/JUGGL/Hello/tree/Step_04)
