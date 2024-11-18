# Ahox's Core

This is the code that powered the core Spigot services of the Minecraft network called MineRift. It includes the database models used by all parts of the network, interfaces used by games and hubs, and utility classes.

## Requirements

To build this core, the following will need to be installed and available from your shell:

* [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) version 131 or later (older versions _might_ work)
* [Git](https://git-scm.com/)
* [Maven](https://maven.apache.org/)

You can find detailed installation instructions for these tools on the (will edit)

## Getting started

You can build this project by running the following command:

```
mvn package
```

> Please note that you might also want to `mvn install` this module to your local `.m2` repo as it is required by most Spigot plugins.
## Architecture

This repo contains the following components:

* Data models and services
* Functionality common to all servers e.g. friends, nicknames, etc.
* MongoDB and Redis service abstractions
* Repository system used to serialize statistics, achievements, and settings data to database values
* Global announcement system
* Achievements API
* Punishment system.
* Server queue API (used for joining servers with friends, parties...)
* Staff utilities
* General utility classes used by dependent modules

## Authors

This project was maintained by the Minerift Network. If you have any questions or problems, feel free to reach out to the specific writers and maintainers of this project:

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/1vye">
          <img width="150" height="150" src="https://github.com/1vye.png?v=3&s=150">
          </br>
          Ahox
        </a>
      </td>
    </tr>
  <tbody>
</table>

## Coding Conventions

* We generally follow the Sun/Oracle coding standards.
* No tabs; use 4 spaces instead
* No trailing whitespaces
* No CRLF line endings, LF only, put your git's `core.autocrlf` on `true`.
* No 80 column limit or 'weird' midstatement newlines.
