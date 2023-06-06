# Hare Project Library

This page is a collection of projects written in Hare. Feel free to submit your
own by sending a patch to
[the mailing list](https://lists.sr.ht/~vladh/hare-project-library).
I'll generally accept all patches, unless your project has very little code or
is something unlikely to be used by a wider audience.

If you're interested specifically in 3D graphics, check out
[hare-3d-graphics](https://sr.ht/~vladh/hare-3d-graphics/).

† project included in the
[Hare extended support libraries](https://harelang.org/extended/)

## Audio

* [~vladh/hare-pipewire](https://git.sr.ht/~vladh/hare-pipewire): Pipewire bindings

## Algorithms

* [~pierrec/hare-lz4](https://git.sr.ht/~pierrec/hare-lz4): LZ4 compression algorithm
* [~sircmpwn/hare-compress](https://git.sr.ht/~sircmpwn/hare-compress)†: Compression algorithms for Hare

## Compilers and interpreters

* [~sircmpwn/habf](https://git.sr.ht/~sircmpwn/habf): Hare Brainfuck compiler
* [~smlavine/bf](https://sr.ht/~smlavine/bf): Modular Brainfuck interpreter written in Hare

## Cryptography and hashing

* [~blainsmith/hare-seahash](https://git.sr.ht/~blainsmith/hare-seahash): Seahash hashing algorithm

## Database tools

* [~blainsmith/hare-sqlite](https://git.sr.ht/~blainsmith/hare-sqlite): SQLite client for Hare
* [~sircmpwn/hare-redis](https://git.sr.ht/~sircmpwn/hare-redis)†: Redis client for Hare

## Date and time

* [~torresjrjr/hare-mbc](https://git.sr.ht/~torresjrjr/hare-mbc): Martian Business Calendar

## General applications

* [~illiliti/hare-keepass](https://codeberg.org/illiliti/hare-keepass): KeePass library & utility
* [~sircmpwn/himitsu](https://sr.ht/~sircmpwn/himitsu): A secret storage system

## Graphics, 2D

* [~sircmpwn/hare-vec](https://git.sr.ht/~sircmpwn/hare-vec): Vector graphics library for Hare
* [~sircmpwn/hare-wayland](https://git.sr.ht/~sircmpwn/hare-wayland): Wayland client & server implementation for Hare
* [~sircmpwn/pixbuf](https://git.sr.ht/~sircmpwn/pixbuf): Pixel buffers for Hare
* [~sircmpwn/tetrominoes](https://git.sr.ht/~sircmpwn/tetrominoes): Tetromino game
* [~une/hare-cairo](https://git.sr.ht/~une/hare-cairo): Cairo bindings for Hare
* [~vladh/hare-freetype2](https://git.sr.ht/~vladh/hare-freetype2): Hare freetype2 bindings
* [~vladh/hello-hare-wl](https://git.sr.ht/~vladh/hello-hare-wl): A Hare 2D graphics demo

## Graphics, 3D

* [~evantj/hare-raylib](https://git.sr.ht/~evantj/hare-raylib): raylib bindings for Hare
* [~sircmpwn/hare-sdl2](https://git.sr.ht/~sircmpwn/hare-sdl2): SDL2 bindings for Hare
* [~turminal/raytracing](https://git.sr.ht/~turminal/raytracing): A simple ray tracer in Hare
* [~vladh/glad](https://git.sr.ht/~vladh/glad): Fork of https://github.com/Dav1dde/glad with Hare support
* [~vladh/hare-gl](https://sr.ht/~vladh/hare-gl): OpenGL bindings for Hare
* [~vladh/hare-glm](https://sr.ht/~vladh/hare-glm): An OpenGL-compatible linear algebra library for Hare
* [~vladh/hare-hazel](https://sr.ht/~vladh/hare-hazel): A simple 3D game engine written from scratch in Hare
* [~vladh/hare-obj](https://sr.ht/~vladh/hare-obj): OBJ file parser for Hare
* [~vladh/hare-vulkan-hello-world](https://sr.ht/~vladh/hare-vulkan-hello-world): A simple demo of Hare's Vulkan bindings
* [~vladh/hare-vulkan](https://sr.ht/~vladh/hare-vulkan): Vulkan bindings for Hare
* [~vladh/starfield](https://sr.ht/~vladh/starfield): The Windows 3.1 “starfield” screensaver in Hare

## GUI

* [~renart/hare-bemenu](https://git.sr.ht/~renart/hare-bemenu): Hare bindings for bemenu
* [~yerinalexey/hare-gi](https://git.sr.ht/~yerinalexey/hare-gi): GTK bindings and GObject Introspection bindings generator for Hare
* [~yerinalexey/hare-libui](https://git.sr.ht/~yerinalexey/hare-libui): Work-in-progress Hare bindings for the libui library

## Hare language utilities

* [~sebsite/hareconv](https://git.sr.ht/~sebsite/hareconv): Hare module -> C header converter
* [~sebsite/haretags](https://git.sr.ht/~sebsite/haretags): ctags implementation for Hare
* [~yerinalexey/afl_harec](https://git.sr.ht/~yerinalexey/afl_harec): Hare instrumentation for [AFL](https://github.com/google/AFL)
* [~yerinalexey/hare-annotate](https://git.sr.ht/~yerinalexey/hare-annotate): A library for implementing code generators

## Hare LSP servers

* [~jfreymuth/hare-ls](https://git.sr.ht/~jfreymuth/hare-ls): hare-ls is a language server for Hare
* [~tomleb/harepls](https://sr.ht/~tomleb/harepls/): A LSP server for the Hare language

## Logging and metrics

* [~blainsmith/hare-clrfmt](https://git.sr.ht/~blainsmith/hare-clrfmt): ANSI colorized text in the terminal
* [~blainsmith/hare-logfmt](https://git.sr.ht/~blainsmith/hare-logfmt): A logfmt formatter for [log::logger](https://docs.harelang.org/log)
* [~blainsmith/hare-prometheus](https://git.sr.ht/~blainsmith/hare-prometheus): [Prometheus](https://prometheus.io) metrics

## Low-level primitives

* [~illiliti/hare-atomics](https://codeberg.org/illiliti/hare-atomics): Atomic operations

## Math

* [~smlavine/quadratic](https://sr.ht/~smlavine/quadratic): A simple command-line quadratic formula solver
* [~yerinalexey/csq](https://sr.ht/~yerinalexey/csq): A calculator for common fractions

## Networking

* [~apreiml/hare-tls](https://git.sr.ht/~apreiml/hare-tls): Hare TLS library
* [~bitfehler/hare-tftp](https://git.sr.ht/~bitfehler/hare-tftp): TFTP library/client/server
* [~blainsmith/hare-icmp](https://git.sr.ht/~blainsmith/hare-icmp): Hare ICMP library
* [~illiliti/hare-dnscrypt](https://codeberg.org/illiliti/hare-dnscrypt): dnscrypt client & server
* [~sircmpwn/btqd](https://git.sr.ht/~sircmpwn/btqd): Bittorrent queue daemon
* [~sircmpwn/echo](https://git.sr.ht/~sircmpwn/echo): A TCP echo server written with Hare and iobus
* [~sircmpwn/hare-irc](https://git.sr.ht/~sircmpwn/hare-irc): net::irc for Hare
* [~sircmpwn/harebot](https://git.sr.ht/~sircmpwn/harebot): IRC bot for the #hare channel on libera.chat
* [~sircmpwn/toothbrush](https://git.sr.ht/~sircmpwn/toothbrush): A finger server and client
* [~yerinalexey/kanji](https://git.sr.ht/~yerinalexey/kanji): Modern IRC server

## Operating systems

* [~bitfehler/hare-netlink](https://git.sr.ht/~bitfehler/hare-netlink): Native Hare access to the Linux netlink API
* [~sircmpwn/hare-linux](https://git.sr.ht/~sircmpwn/hare-linux)†: Extended support for Linux
* [~sircmpwn/hare-virt](https://git.sr.ht/~sircmpwn/hare-virt): hare-virt provides hypervisor support for Hare programs
* [~sircmpwn/helios](https://sr.ht/~sircmpwn/helios): An experimental microkernel

## Parsers and file format utilities

* [~blainsmith/hare-csv](https://git.sr.ht/~blainsmith/hare-csv): CSV reading and writing support for Hare
* [~chrisppy/hare-atom](https://git.sr.ht/~chrisppy/hare-atom): atom implementation for Hare
* [~chrisppy/hare-rss](https://git.sr.ht/~chrisppy/hare-rss): rss implementation for Hare
* [~chrisppy/hare-scfg](https://git.sr.ht/~chrisppy/hare-scfg): A Hare library for a simple configuration file format
* [~ecs/hare-stl](https://git.d2evs.net/~ecs/hare-stl): STL implementation for Hare
* [~jfentker/hare-csv](https://git.sr.ht/~jfentker/hare-csv): CSV support for Hare
* [~kaathewise/hare-regex](https://git.sr.ht/~kaathewise/hare-regex): Hare regex engine with wider functionality
* [~phw/hare-discid](https://git.sr.ht/~phw/hare-discid/): Hare bindings for MusicBrainz libdiscid
* [~pierrec/hare-bmp](https://git.sr.ht/~pierrec/hare-bmp): BMP lossless image format
* [~pierrec/hare-qoi](https://git.sr.ht/~pierrec/hare-qoi): QOI lossless image format
* [~sircmpwn/hare-json](https://sr.ht/~sircmpwn/hare-json)†: JSON support for Hare
* [~sircmpwn/hare-png](https://git.sr.ht/~sircmpwn/hare-png)†: PNG implementation for Hare
* [~sircmpwn/hare-qoi](https://git.sr.ht/~sircmpwn/hare-qoi): Quite OK image format for Hare
* [~sircmpwn/hare-xml](https://git.sr.ht/~sircmpwn/hare-xml)†: XML support for Hare
* [~vladh/hare-spapod](https://git.sr.ht/~vladh/hare-spapod): SPA POD format
* [~vladh/hare-wav](https://git.sr.ht/~vladh/hare-wav): WAV file support

## Utilities and system tools

* [~autumnull/haredo](https://sr.ht/~autumnull/haredo): A simple and unix-idiomatic build automator
* [~autumnull/straws](https://git.sr.ht/~autumnull/straws): Like fortune(1) but not terrible
* [~autumnull/treecat](https://sr.ht/~autumnull/treecat/): Serialize a directory to a tree diagram, and vice versa
* [~sircmpwn/harsh](https://git.sr.ht/~sircmpwn/harsh): A Unix shell inspired by Plan 9's rc
* [~sircmpwn/hautils](https://git.sr.ht/~sircmpwn/hautils): POSIX utilities implemented in Hare
* [~sircmpwn/scheduled](https://git.sr.ht/~sircmpwn/scheduled): A daemon for scheduling tasks
* [~torresjrjr/dc](https://git.sr.ht/~torresjrjr/dc): Tiny reverse polish desk calculator
* [~torresjrjr/ed](https://git.sr.ht/~torresjrjr/ed): POSIX ed, written in Hare
* [~torresjrjr/entr](https://git.sr.ht/~torresjrjr/entr): A utility which runs arbitrary commands when files change
* [~yerinalexey/box](https://git.sr.ht/~yerinalexey/box): Command line encryption utility
* [~yerinalexey/git-walk.ha](https://git.sr.ht/~yerinalexey/git-walk.ha): Hare implementation of git log/show commands
* [~yerinalexey/stopwatch](https://git.sr.ht/~yerinalexey/stopwatch): Terminal stopwatch program
