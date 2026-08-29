# Awesome graphql-java with stars

> Libraries and projects related to [graphql-java](https://github.com/graphql-java/graphql-java) ⭐ 6,223 | 🐛 40 | 🌐 Java | 📅 2026-08-24

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 500,890 | 🐛 105 | 📅 2026-08-21 list thing.*

## Official Spring integration

* [Spring for GraphQL](https://spring.io/projects/spring-graphql) is the official Spring integration for GraphQL, built on GraphQL Java. See the [getting started tutorial](https://spring.io/guides/gs/graphql-server/) for how to build a GraphQL service in 15 minutes.

## Examples

* [spring-petclinic-graphql](https://github.com/spring-petclinic/spring-petclinic-graphql) ⭐ 214 | 🐛 1 | 🌐 JavaScript | 📅 2023-11-26: Port of the Spring PetClinic to Spring Boot, graphql-java and graphql-spring-boot-starter (using React Apollo in the frontend)
* [graphql-datetime-sample-app](https://github.com/donbeave/graphql-java-datetime/tree/master/graphql-datetime-sample-app) ⭐ 154 | 🐛 5 | 🌐 Java | 📅 2026-08-24: GraphQL example app with usage of date and time scalars
* [todomvc-relay-java](https://github.com/graphql-java/todomvc-relay-java) ⭐ 68 | 🐛 4 | 🌐 Java | 📅 2017-11-28: Port of the Relay TodoMVC example to a java backend

## Schema Libraries

### Schema First

* [graphql-java-tools](https://github.com/graphql-java/graphql-java-tools) ⭐ 823 | 🐛 92 | 🌐 Kotlin | 📅 2026-08-25: A schema-first tool for graphql-java inspired by graphql-tools for JS

* [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen/tree/master/plugins/maven) ⭐ 298 | 🐛 90 | 🌐 Java | 📅 2026-08-01: Maven plugin for generating JVM languages(Such as Scala,Kotlin,Java) types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools.

* [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen/tree/master/plugins/gradle) ⭐ 298 | 🐛 90 | 🌐 Java | 📅 2026-08-01: Gradle plugin for generating JVM languages(Such as Scala,Kotlin,Java) types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools.

* [GraphQL Java Generator](https://github.com/graphql-java-generator) is available as a [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project) ⭐ 130 | 🐛 2 | 🌐 Java | 📅 2026-03-27 and a [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project) ⭐ 59 | 🐛 2 | 🌐 Java | 📅 2026-02-26. It has two modes :

  * The Client mode generates the Java classes that contains methods to call the GraphQL endpoint , and the POJO that will contain the data returned by the server.

  * The Server mode generates the boilerplate code for graphql-java. It's an accelerator that makes it easier to use graphql-java. You'll only have to implement what's specific to your server, which are the joins between the GraphQL types.

* [Kobby](https://github.com/ermadmi78/kobby) ⭐ 89 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-17: Codegen plugin of [Kotlin DSL Client](https://blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.

* [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java) ⭐ 72 | 🐛 14 | 🌐 Groovy | 📅 2025-01-29 GraphQL Orchestrator/Gateway library that supports Schema Stitching and Apollo Federation directives to combine schema from multiple GraphQL microservices into a single unified schema.

* [graphql-apigen](https://github.com/Distelli/graphql-apigen) ⭐ 65 | 🐛 18 | 🌐 Java | 📅 2024-01-23: Generate Java APIs with GraphQL Schemas

* [rdbms-to-graphql](https://github.com/ebridges/rdbms-to-graphql) ⭐ 52 | 🐛 2 | 🌐 Java | 📅 2018-07-08: A Java CLI program that generates a GraphQL schema from a JDBC data source.

* [lilo](https://github.com/friatech/lilo) ⭐ 42 | 🐛 4 | 🌐 Java | 📅 2024-05-26: Lilo is a super fast GraphQL stitching library.

* [test-graphql-java](https://github.com/vimalrajselvam/test-graphql-java) ⭐ 25 | 🐛 2 | 🌐 Java | 📅 2025-11-13: A simple library to help testing the GraphQL endpoint with schema files using any HTTP Client library.

* [graphql-schema-from-introspection-generator](https://github.com/mstachniuk/graphql-schema-from-introspection-generator) ⭐ 13 | 🐛 2 | 🌐 Kotlin | 📅 2021-04-07: A Java CLI program that generates a GraphQL schema from Introspection Query result. Useful for migration from Code First.

* [graphql-java-codegen-sbt-plugin](https://github.com/jxnu-liguobin/graphql-java-codegen-sbt-plugin) ⚠️ Archived: SBT plugin for generating JVM languages(Such as Scala,Kotlin,Java) types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools.

* [graphql-braid](https://bitbucket.org/atlassian/graphql-braid): Schema stitching - combines GraphQL backends into one schema.

### Code First

* [Rejoiner](https://github.com/google/rejoiner) ⚠️ Archived: Provides a uniform GraphQL schema on top of gRPC microservices by generating GraphQL types from Protobuf.

* [graphql-kotlin](https://github.com/ExpediaDotCom/graphql-kotlin) ⭐ 1,803 | 🐛 83 | 🌐 Kotlin | 📅 2026-08-21: Code-only GraphQL schema generation for Kotlin

* [GraphQL-SPQR](https://github.com/leangen/GraphQL-SPQR) ⭐ 1,102 | 🐛 91 | 🌐 Java | 📅 2026-01-27: Java 8+ API for rapid development of GraphQL services

* [graphql-java-annotations](https://github.com/graphql-java/graphql-java-annotations) ⭐ 392 | 🐛 5 | 🌐 Java | 📅 2025-10-03: Annotations-based syntax for GraphQL schema definition.

* [graphql-jpa-query](https://github.com/introproventures/graphql-jpa-query) ⭐ 208 | 🐛 61 | 🌐 Java | 📅 2026-03-24: GraphQL Query Api for JPA 2.1 Entity Models

* [SmallRye GraphQL](https://github.com/smallrye/smallrye-graphql) ⭐ 176 | 🐛 136 | 🌐 Java | 📅 2026-08-28: An implementation of the above mentioned Specification used in [Quarkus](https://quarkus.io/blog/quarkus-1-5-final-released/) and [OpenLiberty](https://openliberty.io/blog/2020/06/05/graphql-open-liberty-20006.html)

* [graphql-jpa](https://github.com/jcrygier/graphql-jpa) ⭐ 166 | 🐛 12 | 🌐 Java | 📅 2018-06-11: JPA Implementation of GraphQL (builds on graphql-java)

* [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) ⭐ 134 | 🐛 9 | 🌐 Java | 📅 2017-03-23: Spring Framework GraphQL Library

* [MicroProfile GraphQL](https://github.com/eclipse/microprofile-graphql) ⭐ 102 | 🐛 79 | 🌐 Java | 📅 2026-07-22: Open Specification for Code-first Java GraphQL Services.

* [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) ⭐ 49 | 🐛 11 | 🌐 Java | 📅 2018-09-14: GraphQL-Java add-on that adds support for Schema Generation & Execution for enterprise level applications.

* [graphkool](https://github.com/beyondeye/graphkool) ⭐ 22 | 🐛 1 | 🌐 Kotlin | 📅 2016-12-29: GraphQl-java utilities in kotlin

* [graphql-emf](https://github.com/hallvard/graphql-emf) ⭐ 11 | 🐛 0 | 🌐 Java | 📅 2017-10-13: Support for EMF models and data

* [vertx-graphql-client](https://github.com/graphqly/vertx-graphql-client) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2026-01-15: An elegant implementation for code-first GraphQL clients

* [graphql-reflector](https://github.com/graphqly/graphql-reflector) ⭐ 0 | 🐛 2 | 🌐 Java | 📅 2026-01-15:  A simple GraphQL reflection library for Java code-first applications.

* [Elide](https://elide.io): Java library that lets you build model driven GraphQL APIs for CRUD and Analytics. It has first class support for JPA annotations.

* [Helidon GraphQL](https://medium.com/helidon/microprofile-graphql-support-now-available-in-helidon-mp-dbc7bc0b4af): An implementation of the MicroProfile GraphQL Specification using [Project Helidon](https://helidon.io/) version 2.2.0 and above

## Apollo Federation

* [federation-jvm](https://github.com/apollographql/federation-jvm) ⭐ 272 | 🐛 21 | 🌐 Java | 📅 2026-08-27:  An implementation of the [Apollo Federation Specification](https://www.apollographql.com/docs/federation/federation-spec/) for graphql-java

## Execution Strategies

* [graphql-java-reactive](https://github.com/bsideup/graphql-java-reactive) ⭐ 56 | 🐛 3 | 🌐 Java | 📅 2017-08-12: An execution strategy which is based on Reactive Streams. Project is evolving.

* [graphql-rxjava](https://github.com/nfl/graphql-rxjava) ⚠️ Archived: An execution strategy that makes it easier to use rxjava's Observable

## Exposing a Schema

* [graphql-spring-boot](https://github.com/graphql-java/graphql-spring-boot) ⚠️ Archived: GraphQL and GraphiQL Spring Framework Boot Starters

* [graphql-java-servlet](https://github.com/graphql-java/graphql-java-servlet) ⭐ 229 | 🐛 23 | 🌐 Java | 📅 2026-08-28: Servlet that automatically exposes a schema dynamically built from GraphQL queries and mutations.

* [micronaut-graphql](https://github.com/micronaut-projects/micronaut-graphql) ⭐ 88 | 🐛 28 | 🌐 Java | 📅 2026-08-29: Provides Micronaut GraphQL integration.

* [GORM GraphQL](https://github.com/grails/gorm-graphql) ⚠️ Archived: An fully customizable addon for [GORM](http://gorm.grails.org) (Grails Object Relational Model) to generate a GraphQL schema automatically.

* [graffiti](https://github.com/creactiviti/graffiti) ⭐ 63 | 🐛 0 | 🌐 Java | 📅 2017-12-17 - a headless Java CMS.

* [dropwizard-graphql](https://github.com/smoketurner/dropwizard-graphql) ⚠️ Archived - [Dropwizard](http://dropwizard.io) bundle for exposing a GraphQL endpoint (uses [graphql-java-servlet](https://github.com/graphql-java/graphql-java-servlet) ⭐ 229 | 🐛 23 | 🌐 Java | 📅 2026-08-28 internally)

* [spring-boot-starter-graphql](https://github.com/creactiviti/spring-boot-starter-graphql) ⭐ 41 | 🐛 1 | 🌐 Java | 📅 2018-02-11 - Spring Boot Starter for GraphQL.

* [graphql-jpa-spring-boot-starter](https://github.com/timtebeek/graphql-jpa-spring-boot-starter) ⭐ 37 | 🐛 1 | 🌐 Java | 📅 2022-09-17: Spring Boot starter for GraphQL JPA; Expose JPA entities with GraphQL.

* [Light Java GraphQL](https://github.com/networknt/light-java-graphql) ⭐ 37 | 🐛 10 | 🌐 Java | 📅 2026-08-13: A lightweight, fast microservices framework with all other cross-cutting concerns addressed that is ready to plug in GraphQL schema.

* [Vert.x GraphQL Utils](https://github.com/tibor-kocsis/vertx-graphql-utils) ⭐ 25 | 🐛 0 | 🌐 Java | 📅 2018-05-30 - Vert.x route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x applications.

* [Moqui GraphQL](https://github.com/shendepu/moqui-graphql) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2022-01-15: An addon of Moqui framework to generate GraphQL Schema automatically.

* [vertx-web-graphql](https://vertx.io/docs/vertx-web-graphql/java/): Extends Vert.x Web with the GraphQL-Java library so that you can build a GraphQL server.

## Validation

* [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) ⭐ 138 | 🐛 17 | 🌐 Java | 📅 2026-02-02: A validation library that allows use of @directives to indicate how to validate graphql input arguments.

## Batch Loading

* [java-dataloader](https://github.com/graphql-java/java-dataloader) ⭐ 525 | 🐛 24 | 🌐 Java | 📅 2026-08-20: A pure java 8 port of [Facebook DataLoader](https://github.com/facebook/dataloader) ⭐ 13,385 | 🐛 44 | 🌐 JavaScript | 📅 2026-08-11

## Scalars

* [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) ⭐ 290 | 🐛 5 | 🌐 Java | 📅 2026-08-24: A series extended scalars for graphql-java based projects, brought you you by the same team that helps build graphql-java itself

* [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) ⭐ 154 | 🐛 5 | 🌐 Java | 📅 2026-08-24: A set of ISO 33601, RFC 3339 compatible date time scalars for GraphQL Java

## Tools

* [JS GraphQL IntelliJ Plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin) ⭐ 898 | 🐛 157 | 🌐 Java | 📅 2026-08-26: GraphQL language support for WebStorm, IntelliJ IDEA and other IDEs based on the IntelliJ Platform.
* [graphql-calculator](https://github.com/graphql-calculator/graphql-calculator) ⭐ 111 | 🐛 18 | 🌐 Java | 📅 2026-03-10 - A lightweight graphql calculation engine, implemented based on directive.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the [contributors](https://github.com/graphql-java/awesome-graphql-java/graphs/contributors) ⭐ 592 | 🐛 2 | 📅 2023-11-02 have waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
