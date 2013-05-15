# CQ Parent POM

[CITYTECH, Inc.](http://www.citytechinc.com)

## Overview

Parent POM for Adobe CQ projects that defines a Maven &lt;dependencyManagement&gt; section containing all of the available dependencies that are provided by the CQ5 OSGi container.

CQ projects that define this project as the parent will only need to specify a &lt;dependencies&gt; section containing the subset of dependencies in use, but omit the version and scope elements.

## Versioning

Follows [Semantic Versioning](http://semver.org/) guidelines.