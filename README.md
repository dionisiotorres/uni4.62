#POS.HOST
# This is an Open Source POS forked from uniCenta oPos 4.6.2

## Overview

pos.host ( forked from uniCenta oPos ) is an enterprise level point of sale system and it has the following feature set

* Sales
* Inventory
* Customers
* Suppliers
* Employees
* Reporting

It runs on the following operating systems

* Windows
* Linux
* Mac osX

Full details can be found here: https://opensrci.org/

## Before you start
Install mysql (version 5X supported) and create a schema called unicentaopos

## Build and Run the appication
To get started, simply clone the repository and build the artifacts
### build the artifacts
```
mvn clean assemble
```
### run the application
```
java -jar ./target/unicentaopos
```




