Hari Sekhon - Bash Tools
========================
[![Build Status](https://travis-ci.org/HariSekhon/bash-tools.svg?branch=master)](https://travis-ci.org/HariSekhon/bash-tools)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c61193dd7dcc418b85149bddf93362e4)](https://www.codacy.com/app/harisekhon/bash-tools)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20OS%20X-blue.svg)](https://github.com/harisekhon/bash-tools#hari-sekhon---bash-tools)
[![DockerHub](https://img.shields.io/badge/docker-available-blue.svg)](https://hub.docker.com/r/harisekhon/centos-github/)

Bash Test & Utility library used by all my other [GitHub repos](https://github.com/harisekhon).

- Utility functions (Docker, environment, CI detection, port and HTTP url availability content checks)
- Tests for linting a variety of different programming and build files, including:

- Python (syntax, pep8, pre-byte-compiling)
- Perl
- Java
- Scala
- Make
- Maven
- SBT
- Gradle
- Travis CI
- Ruby
- Shell
- Misc (whitespace, custom enforced checks like not calling quit() in python etc)

Also pulls in many important validation programs from my [PyTools repo](https://github.com/harisekhon/pytools) to validate additional file formats including:

- CSV
- JSON
- Avro
- Parquet
- INI / Properties files (Java)
- LDAP LDIF
- XML
- YAML

Currently utilized to supplement testing of the following repos:

* [Advanced Nagios Plugins Collection](https://github.com/harisekhon/nagios-plugins) - 350+ programs covering every major Hadoop & NoSQL technology and Linux/Unix based infrastructure technologies
* [Perl Tools](https://github.com/harisekhon/tools) - 25 command line tools
* [Python Tools](https://github.com/harisekhon/pytools) - 50+ command line tools
* [Perl Lib](https://github.com/harisekhon/lib) - Perl utility library
* [PyLib](https://github.com/harisekhon/pylib) - Python utility library

[Pre-built Docker images](https://hub.docker.com/u/harisekhon/) are available for those repos (which include this one as a submodule) and the ["docker available"](https://hub.docker.com/r/harisekhon/centos-github/)  icon above links to an [uber image](https://hub.docker.com/r/harisekhon/centos-github/) which contains all my github repos pre-built. There are [Centos](https://hub.docker.com/r/harisekhon/centos-github/), [Debian](https://hub.docker.com/r/harisekhon/debian-github/) and [Ubuntu](https://hub.docker.com/r/harisekhon/ubuntu-github/) versions of this uber Docker image containing all repos.
