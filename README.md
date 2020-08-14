![Context Mapper](https://raw.githubusercontent.com/wiki/ContextMapper/context-mapper-dsl/logo/cm-logo-github-small.png) 
# Context Mapper OSGi Bundles (P2 Publishing Build)
[![Build Status](https://travis-ci.com/ContextMapper/context-mapper-osgi-bundles.svg?branch=master)](https://travis-ci.com/ContextMapper/context-mapper-osgi-bundles) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [ ![Download](https://api.bintray.com/packages/contextmapper/context-mapper-osgi-bundles/updatesites/images/download.svg) ](https://bintray.com/contextmapper/context-mapper-osgi-bundles/updatesites/_latestVersion)

This [Context Mapper](https://contextmapper.org/) repository contains a Gradle build that publishes configured libraries as OSGi bundles to our P2 repository.
We use it to bundle thirdparty libraries that are used in our [Context Mapper Eclipse Plugin](https://github.com/ContextMapper/context-mapper-dsl).

## P2 Repositories
 * [context-mapper-osgi-bundle-snapshots](https://dl.bintray.com/contextmapper/context-mapper-osgi-bundle-snapshots/): Snapshots built on the _master_ branch are published here.
 * [context-mapper-osgi-bundles](https://dl.bintray.com/contextmapper/context-mapper-osgi-bundles/): Released P2 repositories (built on release tags).
 
 ## Available Libraries
 The P2 repository currently contains the following libraries as OSGi bundles:
  * [Freemarker](https://freemarker.apache.org/) (v2.3.30)
  * [Swagger Core](https://github.com/swagger-api/swagger-core/) (v2.1.2)
  * [Swagger Parser](https://github.com/swagger-api/swagger-parser/) (v2.0.20)
  * [stefan-ka's \*.proto Generator (Protocol Buffers)](https://github.com/stefan-ka/protobufgen) (v1.2.0)
