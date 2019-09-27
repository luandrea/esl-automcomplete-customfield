# ESL Autocomplete customfield

This is a plugin for Jira 8.4.0 to understand ho to create an autocomplete custom field.

# Build

To build it you need Atlassian SDK installed on your system.

To create the package to install in Jira you can use this command:

`atlas-mvn package`

# Releases

There are currently two releases:

* v1.0 - this version include only a simple text custom field
* v1.1 - this version include the custom Jquery autocomplete library with JQuery v1.12.4, but currently does not work
* v1.2 - this version has a working autocomplete functionality, but other pages doesn't work like search issues
