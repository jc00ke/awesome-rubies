# awesome-rubies

A collection of awesome Rubies (compilers, interpreters, virtual machines, parsers, docu generators, version managers, etc.) 

---

[ANNOUNCEMENT] Looking for awesome Ruby events (meetups, conferences, camps, etc.) from around the world)? See the [Awesome Events List @ Planet Ruby](https://github.com/planetruby/awesome-events). 

---

## Major Rubies

- [Ruby](https://www.ruby-lang.org), [:octocat:](https://github.com/ruby)- also known as Matz's Ruby Interpreter (MRI) or CRuby; using the YARV (Yet another Ruby VM) since version 1.9 
   - 2014: 2.2  (Dec/24)
   - 2013: 2.1  (Dec/24)
   - 2012: 2.0  (Feb/24, 2013)
- [JRuby](http://jruby.org), [:octocat:](https://github.com/jruby) - Ruby on the Java Virtual Machine (JVM)
   - Upcoming: v9.0.0.0
   - 2014: v1.7.x
- [mruby](http://www.mruby.org), [:octocat:](https://github.com/mruby) - lightweight Ruby; designed for linking and embedding within your application
- [Rubinius (rbx)](http://rubini.us), [:octocat:](https://github.com/rubinius) - designed for concurrency; uses a low-pause generational garbage collector and LLVM-based just-in-time (JIT) native machine code compiler; core library and tools coded in Ruby

## Minor / Upcoming Rubies

- [Topaz](http://topazruby.com), [:octocat:](https://github.com/topazproject) - Ruby coded in Python on top of RPython (the toolchain that powers PyPy) 
- [GoRuby :octocat:](https://github.com/goruby) - Ruby coded in Go

## Discontinued / Rest In Peace (R.I.P.) Rubies 

- [IronRuby](http://ironruby.net), [:octocat:](https://github.com/IronLanguages) - a ruby interpreter built on top of the Microsoft .NET Common Language Runtime (CLR)
- [MacRuby :octocat:](https://github.com/MacRuby) - a ruby interpreter built on top of Apple's Objective-C/Cocoa library
- [MagLev](http://maglev.github.io), [:octocat:](https://github.com/MagLev) - a ruby interpreter built on top of the GemStone/S 3.1 Virtual Machine (VM); note to run MagLev you need a commercial GemStone/S Server license
- [Ruby Enterprise Edition (REE)](http://www.rubyenterpriseedition.com) - builds on top of MRI Rubies, versions 1.8.X and later


## Ruby-to-JavaScript

- [Opal](http://opalrb.org), [:octocat:](https://github.com/opal) - source-to-source compiler
- [rubys/ruby2js :octocat:](https://github.com/rubys/ruby2js) - minimal yet extensible Ruby to JavaScript converter 
- [RubyJS](http://rubyjs.org/), [:octocat:](https://github.com/rubyjs) - JavaScript standard library based on the Ruby core-lib

## Ruby-to-C (LLVM)

- [Crystal](http://crystal-lang.org), [:octocat:](https://github.com/manastech/crystal) - compile to machine code; run a ye good olde binary 

## Ruby-to-Java

- [Mirah](http://www.mirah.org), [:octocat:](https://github.com/mirah) - formerly known as Duby; compiles to Java bytecode; no (extra) runtime library required

## Ruby-to-Objective-C/Cocoa

- [RubyMotion](http://www.rubymotion.com) - commercial compiler for Apple iOS/Cocoa

## Ruby-to-Erlang

- [Elixir](http://elixir-lang.org) - Ruby-inspired syntax; a dynamic, functional language for the Erlang VM compiles to BEAM instructions (bytecode)  

## Ruby Version Manager

- [rvm](https://rvm.io), [:octocat:](https://github.com/rvm) - Ruby enVironment Manager; 27,000 lines of shell scripts to manage your rubies (overwrites your cd)
- [rbenv :octocat:](https://github.com/sstephenson/rbenv) - intercepts Ruby commands using shim executables added into your $PATH
- [chruby :octocat:](https://github.com/postmodern/chruby) - changes the current Ruby

## Ruby Language Research, Papers & Books

- [Ruby under a Microscope - An Illustrated Guide to Ruby Internals](http://www.nostarch.com/rum) by Pat Shaughnessy; No Starch Press; 360 pages; Nov 2013
- [Ruby Performance Optimization: Why Ruby Is Slow, and How to Fix It](https://pragprog.com/book/adrpo/ruby-performance-optimization) by Alexander Dymo; The Pragmatic Programmers 
- [The Ruby Bibliography](http://rubybib.org), [:octocat:](https://github.com/rubybib)
- [Streem Lang :octocat:](https://github.com/matz/streem) - prototype of stream based programming language by Yukihiro Matsumoto

## Ruby Benchmarks & Tests

- [RubyBench](http://rubybench.org), [:octocat:](https://github.com/ruby-bench) - Ruby Releases Benchmarks

## Ruby Type Annotations / Signatures

- [Contracts for Ruby (contracts.ruby) :octocat:](https://github.com/egonSchiele/contracts.ruby) - a contract is one line of code that you write above a method definition; it validates the arguments to the method, and validates the return value of the method
- [Rubype (Ruby+Type) :octocat:](https://github.com/gogotanaka/Rubype) - gradual type checking for Ruby
- [Typedocs :octocat:](https://github.com/todesking/typedocs) - method type annotations for Ruby
- [Typecheck :octocat:](https://github.com/plexus/typecheck) - type checking for Ruby methods 


## Ruby Quick References / Cheat Sheets

- [Ruby QuickRef](http://www.zenspider.com/Languages/Ruby/QuickRef.html) - Language, Standard Library, Tools
- [Learn Ruby in Y Minutes](http://learnxinyminutes.com/docs/ruby), [:octocat:](https://github.com/adambard/learnxinyminutes-docs) - A whirlwind tour of Ruby - learnruby.rb

## Ruby Parser / Unparser

- [seattlerb/ruby_parser (RP) :octocat:](https://github.com/seattlerb/ruby_parser) - a ruby parser written in ruby (using racc -- which does by default use a C extension). RP's output is the same as ParseTree's output: s-expressions using ruby's arrays and base types
- [whitequark/parser :octocat:](https://github.com/whitequark/parser) - a ruby parser written in ruby;  also includes an "unparser" to produce equivalent source code from the parser's Abstract Syntax Tree (AST)s

## Ruby Documentation Generators

- [YARD](http://yardoc.org), [:octocat:](https://github.com/lsegal/yard) - Yay! A Ruby Documentation Tool 
- [SDoc :octocat:](https://github.com/voloko/sdoc) - RDoc generator to build searchable HTML documentation for Ruby code
- [RDoc :octocat:](https://github.com/rdoc) - RDoc produces HTML and online documentation for Ruby code 

## Ruby Linter / Code Checker / Static Code Analyzer

- [RuboCop :octocat:](https://github.com/bbatsov/rubocop) - a Ruby static code analyzer
- [reek :octocat:](https://github.com/troessner/reek) - code smell detector for Ruby


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the ruby-talk mailing list. Thanks!
