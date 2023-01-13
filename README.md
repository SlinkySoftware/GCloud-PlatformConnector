# GCloud Platform Connector Project #
This project consists of three GIT submodules.

* The main application - this is a web application that provides a single REST interface to Genesys Cloud, and allows plug-in modules for managing interactions with third party systems
* The plugin interface specification - A Java interface and base data transfer objects which are to be implemented by plug-ins and consumed by the main application
* A demonstration plugin. This plugin shows how to consume the interface and includes the base functionality for being consumed and publishing the appropriate details into the main application. It should be used as a starting point for all new plugins.
