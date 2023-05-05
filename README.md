# GC-analysis


# Enable GC logs

add the following to JVM system properties

-Xloggc:${PATH}/gc.log -XX:+PrintGCDetails -XX:+PrintTenuringDistribution


resources:

https://cruftex.net/2017/03/28/The-6-Memory-Metrics-You-Should-Track-in-Your-Java-Benchmarks.html#metric-used-memory-after-forced-gc
