# Django Cassandra Engine - the Cassandra backend for Django

All tools you need to start your journey with Apache Cassandra and Django Framework!

Already using <a href="http://datastax.github.io/python-driver/" target="_blank" rel="nofollow">
    DataStax Python Driver for Apache Cassandra
</a>?
That's great! Now you can easily integrate your existing or new Django project with it.

## Overview

*django-cassandra-engine* is the first Cassandra backend for *Django Framework*.
It integrates with Django well and allows you to use <a href="https://datastax.github.io/python-driver/object_mapper.html" target="_blank" rel="nofollow">
    Cqlengine
</a>
directly in your project. All your cassandra models are automatically synced
in the way you're used to. You can focus on writing a good code.

## Features

* integration with latest `python-driver` from DataStax
* working `flush`, `syncdb`, `migrate`, `sync_cassandra`, `inspectdb` and 
  `dbshell` commands
* support for creating/destroying test database
* accepts all `cqlengine` and `cassandra.cluster.Cluster` connection options
* automatic connection/disconnection handling
* works well along with relational databases
* storing [sessions](guide/sessions.md) in Cassandra

## Plans (TODO) ##

* User model stored in Cassandra (auth module)
* Admin panel for Cassandra models
* Forms

## Requirements

* Python>=2.7
* Cassandra>=2.0 (of course)
* cassandra-driver>=2.5
* Django>=1.6

---

Can't wait? [Install me](guide/installation.md)!
