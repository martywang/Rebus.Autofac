# Changelog

## 2.0.0-a1

* Update Autofac dependency to 4.1.0

## 2.0.0-a2

* Test build

## 2.0.0-b01

* Test release

## 2.0.0

* Release 2.0.0

## 3.0.0

* Update to Rebus 3

## 4.0.0

* Update to Rebus 4
* Add .NET Core support (netstandard1.6)
* Fix csproj - thanks [robvanpamel]
* Update Autofac dep to 4.5.0
* Update contracts dep - thanks [trevorreeves]

## 5.0.0

* Change API to work better with the Autofac container builder - no more `.Update` :)

## 5.1.0

* Additional `RegisterRebus` overload that passes `IComponentContext` to the configuration method

## 5.2.0

* Add Rebus handler registration extensions on `ContainerBuilder` and improve resolution performance

## 6.0.0-b01

* Move polymorphic handler resolution resposiblity to the container. If contravariant lookup is wanted, one must register `ContravariantRegistrationSource` on the `ContainerBuilder`

[robvanpamel]: https://github.com/robvanpamel
[trevorreeves]: https://github.com/trevorreeves