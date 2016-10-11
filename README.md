Jetty Runner
============

- [Deploy a Java Web Application that launches with Jetty Runner](https://devcenter.heroku.com/articles/deploy-a-java-web-application-that-launches-with-jetty-runner)

## Run your application

To build your application simply run:

```term
$ mvn clean package
```

And then run your app using the java command:

```term
$ java -jar target/dependency/jetty-runner.jar target/*.war
```

That's it. Your application should start up on port 8080.

or run with shell script

```term
./run.sh
```

http://localhost:9080/
