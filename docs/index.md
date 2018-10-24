# Welcome to Process Studio Documentation

## Introduction
AutomationEdge Process Studio is one of the three major components of AutomationEdge platform.
Other two being AutomationEdge Agent and AutomationEdge Server. Process Studio is a Java based
desktop tool meant for creating or modeling business processes.

### Starting process studio in proxy server environment

* `SET PROXY_DETAILS="-Dhttp.proxyHost=xxx" "-Dhttp.proxyPort=xxx"`   - In case of HTTP proxy.
* `SET PROXY_DETAILS="-Dhttps.proxyHost=xxx" "-Dhttps.proxyPort=xxx"` - In case of HTTPS proxy.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
