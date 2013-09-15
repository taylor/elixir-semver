elixir-semver - Semantic Versioning Library
=============

elixir-semver is a [semantic versioning](http://semver.org) library for Elixir.  It lets you parse and compare two semantic version strings.

Usage
=====

```
vA = SemVer.NewVersion("1.2.3")
vB = SemVer.NewVersion("3.2.1")

IO.puts "#{vA} < #{vB} == #{SemVer.LessThan(vA, vB)}"
```

TODO
====
 * Full compliance with semver.org rules
