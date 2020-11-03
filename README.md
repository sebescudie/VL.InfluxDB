# VL.InfluxDB

_A set of nodes that allow to connect and write to an InfluxDB database_.

## Installation

```
nuget install VL.InfluxDB
```

## Considerations

This plugin only allows to write inside an InfluxDB database. You cannot read anything from it.

## Motivations

This plugin was done in an urgent need to write something to an InfluxDB database, so I did not focus on the reading part.

## Usage

Press <kbd>F1</kbd> and look for the _Send measurements to an InfluxDB database_ HowTo.

## Credits

Implementation of [kichristensen's InfluxDB.WriteOnly](https://github.com/kichristensen/InfluxDB.WriteOnly) .NET library.
