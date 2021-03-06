# SimpleBus/DoctrineORMBridge

[![Build Status](https://travis-ci.org/SimpleBus/DoctrineORMBridge.svg?branch=master)](https://travis-ci.org/SimpleBus/DoctrineORMBridge)

By [Matthias Noback](http://php-and-symfony.matthiasnoback.nl/), Cliff Odijk, Ruud Kamphuis

This package provides command bus middlewares that can be used to integrate
[SimpleBus/MessageBus](https://github.com/SimpleBus/MessageBus) with [Doctrine
ORM](https://github.com/doctrine/doctrine2).

It provides an easy way to [wrap command handling in a database transaction](http://docs.simplebus.io/en/latest/Components/DoctrineDBALBridge.html#transactions) and [handle domain events generated by entities](http://docs.simplebus.io/en/latest/Components/DoctrineORMBridge.html#domain-events).

Resources
---------

  * [Report issues](https://github.com/SimpleBus/SimpleBus/issues) and
    [send Pull Requests](https://github.com/SimpleBus/SimpleBus/pulls)
    in the [main SimpleBus repository](https://github.com/SimpleBus/SimpleBus)
