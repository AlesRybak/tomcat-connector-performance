# tomcat-connector-performance

```bash
rm tomcat-perf.jtl
rm -rf out/*
jmeter -n -t tomcat-perf.jmx -l tomcat-perf.jtl -e -o out
```
