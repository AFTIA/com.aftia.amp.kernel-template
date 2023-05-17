![Deploy Artifacts](https://github.com/AFTIA/com.aftia.amp.amp-kernel-template/workflows/Deploy%20Artifacts/badge.svg?branch=main)

# com.aftia.system.template-kernel
Template of the AFTIA Karaf Kernel

# How to build

Simply run `mvn clean install` in the root of the project

# How to start Karaf

Simply navigate into the `target/assembly/bin` folder of the `amp-kernel-template-core` module and execute the following command `karaf` (if on Windows then `karaf.bat`).

This will return an SSH shell were you can then interact with Karaf programmatically.

# OSGi Console

The OSGi console can be seen visited at `http://localhost:8181/system/console` (username: karaf/ password: karaf) there you can install bundles if required.

# More Information

To read more on Karaf please visit http://karaf.apache.org/manual/latest/ or join the Slack Apache Karaf Channel https://infra.apache.org/slack.html

