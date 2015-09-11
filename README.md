# CentOS 7 with Java

Docker images based from the official Centos7 image with Java8 JDK/JRE installed (currently Oracle only)

# Versions

Currently avaliable versions (by tag).

* `latest` - currently Oracle Java version 8 JRE
* `oracle-8-jre` - Oracle Java version 8 JRE
* `oracle-8-jdk` - Oracle Java version 8 JDK
* `jruby-9.0.1.0` - JRuby 9000 on Oracle Java version 8 JRE

# Usage

Running a bash session with Java8 JRE available

```sh
docker run \
  -it \
  --rm \
  technekes/centos-java:oracle-8-jre \
  bash
```
