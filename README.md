Task4Maven_Invoker
==================
In this project I try to invoke resource:resource goal to copy files A and B (without filtering). If I invoke resource:resource, it works ok, but when I try to invoke iterator-plugin - iterator:invoker I get error:
==============================================================================
Failed to execute goal com.soebes.maven.plugins:iterator-maven-plugin:0.3:invoker (default-cli) on project Task4Maven_TwoProfiles_Invoker:
Unable to parse configuration of mojo com.soebes.maven.plugins:iterator-maven-plugin:0.3:invoker for parameter goals: Cannot assign configuration entry 'goals' with value 'resources:@item@' of type java.lang.String to property of type java.util.List -> [Help 1]
==============================================================================
This problem described here: http://stackoverflow.com/questions/27771058/maven-resourcesresources-goal-invocation-with-help-of-invoker-goal-of-ite
