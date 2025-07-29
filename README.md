# Tomcat 10 Sample Application

It contains 3 different examples. A simple index view, a home with a parameter and a hello servlet.

## Context xml configuration

In rerards to servlet configuration and parameters the following entries should be existing in the tomcat context xml:

1. Enviroment variable

```xml
<Environment name="foo" value="bar-value" type="java.lang.String" override="false" />
```