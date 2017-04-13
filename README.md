[<img src="https://img.shields.io/travis/playframework/play-scala-compile-di-example.svg"/>](https://travis-ci.org/playframework/play-scala-compile-di-example)

# Play Framework with Compile Time DI Tests

This is an example of Play using the Scala API with manually wired compile time dependency injection.

The application loader here is `MyApplicationLoader` which uses `MyComponents` to wire together an injector.  In testing, there are some places where a `WSClient` has to be used, and so some additional components have to be added in.

## Further Documentation

* https://www.playframework.com/documentation/latest/ScalaCompileTimeDependencyInjection 
* https://www.playframework.com/documentation/latest/ScalaTestingWithScalaTest#Using-ScalaTest-+-Play 
* http://www.scalatest.org/user_guide
* http://www.scalatest.org/release_notes/3.0.0
* https://github.com/playframework/scalatestplus-play
