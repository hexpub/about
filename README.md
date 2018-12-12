# Hex Publishing

This organization aims to help Erlang and Elixir library authors to publish their libraries as packages to Hex.pm.
Many library authors have no time or willingness to do this. Automation saves the day!

Roadmap:

* Create spec files for packages that we wish to have on Hex.pm but don't
  * Canonical source
  * Better fork if any
  * Proof that author is not against publishing
    * [Example](https://github.com/seth/ej/issues/28)
* Write scripts to validate and publish them automatically
  * Publish every tag as a version
* Schedule the scripts to run regularly (at Semaphore CI?)
* Accept PRs from anyone

Related projects:

* [zotonic/hexpub](https://github.com/zotonic/hexpub) publishes Zotonic's packages to Hex.pm
