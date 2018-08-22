# Hoist Dockerfile: xh-ubuntu

[Hoist React](https://github.com/exhi/hoist-react/) apps can be deployed via Docker containers running Tomcat (for Hoist's Grails based back-end) and nginx (to serve compiled client JS/CSS and other assets).

We maintain simple base container images are available for both of those [Tomcat](https://github.com/exhi/xh-tomcat/) and [nginx](https://github.com/exhi/xh-nginx/) containers.

This repo is _not_ that, however. This builds a minimal utility image for use where we want to start a container and jump into a shell with fancy things like a text editor available for immediate use.

This image is [available on Docker Hub](https://hub.docker.com/r/xhio/xh-ubuntu/).

----
:mailbox: :phone: :earth_americas: info@xh.io | https://xh.io/contact

Copyright © 2018 Extremely Heavy Industries Inc.
