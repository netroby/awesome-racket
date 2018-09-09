# Awesome Racket

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Awesome Racket, libraries and software. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

Check all complete package list: https://pkgs.racket-lang.org/

### Contents

- [Awesome Racket](#awesome-racket)
    - [Web Frameworks](#web-frameworks)
	- [Game Development](#game-development)
	- [Audio and Music](#audio-and-music)
	- [Compilers](#compilers)
	- [Data Structures](#data-structures)
	- [Third-party APIs](#third-party-apis)
	- [Machine Learning](#machine-learning)
	- [Database Drivers](#database-drivers)
	- [Messaging](#messaging)


## Web Frameworks

*Full stack web frameworks.*

* [web-server/servlet](http://docs.racket-lang.org/web-server/) - Running Web Servlets describes how to run the servlets you’ve written.
* [Spin](https://github.com/dmac/spin) - Write RESTful web apps in Racket.
* [HoLy](https://github.com/nihirash/holy) - HoLy is simple a HTTP-server Library for Racket.


## Game Development

*Awesome game development libraries.*

* [game-engine](https://github.com/srfoster/game-engine) - Scratchpad for racket game stuff.
* [pict3d](https://github.com/jeapostrophe/pict3d) - A 3D engine with a purely functional API.
* [vr-lang](https://github.com/thoughtstem/vr-lang) - Racket Lang for Virtual Reality (Aframe).
* [towers](https://github.com/Metaxal/towers) - Towers is an original 2-player board game.
* [apse](https://github.com/jeapostrophe/apse) - A Pixel Sprite Editor.


## Audio and Music

*Libraries for manipulating audio.*

- [3s](https://github.com/jeapostrophe/3s) - Positional sound and mixing for lux and other applications.
- [libopenal-racket](https://github.com/lehitoskin/libopenal-racket) - Racket wrapper to the OpenAL library first written by gcr in 2012.
- [midi-readwrite](https://github.com/jbclements/midi-readwrite) - Library to read .mid files in racket
- [openal](https://github.com/jeapostrophe/openal) - FFI for OpenAL.
- [osc](https://github.com/jbclements/osc) - Open Sound Control data definitions.
- [portaudio](https://github.com/jbclements/portaudio) - Bindings for portaudio, a cross-platform audio library.
- [rsc3](https://github.com/quakehead/rsc3) - SuperCollider client ported to Racket.
- [RSound](https://github.com/jbclements/RSound) - A framework for manipulating and playing sounds using the portaudio library. Runs on Windows, Mac OS X, and linux.
- [rtmidi](https://github.com/jbclements/rtmidi) - Provides racket bindings for the RtMidi library, thus enabling racket programs to send and receive MIDI events.
- [sonic-pi](https://github.com/jbclements/sonic-pi) - For now, this package starts scsynth just like sonic pi does, and can make a few sounds.
- [taglib](https://github.com/takikawa/taglib-racket) - Bindings to the taglib C library, which provides simple access to audio file metadata.
- [wavelet-transform-haar-1d](https://github.com/jbclements/wavelet-transform-haar-1d) - A library to perform forward and reverse 1-d Haar Wavelet transforms.


## Compilers

*Tools for compiling Racket to other languages.*

- [racketscript](https://github.com/vishesh/racketscript) - A lightweight Racket to JavaScript compiler with some batteries included.
- [urlang](https://github.com/soegaard/urlang) - Write JavaScript with Racket syntax. Bonus: Use Racket to define macros for JavaScript constructs.
- [whalesong-tools](https://github.com/vishesh/drracket-whalesong) - DrRacket tool for compiling with Whalesong.
- [abstract-compilation](https://github.com/philnguyen/abstract-compilation) - DSL reducing boiler plates for doing abstract compilation.
- [minipascal](https://github.com/soegaard/minipascal) - MiniPascal as a Racket language.
- [zordoz](https://github.com/bennn/zordoz) - Explorer for .zo bytecode files.


## Data Structures

*Generic datastructures and algorithms.*

- [algebraic](https://github.com/dedbox/racket-algebraic) - Algebraic structures for untyped Racket.
- [dssl](https://github.com/tov/dssl) - Data Structures Student Language: an extension of ASL for easier imperative programming.
- [dssl2](https://github.com/tov/dssl2) - A language for data structures students.
- [opt](https://gitlab.com/RayRacine/opt) - Optional and Either data type utilities. Provides util function for Typed Racket's Option type as well as defines an Either type.
- [try](https://gitlab.com/RayRacine/try) - A Typed Racket Try datatype and routines for computations that throw exceptions.
- [gls](https://github.com/Kalimehtar/gls) - Generic Little (Object, Type, Anything, ...) System - multiple dispatch on types.
- [graph](https://github.com/stchang/graph) - Generic graph library.
- [phc-adt](https://github.com/jsmaniac/phc-adt) - Algebraic Data Types for Typed/Racket, with features tailored to compiler writing. The data types do not have to be declared before they are used, like prefab structs and symbols. Behind the scenes, this library remembers all the data types in a file, and uses it to implicitly pre-declare them. Mostly stable, although some things may change a bit in the future.
- [quad-tree](https://github.com/dented42/racket-quad-tree) - A fairly simple quad-tree implementation. Nothing terribly fancy. Currently rather unstable.


## Third-party APIs

*Libraries for accessing third party APIs.*

- [aws](https://github.com/greghendershott/aws) - Amazon Web Services including S3, SDB, SES, SNS, SQS, CloudWatch, Glacier, Dynamo, and Route 53.
- [aws-cloudformation-deploy](https://github.com/cjdev/aws-cloudformation-deploy) AWS Cloudformation deployment scripting library.
- [comm-panel](https://github.com/thoughtstem/comm-panel) - Racket GUI widget for sending, receiving, listening, and broadcasting strings over AWS SQS.
- [google](https://github.com/tonyg/racket-google) - Google APIs (Drive, Plus, ...) for Racket.
- [recaptcha](https://github.com/LiberalArtist/recaptcha) - Utilities for using reCAPTCHA with the web-server/formlets API.


## Machine Learning

*Libraries for Machine Learning.*

- [rml-core](https://github.com/johnstonskj/rml-core) - This Package is part of an expected set of packages implementing machine learning capabilities for Racket. The core of this package is the management of 'datasets', these datasets are assumed to be for training and testing of machine learning capabilities.
- [rml-decisiontrees](https://github.com/johnstonskj/rml-decisiontrees) - This Package is part of a set of packages implementing machine learning capabilities for Racket. This particular package implements support for classification of individuals using decision trees.
- [rml-knn](https://github.com/johnstonskj/rml-knn) - This Package is part of a set of packages implementing machine learning capabilities for Racket. This particular package implements the K-Nearest Neighbor approach for classification.
- [tesseract](https://github.com/lasfter/tesseracket) - Bindings for Google's Tesseract-OCR.


## Database Drivers

*Libraries for connecting and operating databases.*

- [db](https://github.com/racket/db) - Database connectivity (main distribution).
- [mongodb](https://github.com/jeapostrophe/mongodb) - A native Racket interface to MongoDB & BSON.
- [binary-class-dbf](https://github.com/Kalimehtar/binary-class-dbf) - Interface to *.dbf files (dBase, Foxpro, ...).
- [dbm](https://github.com/jeapostrophe/dbm) - An interface to UNIX dbm files using a libdbm FFI.
- [fra](https://github.com/jeapostrophe/fra) - Purely functional implementation of relational algebra.
- [redis](https://github.com/stchang/redis) - A redis client for Racket.
- [rackdis](https://github.com/eu90h/rackdis) - Redis bindings
- [racquel](https://github.com/brown131/racquel) - Racquel is an object/relational mapper for Racket.
- [sql](https://github.com/rmculpepper/sql) - an S-expression notation for SQL.
- [sqlite-table](https://github.com/jbclements/sqlite-table) - A quick way to create and query sqlite tables. Basically a simplified wrapper for a subset of the db library.


## Messaging

*Libraries that implement messaging systems.*

- [zmq](https://github.com/mordae/racket-zmq) - Minimal Racket ZeroMQ Bindings.
- [zeromq-r](https://github.com/rmculpepper/racket-zeromq) - Bindings for ZeroMQ.
- [stomp](https://github.com/tonyg/racket-stomp) - STOMP messaging protocol codec and client.
- [neuron-lib](https://github.com/dedbox/racket-neuron) - Impelementation of neuron.
- [profj](https://github.com/mflatt/profj) - Kathy Gray's ProfessorJ language ported to modern DrRacket.