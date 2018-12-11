# Sharding-Spring

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

[![Build Status](https://api.travis-ci.org/sharding-sphere/sharding-spring.png?branch=master)](https://travis-ci.org/sharding-sphere/sharding-sphere)

## Overview

Sharding-Spring is the integration plugin of Spring for [Shrading-Sphere](http://shardingsphere.io/), designed to reduce the cost of using Sharding-Sphere in the Spring framework.

### Sharding-jdbc-spring

Sharding-jdbc-spring provides Spring-Boot autoconfigure and Spring xml namespaces for Sharding-JDBC to reduce the configuration of Sharding-Sphere in Spring.

### Sharding-jdbc-orchestration-spring

Sharding-jdbc-orchestration-spring provides Spring-Boot autoconfigure and Spring xml namespaces for orchestraction based on sharding-jdbc-spring.

### Sharding-transaction-spring

Sharding-transaction-spring extends Spring's `@Transactional` annotation. When using distributed transactions of Sharding-Sphere, applications can switch transaction types with new annotations.