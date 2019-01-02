---
layout: page
---

## Overview

The RubySpec project aims to write a complete executable specification for the
[Ruby](http://ruby-lang.org) programming language that is syntax-compatible
with [RSpec](http://rspec.info). RSpec is essentially a DSL (domain-specific
language) for describing the behavior of code. This project contains specs
that describe Ruby language syntax, [core library](http://ruby-doc.org/core)
classes, and [standard library](http://ruby-doc.org/stdlib) classes.

The specs generally serve two purposes: 1) to drive development, and 2) as a
verification mechanism. These goal can sometimes be at odds. During
development, the code and specs evolve together. For verification, it is
desirable to have a highly stable set of specs that ideally have been audited
for correctness. The specs have been extensively used and developed
[BDD](http://behaviour-driven.org/) style in the [Rubinius](http://rubini.us)
project for almost 4.5 years with numerous contributions by other projects
like [JRuby](http://jruby.org/). Consequently, the specs have
attained a high degree of stability. However, there are a number of core
library classes and numerous standard library classes for which specs still
need to be written.

The following documents describe how the Rubinius specs are organized, the
style used to write them, and special measures (guards) used to write a single
body of specs that accommodates numerous different Ruby implementations.

* [Getting Started](https://github.com/ruby/spec#running-the-specs) -- Get up and running with MSpec and the RubySpec files
* [Organization]({{ site.baseurl }}/organization/) -- Where to find what you are looking for
* [Style Guide]({{ site.baseurl }}/style_guide/) -- Rules to follow while writing or fixing specs
* [Guards]({{ site.baseurl }}/guards/) -- Understand how versions, platforms, and implementations play well together
* [Runners]({{ site.baseurl }}/runners/) -- Detailed help for all the MSpec runner scripts
* [Contributing]({{ site.baseurl }}/contributing/) -- How to get involved improving the RubySpecs
