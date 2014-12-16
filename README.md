You can easily setup logsys-ng or rsyslog and centralize your logging systeam in Java application with SLF4J and Logback API.

* First setup logsys-ng (or rsyslog). You can simply do it with docker [syslog-ng-docker]
* Change the server address in ```src/main/resources/logback.xml```
* Test it with running: mvn compile exec:java

[syslog-ng-docker]: https://github.com/abdollahpour/syslog-ng-docker  "Simply setup syslog-ng-docker"s