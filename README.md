Awesome OCaml
=============

This repository contains a large collection of resources for the OCaml programming language.  
Next follows a curated list of references to awesome tools, frameworks, libraries and articles. It also contains collection of freely available [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) and [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations). **Everything you'll ever need on the road to mastering OCaml**.

This is an open community-driven repository. Fork and create a Pull Request to contribute!


![](https://farm6.staticflickr.com/5306/5677528375_ace9c325ef_z.jpg)

- _Inspired by awesome projects line. Discover [more awesomeness](https://github.com/bayandin/awesome-awesomeness)._
- _Photo by Jim Boud, ["Basking Camel"](https://www.flickr.com/photos/boudster/5677528375)_

## Contents

- [Community](#community)
- [Algorithms and Data Structures](#algorithms-and-data-structures)
- [Application Libraries](#application-libraries)
- [Books](#books)
- [Compilers](#compilers)
- [Concurrency](#concurrency)
- [Databases](#databases)
- [Developer Tools](#developer-tools)
- [Exercises](#exercises)
- [General](#general)
- [Graphics](#graphics)
- [Language-related](#language-related)
- [Logging](#logging)
- [Metaprogramming](#metaprogramming)
- [Networking](#networking)
- [Online Courses](#online-courses)
- [Package Management and Build Tools](#package-management-and-build-tools)
- [Package Management](#package-management)
- [Parallelism](#parallelism)
- [Questions](#questions)
- [Security](#security)
- [Semantic Technology](#semantic-technology)
- [Serialization](#serialization)
- [System Programming](#system-programming)
- [Testing](#testing)
- [Web Development](#web-development)

* * *


## Community

- [Official OCaml Mailing List](http://caml.inria.fr/resources/forums.en.html)
- [Official OCaml Website](http://ocaml.org/)
- [OCaml Planet](http://planet.ocamlcore.org/)


## Algorithms and Data Structures

- [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](http://philtomson.github.io/blog/2014/05/29/comparing-a-machine-learning-algorithm-implemented-in-f-number-and-ocaml/)
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) – A generic graph library for OCaml.


## Application Libraries

- [Cmdliner](https://github.com/dbuenzli/cmdliner) – Declarative definition of command line interfaces for OCaml.
- [Core](https://github.com/janestreet/core) – Jane Street Capital's standard library overlay.
- [React](http://erratique.ch/software/react) – React is an OCaml module for functional reactive programming (FRP). It provides support to program with time varying values: declarative events and signals.
- [ctypes](https://github.com/ocamllabs/ocaml-ctypes) – Library for binding to C libraries using pure OCaml.
- [easy-format](https://github.com/mjambon/easy-format) – Pretty-printing library for OCaml.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) – Light library to deal with RPCs in OCaml.


## Books

- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html) by Allen Downey and Nicholas Monje – How to Think Like a Computer Scientist is an introductory programming textbook based on the OCaml language. It is a modified version of Think Python by Allen Downey. It is intended for newcomers to programming and also those who know some programming but want to learn programming in the function-oriented paradigm, or those who simply want to learn OCaml.
- [OCaml from the Very Beginning](http://ocaml-book.com/) by J. Whitington - OCaml from the Very Beginning will appeal both to new programmers, and experienced programmers eager to explore functional languages such as OCaml.
- [Pearls of Functional Algorithm Design](http://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) by Richard Bird - It summaries 30 hard algorithm problems in function programming world. Although it is for Haskell, the algorithm problems are very interesting and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml are [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) by Y. Minsky, A. Madhavapeddy and J. Hickey - Functional programming for the masses.
- [Unix System Programming in OCaml](http://ocamlunix.forge.ocamlcore.org/) by X. Leroy and D. Rémy – Introduction to Unix system programming, with an emphasis on communications between processes.
- [Using, Understanding, and Unraveling OCaml](http://caml.inria.fr/pub/docs/u3-ocaml) – This book describes both the OCaml language and the theoretical grounds behind its powerful type system.


## Compilers

- [Hack Programming Language](http://hacklang.org/)


## Concurrency

- [Async](http://janestreet.github.io/) — A monadic concurence library to go with the Core library.
- [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).
- [Lwt](http://ocsigen.org/lwt/) — A cooperative threads library for OCaml.


## Databases

- **Bindings**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) — A binding to the NDBM/GDBM Unix "databases".
  - [Mongo.ml](http://massd.github.io/mongo/) – An OCaml driver for Mongodb
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) — PG'OCaml provides an interface to PostgreSQL databases for OCaml applications.
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml/) — OCaml bindings to the SQLite3 database.
- **New Implementations**
  - [Irmin](https://github.com/mirage/irmin) — A distributed database that follows the same design principles as Git.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) — A database with BigTable-like data model atop LevelDB.
- **Overlays**
  - [Macaque](https://github.com/ocsigen/macaque) — Macaque is a library for safe and flexible database queries using comprehensions on top of PG'OCaml.
  - [ORM](https://github.com/mirage/orm/) — ORM for SQLite.


## Developer Tools

- [Try OCaml](http://try.ocamlpro.com/) – Try OCaml in your web browser.
- [pfff](https://github.com/facebook/pfff) – pfff is a set of tools and APIs to perform some static analysis, dynamic analysis, code visualizations, code navigations, or style-preserving source-to-source transformations such as refactorings on source code.
- [utop](https://github.com/diml/utop) – Universal toplevel for OCaml with support of multiline edition, history, real-time and context sensitive completion, colors, and more.
- **Editor Plugins**:
  - [merlin](https://github.com/the-lambda-church/merlin) – Context sensitive completion for Ocaml in Vim and Emacs.
  - [tuareg](https://github.com/ocaml/tuareg) - OCaml mode for Emacs that can run the toplevel and the debugger within Emacs.


## Exercises

- [99 problems](https://github.com/MassD/pearls). 99% solutions are [here](https://github.com/MassD/99)


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](http://tech.esper.com/2014/07/15/why-we-use-ocaml/)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)


## Graphics

- **2D**
  - [archimedes](http://archimedes.forge.ocamlcore.org/) — 2D plotting library.
  - [cairo2](https://github.com/Chris00/ocaml-cairo) — Binding to Cairo, a 2D Vector Graphics Library. Integrates well with lablgtk.
  - [Vg](https://github.com/dbuenzli/vg) – Declarative 2D vector graphics for OCaml.
- **3D**
  - [glMLite](http://www.linux-nantes.org/~fmonnier/OCaml/GL/) — OpenGL bindings for OCaml. Provides an (experimental) functional API.
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/) — Interface to OpenGL. Integrates well with lablgtk.
  - [tgls](http://erratique.ch/software/tgls) — Thin bindings OpenGL 3.{2,3},4.{0,1,2,3,4} and OpenGL ES {2,3}.
- **GUI**
  - [lablgtk](http://lablgtk.forge.ocamlcore.org/) — GTK2 bindings for OCaml with various higher-level facilities to define GUIs.
  - [lablqt](https://github.com/Kakadu/lablqt) – Qt5 bindings for OCaml.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – OCaml pattern-matching extended with regexps


## Logging

- [Volt](https://github.com/codinuum/volt) – A variant of Bolt OCaml logging tool.


## Metaprogramming

- [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
- [Syntax extensions without Camlp4: let's do it!](http://www.lexifi.com/blog/syntax-extensions-without-camlp4-lets-do-it)
- [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – an OCaml dialect for multi-stage programming.


## Networking

- [ocaml-dns](https://github.com/mirage/ocaml-dns) – A pure OCaml implementation of the DNS protocol.
- [ocaml-zmq](https://github.com/issuu/ocaml-zmq) – ZeroMQ bindings for OCaml.


## Online Courses

- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/courses/cs3110/2011sp/lecturenotes.asp).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).


## Package Management and Build Tools

- [OPAM](http://opam.ocamlpro.com/) – A flexible Git-friendly package manager with multiple compiler support.
- [Oasis](http://oasis.forge.ocamlcore.org/) - A tool to integrate a configure, build and install system in your OCaml project. It helps to create standard entry points in your build system and allows external tools to analyse your project easily.
- [obuild](https://github.com/ocaml-obuild/obuild) – Simple package build system for ocaml.
- [jenga](https://github.com/janestreet/jenga) – Monadic build system from Jane Street..


## Parallelism

(_Note: Sorted from the easier to use to the more flexible._)

- **Libraries**:
  - [Parmap](http://rdicosmo.github.io/parmap/) — Provides easy-to-use parallel map and fold functions.
  - [ForkWork](https://github.com/mlin/forkwork) — A simple library for forking child processes to perform work on multiple cores.
  - [Functory](http://functory.lri.fr/About.html) — A distributed computing library which facilitates distributed execution of parallelizable computations in a seamless fashion.
  - [Async.Parallel](https://blogs.janestreet.com/async-parallel/) — A library for spawning processes on a cluster of machines, and passing typed messages between them.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html) — An enhanced system platform library. Contains the `netmulticore` library to compute tasks on as many cores of the machine as needed.

- **Articles**:
  - [What is the state of OCaml's parallelization abilities?](http://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)


## Questions

- [OCaml polymorphism example other than template function?](http://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [Ocaml - polymorphic print and type losing](http://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


## Security

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) – TLS in pure OCaml.


## Semantic Technology

- [OCaml-RDF](http://zoggy.github.io/ocaml-rdf/) – OCaml library to manipulate RDF graphs and execute Sparql queries.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) — Bencode (.torrent file format) reader/writer.
- [biniou](https://github.com/mjambon/biniou) – Extensible binary data format, like JSON but faster.
- [biniou](https://github.com/mjambon/biniou) – Extensible binary data format, like JSON but faster.
- [jsonm](http://erratique.ch/software/jsonm) — Non-blocking streaming JSON codec for OCaml.
- [xmlm](http://erratique.ch/software/xmlm) — A streaming codec to decode and encode the XML data format.
- [yojson](http://mjambon.com/yojson.html) — An optimized parsing and printing library for the JSON format.


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) – Mirage is a programming framework for constructing secure, high-performance network applications across a variety of cloud computing and mobile platforms.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) – Read and write FAT format filesystems from OCaml.
- [ocaml-git](https://github.com/mirage/ocaml-git) – Pure OCaml low-level git bindings.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) – Pure OCaml implementation of the "vchan" shared-memory communication protocol.


## Testing

- [OUnit](https://github.com/warrenharris/ounit) – OUnit is a unit test framework for OCaml. It allows one to easily create unit-tests for OCaml code. It is based on HUnit, a unit testing framework for Haskell.


## Web Development

- **Frameworks**:
  - [Opium](https://github.com/rgrinberg/opium) – Sinatra like web toolkit for OCaml.
  - [Eliom](http://ocsigen.org/eliom/) – Eliom is a framework for programming web sites and client/server web applications. It uses very new concepts making programming very different from all other web programming tools, and allowing to write a complex web site in very few lines of code.

- **Tools**:
  - [COW](https://github.com/mirage/ocaml-cow) – Caml on the Web (COW) is a set of parsers and syntax extensions to let you manipulate HTML, CSS, XML, JSON and Markdown directly from OCaml code.
  - [tyxml](http://ocsigen.org/tyxml) — Library to build valid (according to the W3C spec) Html and Svg trees.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml) – Js_of_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) – RFC3986 URI parsing library.

- **Open Source Projecs**:
  - [Cumulus](https://github.com/Cumulus/Cumulus) – Hacker news like website with the OCaml framework Ocsigen


