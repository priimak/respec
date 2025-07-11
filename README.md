# ReSpec - Register Specification Language

## Goals

ReSpec is a definition of language embedded json that defines various aspect of digital design (primarily
register definitions) and collections of tools that aid interation with ReSpec files. Intent of embedding
register spec in json is to allow it be essentially text and thus make it possible to easily see diff and, if
necessary, direct change using any text editor. At the same various GUI and command line tools are provided to
minimize making mistakes such forming incorrect json or setting internally inconsistent properties (for example
two registers having the same address). For programmatic interaction with ReSpec files a python library is provided.

## Tools

* **_rx_** - GUI editor for respec files. 