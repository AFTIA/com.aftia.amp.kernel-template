![Deploy Artifacts](https://github.com/AFTIA/com.aftia.vm.system.kernel-template/workflows/Deploy%20Artifacts/badge.svg?branch=main)

# com.aftia.system.template-kernel
Template of the AFTIA Karaf Kernel

# How to build

Simply run `mvn clean install` in the root of the project

# How to start Karaf

Simply navigate into the `target/assembly/bin` folder of the `kernel-template-core` module and execute the following command `karaf` (if on Windows then `karaf.bat`).

This will return an SSH shell were you can then interact with Karaf programmatically.


