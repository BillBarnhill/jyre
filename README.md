# Zyre implementation in Java using JeroMQ

This fork of jyre is designed to not need JNI calls, using only JeroMQ

## How to use

Add it to your Maven project's `pom.xml`:

    <!-- for the Zyre using jzmq -->
    <dependency>
      <groupId>org.zyre</groupId>
      <artifactId>zyre</artifactId>
      <version>0.1.0-SNAPSHOT</version>
    </dependency>

    <!-- for the Zyre using JeroMQ -->
    <dependency>
      <groupId>org.zyre</groupId>
      <artifactId>zyre-jeromq</artifactId>
      <version>0.1.0-SNAPSHOT</version>
    </dependency>
~                      
