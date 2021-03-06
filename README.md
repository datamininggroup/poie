PFA Open Inference Engine (POIE): implementations of the PFA specification
========

**As of version 0.8.4, the PFA Open Inference Engine (POIE), Titus, and Aurelius are available with the Apache License v2.0**

**Version v.0.8.4**

The [Portable Format for Analytics (PFA)](http://dmg.org/pfa) is a specification for scoring engines: event-based processors that perform predictive or analytic calculations. It is a common language to help smooth the transition from statistical model development to large-scale and/or online production. For a model expressed as PFA to be run against data, an application is required.

**PFA-OIE** The PFA Open Inference Engine (POIE) is a complete implementation of PFA for the Java Virtual Machine (JVM).  POIE is designed as a library to be embedded in applications or used as a scoring engine container. To make POIE immediately usable, we provide containers that allow POIE to be dropped into an existing workflow. POIE can currently be used as a [standard-input/standard-output process](https://github.com/opendatagroup/hadrian/wiki/Hadrian-Standalone), a [Hadoop map-reduce workflow](https://github.com/opendatagroup/hadrian/wiki/Hadrian-MR), an [actor-based workflow](https://github.com/opendatagroup/hadrian/wiki/Hadrian-Actors) of interacting scoring engines, or as a [servlet in a Java Servlet container](https://github.com/opendatagroup/hadrian/wiki/Hadrian-GAE), including Google App Engine.

**Titus** ([API](http://opendatagroup.github.io/hadrian/titus-0.8.3/titus.genpy.PFAEngine)) is Open Data's complete implementation of PFA for Python. Hadrian and Titus both execute the same scoring engines, but while Hadrian's focus is speed and portability, Titus's focus is on model development. Included with Titus are standard model producers, a [PrettyPFA](https://github.com/opendatagroup/hadrian/wiki/PrettyPFA) parser for easier editing, a [PFA-Inspector](https://github.com/opendatagroup/hadrian/wiki/PFA-Inspector) commandline for interactive analysis of a PFA document, and many other tools and scripts.

In addition, Aurelius is an R package for producing PFA from the R programming language and Antinous is a sidecar app for building models in any environment where Hadrian can be deployed. These and other tools are included in the Hadrian repository.

See the [Hadrian wiki](https://github.com/opendatagroup/hadrian/wiki) for more information, including [installation instructions](https://github.com/opendatagroup/hadrian/wiki/Installation) and tutorials.


