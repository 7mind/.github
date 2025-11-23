We create complex tools which make Scala ecosystem better and Scala engineers productive.

Our notable projects include 

1. [DIStage](https://github.com/7mind/izumi): Phased Dependency Injection/First Class Modules/Multi-Modal Applications for Scala (with [TypeScript](https://github.com/7mind/izumi-chibi-ts) and [Python](https://github.com/7mind/izumi-chibi-py) ports)
2. [BIO](https://github.com/7mind/izumi): Bifunctor Typeclasses
3. [Logstage](https://github.com/7mind/logstage): effortless Structural Logging for Scala, structure is extracted directly from AST
4. [zio/izumi-reflect](https://github.com/zio/izumi-reflect): static portable compile-time reflection for Scala and a simulator of Scala typer, underlying technology of ZIO Zlayer.
5. [Baboon](https://github.com/7mind/baboon): Data Modeling and Versioning language with strong schema evolution capabilities and automatic evolution derivation
6. [SICK](https://github.com/7mind/sick): deduplicated indexed binary storage for JSON
7. [mudyla](https://github.com/7mind/mudyla): mini-orchestrator for scripts in various languages based on typed DAGs
8. [squish-find-the-brains](https://github.com/7mind/squish-find-the-brains): a tool to run SBT under Nix

Also we've made multiple contributions into Scala ecosystem:

- [async tracing](https://zio.dev/reference/error-management/recovering/catching/#catching-traces) for async IO Monad runtimes which later evolved and influenced various implementations in different libraries.
- In Scala 3 & 2 compilers, added support for `-Xkind-projector:underscores` - [underscore syntax for type lambdas](https://github.com/scala/scala3/pull/12378), part of Scala 3 roadmap
- We help testing compiler stability: our libraries are included into [Scala 3 Community Build](https://github.com/scala/scala3/tree/main/community-build/community-projects) and [Scala 3 Open Community Build](https://github.com/VirtusLab/community-build3).
- Orders of magnitude faster [publishing](https://github.com/sbt/sbt/issues/4958) of Scala projects to Sonatype.
- We make lots of `scalac` bug reports regularly
