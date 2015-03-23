# spring-boot-aws-showcase

##build
```
 mvn install
```

## run with spring-boot
```
 mvn spring-boot:run
```

## run with local tomcat
```
 mvn tomcat7:run-war
```

## run on aws

In order to run the application on AWS you need an account and adjust the property values in the pom.

You must set the 'Access Key ID' and 'Secret Access Key' in your settings.xml.

Please refer to the setup documentation of the [beanstalk-maven-plugin](http://docs.ingenieux.com.br/project/beanstalker/).

The demo shows:

status | description  |   link
------------- | --------------|-------------
:white_check_mark: | Show the use of spring-cloud-aws. | [local demo](http://localhost:8080)

#Links
[spring-cloud](https://github.com/spring-projects/spring-cloud)
[spring-boot](https://github.com/spring-projects/spring-boot)
[beanstalk-maven-](http://docs.ingenieux.com.br/project/beanstalker/)
